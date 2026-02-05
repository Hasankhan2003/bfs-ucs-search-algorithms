# AI Search Algorithms Lab

This repository contains my **AI lab work** where I implemented and explored **classical search algorithms** using Python.  
The focus is on understanding how search works on **graphs** and **grids**, not on fancy frameworks.

Everything here was done as part of my lab practice.

---

## What’s inside?

### 1️⃣ Graph Representation
- A graph is created using a Python dictionary
- Nodes are represented as strings
- Edges are represented using adjacency lists

Example:
```python
graph = {
    "S": ["A", "B", "D", "E"],
    "A": ["S"],
    "B": ["C", "D", "S"],
    ...
}
