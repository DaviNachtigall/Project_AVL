# AVL Tree Implementation in C

An efficient, self-balancing Binary Search Tree (AVL Tree) implementation written in C. This project handles dynamic node insertion, automatic height updates, and tree balancing through single and double rotations. It also includes visualization support via Graphviz.
<img width="1444" height="712" alt="image" src="https://github.com/user-attachments/assets/deb396ea-0d1e-4c1f-9274-11fa82694ce8" />

## Features

- **Self-Balancing Operations**: Implements Left, Right, Left-Right, and Right-Left rotations to maintain an $O(\log n)$ height.
- **Dynamic Memory Management**: Includes routines for allocating nodes and fully freeing tree memory to prevent leaks.
- **Graphviz Export**: Automatically generates a `.dot` file to visually render the tree structure.
- **Duplicate Prevention**: Rejects duplicate values to maintain standard AVL properties.

## Getting Started

### Prerequisites

- A C compiler (e.g., `gcc` or `clang`)
- [Graphviz](https://graphviz.org/) *(optional, required only for rendering the tree visually)*

### Building and Running

1. Compile the source code:
   ```bash
   gcc -o avl_tree AVLTreeNumber.c
