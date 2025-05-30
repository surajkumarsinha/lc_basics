# lc_basics


## DP Questions

| Question | Explanation |
|----------|-------------|
| [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/description/) | Do checkout other LIS related problems as well |
| [Burst Balloons](https://leetcode.com/problems/burst-balloons/description/) | You cannot divide the subproblems by choosing to burst the first balloon as k-1th and k+1th balloons will still be dependent on one another for calculating cost, instead remove the last balloon and build the problem from there. |
| [Find the Maximum Length of Valid Subsequence II](https://leetcode.com/problems/find-the-maximum-length-of-valid-subsequence-ii) | NA |
| [Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees-ii/) | DP is used to generate the left and the right vector of Tree Nodes. Good problem which combines DP and tree (binary search tree). |
| [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/description/) | NA |
| [Minimum Cost to Connect Two Groups of Points](https://leetcode.com/problems/minimum-cost-to-connect-two-groups-of-points) | - The group with more nodes will have 1 outgoing edge to the other group.<br>- We check with recursion the minimum sum for connecting all the left edges to the right.<br>- The remaining nodes on the right will be connected to the minimum on the left we can find. |
| [Maximum Frequency After Subarray Operation](https://leetcode.com/problems/maximum-frequency-after-subarray-operation) | Apply Kadane here, where we can try each number and try to make it equal to k |
| [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray) | - If all the numbers are positive or even negative then the product of all the numbers would be the max product subarray <br> - If there are odd negative integers then we need to remove the last or first negative integer to make total product positive <br> - If there is a 0, then we will start the new subarray from there |
| [Jump game 6](https://leetcode.com/problems/jump-game-vi) | `dp[i] = nums[i] + max(dp[j]), where j = [i+1, min(n-1,i+d)]` <br> - To get the max value we can store it in a monotonic decreasing queue when the largest number is not in a range of i, i.e. -> i - d > max_index remove that number. <br> - Also we need the maximum dp[j] value. So from the queue we remove dp values which are less than the max dp[j] value in that range. |
| [Jump game 7](https://leetcode.com/problems/jump-game-vii) | To solve this we can do a bfs or use dp. <ul><li> DP: in range min to max. If there is a 0 present then we can easily reach that range. <br>i.e. `dp[I] = true, if in range (I-max) to (I-min)` there is a 0 which is present. <li> BFS: You can do a standard bfs here. For each position you would have already seen places till pos1 + max. So for the next position in the queue, we can start searching from `max(pos1 + max + 1, pos2 + min) to min(n-1, pos2 + max)` </ul> |
| [Max absolute sum of subaaray](https://leetcode.com/problems/maximum-absolute-sum-of-any-subarray/) | - Find the max subarray and the min subarray sum <br> - Result would be the max of abs results of both subarray sums |



Algorithms and concepts:
https://leetcode.com/discuss/study-guide/2166045/line-sweep-algorithms




## Forming slots and greedy approach: 
<li>Task Scheduler - LeetCode
<li>767. Reorganize String
<li>1054. Distant Barcodes
<li>1405. Longest Happy String
<li>1953. Maximum Number of Weeks for Which You Can Work
<li>2335. Minimum Amount of Time to Fill Cups
<li>358. Rearrange String k Distance Apart (premium)
<li>984. String Without AAA or BBB


## Leetcode with using Knapsack with binary search

https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended-ii/


## Monotonic stack questions:

https://leetcode.com/problems/minimum-cost-tree-from-leaf-values/description/
- 3 approaches:
    - DP: 
        - classic knapsack problem using MCM. At every level: max(left)*max(right) + dfs(i,k) + dfs(k+1,j)
        - The time complexity is around O(n^3)
    - Removing the minimum node until only one node is left
        - Go through the entire array and find the smallest number. Check the product of the smallest node with its closest neighbours. 
    - Monotonic stack
        - When we build a node in the tree, we compared the two numbersaandb.In this process, the smaller one is removed and we won't use it anymore,and the bigger one actually stays.
        - The problem can translated as following:Given an arrayA, choose two neighbors in the array a and b,we can remove the smaller one min(a,b) and the cost is a * b.What is the minimum cost to remove the whole array until only one left?
        - To remove a number a, it needs a cost a * b, where b >= a. So a has to be removed by a bigger number.We want minimise this cost, so we need to minimise b.
        - b has two candidates, the first bigger number on the left, the first bigger number on the right. The cost to remove a is a * min(left, right).

https://leetcode.com/problems/remove-duplicate-letters/
- Interesting problem where a smallest lexicographically subsequence containing unique characters needs to be produced.  
- Start by finding the last seen positions for each character in the string
- Create a monotonic stack such that:
    - You check wether the top element of the stack contains a letter that is lex. larger than the current letter and wether it can be added later to the stack.
        - If yes then we remove the top of the stack and proceed to add the current character
- Then we pop out the stack and print the string

https://leetcode.com/problems/sum-of-total-strength-of-wizards/description/
- Very difficult question as you need to find the pre of prefix sums to get the answer.



## Graph questions

https://leetcode.com/problems/is-graph-bipartite/description/

What does it mean when a graph is bipartite

1. There is no cycle of odd length
2. we can split the nodes of the graph(vertex set of the graph) into 2 subsets sothat there is all the edges go from 1 subsetto the other subset.
3. The graph should be bi-colourable.


https://leetcode.com/problems/second-minimum-time-to-reach-destination/description/

- Very interesting problem which uses bfs and 2 Dist arrays to store the least and the second least distances.

https://leetcode.com/problems/path-with-minimum-effort/description/
- Interesting way to use modified djikstras



## Sliding window questions

https://leetcode.com/problems/minimum-number-of-k-consecutive-bit-flips/description/
- Amazing question which deals with bit manipulation.
- Whenever you see a number as 0, we flip the value and store the index in a deque. 
- Every number might be flipped due to some previous index, therefore the value of the new number would be : nums[I] + dq.size() % 2
- Dq.size() determines the number of times we had to flip the number in the last k interactions
- When the index of the number is outside of the impact caused by the (I-k-1)th index, we remove that index from the dq if it exists



## Binary Search questions

https://leetcode.com/problems/count-complete-tree-nodes/?envType=problem-list-v2&envId=binary-search
- Very interesting problem where you need to apply binary search to find the total number of nodes 


https://leetcode.com/problems/maximum-number-of-tasks-you-can-assign
- You need to make the strongest k workers take the easiest k tasks.
- Maximise on k using binary search
- Then to see if you can assign k tasks to k workers:
    - Use dequeue to store all workers who can take on the work with strength
    - Check if the strongest worker in the queue can take up the task then assign it to him
    - If no then assign the task to the weakest worker and reduce the pills since they will need it to complete the task

https://leetcode.com/problems/maximize-the-minimum-powered-city/description/
- Calculate the power of each station 
- Binary search to see if a min power is possible: {all stations should have a minimum mid power}
- If at station ‘a’, power p is needed, deploy p station at location ‘a + r’ to maximise the stations getting the power. 
- We can make use of range queries:
    - ‘a+p’ would be the total_power of station a
    - extra_power(I) = extra_power(I-1)



## Meet in the middle
https://leetcode.com/problems/closest-subsequence-sum/


## Design
https://leetcode.com/problems/queue-reconstruction-by-height/


