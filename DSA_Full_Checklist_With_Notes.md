# DSA Patterns Tracker

## Pattern 1: Two Pointers - Converging (Sorted Array Target Sum)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 1 | Container With Most Water (11) | [ ] | |
| 2 | 3Sum (15) | :heavy_check_mark: | |
| 3 | 3Sum Closest (16) | :heavy_check_mark: | |
| 4 | 4Sum (18) | [ ] | |
| 5 | Two Sum II - Input Array Is Sorted (167) | [ ] | |
| 6 | Intersection of Two Arrays (349) | [ ] | |
| 7 | Boats to Save People (881) | [ ] | |
| 8 | Squares of a Sorted Array (977) | [ ] | |
| 9 | 3Sum Smaller (259) | [ ] | |

## Pattern 2: Two Pointers - Fast & Slow (Cycle Detection)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 10 | Linked List Cycle (141) | [ ] | |
| 11 | Happy Number (202) | [ ] | |
| 12 | Find the Duplicate Number (287) | [ ] | |
| 13 | Is Subsequence (392) | [ ] | |

## Pattern 3: Two Pointers - Fixed Separation (Nth Node from End)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 14 | Remove Nth Node From End of List (19) | [ ] | |
| 15 | Middle of the Linked List (876) | [ ] | |
| 16 | Delete the Middle Node of a Linked List (2095) | [ ] | |

## Pattern 4: Two Pointers - In-place Array Modification

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 17 | Remove Duplicates from Sorted Array (26) | [ ] | |
| 18 | Remove Element (27) | [ ] | |
| 19 | Sort Colors (75) | [ ] | |
| 20 | Remove Duplicates from Sorted Array II (80) | [ ] | |
| 21 | Move Zeroes (283) | [ ] | |
| 22 | String Compression (443) | [ ] | |
| 23 | Sort Array By Parity (905) | [ ] | |
| 24 | Move Pieces to Obtain a String (2337) | [ ] | |
| 25 | Separate Black and White Balls (2938) | [ ] | |

## Pattern 5: Two Pointers - String Comparison with Backspaces

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 26 | Backspace String Compare (844) | [ ] | |
| 27 | Crawler Log Folder (1598) | [ ] | |
| 28 | Removing Stars From a String (2390) | [ ] | |

## Pattern 6: Two Pointers - Expanding From Center (Palindromes)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 29 | Longest Palindromic Substring (5) | [ ] | |
| 30 | Palindromic Substrings (647) | [ ] | |

## Pattern 7: Two Pointers - String Reversal

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 31 | Reverse Words in a String (151) | [ ] | |
| 32 | Reverse String (344) | [ ] | |
| 33 | Reverse Vowels of a String (345) | [ ] | |
| 34 | Reverse String II (541) | [ ] | |

## Pattern 8: Sliding Window - Fixed Size (Subarray Calculation)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 35 | Moving Average from Data Stream (346) | [ ] | |
| 36 | Maximum Average Subarray I (643) | [ ] | |
| 37 | Calculate Compressed Mean (2985) | [ ] | |
| 38 | Find the Power of K-Size Subarrays I (3254) | [ ] | |
| 39 | Find X-Sum of All K-Long Subarrays I (3318) | [ ] | |

## Pattern 9: Sliding Window - Variable Size (Condition-Based)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 40 | Longest Substring Without Repeating Characters (3) | [ ] | |
| 41 | Minimum Window Substring (76) | [ ] | |
| 42 | Minimum Size Subarray Sum (209) | [ ] | |
| 43 | Contains Duplicate II (219) | [ ] | |
| 44 | Longest Repeating Character Replacement (424) | [ ] | |
| 45 | Subarray Product Less Than K (713) | [ ] | |
| 46 | Fruit Into Baskets (904) | [ ] | |
| 47 | Max Consecutive Ones III (1004) | [ ] | |
| 48 | Longest Continuous Subarray With Absolute Diff Less Than or Equal to Limit (1438) | [ ] | |
| 49 | Longest Subarray of 1's After Deleting One Element (1493) | [ ] | |
| 50 | Minimum Operations to Reduce X to Zero (1658) | [ ] | |
| 51 | Freq (1838) | [ ] | |

