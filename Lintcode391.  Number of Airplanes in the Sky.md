## Lintcode 391 Number of Airplanes in the Sky
### Python Tips" Sorting Methods:
- sorted(list1, key = lambda x:(x[0], x[1])): sorting based on priority of x[0] and x[1]
- list1.sort(key = lambda x:(x[0], x[1])) # in-place
- Using comparator:
``` python
list1 = [(10,1),(10,-1), (10, 1), (10, -1)]
#==> results: [(10, -1),(10, -1), (10, 1), (10, 1)]
def comparator(point1, point2):
    if point1[0] == point2[0]:
        if point1[1] == point2[1]:
            return 0
        else:
            return point1[1]
    else:
        return point1[0] - point2[1]
# does not work
# print(list1.sort(key=cmp_to_key(comparator)))
# works
print(sorted(list1, key=cmp_to_key(comparator)))
```

### Algorithm Sweep Line

- first add all start and point to a point list() from interval
- using tuple (time, +1/-1) +1 if taking off. -1 if landing
- sort start point and end point. 
- loop throuth all points record the max count


```python
class Solution:
    """
    @param airplanes: An interval array
    @return: Count of airplanes are in the sky.
    """
    def countOfAirplanes(self, airplanes):
        # write your code here
        pointList = []
        for oneInterval in airplanes:
            pointList.append((oneInterval.start, 1))
            pointList.append((oneInterval.end, -1))
        # pointList = sorted(pointList, key = lambda x:(x[0], x[1]))
        pointList.sort(key = lambda x:(x[0], x[1]))
        count = 0
        ans = 0
        for onePoint in pointList:
            count += onePoint[1]
            ans = max(ans, count)
        return ans
```
