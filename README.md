# Lab 8 — Breadth-First and Depth-First Search

This repository contains a C++ program demonstrating two fundamental graph traversal algorithms: breadth-first search (BFS) and depth-first search (DFS).

## Contents

- [`Lab8/BFS&DFS.cpp`](Lab8/BFS%26DFS.cpp) — BFS and DFS program
- `Lab8/output/` — output or supporting files, if provided

## Build and run

Requires `g++` or another C++17 compiler:

```bash
g++ -std=c++17 -Wall -Wextra 'Lab8/BFS&DFS.cpp' -o graph-traversal
./graph-traversal
```

Provide the graph and starting vertex as requested by the program. Vertex numbering and graph representation follow the program's input prompts.

## Learning goals

- Traverse graph vertices using BFS and DFS.
- Compare queue-based and stack/recursion-based exploration.
- Observe how traversal order depends on graph representation and neighbor ordering.