## Pattern 10: Sliding Window - Monotonic Queue for Max/Min

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 52 | Sliding Window Maximum (239) | [ ] | |
| 53 | Shortest Subarray with Sum at Least K (862) | ❌ | We need to use deque to track the candidate values and then take the best|
| 54 | Jump Game VI (1696) | ✔️ | Can be done using Dp but we can rather maintain the max in a window of k using deque to avoid recomputation |

## Pattern 11: Sliding Window - Character Frequency Matching

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 55 | TwoSum (1) | [ ] | |
| 56 | Find All Anagrams in a String (438) | [ ] | |
| 57 | Permutation in String (567) | [ ] | |

## Pattern 12: Tree BFS - Level Order Traversal

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 58 | Binary Tree Level Order Traversal (102) | ✔️ | |
| 59 | Binary Tree Zigzag Level Order Traversal (103) | ✔️ | |
| 60 | Binary Tree Right Side View (199) | ✔️ | |
| 61 | Find Largest Value in Each Tree Row (515) | ✔️ | |
| 62 | Maximum Level Sum of a Binary Tree (1161) | [ ] | |

## Pattern 13: Tree DFS - Recursive Preorder Traversal

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 63 | Same Tree (100) | ✔️ | |
| 64 | Symmetric Tree (101) | [ ] | |
| 65 | Construct Binary Tree from Preorder and Inorder Traversal (105) | [ ] | |
| 66 | Flatten Binary Tree to Linked List (114) | [ ] | |
| 67 | Invert Binary Tree (226) | [ ] | |
| 68 | Binary Tree Paths (257) | [ ] | |
| 69 | Smallest String Starting From Leaf (988) | [ ] | |

## Pattern 14: Tree DFS - Recursive Inorder Traversal

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 70 | Binary Tree Inorder Traversal (94) | [ ] | |
| 71 | Validate Binary Search Tree (98) | [ ] | |
| 72 | Binary Search Tree Iterator (173) | [ ] | |
| 73 | Kth Smallest Element in a BST (230) | [ ] | |
| 74 | Find Mode in Binary Search Tree (501) | [ ] | |
| 75 | Minimum Absolute Difference in BST (530) | [ ] | |

## Pattern 15: Tree DFS - Recursive Postorder Traversal

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 76 | Maximum Depth of Binary Tree (104) | [ ] | |
| 77 | Balanced Binary Tree (110) | [ ] | |
| 78 | Binary Tree Maximum Path Sum (124) | [ ] | |
| 79 | Binary Tree Postorder Traversal (145) | [ ] | |
| 80 | House Robber III (337) | [ ] | |
| 81 | Find Leaves of Binary Tree (366) | [ ] | |
| 82 | Diameter of Binary Tree (543) | [ ] | |
| 83 | All Nodes Distance K in Binary Tree (863) | [ ] | |
| 84 | Delete Nodes And Return Forest (1110) | [ ] | |
| 85 | Height of Binary Tree After Subtree Removal Queries (2458) | [ ] | |

## Pattern 16: Tree - Lowest Common Ancestor (LCA) Finding

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 86 | Lowest Common Ancestor of a Binary Search Tree (235) | [ ] | |
| 87 | Lowest Common Ancestor of a Binary Tree (236) | [ ] | |

## Pattern 17: Tree - Serialization and Deserialization

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 88 | Serialize and Deserialize Binary Tree (297) | [ ] | |
| 89 | Subtree of Another Tree (572) | [ ] | |
| 90 | Find Duplicate Subtrees (652) | [ ] | |

## Pattern 18: Graph DFS - Connected Components / Island Counting

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 91 | Surrounded Regions (130) | [ ] | |
| 92 | Number of Islands (200) | [ ] | |
| 93 | Pacific Atlantic Water Flow (417) | [ ] | |
| 94 | Number of Provinces (547) | [ ] | |
| 95 | Max Area of Island (695) | [ ] | |
| 96 | Flood Fill (733) | [ ] | |
| 97 | Keys and Rooms (841) | [ ] | |
| 98 | Number of Enclaves (1020) | [ ] | |
| 99 | Number of Closed Islands (1254) | [ ] | |
| 100 | Count Sub Islands (1905) | [ ] | |
| 101 | Detonate the Maximum Bombs (2101) | [ ] | |

## Pattern 19: Graph BFS - Connected Components / Island Counting

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 102 | 01 Matrix (542) | [ ] | |
| 103 | Rotting Oranges (994) | [ ] | |
| 104 | Shortest Path in Binary Matrix (1091) | [ ] | |

