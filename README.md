# AI Search Algorithms – Lab Practice

This repo is basically my **lab work / practice notebook** where I played around with classic AI search algorithms using Python 🧠🐍

Nothing fancy — just hands-on implementations to understand how these algorithms actually work under the hood.

## What’s inside

### Graph Representation

* A graph is created using a Python dictionary
* Nodes are represented as strings
* Edges are represented using adjacency lists

This sets up the base structure needed for graph traversal algorithms.

### Breadth First Search (BFS)

* Implemented using `collections.deque`
* Keeps track of visited nodes
* Returns the path from **start node to goal node**

Example use case in the notebook:

* Start node: `S`
* Goal node: `I`

### Uniform Cost Search (UCS)

* Uses Python’s built-in `heapq`
* Implemented on a **2D grid (5x5)**
* Supports different movement costs
* Obstacles are represented using `-1`

The goal here was to understand:

* How priority queues work
* Why UCS always expands the lowest-cost path first
* How it differs from BFS

