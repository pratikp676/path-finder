# path-finder
This is a visualization of how Dijkstra and A* algorithm works.

**Dijkstra**

Dijkstra's algorithm is an algorithm for finding the shortest paths between nodes in a graph.The algorithm exists in many variants. Dijkstra's original algorithm found the shortest path between two given nodes, but a more common variant fixes a single node as the "source" node and finds shortest paths from the source to all other nodes in the graph, producing a shortest-path tree.

![dijkstra1](https://user-images.githubusercontent.com/18692459/195420129-ec29fa55-8a27-42e9-be87-9f36890e14bf.gif)

**A-star Visualization**

A* (pronounced "A-star") is a graph traversal and path search algorithm, which is used in many fields of computer science due to its completeness, optimality, and optimal efficiency. 

Compared to Dijkstra's algorithm, the A* algorithm only finds the shortest path from a specified source to a specified goal, and not the shortest-path tree from a specified source to all possible goals. This is a necessary trade-off for using a specific-goal-directed heuristic. For Dijkstra's algorithm, since the entire shortest-path tree is generated, every node is a goal, and there can be no specific-goal-directed heuristic.

![astar](https://user-images.githubusercontent.com/18692459/195420204-d97480b1-a071-493a-9fb3-7f53b0345551.gif)
