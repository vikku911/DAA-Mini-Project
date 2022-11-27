# DAA-Mini-Project
Problem Definition:
To find the shortest path to connect the all the given nodes with the
minimum cost without making a cycle.

Design Technique used:
A greedy algorithm is an approach for solving a problem by selecting the
best option available at the moment. It doesn't worry whether the current
best result will bring the overall optimal result.
The algorithm never reverses the earlier decision even if the choice is
wrong. It works in a top-down approach. 
This algorithm may not produce the best result for all the problems. It's
because it always goes for the local best choice to produce the global
best result.
However, we can determine if the algorithm can be used with any
problem if the problem has the following properties:
1. Greedy Choice Property
2. Optimal Substructure.

Advantages of Greedy Approach

• The algorithm is easier to describe.
• This algorithm can perform better than other algorithms (but, not
in all cases). 

Drawback of Greedy Approach

As mentioned earlier, the greedy algorithm doesn't always produce the
optimal solution. This is the major disadvantage of the algorithm
For example, suppose we want to find the longest path in the graph
below from root to leaf. Let's use the greedy algorithm here. 

What is Kruskal’s algorithm?
Spanning tree is the sum of weights of all the edges in a tree.
A minimum spanning tree (MST) is one which costs the least among all
spanning trees. 

Step to Kruskal’s algorithm:

● Sort the graph edges with respect to their weights.
● Start adding edges to the minimum spanning tree from the edge
with the smallest weight until the edge of the largest weight.
● Only add edges which don’t form a cycle—edges which connect
only disconnected components.
 Or as a simpler explanation,
 Step 1 – Remove all loops and parallel edges
 Step 2 – Arrange all the edges in
ascending order of cost
 Step 3 – Add edges with least weight
But how do you check whether two vertices are connected or not?
That’s where the real-life example of Disjoint Sets come into use.

Time Complexity :

The time complexity of Kruskal's minimum spanning tree algorithm is O
(E* log V), where E is the number of edges in the graph and V is the
number of vertices.

Space Complexity:

The space complexity of Kruskal's minimum spanning tree algorithm is
O (|E| + |V|), where E is the number of edges in the graph and V is the
number of vertices. 

Conclusion:-

 Kruskal algorithm is used to find minimum cost by connecting all the
given nodes without forming a cycle.
 Kruskal algorithm is faster and mainly used for spare graphs
 Kruskal algorithm is much better than prim’s algorithm to connect all
the given nodes faster than prim’s.
