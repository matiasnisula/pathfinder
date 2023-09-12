# Project Specification

The aim of this project is to compare and analyze how to find the shortest path between two nodes in a graph using two path finding algorithms; Dijkstra's and IDA*.

## Data Structures and Algorithms
- **Algorithms:**
  - Dijkstra's Algorithm
  - IDA* Algorithm

- **Data Structures:**
  - Heap (Dijkstra)
  - Tree, Stack (IDA*)

## Time and Space Complexities
#### Dijkstra's Algorithm
  - Time Complexity: O((V + E) log V) with a priority queue or heap, where V is the number of vertices and E is the number of edges.
  - Space Complexity: O(V)

#### IDA* Algorithm
  - Time Complexity: O(b^d), where b is the branching factor and d is the depth of the shallowest goal state.
  - Space Complexity: O(d), where d is the depth of the shallowest goal state.

## Program Input and Usage
- **Input:** TODO

## Programming language
C#

## Documentation Language
English

## Degree Program
Tietojenkäsittelytieteen kandidaatti (TKT)

## Sources
- https://en.wikipedia.org/wiki/Iterative_deepening_A*
- https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm
- http://theory.stanford.edu/~amitp/GameProgramming/AStarComparison.html
