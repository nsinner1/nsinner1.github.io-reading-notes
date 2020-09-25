<h1>Graphs</h1>
https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html

A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.

Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
Edge - An edge is a connection between two nodes.
Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
Degree - The degree of a vertex is the number of edges connected to that vertex.

Undirected Graphs
An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.

For example, in the graph below, Node C is connected to Node A, Node E and Node B. There are no “directions” given to point to specific vertices. The connection is bi-directional.

Directed Graphs (Digraph)
A Directed Graph also called a Digraph is a graph where every edge is directed.

Unlike an undirected graph, a Digraph has direction. Each node is directed at another node with a specific requirement of what node should be referenced next.

Compare the visual below with the undirected graph above. Can you see the difference? The Digraph has arrows pointing to specific nodes.

Complete vs Connected vs Disconnected
There are many different types of graphs. This depends on how connected the graphs are to other node/vertices.

The three different types are completed, connected, and disconnected.

Complete Graphs
A complete graph is when all nodes are connected to all other nodes.

Looking at the graph we are representing, you can see that Vertex A connects to both Vertex D and Vertex C. To show this, we place a 1 in the position of (a,c) and (a,d).
We follow this same pattern for the other vertex’s and where they are connected.
If there is not an edge/connection between the vertex’s, we represent this by placing a 0 in the appropriate point of the matrix.