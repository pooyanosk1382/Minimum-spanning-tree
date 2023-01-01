# Minimum-spanning-tree
Minimum spanning tree codes. 
Codes of Prim, Boruvka and Kruskal.
They found the minimum spanning tree in a graph.

# Prim
Prim's Algorithm is a greedy algorithm that is used to find the minimum spanning tree from a graph. Prim's algorithm finds the subset of edges that includes every vertex of the graph such that the sum of the weights of the edges can be minimized.

Prim's algorithm starts with the single node and explores all the adjacent nodes with all the connecting edges at every step. The edges with the minimal weights causing no cycles in the graph got selected.

# Boruvka
Boruvka's algorithm is straightforward and intuitive. It is a greedy algorithm that constructs a globally "optimal" solution using smaller, locally optimal solutions for smaller sub problems.

Greedy algorithms are generally concerned with the most optimal solution when the smaller steps add up.

# Kruskal
In Kruskal's algorithm, we start from edges with the lowest weight and keep adding the edges until the goal is reached. The steps to implement Kruskal's algorithm are listed as follows -

    First, sort all the edges from low weight to high.
    Now, take the edge with the lowest weight and add it to the spanning tree. If the edge to be added creates a cycle, then reject the edge.
    Continue to add the edges until we reach all vertices, and a minimum spanning tree is created.
