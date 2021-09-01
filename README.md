### 8/23
- [1229. Meeting Scheduler(Medium)](https://github.com/eebowen/leetcode/blob/main/1229.%20Meeting%20Scheduler.md).
Two pointers and scan line. Pretty easy.
- [986. Interval List Intersections (Medium)](https://github.com/eebowen/leetcode/blob/main/986.%20Interval%20List%20Intersections.md). 
Similar as 1229 using two pointers and scan line. Pretty easy.
- [759. Employee Free Time (Hard)](https://github.com/eebowen/leetcode/blob/main/759.%20Employee%20Free%20Time.md). 
Scan Line, deque, use an maxEnd varable

### 8/24
- [560. Subarray Sum Equals K (Medium)](https://github.com/eebowen/leetcode/blob/main/560.%20Subarray%20Sum%20Equals%20K.md).
Four methods. Prefix sum. Hashmap for storing sum values to look up like two sum. 
- [218. The Skyline Problem (Hard)](https://github.com/eebowen/leetcode/blob/main/218.%20The%20Skyline%20Problem.md).
Python max heap hard to use, and no remove function, so used SortedList from sortedcontainers.

### 8/25
- [111. Minimum Depth of Binary Tree (Easy)](https://github.com/eebowen/leetcode/blob/main/111.%20Minimum%20Depth%20of%20Binary%20Tree.md).
Two methods, 1. recursion DFS. 2. queue BFS.
- [102. Binary Tree Level Order Traversal (Medium)](https://github.com/eebowen/leetcode/blob/main/102.%20Binary%20Tree%20Level%20Order%20Traversal.md).
2 method. 1. recursion DFS. 2.queue BFS.
- [127. Word Ladder(Hard)](https://github.com/eebowen/leetcode/blob/main/127.%20Word%20Ladder.md). 
2 method. 1. one direction BFS. 2. 2 direction BFS.

### 8/26
- [490. The Maze (Hard)](https://github.com/eebowen/leetcode/blob/main/490.%20The%20Maze.md). Brute force BFS. 
- [505. The Maze II (Medium)](https://github.com/eebowen/leetcode/blob/main/505.%20The%20Maze%20II.md). Dijkstra's algorithm

### 8/27
- [283. Move Zeroes (Easy)](https://github.com/eebowen/leetcode/blob/main/283.%20Move%20Zeroes.md). Two pointers methods. Need review!!!
- [811. Subdomain Visit Count (Medium)](https://github.com/eebowen/leetcode/blob/main/811.%20Subdomain%20Visit%20Count.md).
defaultdict and split method.

### 8/28
- [207. Course Schedule (Medium)](https://github.com/eebowen/leetcode/blob/main/207.%20Course%20Schedule.md).
Use defaultdict and a list to store the graph. Use heap to perform BFS.
- [724. Find Pivot Index (Esay)](https://github.com/eebowen/leetcode/blob/main/724.%20Find%20Pivot%20Index.md). 
Two methods. 1. One pointer to adjust left and right sum. 2. Use prefix sum.
- [210. Course Schedule II (Medium)](https://github.com/eebowen/leetcode/blob/main/210.%20Course%20Schedule%20II.md).
Similar as 207 Course Schedule.
- [278. First Bad Version (Esay)](https://github.com/eebowen/leetcode/blob/main/278.%20First%20Bad%20Version.md).
Two methods. 1. returns left or right. 2. use a variable to record ans. 
- [4. Median of Two Sorted Arrays (Hard)](https://github.com/eebowen/leetcode/blob/main/4.%20Median%20of%20Two%20Sorted%20Arrays.md).
Binary Search on one array only and use it for the second array with some constrains. 
- [704. Binary Search (Easy)](https://github.com/eebowen/leetcode/blob/main/704.%20Binary%20Search.md). Template binary search problem.
- [34. First and Last in Sorted Array (Medium)](https://github.com/eebowen/leetcode/blob/main/34.%20First%20and%20Last%20in%20Sorted%20Array.md).
Find the left boundary and right boundary (first occurance and last occurance).

### 8/29
- [33. Search in Rotated Sorted Array (Medium)](https://github.com/eebowen/leetcode/blob/main/33.%20Search%20in%20Rotated%20Sorted%20Array.md).
Determine which part is in order.
- [702. Search in a Sorted Array of Unknown Size (Medium)](https://github.com/eebowen/leetcode/blob/main/702.%20Search%20in%20a%20Sorted%20Array%20of%20Unknown%20Size.md).
Find the right bound first and then binary search.

### 8/30 
- [74. Search a 2D Matrix (Medium)](https://github.com/eebowen/leetcode/blob/main/74.%20Search%20a%202D%20Matrix.md).
Basic binary search template.
- [35. Search Insert Position (Easy)](https://github.com/eebowen/leetcode/blob/main/35.%20Search%20Insert%20Position.md).
Basic binary search template.
- [162. Find Peak Element (Medium)](https://github.com/eebowen/leetcode/blob/main/162.%20Find%20Peak%20Element.md).
Binary search template. using left + 1 < right is better.
- [69. Sqrt(x) (Easy)](https://github.com/eebowen/leetcode/blob/main/69.%20Sqrt(x).md).
- [287. Find the Duplicate Number (Medium)](https://github.com/eebowen/leetcode/blob/main/287.%20Find%20the%20Duplicate%20Number.md).
Use binary search in a spefic range.
- [875. Koko Eating Bananas (Medium)](https://github.com/eebowen/leetcode/blob/main/875.%20Koko%20Eating%20Bananas.md)
Use binary search. Needs to determine the range and target conditions.

### 8/31
- [1011. Capacity To Ship Packages Within D Days (Medium)](https://github.com/eebowen/leetcode/blob/main/1011.%20Capacity%20To%20Ship%20Packages%20Within%20D%20Days.md).
Binary search with special range, similar to Koko eating banana.
- [528. Random Pick with Weight (Medium)](https://github.com/eebowen/leetcode/blob/main/528.%20Random%20Pick%20with%20Weight.md).
Binary search with prefix sum. random a sum, and find the interval.
- [Redo 4. Median of Two Sorted Arrays (Hard)](https://github.com/eebowen/leetcode/blob/main/4.%20Median%20of%20Two%20Sorted%20Arrays.md).
Spent 1h but still cant finish debuging, always array out of bound.
-[1060. Missing Element in Sorted Array (Medium)](https://github.com/eebowen/leetcode/blob/main/1060.%20Missing%20Element%20in%20Sorted%20Array.md).
Binary search on comparing missing bumbers with k.
