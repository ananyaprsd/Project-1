# Breadth-First Search (BFS) Algorithm in Python

This project demonstrates the **Breadth-First Search (BFS)** algorithm for graph traversal using Python.  
It explores nodes in a graph level by level, starting from a given source node.

---

## 🧠 Overview
BFS is a fundamental graph traversal algorithm used in:
- Pathfinding and network routing
- Web crawlers
- Social network analysis
- Shortest path algorithms (in unweighted graphs)

In this implementation:
- The graph is represented using an adjacency list.
- A queue is used to manage the order of node exploration.
- Each visited node is printed in traversal order.

---

## 🧩 Code Summary
```python
v = {'a', 'b', 'c', 'd', 'e'}

graph = {
    'a': ['b', 'c'],
    'b': ['a', 'd'],
    'c': ['a', 'd'],
    'd': ['b', 'c', 'e'],
    'e': ['d']
}

visited = []
queue = []

def bfs(visited, graph, node):
    visited.append(node)
    queue.append(node)
    while queue:
        m = queue.pop(0)
        print(m, end=" ")
        for neighbour in graph[m]:
            if neighbour not in visited:
                visited.append(neighbour)
                queue.append(neighbour)

print("The path of BFS algorithm is:")
bfs(visited, graph, 'a')


Output Example
The path of BFS algorithm is:
a b c d e

How to Run

Save the file as bfs.py

Run the program:

python bfs.py


The BFS traversal order will be displayed in the console.

Technologies Used

Python 3

Data structures: List, Queue

👩‍💻 Author

Ananya Prasad M
MSc Electronics (Specialization: Artificial Intelligence)