## Pattern 20: Graph DFS - Cycle Detection (Directed Graph)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 105 | Course Schedule (207) | [ ] | |
| 106 | Course Schedule II (210) | [ ] | |
| 107 | Find Eventual Safe States (802) | [ ] | |
| 108 | All Paths from Source Lead to Destination (1059) | [ ] | |

## Pattern 21: Graph BFS - Topological Sort (Kahn's Algorithm)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 109 | Course Schedule II (210) | [ ] | |
| 110 | Alien Dictionary (269) | [ ] | |
| 111 | Minimum Height Trees (310) | [ ] | |
| 112 | Sequence Reconstruction (444) | [ ] | |
| 113 | Parallel Courses (1136) | [ ] | |
| 114 | Largest Color Value in a Directed Graph (1857) | [ ] | |
| 115 | Parallel Courses III (2050) | [ ] | |
| 116 | Find All Possible Recipes from Given Supplies (2115) | [ ] | |
| 117 | Build a Matrix With Conditions (2392) | [ ] | |

## Pattern 22: Graph - Deep Copy / Cloning

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 118 | Clone Graph (133) | [ ] | |
| 119 | Find the City With the Smallest Number of Neighbors at a Threshold Distance (1334) | [ ] | |
| 120 | Copy List with Random Pointer (138) | [ ] | |
| 121 | Clone N-ary Tree (1490) | [ ] | |

## Pattern 23: Graph - Shortest Path (Dijkstra's Algorithm)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 122 | Network Delay Time (743) | [ ] | |
| 123 | Swim in Rising Water (778) | [ ] | |
| 124 | Path with Maximum Probability (1514) | [ ] | |
| 125 | Path With Minimum Effort (1631) | [ ] | |
| 126 | Number of Ways to Arrive at Destination (1976) | [ ] | |
| 127 | Second Minimum Time to Reach Destination (2045) | [ ] | |
| 128 | Minimum Weighted Subgraph With the Required Paths (2203) | [ ] | |
| 129 | Minimum Obstacle Removal to Reach Corner (2290) | [ ] | |
| 130 | Minimum Time to Visit a Cell In a Grid (2577) | [ ] | |
| 131 | Find the Safest Path in a Grid (2812) | [ ] | |

## Pattern 24: Graph - Shortest Path (Bellman-Ford / BFS+K)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 132 | Cheapest Flights Within K Stops (787) | [ ] | |
| 133 | Shortest Path with Alternating Colors (1129) | [ ] | |

## Pattern 25: Graph - Union-Find (Disjoint Set Union - DSU)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 134 | Number of Islands (200) | [ ] | |
| 135 | Graph Valid Tree (261) | [ ] | |
| 136 | Number of Islands II (305) | [ ] | |
| 137 | Number of Connected Components in an Undirected Graph (323) | [ ] | |
| 138 | Number of Provinces (547) | [ ] | |
| 139 | Redundant Connection (684) | [ ] | |
| 140 | Accounts Merge (721) | [ ] | |
| 141 | Sentence Similarity II (737) | [ ] | |
| 142 | Most Stones Removed with Same Row or Column (947) | [ ] | |
| 143 | Largest Component Size by Common Factor (952) | [ ] | |
| 144 | Regions Cut By Slashes (959) | [ ] | |
| 145 | The Earliest Moment When Everyone Become Friends (1101) | [ ] | |

## Pattern 26: Strongly Connected Components (Kosaraju / Tarjan)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 146 | Course Schedule II (210) | [ ] | |
| 147 | Number of Provinces (547) | [ ] | |
| 148 | Critical Connections in a Network (1192) | [ ] | |
| 149 | Maximum Employees to Be Invited to a Meeting (2127) | [ ] | |

## Pattern 27: Bridges & Articulation Points (Tarjan low-link)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 150 | Critical Connections in a Network (1192) | [ ] | |
| 151 | Longest Cycle in a Graph (2360) | [ ] | |

## Pattern 28: Minimum Spanning Tree (Kruskal / Prim / DSU + heap)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 152 | Connecting Cities With Minimum Cost (1135) | [ ] | |
| 153 | Min Cost to Connect All Points (1584) | [ ] | |
| 154 | Optimize Water Distribution in a Village (1168) | [ ] | |
| 155 | Find Critical and Pseudo-Critical Edges in Minimum Spanning Tree (1489) | [ ] | |

