# IEDA5230
Consider a Traveling Salesman Problem with a network of n nodes. Each arc (i, j) has a cost Cij. An initial solution is given as (1, 2, …, n). This solution can be broken into multiple segments, where each segment is a subsequence of the initial solution. Below is an example with four segments, where (1, 2, 3) is a segment of length 3, (4, 5, 6, 7) is a segment of length 4, (8) is a segment length 1, and so on.
 (1, 2, 3 | 4, 5, 6, 7 | 8 | 9, 10, …, n).
We want to improve the initial solution by making some segment-based changes. To make it simple, we always assume the first segment starts from node 1. 
