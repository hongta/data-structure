# Union-Find (aka Disjoint-set)
A disjoint-set data structure that partitions a set into disjoint subsets.

### Basic abstractions
  * set of objects
  * **union** command: connect two objects
  * **find** query: is there a path connecting one object to another?

### Data type (API)
  * `union(int p, int q)`: add connection between p and q
  * `find(int p)` component identifier for p (0 to N - 1 )
  * `connected()` are p and q in the same component
  * `count()` number of components

### Implementations
  * Java
  * Python

### Applications
  * Percolation
  * Dynamic graph connectivity.
  * Lowest Common Ancestor in a Tree or DAG
  * Kruskal's minimum spanning tree algorithm

### References
  * [Coursera Algorithms, Part I](https://www.coursera.org/learn/algorithms-part1/)