## Pattern 29: Bidirectional BFS (BFS optimization for known source & target)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 156 | Word Ladder (127) | [ ] | |
| 157 | Word Ladder II (126) | [ ] | |
| 158 | Bus Routes (815) | [ ] | |

## Pattern 30: DP - 1D Array (Fibonacci Style)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 159 | Climbing Stairs (70) | [ ] | |
| 160 | Decode Ways (91) | [ ] | |
| 161 | House Robber (198) | [ ] | |
| 162 | House Robber II (213) | [ ] | |
| 163 | House Robber III (337) | [ ] | |
| 164 | Fibonacci Number (509) | [ ] | |
| 165 | Delete and Earn (740) | [ ] | |
| 166 | Min Cost Climbing Stairs (746) | [ ] | |

## Pattern 31: DP - 1D Array (Kadane's Algorithm for Max/Min Subarray)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 167 | Maximum Subarray (53) | [ ] | |
| 168 | Maximum Sum Circular Subarray (918) | [ ] | |
| 169 | Maximum Score Of Spliced Array (2321) | [ ] | |
| 170 | Maximum Absolute Sum of Any Subarray (1749) | [ ] | |
| 171 | Maximum Product Subarray (152) | [ ] | |

## Pattern 32: DP - 1D Array (Coin Change / Unbounded Knapsack Style)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 172 | Coin Change (322) | [ ] | |
| 173 | Combination Sum IV (377) | [ ] | |
| 174 | Coin Change II (518) | [ ] | |

## Pattern 33: DP - 1D Array (0/1 Knapsack Subset Sum Style)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 175 | Partition Equal Subset Sum (416) | [ ] | |
| 176 | Target Sum (494) | [ ] | |

## Pattern 34: DP - 1D Array (Word Break Style)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 177 | Word Break (139) | [ ] | |
| 178 | Word Break II (140) | [ ] | |

## Pattern 35: DP - 2D Array (Longest Common Subsequence - LCS)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 179 | Longest Common Subsequence (1143) | [ ] | |
| 180 | Shortest Common Supersequence (1092) | [ ] | |
| 181 | Minimum Insertion Steps to Make a String Palindrome (1312) | [ ] | |

## Pattern 36: DP - 2D Array (Edit Distance / Levenshtein Distance)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 182 | Edit Distance (72) | [ ] | |
| 183 | Delete Operation for Two Strings (583) | [ ] | |
| 184 | Minimum ASCII Delete Sum for Two Strings (712) | [ ] | |

## Pattern 37: DP - 2D Array (Unique Paths on Grid)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 185 | Unique Paths (62) | [ ] | |
| 186 | Unique Paths II (63) | [ ] | |
| 187 | Minimum Path Sum (64) | [ ] | |
| 188 | Triangle (120) | [ ] | |
| 189 | Maximal Square (221) | [ ] | |
| 190 | Minimum Falling Path Sum (931) | [ ] | |
| 191 | Count Square Submatrices with All Ones (1277) | [ ] | |

## Pattern 38: DP - Interval DP

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 192 | Burst Balloons (312) | [ ] | |
| 193 | Remove Boxes (546) | [ ] | |

## Pattern 39: DP - Catalan Numbers

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 194 | Unique Binary Search Trees II (95) | [ ] | |
| 195 | Unique Binary Search Trees (96) | [ ] | |
| 196 | Different Ways to Add Parentheses (241) | [ ] | |

## Pattern 40: DP - Longest Increasing Subsequence (LIS)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 197 | Longest Increasing Subsequence (300) | [ ] | |
| 198 | Russian Doll Envelopes (354) | [ ] | |
| 199 | Minimum Number of Removals to Make Mountain Array (1671) | [ ] | |
| 200 | Longest Increasing Subsequence II (2407) | [ ] | |

## Pattern 41: DP - Stock problems

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 201 | Best Time to Buy and Sell Stock (121) | [ ] | |
| 202 | Best Time to Buy and Sell Stock II (122) | [ ] | |
| 203 | Best Time to Buy and Sell Stock III (123) | [ ] | |
| 204 | Best Time to Buy and Sell Stock IV (188) | [ ] | |
| 205 | Best Time to Buy and Sell Stock with Cooldown (309) | [ ] | |

