# Labyrinth Generator — C

This project implements a maze (labyrinth) generator in pure C, focusing on low-level memory management, grid-based algorithms, and procedural generation techniques.

The maze is generated programmatically using a classical algorithm and represented as a 2D grid, where walls and paths are explicitly managed in memory.

---

## Objectives

- Practice C programming with explicit memory management
- Implement a grid-based algorithm from scratch
- Explore procedural content generation
- Reinforce algorithmic thinking and control flow
- Write clean, modular, and well-structured C code

---

## Algorithm

The maze is generated using **Depth-First Search (DFS) with backtracking**, a common algorithm for procedural maze generation.

High-level steps:
1. Start from an initial cell
2. Randomly choose an unvisited neighboring cell
3. Remove the wall between the current cell and the chosen neighbor
4. Recursively visit the neighbor
5. Backtrack when no unvisited neighbors remain

This approach guarantees:
- A fully connected maze
- No isolated sections
- Exactly one path between any two cells (perfect maze)

---

## Features

- Configurable maze size
- Randomized generation
- Grid-based representation
- ASCII visualization in terminal
- Modular design (separation between logic and visualization)

---


