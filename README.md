# KCore
Computing the all the subgraphs of graph G where all degree of vertices is greater than K 

# Computing method
1) Every vertex keeps two tags: is_deleted, current_degree
2) If the degree of vertex is smaller than K, it will be deleted from the graph G. Then all adjacent vertices will be informed of this deletion.
3) Informed adjacent vertives update their degree.

# Input
Indirected (or paired directed) graph

#Output
all vertices with degree greater than K
