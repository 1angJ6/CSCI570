# Lecture 2

* runtime complexities
    * worst case complexity (single input)
    * best
    * average (only one but random input)
    * amortized ()
    
* Upper bound(上限 big O)
    * exists f(n) <= c * g(n)
    
* 下限 big omiga
    * f(n) >= g(n)


## Graphs (V,E)
* degree of a graphs
    * undirected 2E
    * directed E
    
* representing graphs
    * adjacency list
    * adjacency matrix
    
* Tree (kind of graph) (without cycle)

* Theorems: 
    * G is tree => every two nodes of G are joined by a unique path
    * every two nodes of G are joined by a unique path => G is connected and V = E + 1
        * base case: V = 2 => E = 1
        * assume true for every grapth with < V vertices (to v-1 then prove v)
        * Leg G have V nodes and let x and y be adjacent
    * G is connected and V = E + 1 => G is acyclic and V = E + 1
* Corollary: Every nontrivial tree has at least two vertices of degree 1. (Proof. handshake theorem)

## Graph traversals
* DFS
* BFS
    
    