# AVL Tree

This repository contains an implementation of an AVL Tree, a self-balancing binary search tree. AVL trees maintain a balanced structure, ensuring that the height difference between left and right subtrees (known as the balance factor) is at most 1.

## Overview

- `TreeNode` Class: Represents a node in the AVL tree.
  - Attributes:
    - `value`: Value stored in the node.
    - `left`: Pointer to the left child node.
    - `right`: Pointer to the right child node.

- `AVLTree` Class: Represents the AVL tree structure.
  - Attributes:
    - `root`: Pointer to the root node.
  - Methods:
    - `isTreeEmpty()`: Check if the tree is empty.
    - `height()`: Get the height of a node.
    - `getBalanceFactor()`: Get the balance factor of a node.
    - `rightRotate()`: Perform a right rotation.
    - `leftRotate()`: Perform a left rotation.
    - `insert()`: Insert a node into the AVL tree.
    - `minValueNode()`: Find the node with the minimum value.
    - `deleteNode()`: Delete a node from the AVL tree.
    - `print2D()`: Print the AVL tree in 2D format.
    - `printPreorder()`, `printInorder()`, `printPostorder()`: Perform preorder, inorder, and postorder traversal.
    - `printLevelOrderBFS()`: Print the AVL tree using level order traversal.
    - `iterativeSearch()`, `recursiveSearch()`: Perform iterative and recursive searches.
    
## Usage


1. Create an instance of the `AVLTree` class.
2. Use the provided methods to perform various operations like insertion, deletion, traversal, searching, etc.

```cpp
#include <iostream>
#include <cstdlib> 
using namespace std;


int main() {
    AVLTree obj;
    int option, val;

    do {
        // Select options on Console
        cin >> option;
        TreeNode* new_node = new TreeNode();

        switch (option) {
            // Menu options...
        }

    } while (option != 0);

    return 0;
}
