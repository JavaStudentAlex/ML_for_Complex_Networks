#note #algorithm 

The Tarjan's algorithm finds connected components in both directed and undirected networks. It is modified DFS search where each node gets two values:
- id - topological number of the node
- low_link_id - the id of the node with the lowest id which can be traversed from the current node
The time complexity is: O(n + m).