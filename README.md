## Binary tree 🌱

![App Screenshot](https://www.nicepng.com/png/detail/265-2653801_binary-plan-binary-tree-mlm-png.png)

## Description 👋
In computer science, a binary tree is a tree data structure where each node can have at most two children: a left child and a right child. It is a type of k-ary tree, specifically with k=2.
A binary tree can be defined recursively using set theory. It consists of a tuple (L, S, R), where L and R are binary trees themselves (or the empty set), and S is a singleton set containing the root node. It's worth noting that some authors also consider the empty set as a valid binary tree.
This definition highlights the hierarchical nature of a binary tree, where nodes can be organized into levels, and each node has a parent-child relationship with its adjacent nodes. The binary tree structure is widely used in various algorithms and data structures in computer science due to its versatility and efficient traversal properties.

## Basic Binary Tree👍

```bash
  /**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
```
- Binary Search Tree:
```bash
  typedef struct binary_tree_s bst_t;
```
- AVL Tree
```bash
  typedef struct binary_tree_s avl_t;
```
- Max Binary Heap
```bash
  typedef struct binary_tree_s heap_t;
```
## Authors
- [Mouayed sabbagh](https://github.com/MOUAYEDSB)
-