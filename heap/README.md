# Heap
A heap is useful data structure when you need to remove the object with the highest (or lowest) priority. A common use of a heap is to implement a priority queue.

### Data type (API)
  * `insert` or `push`: add a new key into the heap
  * `find-min` or `find-max`:  find minimum key of min-heap, maximum key in max-heap
  * `extract-min` or `extract-max`: return and delete minimum key or maximum key
  * `is-empay` is the heap empty ?
  * `size` number of keys in the heap


### Implementations
  * Java
    * `java.util.PriorityQueue`
  * Python
    * `heapq` module
  * Go
    * `heap` package
  * PHP
    * `SplMaxHeap` and `SplMinHeap`

### Applications
  * Heapsort: One of the best sorting methods being in-place and with no quadratic worst-case scenarios.
  * Priority Queue
  * Order statistics: The Heap data structure can be used to efficiently find the kth smallest (or largest) element in an array.

### References