## Pattern 42: Heap - Top K Elements (Selection/Frequency)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 206 | Kth Largest Element in an Array (215) | [ ] | |
| 207 | Top K Frequent Elements (347) | [ ] | |
| 208 | Sort Characters By Frequency (451) | [ ] | |
| 209 | Relative Ranks (506) | [ ] | |
| 210 | Kth Largest Element in a Stream (703) | [ ] | |
| 211 | K Closest Points to Origin (973) | [ ] | |
| 212 | Last Stone Weight (1046) | [ ] | |
| 213 | Take Gifts From the Richest Pile (2558) | [ ] | |

## Pattern 43: Heap - Two Heaps for Median Finding

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 214 | Find Median from Data Stream (295) | [ ] | |
| 215 | Finding MK Average (1825) | [ ] | |

## Pattern 44: Heap - K-way Merge

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 216 | Merge k Sorted Lists (23) | [ ] | |
| 217 | Find K Pairs with Smallest Sums (373) | [ ] | |
| 218 | Kth Smallest Element in a Sorted Matrix (378) | [ ] | |
| 219 | Smallest Range Covering Elements from K Lists (632) | [ ] | |

## Pattern 45: Heap - Scheduling / Minimum Cost (Greedy with Priority Queue)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 220 | Meeting Rooms II (253) | [ ] | |
| 221 | Reorganize String (767) | [ ] | |
| 222 | Minimum Cost to Hire K Workers (857) | [ ] | |
| 223 | Furthest Building You Can Reach (1642) | [ ] | |
| 224 | Maximum Average Pass Ratio (1792) | [ ] | |
| 225 | Single-Threaded CPU (1834) | [ ] | |
| 226 | The Number of the Smallest Unoccupied Chair (1942) | [ ] | |
| 227 | Meeting Rooms III (2402) | [ ] | |

## Pattern 46: Backtracking - Subsets (Include/Exclude)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 228 | Letter Combinations of a Phone Number (17) | [ ] | |
| 229 | Combinations (77) | [ ] | |
| 230 | Subsets (78) | [ ] | |
| 231 | Subsets II (90) | [ ] | |

## Pattern 47: Backtracking - Permutations

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 232 | Next Permutation (31) | [ ] | |
| 233 | Permutations (46) | [ ] | |
| 234 | Permutation Sequence (60) | [ ] | |

## Pattern 48: Backtracking - Combination Sum

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 235 | Combination Sum (39) | [ ] | |
| 236 | Combination Sum II (40) | [ ] | |

## Pattern 49: Backtracking - Parentheses Generation

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 237 | Generate Parentheses (22) | [ ] | |
| 238 | Remove Invalid Parentheses (301) | [ ] | |

## Pattern 50: Backtracking - Word Search / Path Finding in Grid

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 239 | Word Search (79) | [ ] | |
| 240 | Word Search II (212) | [ ] | |
| 241 | Check if Word Can Be Placed In Crossword (2018) | [ ] | |

## Pattern 51: Backtracking - N-Queens / Constraint Satisfaction

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 242 | Sudoku Solver (37) | [ ] | |
| 243 | N-Queens (51) | [ ] | |

## Pattern 52: Backtracking - Palindrome Partitioning

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 244 | Palindrome Partitioning (131) | [ ] | |
| 245 | Palindrome Partitioning II (132) | [ ] | |
| 246 | Pseudo-Palindromic Paths in a Binary Tree (1457) | [ ] | |

## Pattern 53: Greedy - Interval Merging/Scheduling

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 247 | Merge Intervals (56) | [ ] | |
| 248 | Insert Interval (57) | [ ] | |
| 249 | Employee Free Time (759) | [ ] | |
| 250 | Interval List Intersections (986) | [ ] | |
| 251 | Divide Intervals Into Minimum Number of Groups (2406) | [ ] | |

## Pattern 54: Greedy - Jump Game Reachability/Minimization

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 252 | Jump Game II (45) | [ ] | |
| 253 | Jump Game (55) | [ ] | |

## Pattern 55: Greedy - Buy/Sell Stock

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 254 | Best Time to Buy and Sell Stock (121) | [ ] | |
| 255 | Best Time to Buy and Sell Stock II (122) | [ ] | |

## Pattern 56: Greedy - Gas Station Circuit

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 256 | Gas Station (134) | [ ] | |
| 257 | Maximize the Topmost Element After K Moves (2202) | [ ] | |

