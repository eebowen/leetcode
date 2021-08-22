## Lintcode 391 Number of Airplanes in the Sky
### Python sorting methods:
- sorted(list1, key=key = lambda x:(x[0], x[1])): sorting based on priority of x[0] and x[1]
- list1.sort(key = lambda x:(x[0], x[1])) # in-place

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
