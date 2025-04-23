# Graph2
1: Explain with the help of an example, "Why Dijkstra's algorithm fails on negative weights".

![Graph 2 drawio](https://github.com/user-attachments/assets/5d063e2f-c32f-47a7-8359-2c7dfdab2756)

In this diagram, we assign 3 nodes. The Dijkstra algorithm is set to find the shortest path. The only issue with the algorithm is that it can't backtrack and reprocess paths after finding one. Since we have the Nodes 2 and 4, we pick the smallest distance, that being 2, and we make C = 2 + (-5) = -.3 Since it can't backtrack, it doesn't understand that A to B to C is better than A to C.

https://youtu.be/s8vJaqp1rlI
