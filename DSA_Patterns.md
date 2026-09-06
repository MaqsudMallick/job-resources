<!-- Problem links resolved against LeetCode's official catalogue. `≈` marks the closest LeetCode variant rather than a verbatim restatement. -->
# DSA Questions + Patterns

**500 Curated Problems for FAANG & Top-Tier Interview Preparation**

*Covering Arrays, Strings, Trees, Graphs, DP, and 20+ Core Topics*

## Introduction

This document is a comprehensive, formally curated collection of 500 Data Structures and Algorithms (DSA) questions designed for candidates preparing for technical interviews at top technology companies including Google, Amazon, Apple, Netflix, Meta (FAANG), Microsoft, and other tier-1 organisations. Each question is accompanied by its associated algorithmic pattern, enabling a pattern-first study approach that dramatically improves problem-solving speed and accuracy during interviews.

Questions are organized by topic and sub-topic. Difficulty is annotated as [Easy], [Medium], or [Hard]. Master the patterns, not just the problems.

## Section 1: Arrays (Q1 – Q50)

### 1.1 Two Pointers

> **Pattern:** Two Pointers — use two indices moving toward/away from each other to reduce O(n²) to O(n).

1. [Two Sum (sorted array)](https://leetcode.com/problems/two-sum/) `[Easy]`
2. [Three Sum](https://leetcode.com/problems/3sum/) `[Medium]`
3. [Four Sum](https://leetcode.com/problems/4sum/) `[Medium]`
4. [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) `[Medium]`
5. [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) `[Hard]`
6. [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) `[Easy]`
7. [Move Zeroes to End](https://leetcode.com/problems/move-zeroes/) `[Easy]`
8. [Sort Colors (Dutch National Flag)](https://leetcode.com/problems/sort-colors/) `[Medium]`
9. [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) `[Medium]`
10. [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) `[Easy]`

### 1.2 Sliding Window

> **Pattern:** Sliding Window — maintain a window of elements; expand/shrink to satisfy a constraint.

11. [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) `[Medium]`
12. [Maximum Sum Subarray of Size K](https://leetcode.com/problems/maximum-sum-of-distinct-subarrays-with-length-k/) `[Easy]` — ≈ *Maximum Sum of Distinct Subarrays With Length K* (LC adds an all-distinct constraint)
13. [Fruit Into Baskets (at most 2 distinct)](https://leetcode.com/problems/fruit-into-baskets/) `[Medium]`
14. [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) `[Hard]`
15. [Longest Subarray with Ones after Replacement](https://leetcode.com/problems/max-consecutive-ones-iii/) `[Medium]`
16. [Permutation in String](https://leetcode.com/problems/permutation-in-string/) `[Medium]`
17. [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) `[Medium]`
18. [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) `[Hard]`
19. [Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii/) `[Medium]`
20. [Number of Subarrays with Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) `[Medium]`

### 1.3 Prefix Sum / Difference Array

> **Pattern:** Prefix Sum — precompute cumulative sums for O(1) range queries.

21. [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) `[Medium]`
22. [Range Sum Query — Immutable](https://leetcode.com/problems/range-sum-query-immutable/) `[Easy]`
23. [Continuous Subarray Sum (multiple of k)](https://leetcode.com/problems/continuous-subarray-sum/) `[Medium]`
24. [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) `[Medium]`
25. [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) `[Easy]`
26. [Count Subarrays with Equal 0s and 1s](https://leetcode.com/problems/contiguous-array/) `[Medium]`
27. [Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) `[Medium]`
28. [Minimum Operations to Reduce X to Zero](https://leetcode.com/problems/minimum-operations-to-reduce-x-to-zero/) `[Medium]`
29. [Running Sum of 1D Array](https://leetcode.com/problems/running-sum-of-1d-array/) `[Easy]`
30. [Random Pick with Weight](https://leetcode.com/problems/random-pick-with-weight/) `[Medium]`

### 1.4 Kadane's / Greedy on Arrays

> **Pattern:** Kadane's Algorithm — track local and global maximum for maximum subarray problems.

31. [Maximum Subarray (Kadane's)](https://leetcode.com/problems/maximum-subarray/) `[Medium]`
32. [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) `[Medium]`
33. [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) `[Easy]`
34. [Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) `[Medium]`
35. [Jump Game](https://leetcode.com/problems/jump-game/) `[Medium]`
36. [Jump Game II (minimum jumps)](https://leetcode.com/problems/jump-game-ii/) `[Medium]`
37. [Gas Station](https://leetcode.com/problems/gas-station/) `[Medium]`
38. [Candy Distribution](https://leetcode.com/problems/candy/) `[Hard]`
39. [Partition Labels](https://leetcode.com/problems/partition-labels/) `[Medium]`
40. [Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/) `[Medium]`

### 1.5 Sorting & Searching in Arrays

> **Pattern:** Sorting + Binary Search — sort once, then binary-search for O(n log n) solutions.

41. [Merge Intervals](https://leetcode.com/problems/merge-intervals/) `[Medium]`
42. [Insert Interval](https://leetcode.com/problems/insert-interval/) `[Medium]`
43. [Meeting Rooms II (min conference rooms)](https://leetcode.com/problems/meeting-rooms-ii/) `[Medium]`
44. [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) `[Medium]`
45. [Largest Number (custom sort)](https://leetcode.com/problems/largest-number/) `[Medium]`
46. [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) `[Medium]`
47. [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) `[Medium]`
48. [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) `[Medium]`
49. [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) `[Hard]`
50. [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) `[Medium]`
## Section 2: Strings (Q51 – Q90)

### 2.1 String Manipulation & Hashing

> **Pattern:** HashMap / Frequency Count — count character frequencies to compare or find patterns.

51. [Valid Anagram](https://leetcode.com/problems/valid-anagram/) `[Easy]`
52. [Group Anagrams](https://leetcode.com/problems/group-anagrams/) `[Medium]`
53. [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/) `[Easy]`
54. [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/) `[Medium]`
55. [String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/) `[Medium]`
56. [Roman to Integer](https://leetcode.com/problems/roman-to-integer/) `[Easy]`
57. [Integer to Roman](https://leetcode.com/problems/integer-to-roman/) `[Medium]`
58. [Count and Say](https://leetcode.com/problems/count-and-say/) `[Medium]`
59. [ZigZag Conversion](https://leetcode.com/problems/zigzag-conversion/) `[Medium]`
60. [Multiply Strings](https://leetcode.com/problems/multiply-strings/) `[Medium]`
61. [Longest Palindrome (by rearrangement)](https://leetcode.com/problems/longest-palindrome/) `[Easy]`
62. [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) `[Easy]`

### 2.2 Sliding Window on Strings

> **Pattern:** Variable-size Sliding Window — track character counts inside a window.

63. [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) `[Medium]`
64. [Minimum Window Substring (revisited with string focus)](https://leetcode.com/problems/minimum-window-substring/) `[Hard]`
65. [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) `[Medium]`
66. [Longest Substring with At Most Two Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/) `[Medium]`
67. [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) `[Medium]`
68. [Palindromic Substrings (count all)](https://leetcode.com/problems/palindromic-substrings/) `[Medium]`

### 2.3 Pattern Matching

> **Pattern:** KMP / Rabin-Karp / Z-Algorithm — efficient O(n+m) substring search.

69. [Implement strStr() / Needle in Haystack](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/) `[Easy]`
70. [Repeated Substring Pattern](https://leetcode.com/problems/repeated-substring-pattern/) `[Easy]`
71. [Shortest Palindrome (KMP)](https://leetcode.com/problems/shortest-palindrome/) `[Hard]`
72. [Longest Happy Prefix (KMP failure function)](https://leetcode.com/problems/longest-happy-prefix/) `[Hard]`
73. [Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/) `[Easy]`
74. [Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) `[Hard]`
75. [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) `[Hard]`
76. [Word Break](https://leetcode.com/problems/word-break/) `[Medium]`
77. [Word Break II](https://leetcode.com/problems/word-break-ii/) `[Hard]`
78. [Decode Ways](https://leetcode.com/problems/decode-ways/) `[Medium]`

### 2.4 Stack-based String Problems

> **Pattern:** Monotonic Stack / Explicit Stack — process characters left-to-right with a stack.

79. [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) `[Easy]`
80. [Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/) `[Medium]`
81. [Score of Parentheses](https://leetcode.com/problems/score-of-parentheses/) `[Medium]`
82. [Decode String (k\1encoded\1string\1)](https://leetcode.com/problems/decode-string/) `[Medium]`
83. [Remove All Adjacent Duplicates in String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) `[Easy]`
84. [Remove K Digits](https://leetcode.com/problems/remove-k-digits/) `[Medium]`
85. [Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/) `[Medium]`
86. [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) `[Medium]`
87. [Remove Duplicate Letters (lexicographically smallest)](https://leetcode.com/problems/remove-duplicate-letters/) `[Medium]`
88. [Largest Rectangle in Histogram (string of bars)](https://leetcode.com/problems/largest-rectangle-in-histogram/) `[Hard]`
## Section 3: Linked Lists (Q91 – Q120)

### 3.1 Fast & Slow Pointers

> **Pattern:** Floyd's Cycle Detection — two pointers at different speeds to detect cycles and midpoints.

89. [Linked List Cycle Detection](https://leetcode.com/problems/linked-list-cycle/) `[Easy]`
90. [Linked List Cycle II (entry point)](https://leetcode.com/problems/linked-list-cycle-ii/) `[Medium]`
91. [Find the Middle of Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) `[Easy]`
92. [Happy Number (cycle in sequence)](https://leetcode.com/problems/happy-number/) `[Easy]`
93. [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) `[Easy]`
94. [Reorder List (L0→Ln→L1→Ln-1)](https://leetcode.com/problems/reorder-list/) `[Medium]`

### 3.2 Reversal & Merging

> **Pattern:** In-place Reversal — reverse sublists or entire lists using pointer manipulation.

95. [Reverse a Linked List](https://leetcode.com/problems/reverse-linked-list/) `[Easy]`
96. [Reverse Linked List II (sub-list)](https://leetcode.com/problems/reverse-linked-list-ii/) `[Medium]`
97. [Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) `[Hard]`
98. [Rotate List by k](https://leetcode.com/problems/rotate-list/) `[Medium]`
99. [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) `[Easy]`
100. [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) `[Hard]`
101. [Sort List (merge sort on LL)](https://leetcode.com/problems/sort-list/) `[Medium]`
102. [Partition List around value x](https://leetcode.com/problems/partition-list/) `[Medium]`
103. [Remove Nth Node from End](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) `[Medium]`
104. [Delete Node in a Linked List (no head)](https://leetcode.com/problems/delete-node-in-a-linked-list/) `[Easy]`
105. [Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) `[Medium]`
106. [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) `[Easy]`
107. [Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) `[Medium]`
108. [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) `[Medium]`
109. [LRU Cache (design problem)](https://leetcode.com/problems/lru-cache/) `[Medium]`

### 3.3 Advanced Linked List

110. [LFU Cache](https://leetcode.com/problems/lfu-cache/) `[Hard]`
111. [Design Skiplist](https://leetcode.com/problems/design-skiplist/) `[Hard]`
112. [Add Two Numbers (LL representation)](https://leetcode.com/problems/add-two-numbers/) `[Medium]`
113. [Add Two Numbers II (no reversal)](https://leetcode.com/problems/add-two-numbers-ii/) `[Medium]`
114. [Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) `[Medium]`
115. [Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) `[Medium]`
116. [Next Greater Node in Linked List](https://leetcode.com/problems/next-greater-node-in-linked-list/) `[Medium]`
117. [Insert into a Sorted Circular Linked List](https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list/) `[Medium]`
118. [Convert Binary Number in LL to Integer](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/) `[Easy]`
## Section 4: Stacks & Queues (Q121 – Q145)

### 4.1 Monotonic Stack

> **Pattern:** Monotonic Stack — maintain a stack in increasing/decreasing order for next-greater/smaller queries.

119. [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) `[Easy]`
120. [Next Greater Element II (circular)](https://leetcode.com/problems/next-greater-element-ii/) `[Medium]`
121. [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) `[Medium]`
122. [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) `[Hard]`
123. [Maximal Rectangle in Binary Matrix](https://leetcode.com/problems/maximal-rectangle/) `[Hard]`
124. [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) `[Medium]`
125. [Maximum Width Ramp](https://leetcode.com/problems/maximum-width-ramp/) `[Medium]`
126. [Online Stock Span](https://leetcode.com/problems/online-stock-span/) `[Medium]`
127. [132 Pattern](https://leetcode.com/problems/132-pattern/) `[Medium]`
128. [Asteroid Collision](https://leetcode.com/problems/asteroid-collision/) `[Medium]`

### 4.2 Queue / Deque Patterns

> **Pattern:** Monotonic Deque — maintain a deque for sliding window max/min in O(n).

129. [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) `[Hard]`
130. First Negative in Every Window of Size K `[Medium]` — *no LeetCode equivalent (GFG classic)*
131. [Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/) `[Easy]`
132. [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) `[Easy]`
133. [Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) `[Medium]`
134. [Design Circular Deque](https://leetcode.com/problems/design-circular-deque/) `[Medium]`
135. Max of Min for Every Window Size `[Hard]` — *no LeetCode equivalent (GFG classic)*
136. [Shortest Subarray with Sum at Least K](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) `[Hard]`
137. [Jump Game VI (DP + deque)](https://leetcode.com/problems/jump-game-vi/) `[Medium]`
138. [Constrained Subsequence Sum](https://leetcode.com/problems/constrained-subsequence-sum/) `[Hard]`
139. [Task Scheduler](https://leetcode.com/problems/task-scheduler/) `[Medium]`
140. [Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls/) `[Easy]`
141. [Dota2 Senate](https://leetcode.com/problems/dota2-senate/) `[Medium]`
142. [Reveal Cards in Increasing Order](https://leetcode.com/problems/reveal-cards-in-increasing-order/) `[Medium]`
143. [Rotten Oranges (BFS)](https://leetcode.com/problems/rotting-oranges/) `[Medium]`
## Section 5: Binary Search (Q146 – Q175)

### 5.1 Classic Binary Search

> **Pattern:** Binary Search — repeatedly halve the search space on a monotonic function.

144. [Binary Search (basic)](https://leetcode.com/problems/binary-search/) `[Easy]`
145. [First Bad Version](https://leetcode.com/problems/first-bad-version/) `[Easy]`
146. [Search Insert Position](https://leetcode.com/problems/search-insert-position/) `[Easy]`
147. [Count of Range Sum (advanced)](https://leetcode.com/problems/count-of-range-sum/) `[Hard]`
148. [Find Peak Element](https://leetcode.com/problems/find-peak-element/) `[Medium]`
149. [Find Minimum in Rotated Sorted Array II (duplicates)](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/) `[Hard]`
150. [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/) `[Medium]`
151. [Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/) `[Medium]`
152. [Kth Smallest Element in Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) `[Medium]`
153. [Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) `[Medium]`

### 5.2 Binary Search on Answer

> **Pattern:** Parametric Search — binary search on the answer space, validate with a feasibility function.

154. [Capacity to Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/) `[Medium]`
155. [Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/) `[Hard]`
156. [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/) `[Medium]`
157. [Minimum Number of Days to Make m Bouquets](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/) `[Medium]`
158. [Magnetic Force Between Two Balls](https://leetcode.com/problems/magnetic-force-between-two-balls/) `[Medium]`
159. [Find the Smallest Divisor Given a Threshold](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/) `[Medium]`
160. [Allocate Minimum Number of Pages](https://leetcode.com/problems/split-array-largest-sum/) `[Medium]`
161. [Aggressive Cows (SPOJ classic)](https://leetcode.com/problems/magnetic-force-between-two-balls/) `[Medium]`
162. [Painters Partition Problem](https://leetcode.com/problems/split-array-largest-sum/) `[Hard]`
163. [EKO — Cutting Trees (binary search on height)](https://leetcode.com/problems/maximum-candies-allocated-to-k-children/) `[Medium]` — ≈ *Maximum Candies Allocated to K Children* (same binary-search-on-answer shape, different framing)
164. [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) `[Hard]`
165. [K-th Smallest Prime Fraction](https://leetcode.com/problems/k-th-smallest-prime-fraction/) `[Hard]`
166. [Find K-th Smallest Pair Distance](https://leetcode.com/problems/find-k-th-smallest-pair-distance/) `[Hard]`
167. [Count of Pairs with Sum Less Than Target](https://leetcode.com/problems/count-pairs-whose-sum-is-less-than-target/) `[Easy]`
168. [Maximum Running Time of N Computers](https://leetcode.com/problems/maximum-running-time-of-n-computers/) `[Hard]`

### 5.3 Bisect Tricks

169. [Longest Increasing Subsequence (O(n log n))](https://leetcode.com/problems/longest-increasing-subsequence/) `[Medium]`
170. [Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) `[Hard]`
171. [Count of Smaller Numbers After Self (BIT/BST)](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) `[Hard]`
172. [Minimum Operations to Make Array Increasing](https://leetcode.com/problems/minimum-operations-to-make-the-array-increasing/) `[Easy]`
173. [Maximum Profit in Job Scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/) `[Hard]`
174. [Number of Longest Increasing Subsequences](https://leetcode.com/problems/number-of-longest-increasing-subsequence/) `[Medium]`
## Section 6: Trees (Q176 – Q230)

### 6.1 Tree Traversals

> **Pattern:** DFS (Pre/In/Post-order) & BFS (Level-order) — foundation of nearly all tree problems.

175. [Binary Tree Inorder Traversal (iterative)](https://leetcode.com/problems/binary-tree-inorder-traversal/) `[Easy]`
176. [Binary Tree Preorder Traversal (iterative)](https://leetcode.com/problems/binary-tree-preorder-traversal/) `[Easy]`
177. [Binary Tree Postorder Traversal (iterative)](https://leetcode.com/problems/binary-tree-postorder-traversal/) `[Easy]`
178. [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) `[Medium]`
179. [Binary Tree Zigzag Level Order](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) `[Medium]`
180. [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) `[Medium]`
181. [Average of Levels in Binary Tree](https://leetcode.com/problems/average-of-levels-in-binary-tree/) `[Easy]`
182. [N-ary Tree Level Order Traversal](https://leetcode.com/problems/n-ary-tree-level-order-traversal/) `[Medium]`
183. [Vertical Order Traversal](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) `[Hard]`
184. [Boundary Traversal of Binary Tree](https://leetcode.com/problems/boundary-of-binary-tree/) `[Medium]`

### 6.2 Binary Tree Properties

> **Pattern:** Tree Recursion — solve sub-problems on left/right subtrees and combine results.

185. [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) `[Easy]`
186. [Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/) `[Easy]`
187. [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) `[Easy]`
188. [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) `[Easy]`
189. [Same Tree](https://leetcode.com/problems/same-tree/) `[Easy]`
190. [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) `[Easy]`
191. [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) `[Easy]`
192. [Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) `[Medium]`
193. [Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) `[Easy]`
194. [Path Sum](https://leetcode.com/problems/path-sum/) `[Easy]`
195. [Path Sum II (all paths)](https://leetcode.com/problems/path-sum-ii/) `[Medium]`
196. [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) `[Hard]`
197. [Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) `[Medium]`
198. [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) `[Medium]`
199. [Populating Next Right Pointers](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) `[Medium]`

### 6.3 Binary Search Trees (BST)

> **Pattern:** BST Property — left < root < right; enables O(log n) search, insert, delete.

200. [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) `[Medium]`
201. [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) `[Medium]`
202. [Lowest Common Ancestor of BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) `[Easy]`
203. [Lowest Common Ancestor of Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) `[Medium]`
204. [Convert Sorted Array to BST](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) `[Easy]`
205. [Convert BST to Greater Tree](https://leetcode.com/problems/convert-bst-to-greater-tree/) `[Medium]`
206. [Insert into a BST](https://leetcode.com/problems/insert-into-a-binary-search-tree/) `[Medium]`
207. [Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) `[Medium]`
208. [Recover Binary Search Tree (two nodes swapped)](https://leetcode.com/problems/recover-binary-search-tree/) `[Hard]`
209. [Unique Binary Search Trees (count)](https://leetcode.com/problems/unique-binary-search-trees/) `[Medium]`
210. [Unique Binary Search Trees II (generate all)](https://leetcode.com/problems/unique-binary-search-trees-ii/) `[Medium]`
211. [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) `[Hard]`
212. [Binary Tree Cameras](https://leetcode.com/problems/binary-tree-cameras/) `[Hard]`
213. [Construct BST from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/) `[Medium]`
214. [Two Sum IV in BST](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/) `[Easy]`

### 6.4 Segment Trees & BITs (Advanced)

> **Pattern:** Segment Tree / Fenwick Tree — O(log n) range queries and point updates.

215. [Range Sum Query — Mutable (Segment Tree / BIT)](https://leetcode.com/problems/range-sum-query-mutable/) `[Medium]`
216. [Range Minimum Query](https://leetcode.com/problems/range-sum-query-mutable/) `[Medium]` — ≈ *Range Sum Query - Mutable* (segment-tree home on LC; RMQ itself is textbook)
217. [Count of Range Sum (Merge Sort / BIT)](https://leetcode.com/problems/count-of-range-sum/) `[Hard]`
218. [Number of Longest Increasing Subsequences (Segment Tree)](https://leetcode.com/problems/number-of-longest-increasing-subsequence/) `[Medium]`
219. [The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) `[Hard]`
220. [My Calendar I, II, III](https://leetcode.com/problems/my-calendar-i/) `[Medium]`
221. [Rectangle Area II (coordinate compression)](https://leetcode.com/problems/rectangle-area-ii/) `[Hard]`
222. [Falling Squares](https://leetcode.com/problems/falling-squares/) `[Hard]`
223. [Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/) `[Medium]`
224. [Data Stream as Disjoint Intervals](https://leetcode.com/problems/data-stream-as-disjoint-intervals/) `[Hard]`

### 6.5 Tries

> **Pattern:** Trie (Prefix Tree) — efficient prefix search and autocomplete in O(L) per query.

225. [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) `[Medium]`
226. [Word Search II (Trie + DFS)](https://leetcode.com/problems/word-search-ii/) `[Hard]`
227. [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) `[Medium]`
228. [Replace Words with Root (Trie)](https://leetcode.com/problems/replace-words/) `[Medium]`
229. [Maximum XOR of Two Numbers (Trie)](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) `[Medium]`
230. [Palindrome Pairs (Trie)](https://leetcode.com/problems/palindrome-pairs/) `[Hard]`
## Section 7: Heaps & Priority Queues (Q232 – Q255)

### 7.1 Top-K Pattern

> **Pattern:** Min-Heap of size K — maintain the K largest elements efficiently.

231. [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) `[Easy]`
232. [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) `[Medium]`
233. [Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/) `[Medium]`
234. [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) `[Medium]`
235. [Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/) `[Medium]`
236. [Kth Smallest Element in Sorted Matrix (Heap)](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) `[Medium]`
237. [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) `[Medium]`
238. [Reorganize String](https://leetcode.com/problems/reorganize-string/) `[Medium]`
239. [Task Scheduler (Heap approach)](https://leetcode.com/problems/task-scheduler/) `[Medium]`
240. [Maximum Frequency Stack](https://leetcode.com/problems/maximum-frequency-stack/) `[Hard]`

### 7.2 Two-Heap Pattern

> **Pattern:** Two Heaps — one max-heap and one min-heap to find the median dynamically.

241. [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) `[Hard]`
242. [Sliding Window Median](https://leetcode.com/problems/sliding-window-median/) `[Hard]`
243. [IPO (Maximize Capital)](https://leetcode.com/problems/ipo/) `[Hard]`
244. [Minimum Cost to Connect Sticks](https://leetcode.com/problems/minimum-cost-to-connect-sticks/) `[Medium]`
245. [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) `[Hard]`
246. [Ugly Number II](https://leetcode.com/problems/ugly-number-ii/) `[Medium]`
247. [Super Ugly Number](https://leetcode.com/problems/super-ugly-number/) `[Medium]`
248. [Meeting Rooms III (heap-based room assignment)](https://leetcode.com/problems/meeting-rooms-iii/) `[Hard]`
249. [Employee Free Time](https://leetcode.com/problems/employee-free-time/) `[Hard]`
250. [Process Tasks Using Servers](https://leetcode.com/problems/process-tasks-using-servers/) `[Medium]`
251. [Single-Threaded CPU](https://leetcode.com/problems/single-threaded-cpu/) `[Medium]`
252. [Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/) `[Medium]`
## Section 8: Graphs (Q256 – Q310)

### 8.1 BFS (Shortest Path / Level-order)

> **Pattern:** BFS — explore nodes level by level; guarantees shortest path in unweighted graphs.

253. [Number of Islands](https://leetcode.com/problems/number-of-islands/) `[Medium]`
254. [Max Area of Island](https://leetcode.com/problems/max-area-of-island/) `[Medium]`
255. [Flood Fill](https://leetcode.com/problems/flood-fill/) `[Easy]`
256. [Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/) `[Medium]`
257. [01 Matrix (multi-source BFS)](https://leetcode.com/problems/01-matrix/) `[Medium]`
258. [Rotting Oranges](https://leetcode.com/problems/rotting-oranges/) `[Medium]`
259. [Walls and Gates (multi-source BFS)](https://leetcode.com/problems/walls-and-gates/) `[Medium]`
260. [Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/) `[Medium]`
261. [Snakes and Ladders](https://leetcode.com/problems/snakes-and-ladders/) `[Medium]`
262. [Open the Lock](https://leetcode.com/problems/open-the-lock/) `[Medium]`
263. [Word Ladder](https://leetcode.com/problems/word-ladder/) `[Hard]`
264. [Word Ladder II (all shortest paths)](https://leetcode.com/problems/word-ladder-ii/) `[Hard]`
265. [Minimum Knight Moves](https://leetcode.com/problems/minimum-knight-moves/) `[Medium]`
266. [Bus Routes (BFS on routes)](https://leetcode.com/problems/bus-routes/) `[Hard]`
267. [Cut Off Trees for Golf Event](https://leetcode.com/problems/cut-off-trees-for-golf-event/) `[Hard]`

### 8.2 DFS / Backtracking on Graphs

> **Pattern:** DFS with Visited Set — explore all paths; detect cycles and connected components.

268. [Clone Graph](https://leetcode.com/problems/clone-graph/) `[Medium]`
269. [Course Schedule (cycle detection)](https://leetcode.com/problems/course-schedule/) `[Medium]`
270. [Course Schedule II (topological sort)](https://leetcode.com/problems/course-schedule-ii/) `[Medium]`
271. [Number of Connected Components in Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) `[Medium]`
272. [Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) `[Medium]`
273. [Redundant Connection (Union-Find)](https://leetcode.com/problems/redundant-connection/) `[Medium]`
274. [Accounts Merge (Union-Find / DFS)](https://leetcode.com/problems/accounts-merge/) `[Medium]`
275. [All Paths from Source to Target](https://leetcode.com/problems/all-paths-from-source-to-target/) `[Medium]`
276. [Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/) `[Medium]`
277. [Possible Bipartition](https://leetcode.com/problems/possible-bipartition/) `[Medium]`

### 8.3 Topological Sort

> **Pattern:** Kahn's Algorithm / DFS Post-order — linear ordering of nodes in a DAG.

278. [Alien Dictionary](https://leetcode.com/problems/alien-dictionary/) `[Hard]`
279. [Sequence Reconstruction](https://leetcode.com/problems/sequence-reconstruction/) `[Medium]`
280. [Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/) `[Medium]`
281. [Find Eventual Safe States](https://leetcode.com/problems/find-eventual-safe-states/) `[Medium]`
282. [Parallel Courses (min semesters)](https://leetcode.com/problems/parallel-courses/) `[Medium]`
283. [Sort Items by Groups Respecting Dependencies](https://leetcode.com/problems/sort-items-by-groups-respecting-dependencies/) `[Hard]`

### 8.4 Union-Find (Disjoint Set Union)

> **Pattern:** DSU with Path Compression + Union by Rank — near-O(1) amortised operations.

284. [Find if Path Exists in Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/) `[Easy]`
285. [Number of Provinces](https://leetcode.com/problems/number-of-provinces/) `[Medium]`
286. [Redundant Connection II (directed)](https://leetcode.com/problems/redundant-connection-ii/) `[Hard]`
287. [Making a Large Island](https://leetcode.com/problems/making-a-large-island/) `[Hard]`
288. [Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/) `[Hard]`
289. [Earliest Moment When Everyone Become Friends](https://leetcode.com/problems/the-earliest-moment-when-everyone-become-friends/) `[Medium]`
290. [Satisfiability of Equality Equations](https://leetcode.com/problems/satisfiability-of-equality-equations/) `[Medium]`
291. [Remove Max Number of Edges to Keep Graph Fully Traversable](https://leetcode.com/problems/remove-max-number-of-edges-to-keep-graph-fully-traversable/) `[Hard]`

### 8.5 Shortest Path Algorithms

> **Pattern:** Dijkstra / Bellman-Ford / Floyd-Warshall — weighted shortest paths.

292. [Network Delay Time (Dijkstra)](https://leetcode.com/problems/network-delay-time/) `[Medium]`
293. [Path with Maximum Probability](https://leetcode.com/problems/path-with-maximum-probability/) `[Medium]`
294. [Cheapest Flights Within K Stops (Bellman-Ford)](https://leetcode.com/problems/cheapest-flights-within-k-stops/) `[Medium]`
295. [Find the City with Smallest Number of Neighbors (Floyd-Warshall)](https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/) `[Medium]`
296. [Path with Minimum Effort (Dijkstra / Binary Search)](https://leetcode.com/problems/path-with-minimum-effort/) `[Medium]`
297. [Number of Ways to Arrive at Destination](https://leetcode.com/problems/number-of-ways-to-arrive-at-destination/) `[Medium]`
298. [Minimum Weighted Subgraph with Required Paths](https://leetcode.com/problems/minimum-weighted-subgraph-with-the-required-paths/) `[Hard]`
299. [Minimum Score of a Path Between Two Cities](https://leetcode.com/problems/minimum-score-of-a-path-between-two-cities/) `[Medium]`
300. [Reachable Nodes in Subdivided Graph](https://leetcode.com/problems/reachable-nodes-in-subdivided-graph/) `[Hard]`
301. K-th Shortest Path (Yen's Algorithm concept) `[Hard]` — *no LeetCode equivalent (algorithm concept (Yen's), not a LC problem)*

### 8.6 Minimum Spanning Tree

> **Pattern:** Kruskal's / Prim's — greedily build a spanning tree with minimum total edge weight.

302. [Min Cost to Connect All Points (Prim's)](https://leetcode.com/problems/min-cost-to-connect-all-points/) `[Medium]`
303. [Optimize Water Distribution in a Village](https://leetcode.com/problems/optimize-water-distribution-in-a-village/) `[Hard]`
304. [Critical Connections in a Network (Bridges)](https://leetcode.com/problems/critical-connections-in-a-network/) `[Hard]`
305. [Minimum Cost to Reach City with Tolls](https://leetcode.com/problems/minimum-cost-to-reach-city-with-discounts/) `[Medium]` — ≈ *Minimum Cost to Reach City With Discounts* (LC uses discounts rather than tolls)
306. [Find Critical and Pseudo-Critical Edges in MST](https://leetcode.com/problems/find-critical-and-pseudo-critical-edges-in-minimum-spanning-tree/) `[Hard]`
## Section 9: Dynamic Programming (Q311 – Q390)

### 9.1 1-D DP (Linear Recurrences)

> **Pattern:** 1-D DP — state is a single index; transition from previous states.

307. [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) `[Easy]`
308. [House Robber](https://leetcode.com/problems/house-robber/) `[Medium]`
309. [House Robber II (circular)](https://leetcode.com/problems/house-robber-ii/) `[Medium]`
310. [House Robber III (tree DP)](https://leetcode.com/problems/house-robber-iii/) `[Medium]`
311. [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) `[Easy]`
312. [Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) `[Easy]`
313. [Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number/) `[Easy]`
314. [Coin Change (minimum coins)](https://leetcode.com/problems/coin-change/) `[Medium]`
315. [Coin Change II (number of ways)](https://leetcode.com/problems/coin-change-ii/) `[Medium]`
316. [Perfect Squares](https://leetcode.com/problems/perfect-squares/) `[Medium]`
317. [Integer Break](https://leetcode.com/problems/integer-break/) `[Medium]`
318. [Decode Ways](https://leetcode.com/problems/decode-ways/) `[Medium]`
319. [Decode Ways II](https://leetcode.com/problems/decode-ways-ii/) `[Hard]`
320. [Ugly Number III](https://leetcode.com/problems/ugly-number-iii/) `[Medium]`
321. [N-th Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number/) `[Easy]`

### 9.2 2-D DP (Grid / Two Sequences)

> **Pattern:** 2-D DP — state is two indices (i, j); fill a table row by row.

322. [Unique Paths](https://leetcode.com/problems/unique-paths/) `[Medium]`
323. [Unique Paths II (with obstacles)](https://leetcode.com/problems/unique-paths-ii/) `[Medium]`
324. [Minimum Path Sum in Grid](https://leetcode.com/problems/minimum-path-sum/) `[Medium]`
325. [Dungeon Game (reverse DP)](https://leetcode.com/problems/dungeon-game/) `[Hard]`
326. [Maximal Square](https://leetcode.com/problems/maximal-square/) `[Medium]`
327. [Count Square Submatrices with All Ones](https://leetcode.com/problems/count-square-submatrices-with-all-ones/) `[Medium]`
328. [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) `[Medium]`
329. [Shortest Common Supersequence](https://leetcode.com/problems/shortest-common-supersequence/) `[Hard]`
330. [Edit Distance](https://leetcode.com/problems/edit-distance/) `[Hard]`
331. [Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/) `[Hard]`
332. [Interleaving String](https://leetcode.com/problems/interleaving-string/) `[Medium]`
333. [Regular Expression Matching (DP)](https://leetcode.com/problems/regular-expression-matching/) `[Hard]`
334. [Wildcard Matching (DP)](https://leetcode.com/problems/wildcard-matching/) `[Hard]`
335. [Scramble String](https://leetcode.com/problems/scramble-string/) `[Hard]`
336. [Burst Balloons (interval DP)](https://leetcode.com/problems/burst-balloons/) `[Hard]`

### 9.3 Knapsack Variants

> **Pattern:** 0/1 Knapsack / Unbounded Knapsack — classic DP on items with weight/value.

337. [0/1 Knapsack Problem](https://leetcode.com/problems/partition-equal-subset-sum/) `[Medium]` — ≈ *Partition Equal Subset Sum* (0/1 knapsack feasibility; max-value version not on LC)
338. [Unbounded Knapsack](https://leetcode.com/problems/coin-change-ii/) `[Medium]` — ≈ *Coin Change II* (unbounded knapsack counting; max-value version not on LC)
339. [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) `[Medium]`
340. [Target Sum (assign +/- to reach target)](https://leetcode.com/problems/target-sum/) `[Medium]`
341. [Last Stone Weight II (knapsack)](https://leetcode.com/problems/last-stone-weight-ii/) `[Medium]`
342. [Ones and Zeroes (2D knapsack)](https://leetcode.com/problems/ones-and-zeroes/) `[Medium]`
343. [Profitable Schemes](https://leetcode.com/problems/profitable-schemes/) `[Hard]`
344. [Number of Dice Rolls with Target Sum](https://leetcode.com/problems/number-of-dice-rolls-with-target-sum/) `[Medium]`
345. [Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) `[Medium]`
346. [Count Ways to Build Good Strings](https://leetcode.com/problems/count-ways-to-build-good-strings/) `[Medium]`

### 9.4 Interval / Range DP

> **Pattern:** Interval DP — solve subproblems over all intervals [i, j], merge results.

347. [Matrix Chain Multiplication](https://leetcode.com/problems/burst-balloons/) `[Hard]` — ≈ *Burst Balloons* (same interval-DP pattern as matrix chain multiplication)
348. [Minimum Cost Tree from Leaf Values](https://leetcode.com/problems/minimum-cost-tree-from-leaf-values/) `[Medium]`
349. [Strange Printer](https://leetcode.com/problems/strange-printer/) `[Hard]`
350. [Remove Boxes](https://leetcode.com/problems/remove-boxes/) `[Hard]`
351. [Zuma Game](https://leetcode.com/problems/zuma-game/) `[Hard]`
352. [Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) `[Hard]`
353. [Optimal Strategy for a Game](https://leetcode.com/problems/predict-the-winner/) `[Medium]`
354. [Palindrome Partitioning II (min cuts)](https://leetcode.com/problems/palindrome-partitioning-ii/) `[Hard]`
355. [Palindrome Partitioning IV (3 parts)](https://leetcode.com/problems/palindrome-partitioning-iv/) `[Hard]`
356. [Maximum Coins You Can Get](https://leetcode.com/problems/maximum-number-of-coins-you-can-get/) `[Medium]`

### 9.5 State-Machine DP (Stocks & Transactions)

> **Pattern:** State Machine DP — model allowed states (holding/not holding) and transitions.

357. [Best Time to Buy and Sell Stock III (at most 2 transactions)](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/) `[Hard]`
358. [Best Time to Buy and Sell Stock IV (at most k transactions)](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/) `[Hard]`
359. [Best Time to Buy and Sell Stock with Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) `[Medium]`
360. [Best Time to Buy and Sell Stock with Transaction Fee](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) `[Medium]`
361. [Paint House](https://leetcode.com/problems/paint-house/) `[Medium]`
362. [Paint House II (k colors)](https://leetcode.com/problems/paint-house-ii/) `[Hard]`
363. [Paint Fence](https://leetcode.com/problems/paint-fence/) `[Medium]`
364. [Student Attendance Record II](https://leetcode.com/problems/student-attendance-record-ii/) `[Hard]`
365. [Coin Path (min cost with k steps)](https://leetcode.com/problems/coin-path/) `[Hard]`
366. [Number of Ways to Stay in the Same Place After Some Steps](https://leetcode.com/problems/number-of-ways-to-stay-in-the-same-place-after-some-steps/) `[Hard]`

### 9.6 Bitmask DP

> **Pattern:** Bitmask DP — represent subsets as bitmasks; ideal for small n (≤20).

367. [Traveling Salesman Problem (bitmask DP)](https://leetcode.com/problems/shortest-path-visiting-all-nodes/) `[Hard]` — ≈ *Shortest Path Visiting All Nodes* (TSP-style bitmask DP over subsets)
368. [Partition to K Equal Sum Subsets](https://leetcode.com/problems/partition-to-k-equal-sum-subsets/) `[Medium]`
369. [Minimum XOR Sum of Two Arrays (assignment)](https://leetcode.com/problems/minimum-xor-sum-of-two-arrays/) `[Hard]`
370. [Maximum Students Taking Exam](https://leetcode.com/problems/maximum-students-taking-exam/) `[Hard]`
371. [Stickers to Spell Word](https://leetcode.com/problems/stickers-to-spell-word/) `[Hard]`
372. [Shortest Path Visiting All Nodes (BFS + bitmask)](https://leetcode.com/problems/shortest-path-visiting-all-nodes/) `[Hard]`
373. [Number of Ways to Wear Different Hats to Each Other](https://leetcode.com/problems/number-of-ways-to-wear-different-hats-to-each-other/) `[Hard]`
374. [Count Ways to Distribute Candies](https://leetcode.com/problems/count-ways-to-distribute-candies/) `[Hard]`
375. [Maximize Score After N Operations](https://leetcode.com/problems/maximize-score-after-n-operations/) `[Hard]`
376. [Find the Shortest Superstring (bitmask DP)](https://leetcode.com/problems/find-the-shortest-superstring/) `[Hard]`

### 9.7 DP on Trees & Graphs

377. [Diameter of N-ary Tree](https://leetcode.com/problems/diameter-of-n-ary-tree/) `[Hard]`
378. [Binary Tree Maximum Path Sum (revisited)](https://leetcode.com/problems/binary-tree-maximum-path-sum/) `[Hard]`
379. [Maximum Sum of 3 Non-Overlapping Subarrays](https://leetcode.com/problems/maximum-sum-of-3-non-overlapping-subarrays/) `[Hard]`
380. [Cherry Pickup](https://leetcode.com/problems/cherry-pickup/) `[Hard]`
381. [Cherry Pickup II (two robots)](https://leetcode.com/problems/cherry-pickup-ii/) `[Hard]`
382. [Minimum Difficulty of a Job Schedule](https://leetcode.com/problems/minimum-difficulty-of-a-job-schedule/) `[Hard]`
383. [Build Array Where You Can Find the Maximum Exactly K Comparisons](https://leetcode.com/problems/build-array-where-you-can-find-the-maximum-exactly-k-comparisons/) `[Hard]`
384. [Number of Music Playlists](https://leetcode.com/problems/number-of-music-playlists/) `[Hard]`
385. [Count Vowels Permutation](https://leetcode.com/problems/count-vowels-permutation/) `[Hard]`
386. [Minimum Cost to Cut a Stick](https://leetcode.com/problems/minimum-cost-to-cut-a-stick/) `[Hard]`
## Section 10: Backtracking (Q391 – Q420)

### 10.1 Subsets & Combinations

> **Pattern:** Backtracking — explore all choices recursively; prune branches that violate constraints.

387. [Subsets](https://leetcode.com/problems/subsets/) `[Medium]`
388. [Subsets II (with duplicates)](https://leetcode.com/problems/subsets-ii/) `[Medium]`
389. [Combinations](https://leetcode.com/problems/combinations/) `[Medium]`
390. [Combination Sum](https://leetcode.com/problems/combination-sum/) `[Medium]`
391. [Combination Sum II (each number once)](https://leetcode.com/problems/combination-sum-ii/) `[Medium]`
392. [Combination Sum III (exactly k numbers)](https://leetcode.com/problems/combination-sum-iii/) `[Medium]`
393. [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) `[Medium]`
394. [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) `[Medium]`
395. [Count Numbers with Unique Digits](https://leetcode.com/problems/count-numbers-with-unique-digits/) `[Medium]`
396. [Beautiful Arrangement](https://leetcode.com/problems/beautiful-arrangement/) `[Medium]`

### 10.2 Permutations

> **Pattern:** Permutation Backtracking — swap elements or use a visited array.

397. [Permutations](https://leetcode.com/problems/permutations/) `[Medium]`
398. [Permutations II (with duplicates)](https://leetcode.com/problems/permutations-ii/) `[Medium]`
399. [Next Permutation](https://leetcode.com/problems/next-permutation/) `[Medium]`
400. [Permutation Sequence (kth permutation)](https://leetcode.com/problems/permutation-sequence/) `[Hard]`
401. [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) `[Medium]`
402. [Word Search](https://leetcode.com/problems/word-search/) `[Medium]`
403. [N-Queens](https://leetcode.com/problems/n-queens/) `[Hard]`
404. [N-Queens II (count solutions)](https://leetcode.com/problems/n-queens-ii/) `[Hard]`
405. [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) `[Hard]`
406. [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) `[Hard]`

### 10.3 Advanced Backtracking

407. [Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) `[Hard]`
408. [Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) `[Medium]`
409. [Letter Tile Possibilities](https://leetcode.com/problems/letter-tile-possibilities/) `[Medium]`
410. [Splitting a String Into Descending Consecutive Values](https://leetcode.com/problems/splitting-a-string-into-descending-consecutive-values/) `[Medium]`
411. [Number of Squareful Arrays](https://leetcode.com/problems/number-of-squareful-arrays/) `[Hard]`
412. [Maximum Length of a Concatenated String with Unique Characters](https://leetcode.com/problems/maximum-length-of-a-concatenated-string-with-unique-characters/) `[Medium]`
413. [Tiling a Rectangle with the Fewest Squares](https://leetcode.com/problems/tiling-a-rectangle-with-the-fewest-squares/) `[Hard]`
414. [Coloring a Border](https://leetcode.com/problems/coloring-a-border/) `[Medium]`
415. [Factor Combinations](https://leetcode.com/problems/factor-combinations/) `[Medium]`
416. [Construct the Lexicographically Largest Valid Sequence](https://leetcode.com/problems/construct-the-lexicographically-largest-valid-sequence/) `[Medium]`
## Section 11: Greedy Algorithms (Q421 – Q445)

### 11.1 Interval & Scheduling Greedy

> **Pattern:** Greedy Selection — always pick the locally optimal choice; prove exchange argument.

417. [Activity Selection / Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) `[Medium]`
418. [Minimum Number of Platforms Required](https://leetcode.com/problems/meeting-rooms-ii/) `[Medium]`
419. Job Sequencing Problem `[Medium]` — *no LeetCode equivalent (GFG classic)*
420. Fractional Knapsack `[Easy]` — *no LeetCode equivalent (GFG greedy classic)*
421. [N meetings in one room](https://leetcode.com/problems/non-overlapping-intervals/) `[Easy]`
422. [Assign Cookies](https://leetcode.com/problems/assign-cookies/) `[Easy]`
423. [Lemonade Change](https://leetcode.com/problems/lemonade-change/) `[Easy]`
424. [Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) `[Medium]`
425. [Two City Scheduling](https://leetcode.com/problems/two-city-scheduling/) `[Medium]`
426. [Minimum Cost to Move Chips to Same Position](https://leetcode.com/problems/minimum-cost-to-move-chips-to-the-same-position/) `[Easy]`

### 11.2 String & Array Greedy

427. [Remove K Digits (smallest number)](https://leetcode.com/problems/remove-k-digits/) `[Medium]`
428. [Largest Number After Removing k Digits (largest)](https://leetcode.com/problems/remove-k-digits/) `[Medium]`
429. [Maximum Units on a Truck](https://leetcode.com/problems/maximum-units-on-a-truck/) `[Easy]`
430. [Minimum Deletions to Make Character Frequencies Unique](https://leetcode.com/problems/minimum-deletions-to-make-character-frequencies-unique/) `[Medium]`
431. [Minimum Number of Flips to Make Binary String Alternating](https://leetcode.com/problems/minimum-number-of-flips-to-make-the-binary-string-alternating/) `[Medium]`
432. [Minimum Swaps to Balance Parentheses](https://leetcode.com/problems/minimum-number-of-swaps-to-make-the-string-balanced/) `[Medium]`
433. [Maximum Score from Removing Substrings](https://leetcode.com/problems/maximum-score-from-removing-substrings/) `[Medium]`
434. [Wiggle Subsequence](https://leetcode.com/problems/wiggle-subsequence/) `[Medium]`
435. [Dota2 Senate (greedy queue)](https://leetcode.com/problems/dota2-senate/) `[Medium]`
436. [Minimum Time to Make Rope Colorful](https://leetcode.com/problems/minimum-time-to-make-rope-colorful/) `[Medium]`
437. [Boats to Save People](https://leetcode.com/problems/boats-to-save-people/) `[Medium]`
438. [Advantage Shuffle](https://leetcode.com/problems/advantage-shuffle/) `[Medium]`
439. [Maximum Performance of a Team](https://leetcode.com/problems/maximum-performance-of-a-team/) `[Hard]`
440. [Minimize Maximum Pair Sum in Array](https://leetcode.com/problems/minimize-maximum-pair-sum-in-array/) `[Medium]`
441. Earliest Deadline First Scheduling `[Medium]` — *no LeetCode equivalent (scheduling theory, not a LC problem)*
## Section 12: Hashing, Math & Bit Manipulation (Q446 – Q470)

### 12.1 HashMap / HashSet Patterns

> **Pattern:** HashMap — O(1) lookups to avoid nested loops; track frequency, index, or pairs.

442. [Two Sum (HashMap)](https://leetcode.com/problems/two-sum/) `[Easy]`
443. [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) `[Medium]`
444. [4Sum II (count tuples)](https://leetcode.com/problems/4sum-ii/) `[Medium]`
445. [Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/) `[Easy]`
446. [Word Pattern](https://leetcode.com/problems/word-pattern/) `[Easy]`
447. [Bulls and Cows](https://leetcode.com/problems/bulls-and-cows/) `[Medium]`
448. [Brick Wall (maximum bricks not cut)](https://leetcode.com/problems/brick-wall/) `[Medium]`
449. [Subarray Sum Equals K (revisited with HashMap)](https://leetcode.com/problems/subarray-sum-equals-k/) `[Medium]`
450. [Contiguous Array (equal 0s and 1s)](https://leetcode.com/problems/contiguous-array/) `[Medium]`
451. [Maximum Size Subarray Sum Equals k](https://leetcode.com/problems/maximum-size-subarray-sum-equals-k/) `[Medium]`

### 12.2 Math & Number Theory

> **Pattern:** Number Theory — prime sieves, GCD/LCM, modular arithmetic, combinatorics.

452. [Count Primes (Sieve of Eratosthenes)](https://leetcode.com/problems/count-primes/) `[Medium]`
453. [Power of Two / Three / Four](https://leetcode.com/problems/power-of-two/) `[Easy]`
454. [Excel Sheet Column Number](https://leetcode.com/problems/excel-sheet-column-number/) `[Easy]`
455. [Happy Number (Floyd's cycle)](https://leetcode.com/problems/happy-number/) `[Easy]`
456. [Ugly Number](https://leetcode.com/problems/ugly-number/) `[Easy]`
457. [Reverse Integer](https://leetcode.com/problems/reverse-integer/) `[Medium]`
458. [Palindrome Number](https://leetcode.com/problems/palindrome-number/) `[Easy]`
459. [Factorial Trailing Zeroes](https://leetcode.com/problems/factorial-trailing-zeroes/) `[Medium]`
460. [Nth Digit](https://leetcode.com/problems/nth-digit/) `[Medium]`
461. [Super Power (modular exponentiation)](https://leetcode.com/problems/super-pow/) `[Medium]`

### 12.3 Bit Manipulation

> **Pattern:** Bit Tricks — XOR, AND/OR masks, Brian Kernighan's algorithm for O(1) bit operations.

462. [Single Number](https://leetcode.com/problems/single-number/) `[Easy]`
463. [Single Number II (bit counting)](https://leetcode.com/problems/single-number-ii/) `[Medium]`
464. [Single Number III (two unique)](https://leetcode.com/problems/single-number-iii/) `[Medium]`
465. [Number of 1 Bits (Hamming Weight)](https://leetcode.com/problems/number-of-1-bits/) `[Easy]`
466. [Counting Bits (0 to n)](https://leetcode.com/problems/counting-bits/) `[Easy]`
467. [Reverse Bits](https://leetcode.com/problems/reverse-bits/) `[Easy]`
468. [Missing Number](https://leetcode.com/problems/missing-number/) `[Easy]`
469. [Sum of Two Integers (without + operator)](https://leetcode.com/problems/sum-of-two-integers/) `[Medium]`
470. [Maximum XOR of Two Numbers in Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) `[Medium]`
471. [UTF-8 Validation](https://leetcode.com/problems/utf-8-validation/) `[Medium]`
## Section 13: System Design & Data Structure Design (Q471 – Q500)

### 13.1 Classic Design Problems

> **Pattern:** OOP + Right Data Structures — combine hash maps, heaps, doubly linked lists for O(1) ops.

472. [Design LRU Cache](https://leetcode.com/problems/lru-cache/) `[Medium]`
473. [Design LFU Cache](https://leetcode.com/problems/lfu-cache/) `[Hard]`
474. [Design Twitter (top 10 tweets feed)](https://leetcode.com/problems/design-twitter/) `[Medium]`
475. [Design a Hit Counter](https://leetcode.com/problems/design-hit-counter/) `[Medium]`
476. [Design a Rate Limiter (token bucket)](https://leetcode.com/problems/logger-rate-limiter/) `[Medium]` — ≈ *Logger Rate Limiter* (fixed-window logger, not a token bucket)
477. [Design In-Memory File System](https://leetcode.com/problems/design-in-memory-file-system/) `[Hard]`
478. [Design Search Autocomplete System (Trie + heap)](https://leetcode.com/problems/design-search-autocomplete-system/) `[Hard]`
479. [Design a Phone Directory](https://leetcode.com/problems/design-phone-directory/) `[Medium]`
480. [Implement Trie with Count](https://leetcode.com/problems/implement-trie-ii-prefix-tree/) `[Medium]`
481. [Design Underground System (check-in/check-out)](https://leetcode.com/problems/design-underground-system/) `[Medium]`

### 13.2 Randomized & Probabilistic Structures

> **Pattern:** Reservoir Sampling / Fisher-Yates — uniform random sampling in O(1) space.

482. [Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/) `[Medium]`
483. [Random Pick Index (reservoir sampling)](https://leetcode.com/problems/random-pick-index/) `[Medium]`
484. [Linked List Random Node](https://leetcode.com/problems/linked-list-random-node/) `[Medium]`
485. [Random Pick with Weight](https://leetcode.com/problems/random-pick-with-weight/) `[Medium]`
486. [Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/) `[Medium]`
487. [Insert Delete GetRandom O(1) — Duplicates Allowed](https://leetcode.com/problems/insert-delete-getrandom-o1-duplicates-allowed/) `[Hard]`

### 13.3 Stream / Online Algorithms

> **Pattern:** Online Algorithms — process data one element at a time without looking back.

488. [Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) `[Easy]`
489. [Find Median from Data Stream (revisited)](https://leetcode.com/problems/find-median-from-data-stream/) `[Hard]`
490. [Kth Largest Element in a Stream (revisited)](https://leetcode.com/problems/kth-largest-element-in-a-stream/) `[Easy]`
491. [Design a Stack with Increment Operation](https://leetcode.com/problems/design-a-stack-with-increment-operation/) `[Medium]`
492. [Design a Stack with getMin() / getMax()](https://leetcode.com/problems/min-stack/) `[Easy]`
493. [Time-Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/) `[Medium]`
494. [Design an Ordered Stream](https://leetcode.com/problems/design-an-ordered-stream/) `[Easy]`
495. [Snapshot Array](https://leetcode.com/problems/snapshot-array/) `[Medium]`
496. [Design a Log Aggregation System](https://leetcode.com/problems/design-log-storage-system/) `[Medium]` — ≈ *Design Log Storage System* (storage/query rather than full aggregation)
497. [First Unique Number in Stream](https://leetcode.com/problems/first-unique-number/) `[Medium]`

### 13.4 Advanced Design Challenges

498. [Word Filter (prefix + suffix search, Trie)](https://leetcode.com/problems/prefix-and-suffix-search/) `[Hard]`
499. [Exam Room (seat assignment)](https://leetcode.com/problems/exam-room/) `[Medium]`
500. [My Calendar I / II / III](https://leetcode.com/problems/my-calendar-i/) `[Medium]`
501. [Range Module (add/remove/query ranges)](https://leetcode.com/problems/range-module/) `[Hard]`
502. [All O'one Data Structure (O(1) min/max string freq)](https://leetcode.com/problems/all-oone-data-structure/) `[Hard]`
503. [Design a Food Rating System](https://leetcode.com/problems/design-a-food-rating-system/) `[Medium]`
504. [Stock Price Fluctuation (max/min with updates)](https://leetcode.com/problems/stock-price-fluctuation/) `[Medium]`
505. [Find Servers That Handled Most Requests](https://leetcode.com/problems/find-servers-that-handled-most-number-of-requests/) `[Hard]`
506. [Booking Concert Tickets in Groups](https://leetcode.com/problems/booking-concert-tickets-in-groups/) `[Hard]`
507. [Subrectangle Queries](https://leetcode.com/problems/subrectangle-queries/) `[Medium]`
## Appendix A: Topic Summary & Pattern Quick-Reference

| Section | Topic | Q Range | Key Pattern(s) |
|---:|---|---|---|
| 1 | Arrays | 1 – 50 | Two Pointers, Sliding Window, Prefix Sum, Kadane's |
| 2 | Strings | 51 – 90 | HashMap, Sliding Window, KMP, Monotonic Stack |
| 3 | Linked Lists | 91 – 120 | Fast & Slow Pointers, In-place Reversal, Merge |
| 4 | Stacks & Queues | 121 – 145 | Monotonic Stack, Monotonic Deque, BFS |
| 5 | Binary Search | 146 – 175 | Classic BS, Parametric Search, Bisect |
| 6 | Trees | 176 – 231 | DFS/BFS, Recursion, BST, Segment Tree, Trie |
| 7 | Heaps | 232 – 255 | Top-K (min-heap), Two-Heap Median |
| 8 | Graphs | 256 – 310 | BFS, DFS, Topo Sort, DSU, Dijkstra, MST |
| 9 | Dynamic Programming | 311 – 390 | 1-D/2-D DP, Knapsack, Interval, Bitmask, State-Machine |
| 10 | Backtracking | 391 – 420 | Subset/Combo, Permutation, Constraint Pruning |
| 11 | Greedy | 421 – 445 | Interval Greedy, Exchange Argument |
| 12 | Hashing & Math | 446 – 470 | HashMap, Number Theory, Bit Manipulation |
| 13 | Design | 471 – 500 | OOP + HashMap/Heap/Trie, Reservoir Sampling |

## Appendix B: Recommended 12-Week Study Plan

**Week 1–2:** Arrays (Q1–Q50) + Strings (Q51–Q90) — master sliding window and two-pointer patterns.

**Week 3:** Linked Lists (Q91–Q120) + Stacks & Queues (Q121–Q145) — pointer manipulation and monotonic structures.

**Week 4:** Binary Search (Q146–Q175) — classic and parametric search; practice writing bug-free lo/hi/mid logic.

**Week 5–6:** Trees (Q176–Q231) + Heaps (Q232–Q255) — DFS/BFS recursion, BST operations, Trie, priority queues.

**Week 7–8:** Graphs (Q256–Q310) — BFS/DFS, topological sort, Union-Find, Dijkstra, MST.

**Week 9–10:** Dynamic Programming (Q311–Q390) — start with 1-D, progress to 2-D, knapsack, interval, bitmask.

**Week 11:** Backtracking (Q391–Q420) + Greedy (Q421–Q445) — pruning strategies, exchange argument proofs.

**Week 12:** Hashing & Math (Q446–Q470) + Design (Q471–Q500) — mock interviews; time yourself strictly.

## Closing Remarks

Consistent, pattern-focused practice is the most reliable path to success in FAANG-level technical interviews. Rather than memorising solutions, internalise the underlying pattern for each problem category. When you encounter an unfamiliar problem, identify which pattern it resembles and apply the corresponding template. Complement this list with timed mock interviews, peer code reviews, and systematic complexity analysis (time and space) for every solution you write.

Best of luck with your preparation. You have everything you need — now execute.

