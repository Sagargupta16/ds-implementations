# Data Structures & Algorithms -- C++ Implementations

A comprehensive C++ library of fundamental data structures and algorithms, from basic arrays and recursion to advanced graph algorithms and self-balancing trees.

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Algorithms](https://img.shields.io/badge/Algorithms-16_Topics-blue?style=flat)
![Educational](https://img.shields.io/badge/Purpose-Educational-green?style=flat)

## Overview

Well-documented C++ implementations of core data structures and algorithms organized into 16 topics. Each implementation prioritizes clarity and educational value, covering the full spectrum from basic recursion patterns to minimum spanning trees and AVL tree rotations.

## Topics Covered

```
DS-Implementations/
├── 01_Recursion/           # Tail, head, tree, nested recursion
├── 02_Arrays/              # Array operations, 2D arrays
├── 03_ArrayADT/            # Array ADT, merging, set operations
├── 05_Matrices/            # Diagonal, triangular, symmetric, Toeplitz
├── 06_SparseMatrix/        # Sparse matrix, polynomial operations
├── 07_LinkedList/          # Singly, doubly, circular
├── 08_Stack/               # Array/LL stack, infix-to-postfix, balanced parens
├── 09_Queue/               # Circular, priority, deque, queue-from-stacks
├── 10_Tree/                # Binary tree (array/LL), all traversals
├── 11_BST/                 # Binary Search Tree operations
├── 12_AVLT/                # AVL Trees with rotations
├── 13_Search Tree/         # 2-3 Trees, 2-3-4 Trees, Red-Black Trees
├── 14_Heap/                # Min/max heaps, heap sort
├── 15_SortingTechs/        # 9 sorting algorithms
├── 16_HashingTechs.cpp/    # Chaining, linear/quadratic probing, double hashing
└── 17_Graphs/              # Adjacency matrix, BFS, DFS, MST
```

## Algorithms Index

### Sorting (15_SortingTechs)

| Algorithm | Time (Avg) | Time (Worst) | Space | Stable |
|-----------|-----------|-------------|-------|--------|
| Bubble Sort | O(n^2) | O(n^2) | O(1) | Yes |
| Selection Sort | O(n^2) | O(n^2) | O(1) | No |
| Insertion Sort | O(n^2) | O(n^2) | O(1) | Yes |
| Merge Sort | O(n log n) | O(n log n) | O(n) | Yes |
| Quick Sort | O(n log n) | O(n^2) | O(log n) | No |
| Heap Sort* | O(n log n) | O(n log n) | O(1) | No |
| Count Sort | O(n+k) | O(n+k) | O(k) | Yes |
| Bin/Bucket Sort | O(n+k) | O(n^2) | O(n+k) | Yes |
| Radix Sort | O(nk) | O(nk) | O(n+k) | Yes |
| Shell Sort | O(n log n) | O(n^2) | O(1) | No |

*Heap Sort lives in `14_Heap/02_HeapSort.cpp`.

### Graph Algorithms (17_Graphs)

| Algorithm | Purpose | Complexity |
|-----------|---------|-----------|
| BFS | Level-order traversal | O(V+E) |
| DFS | Depth-first traversal | O(V+E) |
| Prim's | Minimum spanning tree | O(V^2) |
| Kruskal's | Minimum spanning tree | O(E log E) |

### Tree Operations

| Structure | Key Operations |
|-----------|---------------|
| BST | Insert, delete, search, traversals |
| AVL Tree | Rotations (LL, RR, LR, RL), balancing |
| 2-3 Tree | Multi-key nodes, split/merge |
| Red-Black Tree | Color-based balancing |

## Getting Started

### Prerequisites

- C++ compiler (GCC, Clang, or MSVC)

### Compile and Run

```bash
git clone https://github.com/Sagargupta16/DS-Implementations.git
cd DS-Implementations

# Example: Run merge sort
g++ -o mergesort 15_SortingTechs/05_MergeSort.cpp
./mergesort

# Example: Run graph traversals (BFS, DFS)
g++ -o graph 17_Graphs/01_undirected_unweighted/01_adjacency_matrix.cpp
./graph
```

## Learning Path

| Level | Topics |
|-------|--------|
| Beginner | Recursion -> Arrays -> Linked Lists |
| Intermediate | Stacks -> Queues -> Trees -> Sorting |
| Advanced | Graphs -> Hashing -> AVL/Red-Black Trees |

## License

MIT -- Open source for educational use.
