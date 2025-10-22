# 🌳 Depth-First Search (DFS) — Python

A simple **graph traversal** project demonstrating the **Depth-First Search (DFS)** algorithm using recursion.

---

## 🔍 Overview
- Explores nodes by going deep before backtracking  
- Uses adjacency list representation  
- Prints traversal order from a chosen start node  

---

## 🧩 Example Code
```python
def dfs(visited, graph, node):
    if node not in visited:
        print(node)
        visited.append(node)
        for neighbour in graph[node]:
            dfs(visited, graph, neighbour)

dfs(visited, graph, 'a')

Output:

a  
b  
d  
e  
c  
f  
g

 Run it
python dfs_traversal.py

Author
Ananya Prasad M
MSc Electronics (AI), University of Kerala