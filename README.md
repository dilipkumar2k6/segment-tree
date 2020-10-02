# Why Segment Tree?
- Used to run Range sum query
- I.e. sum of all nums for given range
![](assets/range-sum-query.png)
- Prefix sum is used to get the range sum query
- Prefix sum approach doesn't work well if input array is keep getting mutated
- Segment tree is used when input is frequently get mutated
![](assets/compare.png)
# Construct Segment tree
- Use partition algo of merge sort to partition array into fragments
![](assets/partition.png)
- After partition, we will return value from leaf to parent
![](assets/calculate-sum.png)
- Segment tree will be constructed as below
![](assets/segment-tree.png)
- Use array to store segment tree, similar to Heap
![](assets/similar-to-heap.png)
- Construct segment tree 
![](assets/construction-flow.png)
- Algorithm to construct segment tree
![](assets/construction-algo.png)
# Segment tree theory
![](assets/theory.png)
# Find Range Sum
- There are three types of overlap
![](assets/overlap-types.png)
- Find range sum flow
![](assets/find-range-sum-flow.png)
- Find range sum algo
![](assets/find-range-sum-algo.png)
# Update operation
![](assets/update-flow-algo.png)
# Time complexity
![](assets/time-complexity.png)
# Comparison
![](assets/compare-algo.png)
# Problems

# Reference
https://www.youtube.com/watch?v=ZBHKZF5w4YU
https://www.youtube.com/watch?v=2bSS8rtFym4