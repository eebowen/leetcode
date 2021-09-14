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
- [1060. Missing Element in Sorted Array (Medium)](https://github.com/eebowen/leetcode/blob/main/1060.%20Missing%20Element%20in%20Sorted%20Array.md).
Binary search on comparing missing bumbers with k.

### 9/1
- [415. Add Strings (Easy)](https://github.com/eebowen/leetcode/blob/main/415.%20Add%20Strings.md).
two pointers for string. **Using while loop for two pointer questions.**
- [11. Container With Most Water(Medium)](https://github.com/eebowen/leetcode/blob/main/11.%20Container%20With%20Most%20Water.md).
two pointers and calculate the area.

### 9/2
- [2. Add Two Numbers (Medium)](https://github.com/eebowen/leetcode/blob/main/2.%20Add%20Two%20Numbers.md).
Two pointers and a carry.
- [912. Sort an Array (Medium)](https://github.com/eebowen/leetcode/blob/main/912.%20Sort%20an%20Array.md).
Two sorting method, quick sort and merge sort.
- [1. Two Sum (Easy)](https://github.com/eebowen/leetcode/blob/main/1.%20Two%20Sum.md). 
A hash table, key: num, value: index.
- [167. Two Sum II - Input array is sorted (Easy)](https://github.com/eebowen/leetcode/blob/main/167.%20Two%20Sum%20II%20-%20Input%20array%20is%20sorted.md). 
Two pointers from begin and end.
- [15. 3Sum (medium)](https://github.com/eebowen/leetcode/blob/main/3Sum.md). 
Two pointers or hash map
- [49. Group Anagrams (Medium)](https://github.com/eebowen/leetcode/blob/main/49.%20Group%20Anagrams.md). 
Hashmap/defaultdict with keys being strings and values being lists.
- [75. Sort Colors (Mdeium)](https://github.com/eebowen/leetcode/blob/main/75.%20Sort%20Colors.md). 
Use 3 pionters: two fixed pointers, l and r, on both side for representing 0 and 2. One floating pinter m in the middle.
- [445. Add Two Numbers II (Medium)](https://github.com/eebowen/leetcode/blob/main/445.%20Add%20Two%20Numbers%20II.md). 
Two pointers with a carry. Reversing a linked list.

### 9/3
- [206. Reverse Linked List (Easy)](https://github.com/eebowen/leetcode/blob/main/206.%20Reverse%20Linked%20List.md). 
1). Two pointers: cur and prev. 2). Recursion: fixed the first pointer and recursive reverse the latter ones.
- [345. Reverse Vowels of a String (Easy)](https://github.com/eebowen/leetcode/blob/main/345.%20Reverse%20Vowels%20of%20a%20String.md). 
two pointers. Change string to list using **list('abc')**.
- [560 Subarray Sum Equals K (Medium)]. Second time.
- [974. Subarray Sums Divisible by K (Medium)](https://github.com/eebowen/leetcode/blob/main/974.%20Subarray%20Sums%20Divisible%20by%20K.md). 
1). Use 2 prefix sum and a hashtable/dict {prefix sum % k: count} and then same as two sum. 2). need to consider the reminder of negitive value, so (reminder + k) to transfer it to positive. 3). Set dict[0] = 1.
- [26. Remove Duplicates from Sorted Array (Medium)](https://github.com/eebowen/leetcode/blob/main/26.%20Remove%20Duplicates%20from%20Sorted%20Array.md). 
Two pionters both start from the left.
- [80. Remove Duplicates from Sorted Array II (Medium)](https://github.com/eebowen/leetcode/blob/main/80.%20Remove%20Duplicates%20from%20Sorted%20Array%20II.md).
**[Tricky, review again.]** Use two pointers one fixed pointer(l) and one floating(r).  
- [283. Move Zeroes (Easy)]. Second time.
- [3. Longest Substring Without Repeating Characters (Medium)](https://github.com/eebowen/leetcode/blob/main/3.%20Longest%20Substring%20Without%20Repeating%20Characters.md).
1). Two pointers, sliding windows, set/hashset. 2). Need to check clearfully when running examples
- [209. Minimum Size Subarray Sum (Medium)](https://github.com/eebowen/leetcode/blob/main/209.%20Minimum%20Size%20Subarray%20Sum.md).
Positive integers so can use two pointers/sliding window. Can we use hashmap?

### 9/4 
- [438. Find All Anagrams in a String (Medium)](https://github.com/eebowen/leetcode/blob/main/438.%20Find%20All%20Anagrams%20in%20a%20String.md).
Use a sliding window and hashtable/dict for all lowercase chars. Compare two tables/dicts. 
- [227. Basic Calculator II (Medium)](https://github.com/eebowen/leetcode/blob/main/227.%20Basic%20Calculator%20II.md).
Use a stack to push numbers and do operations when meet previous operator.
- [224. Basic Calculator (Hard)](https://github.com/eebowen/leetcode/blob/main/224.%20Basic%20Calculator.md).
**1).** Use sum and sign to store the current sum and previous sign. **2).** use while loop to go though all digit of a number. **3).** When '(' append, when ')' pop.

### 9/5
- [349. Intersection of Two Arrays (Easy)](https://github.com/eebowen/leetcode/blob/main/349.%20Intersection%20of%20Two%20Arrays.md)
Use 2 sets or a binary search.

### 9/6
- [350. Intersection of Two Arrays II (Easy)](https://github.com/eebowen/leetcode/blob/main/350.%20Intersection%20of%20Two%20Arrays%20II.md).
2 methods, Hash table or sort. 3 follow ups. 
- [239. Sliding Window Maximum (Hard)](https://github.com/eebowen/leetcode/blob/main/239.%20Sliding%20Window%20Maximum.md)
Use a deque for storing numbers in decreasing order. When first number is out of range, pop. The ans is the first number in the deque.
- [42. Trapping Rain Water (Hard)](https://github.com/eebowen/leetcode/blob/main/42.%20Trapping%20Rain%20Water.md)
Use two opposite directional pointers to calculate max height for each direction. Use min of (max_left, max_right) - height for water difference at each location
- [102. Binary Tree Level Order Traversal (Medium)] Second time.
- [56. Merge Intervals (Medium)](https://github.com/eebowen/leetcode/blob/main/56.%20Merge%20Intervals.md). Second time.
Sort and list. Don't forgot corner cases.

### 9/7
- [200. Number of Islands (Medium)](https://github.com/eebowen/leetcode/blob/main/200.%20Number%20of%20Islands.md).
Second time. BFS and deque. 
- [236. Lowest Common Ancestor of a Binary Tree](https://github.com/eebowen/leetcode/blob/main/236.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree.md).
Return the node if found and pass it up.
- [235. Lowest Common Ancestor of a Binary Search Tree (Medium)](https://github.com/eebowen/leetcode/blob/main/235.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Search%20Tree.md).
Compare values and go left or right. Improve the order of if else makes code better.

### 9/8
- [28. Implement strStr() (Easy)](https://github.com/eebowen/leetcode/blob/main/28.%20Implement%20strStr().md).
Use string equal. Be careful on for loop conditions.
- [103. Binary Tree Zigzag Level Order Traversal (Medium)](https://github.com/eebowen/leetcode/blob/main/103.%20Binary%20Tree%20Zigzag%20Level%20Order%20Traversal.md).
Same way of using queue, but append to result using different order.
- [557. Reverse Words in a String III (Easy)](https://github.com/eebowen/leetcode/blob/main/557.%20Reverse%20Words%20in%20a%20String%20III.md).
Reverse a string using deque and append all sapces.
- [199. Binary Tree Right Side View (Medium)](https://github.com/eebowen/leetcode/blob/main/199.%20Binary%20Tree%20Right%20Side%20View.md).
Level order traversal and store the last element.
- [695. Max Area of Island (Medium)](https://github.com/eebowen/leetcode/blob/main/695.%20Max%20Area%20of%20Island.md).
BFS. Similar to number of islands.

### 9/9
- [263. Ugly Number(Easy)](https://github.com/eebowen/leetcode/blob/main/263.%20Ugly%20Number.md)
Devide all prime numbers if divisible, and return n == 1.
- [1041. Robot Bounded In Circle (Medium)](https://github.com/eebowen/leetcode/blob/main/1041.%20Robot%20Bounded%20In%20Circle.md).
Two conditions: 1). Return to origin after one iter. 2). Location changed and direction also changed at the end of one iter. Also need to change dir when turns.
- [221. Maximal Square (Medium)](https://github.com/eebowen/leetcode/blob/main/221.%20Maximal%20Square.md).
Use an hash map/ dict for the max area/lenth for each cell. Check right, down and corner to see if it can be a square. Recursively check the lenth of the adjusent squere and add them to the dict.
- [78. Subsets (Medium)](https://github.com/eebowen/leetcode/blob/main/78.%20Subsets.md).
Combination algorithm, DFS. For loop for different the length of the sub_set. dfs(lenth, start_number, cur_set)
- [90. Subsets II (Medium)](https://github.com/eebowen/leetcode/blob/main/90.%20Subsets%20II.md).
Simiar to 78. Subsets, just need to sort the input and skip repeated numbers. 
- [1091. Shortest Path in Binary Matrix (Medium)](https://github.com/eebowen/leetcode/blob/main/1091.%20Shortest%20Path%20in%20Binary%20Matrix.md).
BFS Graph shortest path.

### 9/10
- [190. Reverse Bits (easy)](https://github.com/eebowen/leetcode/blob/main/190.%20Reverse%20Bits.md).
Use n >> i & 1 to get a bit value at i.
- [542. 01 Matrix (Medium)](https://github.com/eebowen/leetcode/blob/main/542.%2001%20Matrix.md).
Has multiple targets, use all of them as starting point to be more efficient. 
- [98. Validate Binary Search Tree (Medium)](https://github.com/eebowen/leetcode/blob/main/98.%20Validate%20Binary%20Search%20Tree.md).
Top down recursion or in-order traversal.

### 9/11
- [6. ZigZag Conversion (Medium)](https://github.com/eebowen/leetcode/blob/main/6.%20ZigZag%20Conversion.md).
String. For loop if there is a fixed increment.
- [55. Jump Game (Medium)](https://github.com/eebowen/leetcode/blob/main/55.%20Jump%20Game.md). 
[Question](https://leetcode.com/problems/jump-game/). 
Greedy, backward.
- [286. Walls and Gates (Medium)](https://github.com/eebowen/leetcode/blob/main/286.%20Walls%20and%20Gates.md). 
[Quesiton](https://leetcode.com/problems/walls-and-gates/). 
Use multiple targets as starting points and add to queue. 
Use a function to check valid and add node to queue. 
Check BFS **INDEX x_new and y_new**. 
- [210. Course Schedule II (Medium)](https://github.com/eebowen/leetcode/blob/main/210.%20Course%20Schedule%20II.md). 2nd, BFS.

### 9/13
- [39. Combination Sum (Medium)](https://github.com/eebowen/leetcode/blob/main/39.%20Combination%20Sum.md).
Sort list first. Use DFS for combination problem.

### 9/14
- [46. Permutations (medium)](https://github.com/eebowen/leetcode/blob/main/46.%20Permutations.md). 
DFS for permutation problems.
- [47. Permutations II](https://github.com/eebowen/leetcode/blob/main/47.%20Permutations%20II.md). 
DFS for permutation problems.
- [78. Subsets (Medium)](https://github.com/eebowen/leetcode/blob/main/78.%20Subsets.md).
Second time.
