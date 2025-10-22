# A* Pathfinding Algorithm in Python

This project implements the **A\*** (A-star) algorithm — a popular graph search and pathfinding technique used in AI, robotics, and navigation systems.

## 🧩 Overview
The program demonstrates how A* explores paths in a weighted graph using heuristics to find the optimal route from a start node to a goal node.

### Graph Example
The example graph includes nodes:
A, B, C, D, E, F, Z

and the algorithm finds the best path from `A` to `Z`.

## ⚙️ How It Works
- Each node stores its neighbors and edge weights.
- The heuristic (estimated cost to the goal) guides exploration.
- A priority queue determines the next most promising node.
- The algorithm continues until the goal is reached.

## 🧠 Technologies Used
- **Python 3**
- **Priority Queue (queue module)**
- **Heuristic-based Search**

## 🚀 How to Run
1. Download the file `astar_algorithm.py`
2. Open a terminal and run:
   ```bash
   python astar_algorithm.py
The console will print the traversal order of visited nodes.

Output Example
edges :  {'/': ['A'], 'A': ['B', 'C', 'D'], 'B': ['A', 'E'], ...}
weights :  {('/', 'A'): 0, ('A', 'B'): 9, ...}
Traversal :  ['A', 'B', 'C', 'E', 'D', 'F', 'Z']

Author
Ananya Prasad M
MSc Electronics (AI), University of Kerala
