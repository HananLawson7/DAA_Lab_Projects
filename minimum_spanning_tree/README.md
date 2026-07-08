# Minimum Spanning Tree using Kruskal's and Prim's Algorithms

A Python implementation of **Minimum Spanning Tree (MST)** algorithms using **Kruskal's Algorithm** and **Prim's Algorithm**, along with a comparison of their results.

## Features

* Kruskal's Algorithm implementation
* Prim's Algorithm implementation
* Union-Find (Disjoint Set Union) with Path Compression and Union by Rank
* Priority Queue (Min Heap) implementation for Prim's Algorithm
* MST edge list generation
* Total MST cost calculation

## Project Structure

```text
Minimum_Spanning_Tree/
├── mst.py
└── README.md
```

## Run

```bash
python mst.py
```

## Sample Output

```text
=== Kruskal's MST ===
Edge (0 - 3)  Weight: 5
Edge (2 - 4)  Weight: 5
Edge (3 - 5)  Weight: 6
Edge (0 - 1)  Weight: 7
Edge (1 - 4)  Weight: 7
Edge (4 - 6)  Weight: 9
Total MST Cost: 39

=== Prim's MST ===
Edge (0 - 3)  Weight: 5
Edge (3 - 5)  Weight: 6
Edge (0 - 1)  Weight: 7
Edge (1 - 4)  Weight: 7
Edge (4 - 2)  Weight: 5
Edge (4 - 6)  Weight: 9
Total MST Cost: 39
```

## Complexity Analysis

| Algorithm                   | Best Case  | Average Case | Worst Case |
| --------------------------- | ---------- | ------------ | ---------- |
| Kruskal's Algorithm         | O(E log E) | O(E log E)   | O(E log E) |
| Prim's Algorithm (Min Heap) | O(E log V) | O(E log V)   | O(E log V) |

where:

* **V** = Number of vertices
* **E** = Number of edges

## Author

Hanan Lawson

## Course

Design and Analysis of Algorithms (DAA) Lab
