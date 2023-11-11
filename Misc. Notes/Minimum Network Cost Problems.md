---
tags:
  - operations-research
  - mathematics
  - sem5
---
### The **minimum-cost flow problem** (**MCFP**) is an [optimization](https://en.wikipedia.org/wiki/Optimization "Optimization") and [decision problem](https://en.wikipedia.org/wiki/Decision_problem "Decision problem") to find the cheapest possible way of sending a certain amount of flow through a [flow network](https://en.wikipedia.org/wiki/Flow_network "Flow network").

## Graph Theory:
$G(V,E) -> Graph\space({Vertices,}\space{Edges})$ 
Directed Graphs only have one direction, not bidirectional
Vertices Giving Nodes, and Edges being the pathways

To understand the problem one must have a basic understanding of Shortest Path problems using Graph Theory and, Negative Cost Ars and Maximum Flow theory.

Negative cost arcs refer to edges in a graph where the cost of traversing the edge is negative. 

Maximum flow theory is a concept in graph theory and network optimization that deals with determining the maximum amount of flow that can pass through a network or graph.

Here,
$c_{ij}$ $x_y$

cij is cost of nodes from i to j
xy is the number of units flowing from i to j

Subject to:

b = net flow (outbound -  inbound)
Bound between an upperbound and a lowerbound value of net flow.

# Network Simplex Method:
Network programs can be seen as minimum cost flow problems in a graph We associate a digraph $G = ({V},\space{E})$ to the matrix of a network program:

- Vertices V correspond to rows (constraints) 
- Edges E correspond to columns (variables) 
- A column with a 1 at row $i$ and a − 1 at row $k$ gives an edge $(i, k )$ 

- Then we can reinterpret the other elements of the network program: 
	- Each variable $x_j$ is the flow sent along the $j$-th edge 
	- The cost of sending 1 unit of flow is $c_j$ 
	- Flow cannot exceed capacity $u_j$ 
	- There must be a minimum flow $l_j$ (usually, 0 ) 
	- Total production of flow at vertex i is determined by $b_i$

So solving the network program consists in finding the feasible flow along the graph that minimizes the cost

## The question is of the form:
![[Pasted image 20231103123235.png]]
![[Pasted image 20231103122748.png]]

## Try new
 What we have just done is built a graph where any maximum flow from supply to demand that saturates all the extra edges out of supply and into demand can be converted into a feasible circulation (by just removing these dummy nodes and edges). In particular, the minimum cost circulation problem is now the minimum cost flow problem, which we can solve with the MCF algorithm. 