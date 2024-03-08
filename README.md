# minimum spanning tree path saving
A rudimentary particularly odd solution proposed for an nxn graph in attempt to compute the saved distance when a minimum spanning tree is drawn from the structure

---

### Advantage:
Since databases are accessed regularly, the sorting operation requires to be performed only once and thereafter repetitive searches at reduced speeds can be performed.


### Disadvantage:
The algorithm is dependent on the number of vertices instead of the number of edges.

---

### Recommendations(reiterated):
* In real-world situations its rare to encounter a fully connected graph. Therefore dealing with pointless empty spaces in the structure that lack distances is a valid option

* That nested dictionary structure is a little excessive on memory and may not be wise

* An implementation for "sorted vertices" that isn't discriminant of directed or undirected matrices would prove valuable

* Utilising parallelised merge sort could further decrease runtime

* A proper merge sort without the use of 'temp' array and an excess linear passage of elements without pecking away at memory is much appreciated.

* Calculation of edge summations with the algorithm “sum” needs to be performed using iteration instead of recursion to avoid raising maximum recursion depth related errors

* The search operation relative to the vertices number after sorting need not be linear but could be adjusted to suit differing requirements.

* An advanced sorting algorithm that runs lower than O(n log(n)) is required if time complexity is to be significantly reduced

