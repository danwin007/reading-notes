# Graphs

## Glossary

### Graphs
  * `vertices` or `nodes`
  * `edges`
* `Undirected Graph`
  - edges have no directions pointing to specific vertices
* `Directed Graph`or `Digraph`
  - edges have directions pointing to nodes
* `Complete Graph`
  - all nodes are connected to other nodes
* `Connected Graph`
  - all nodes have at least one edge
  - a `tree` is a form of connected graph
* `Disconnected Graph`
  - some nodes may not have edges
* `Acylclic Graph`
  - a directed graph without cycles or `DAG`
  - a cycle is when a node can be traversed through and potentially end up back at itself
* `Cyclic Graph`
  - a graph with cycles
  - a cycle is a path of a positive length that starts and ends at the same vertex/node
  
### Graphs are represented through:

* `Adjacency Matrix`
  - represented by a 2d array
  - `n` vertices means an `n x n` Boolean matrix
  - each row and column represents each vertex of the data structure
  - the elements of both the column and the row must add up to `1` if there is an edge that connects the two, or `0` if there isn't a connection
  * `sparse graph`
    - where there are very few connections
  * `dense graph`
    - where there are many connections
* `Adjacency List`
  - most common way to rep graphs
  - a collection of linked lists or array that lists all of the other vertices that are connected
  - makes it easy to see if one node connects to another

* `Weighted Graph`
  - a graph with numbers assigned to edges
  - numbers are called weights
  - when showing a weighted graph in an adjacency matrix, you show a connection by setting the element to rep the weight between the two paths, with `0` if there isn't a connection
  - with adjacency lists, you must include *both* the weight and the name of the adjacent vertex

### Traversals
:(

### Real World Uses of Graphs
* GPS and mapping
* Driving directions
* Social networks
* Airline traffic
* Product suggestions
