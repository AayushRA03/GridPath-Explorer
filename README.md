# 🌐 A\* Pathfinding Algorithm Visualizer

This project is a visual demonstration of the **A\* (A-Star) pathfinding algorithm** built with **Pygame**. It lets users draw walls, set start and end points, and visually observe how A\* efficiently finds the shortest path in a grid.
![test run](https://github.com/user-attachments/assets/5c5a01b5-58de-4913-90a4-940aa61990aa)



> The A\* algorithm is widely used in games and navigation systems due to its optimal and complete nature.

---

## 🚀 Features

* Interactive grid where:

  * 🟧 Orange = Start node
  * 🟦 Turquoise = End node
  * ⬛ Black = Barrier
  * 🟥 Red = Closed nodes
  * 🟩 Green = Open nodes
  * 🟪 Purple = Final path

* Mouse interaction to create barriers and points.

* Spacebar to start the A\* algorithm.

* "C" key to clear/reset the grid.

---

## 🧠 Algorithm Details

**A\*** is a graph traversal and path search algorithm, which finds the shortest path between nodes using:

```
f(n) = g(n) + h(n)
```

* `g(n)` is the cost from the start node to the current node.
* `h(n)` is the heuristic estimated cost to reach the end node (here: Manhattan distance).

---

## 🖥️ How to Run

### 🔧 Requirements

* Python 3.6+
* Pygame

### 📦 Installation

```bash
pip install pygame
```

### ▶️ Run the script

```bash
python astar_pathfinding_visualizer.py
```

---

## 🕹️ Controls

| Action                      | Control           |
| --------------------------- | ----------------- |
| Set Start Node              | Left-click        |
| Set End Node                | Left-click        |
| Draw Barriers (Walls)       | Left-click & drag |
| Erase Nodes                 | Right-click       |
| Start Pathfinding Algorithm | Press `SPACE`     |
| Clear Grid                  | Press `C`         |
| Quit Program                | Press Close (X)   |

---

## 🗂️ Project Structure

```
.
├── astar_pathfinding_visualizer.py   # Main script
├── README.md                         # Project documentation
```

---

## 🛠️ Technologies Used

* **Python**
* **Pygame**
* **A* Algorithm (Graph Search)*\*

---

## ✨ Screenshots

| Building Barriers                           | Visualizing Path                         |
| ------------------------------------------- | ---------------------------------------- |
| ![Barrier](https://i.imgur.com/LzwOnVq.png) | ![Path](https://i.imgur.com/sT3aOGN.png) |

---

## 📌 To Do (Suggestions for Improvement)

* Add diagonal movement
* Support for other algorithms (Dijkstra, BFS, DFS)
* Adjustable grid size and speed
* GUI controls for interactions (buttons, sliders)

---