## Pattern 57: Greedy - Task Scheduling (Frequency Based)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 258 | Task Scheduler (621) | [ ] | |
| 259 | Reorganize String (767) | [ ] | |
| 260 | Distant Barcodes (1054) | [ ] | |

## Pattern 58: Greedy - Sorting Based

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 261 | Assign Cookies (455) | [ ] | |
| 262 | Candy (135) | [ ] | |
| 263 | Queue Reconstruction by Height (406) | [ ] | |
| 264 | Two City Scheduling (1029) | [ ] | |

## Pattern 59: Binary Search - On Sorted Array/List

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 265 | Search Insert Position (35) | [ ] | |
| 266 | Sqrt(x) (69) | [ ] | |
| 267 | Search a 2D Matrix (74) | [ ] | |
| 268 | First Bad Version (278) | [ ] | |
| 269 | Guess Number Higher or Lower (374) | [ ] | |
| 270 | Single Element in a Sorted Array (540) | [ ] | |
| 271 | Binary Search (704) | [ ] | |
| 272 | Kth Missing Positive Number (1539) | [ ] | |

## Pattern 60: Binary Search - Find Min/Max in Rotated Sorted Array

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 273 | Search in Rotated Sorted Array (33) | [ ] | |
| 274 | Search in Rotated Sorted Array II (81) | [ ] | |
| 275 | Find Minimum in Rotated Sorted Array (153) | [ ] | |
| 276 | Find Peak Element (162) | [ ] | |
| 277 | Peak Index in a Mountain Array (852) | [ ] | |
| 278 | Find in Mountain Array (1095) | [ ] | |

## Pattern 61: Binary Search - On Answer / Condition Function

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 279 | Split Array Largest Sum (410) | [ ] | |
| 280 | Minimize Max Distance to Gas Station (774) | [ ] | |
| 281 | Koko Eating Bananas (875) | [ ] | |
| 282 | Capacity To Ship Packages Within D Days (1011) | [ ] | |
| 283 | Minimum Number of Days to Make m Bouquets (1482) | [ ] | |
| 284 | Minimum Limit of Balls in a Bag (1760) | [ ] | |
| 285 | Minimized Maximum of Products Distributed to Any Store (2064) | [ ] | |
| 286 | Maximum Candies Allocated to K Children (2226) | [ ] | |

## Pattern 62: Binary Search - Find First/Last Occurrence

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 287 | Find First and Last Position of Element in Sorted Array (34) | [ ] | |
| 288 | Find K Closest Elements (658) | [ ] | |

## Pattern 63: Binary Search - Median / Kth across Two Sorted Arrays

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 289 | Median of Two Sorted Arrays (4) | [ ] | |
| 290 | Find K-th Smallest Pair Distance (719) | [ ] | |
| 291 | Kth Smallest Element in a Sorted Matrix (378) | [ ] | |

## Pattern 64: Stack - Valid Parentheses Matching

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 292 | Valid Parentheses (20) | [ ] | |
| 293 | Longest Valid Parentheses (32) | [ ] | |
| 294 | Minimum Add to Make Parentheses Valid (921) | [ ] | |
| 295 | Minimum Remove to Make Valid Parentheses (1249) | [ ] | |
| 296 | Minimum Number of Swaps to Make the String Balanced (1963) | [ ] | |

## Pattern 65: Stack - Monotonic Stack

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 297 | Remove K Digits (402) | [ ] | |
| 298 | Next Greater Element I (496) | [ ] | |
| 299 | Next Greater Element II (503) | [ ] | |
| 300 | Daily Temperatures (739) | [ ] | |
| 301 | Online Stock Span (901) | [ ] | |
| 302 | Sum of Subarray Minimums (907) | ✔️ | Basic next and previous smaller integer problem with stack |
| 303 | Maximum Width Ramp (962) | [ ] | |
| 304 | Final Prices With a Special Discount in a Shop (1475) | [ ] | |
| 305 | Find the Most Competitive Subsequence (1673) | [ ] | |

## Pattern 66: Stack - Expression Evaluation (RPN/Infix)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 306 | Evaluate Reverse Polish Notation (150) | [ ] | |
| 307 | Basic Calculator (224) | [ ] | |
| 308 | Basic Calculator II (227) | [ ] | |
| 309 | Basic Calculator III (772) | [ ] | |

## Pattern 67: Stack - Simulation / Backtracking Helper

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 310 | Simplify Path (71) | [ ] | |
| 311 | Decode String (394) | [ ] | |
| 312 | Asteroid Collision (735) | [ ] | |

