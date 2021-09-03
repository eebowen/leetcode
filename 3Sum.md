## 15. 3Sum (Medium)
\[tag\] two pointers

- hashmap
  - for 2 sum solution, use a hash map for numbers, occurance. 
  - for 3 sum, fix an pointer, use hash map for all elements on the right. so n^2
- sorted and 3 pointers
  - fix first pointer, use 2 pointers for all elements on the right.


```python

class Solution:
    def threeSum(self, nums: List[int]) -> List[List[int]]:
        nums.sort()
        print(nums)
        ans = []
        # or use for i, num in enumerate(nums):
        for i in range(len(nums)):
            if i > 0 and nums[i] == nums[i - 1]:
                continue
            left = i + 1
            right = len(nums) - 1
            target = 0 - nums[i]
            while left < right:
                if nums[left] + nums[right] < target:
                    left += 1
                elif nums[left] + nums[right] > target:
                    right -= 1
                else:
                    ans.append([nums[i], nums[left], nums[right]])
                    left, right = left + 1, right - 1
                    while left < right and nums[left] == nums[left - 1]:
                        left += 1
                    # one condition above is actually enough
                    while left < right and nums[right] == nums[right + 1]:
                        right -= 1
        return ans
```
