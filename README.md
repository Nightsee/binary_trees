# Binary Trees

## What is a Binary Tree?
A binary tree is a data structure composed of nodes, each having at most two children, forming a hierarchical structure.

## Binary Tree vs. Binary Search Tree (BST)
A binary tree is a general structure with no specific ordering of elements. A Binary Search Tree (BST) is a type of binary tree where the left child's value is less than the parent's value, and the right child's value is greater. This enables efficient searching.

## Time Complexity Gain Compared to Linked Lists
Binary trees can provide faster search, insertion, and deletion operations compared to linked lists. Searching in a balanced binary search tree has a time complexity of O(log n), while linked lists have O(n) time complexity for these operations.

## Concepts of Binary Trees
- **Depth**: The level of a node in the tree (root has depth 0).
- **Height**: The length of the longest path from a node to a leaf.
- **Size**: The total number of nodes in the tree.

## Traversal Methods for Binary Trees
1. **In-Order**: Left, Root, Right.
2. **Pre-Order**: Root, Left, Right.
3. **Post-Order**: Left, Right, Root.
4. **Level-Order**: Traverse by levels, left to right.

## Types of Binary Trees
- **Complete Binary Tree**: Every level is fully filled, except possibly the last level. Nodes are filled left to right.
- **Full Binary Tree**: Every node has either 0 or 2 children.
- **Perfect Binary Tree**: All internal nodes have exactly two children, and all leaf nodes are at the same level.
- **Balanced Binary Tree**: The height difference between the left and right subtrees of any node is at most one.