## Pattern 68: Stack - Min Stack Design

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 313 | Min Stack (155) | [ ] | |
| 314 | Maximum Frequency Stack (895) | [ ] | |
| 315 | Online Stock Span (901) | [ ] | |

## Pattern 69: Stack - Largest Rectangle in Histogram

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 316 | Largest Rectangle in Histogram (84) | [ ] | |
| 317 | Maximal Rectangle (85) | [ ] | |

## Pattern 70: Bitwise XOR - Finding Single/Missing Number

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 318 | Single Number (136) | [ ] | |
| 319 | Single Number II (137) | [ ] | |
| 320 | Missing Number (268) | [ ] | |
| 321 | Find the Difference (389) | [ ] | |

## Pattern 71: Bitwise AND - Counting Set Bits (Hamming Weight)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 322 | Number of 1 Bits (191) | [ ] | |
| 323 | Power of Two (231) | [ ] | |
| 324 | Total Hamming Distance (477) | [ ] | |

## Pattern 72: Bitwise DP - Counting Bits Optimization

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 325 | Counting Bits (338) | [ ] | |
| 326 | Parallel Courses II (1494) | [ ] | |
| 327 | Count Triplets That Can Form Two Arrays of Equal XOR (1442) | [ ] | |

## Pattern 73: Bitwise Operations - Power of Two/Four Check

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 328 | Power of Two (231) | [ ] | |
| 329 | Power of Four (342) | [ ] | |

## Pattern 74: Linked List - In-place Reversal

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 330 | Remove Duplicates from Sorted List (83) | [ ] | |
| 331 | Reverse Linked List II (92) | [ ] | |
| 332 | Reverse Linked List (206) | [ ] | |
| 333 | Reverse Nodes in k-Group (25) | [ ] | |
| 334 | Palindrome Linked List (234) | [ ] | |
| 335 | Remove Duplicates from Sorted List II (82) | [ ] | |

## Pattern 75: Linked List - Merging Two Sorted Lists

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 336 | Merge Two Sorted Lists (21) | [ ] | |
| 337 | Merge k Sorted Lists (23) | [ ] | |

## Pattern 76: Linked List - Addition of Numbers

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 338 | Add Two Numbers (2) | [ ] | |
| 339 | Plus One Linked List (369) | [ ] | |

## Pattern 77: Linked List - Intersection Detection

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 340 | Intersection of Two Linked Lists (160) | [ ] | |
| 341 | Minimum Index Sum of Two Lists (599) | [ ] | |

## Pattern 78: Linked List - Reordering / Partitioning

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 342 | Swap Nodes in Pairs (24) | [ ] | |
| 343 | Rotate List (61) | [ ] | |
| 344 | Partition List (86) | [ ] | |
| 345 | Reorder List (143) | [ ] | |
| 346 | Odd Even Linked List (328) | [ ] | |

## Pattern 79: Array/Matrix - In-place Rotation

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 347 | Rotate Image (48) | [ ] | |
| 348 | Rotate Array (189) | [ ] | |
| 349 | Transpose Matrix (867) | [ ] | |

## Pattern 80: Array/Matrix - Spiral Traversal

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 350 | Spiral Matrix (54) | [ ] | |
| 351 | Spiral Matrix II (59) | [ ] | |
| 352 | Spiral Matrix III (885) | [ ] | |
| 353 | Spiral Matrix IV (2326) | [ ] | |

## Pattern 81: Array/Matrix - Set Matrix Zeroes (In-place Marking)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 354 | Set Matrix Zeroes (73) | [ ] | |
| 355 | Game of Life (289) | [ ] | |
| 356 | Diagonal Traverse (498) | [ ] | |

## Pattern 82: Array - Product Except Self (Prefix/Suffix Products)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 357 | Product of Array Except Self (238) | [ ] | |
| 358 | Longest Mountain in Array (845) | [ ] | |
| 359 | Minimum Penalty for a Shop (2483) | [ ] | |

## Pattern 83: Array - Plus One (Handling Carry)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 360 | Plus One (66) | [ ] | |
| 361 | Multiply Strings (43) | [ ] | |
| 362 | Add to Array-Form of Integer (989) | [ ] | |
| 363 | Add Binary (67) | [ ] | |

