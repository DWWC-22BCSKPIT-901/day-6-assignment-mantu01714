[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/buedSDFh)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17602120&assignment_repo_type=AssignmentRepo)
# DAY-6

## Problems

### 1. Binary Tree Inorder Traversal
- **Description**: Given the root of a binary tree, return the inorder traversal of its nodes' values.
- **Example**:
  - Input: `root = [1, null, 2, 3]`
  - Output: `[1, 3, 2]`
- **Solution Highlights**: Utilizes recursion or an iterative stack-based approach to traverse the tree in inorder.

### 2. Same Tree
- **Description**: Two binary trees are considered the same if they are structurally identical, and the nodes have the same value.
- **Example**:
  - Input: `p = [1, 2, 3], q = [1, 2, 3]`
  - Output: `true`
  - Input: `p = [1, 2], q = [1, null, 2]`
  - Output: `false`
- **Solution Highlights**: Compares nodes recursively, ensuring both structure and values match.

### 3. Construct Binary Tree from Preorder and Inorder Traversal
- **Description**: Given two integer arrays, construct the binary tree using the preorder and inorder traversals.
- **Example**:
  - Input: `preorder = [3, 9, 20, 15, 7], inorder = [9, 3, 15, 20, 7]`
  - Output: `[3, 9, 20, null, null, 15, 7]`
- **Solution Highlights**: Recursively constructs the tree by identifying the root in preorder and partitioning the inorder array.

### 4. Binary Tree Maximum Path Sum
- **Description**: Return the maximum path sum of any non-empty path in a binary tree.
- **Example**:
  - Input: `root = [1, 2, 3]`
  - Output: `6`
- **Solution Highlights**: Uses depth-first search to calculate the maximum path sum by considering paths passing through each node.

### 5. Count Number of Possible Root Nodes
- **Description**: Determines the number of possible root nodes of a tree given edges, guesses, and a correctness threshold.
- **Example**:
  - Input: `edges = [[0,1],[1,2],[1,3],[4,2]], guesses = [[1,3],[0,1],[1,0],[2,4]], k = 3`
  - Output: `3`
- **Solution Highlights**: Employs graph traversal to count correct guesses for different root configurations.