## Pattern 84: Array - Merge Sorted Array (In-place from End)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 364 | Merge Sorted Array (88) | [ ] | |
| 365 | Squares of a Sorted Array (977) | [ ] | |

## Pattern 85: Array - Cyclic Sort

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 366 | First Missing Positive (41) | [ ] | |
| 367 | Missing Number (268) | [ ] | |
| 368 | Find the Duplicate Number (287) | [ ] | |
| 369 | Find All Duplicates in an Array (442) | [ ] | |
| 370 | Find All Numbers Disappeared in an Array (448) | [ ] | |

## Pattern 86: String - Palindrome Check (Two Pointers / Reverse)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 371 | Palindrome Number (9) | [ ] | |
| 372 | Valid Palindrome (125) | [ ] | |
| 373 | Valid Palindrome II (680) | [ ] | |

## Pattern 87: String - Anagram Check (Frequency Count/Sort)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 374 | Group Anagrams (49) | [ ] | |
| 375 | Valid Anagram (242) | [ ] | |

## Pattern 88: String - Roman to Integer Conversion

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 376 | Roman to Integer (13) | [ ] | |
| 377 | Integer to Roman (12) | [ ] | |

## Pattern 89: String - String to Integer (atoi)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 378 | String to Integer (atoi) (8) | [ ] | |
| 379 | Valid Number (65) | [ ] | |

## Pattern 90: String - Multiply Strings (Manual Simulation)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 380 | Multiply Strings (43) | [ ] | |
| 381 | Add Strings (415) | [ ] | |
| 382 | Add Binary (67) | [ ] | |

## Pattern 91: String Matching - Naive / KMP / Rabin-Karp

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 383 | Find the Index of the First Occurrence in a String (28) | [ ] | |
| 384 | Shortest Palindrome (214) | [ ] | |
| 385 | Repeated String Match (686) | [ ] | |
| 386 | Rotate String (796) | [ ] | |
| 387 | Find Beautiful Indices in the Given Array II (3008) | [ ] | |

## Pattern 92: String - Repeated Substring Pattern Detection

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 388 | Repeated Substring Pattern (459) | [ ] | |
| 389 | Find the Index of the First Occurrence in a String (28) | [ ] | |
| 390 | Repeated String Match (686) | [ ] | |

## Pattern 93: Design (General/Specific)

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 391 | LRU Cache (146) | [ ] | |
| 392 | Min Stack (155) | [ ] | |
| 393 | Implement Stack using Queues (225) | [ ] | |
| 394 | Implement Queue using Stacks (232) | [ ] | |
| 395 | Flatten 2D Vector (251) | [ ] | |
| 396 | Encode and Decode Strings (271) | [ ] | |
| 397 | Find Median from Data Stream (295) | [ ] | |
| 398 | Flatten Nested List Iterator (341) | [ ] | |
| 399 | Moving Average from Data Stream (346) | [ ] | |
| 400 | Design Snake Game (353) | [ ] | |
| 401 | Logger Rate Limiter (359) | [ ] | |
| 402 | Design Hit Counter (362) | [ ] | |
| 403 | Design Phone Directory (379) | [ ] | |
| 404 | Insert Delete GetRandom O(1) (380) | [ ] | |
| 405 | All O`one Data Structure (432) | [ ] | |
| 406 | LFU Cache (460) | [ ] | |
| 407 | Design Compressed String Iterator (604) | [ ] | |

## Pattern 94: Tries

| S.No | Question | Status | Notes |
|------|----------|--------|-------|
| 408 | Implement Trie (Prefix Tree) (208) | [ ] | |
| 409 | Design Add and Search Words Data Structure (211) | [ ] | |
| 410 | Longest Word in Dictionary (720) | [ ] | |
| 411 | Replace Words (648) | [ ] | |
| 412 | Word Squares (425) | [ ] | |
| 413 | Design Search Autocomplete System (642) | [ ] | |
| 414 | Prefix and Suffix Search (745) | [ ] | |

---

### Instructions:
- Replace `[ ]` with `[x]` to mark questions as completed
- Use the Notes column to add important observations, approaches, or links to solutions
- Each question has a unique serial number for easy tracking
- Total questions: 414

### How to use this tracker:
1. Save this markdown file locally
2. Open in any markdown editor (VS Code, Obsidian, Notion, etc.)
3. Check off completed problems and add notes
4. Track your progress through each pattern systematically
