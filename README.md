# Binary Trees Project

## Overview

This project is part of a series of programming challenges focused on binary trees. It includes various C functions implemented to manipulate binary trees, such as creating, traversing, measuring properties like height and size, and checking for specific conditions like fullness and perfection.

## Project Structure

The project contains the following files:

- **`binary_trees.h`**: Header file containing function prototypes and struct definitions.
- **`0-binary_tree_node.c`**: Function to create a new binary tree node.
- **`1-binary_tree_insert_left.c`**: Function to insert a node as the left child of another node.
- **`2-binary_tree_insert_right.c`**: Function to insert a node as the right child of another node.
- **`3-binary_tree_delete.c`**: Function to delete an entire binary tree.
- **`4-binary_tree_is_leaf.c`**: Function to check if a node is a leaf (has no children).
- **`5-binary_tree_is_root.c`**: Function to check if a node is a root (has no parent).
- **`6-binary_tree_preorder.c`**: Function to traverse a binary tree using pre-order traversal.
- **`7-binary_tree_inorder.c`**: Function to traverse a binary tree using in-order traversal.
- **`8-binary_tree_postorder.c`**: Function to traverse a binary tree using post-order traversal.
- **`9-binary_tree_height.c`**: Function to measure the height of a binary tree.
- **`10-binary_tree_depth.c`**: Function to measure the depth of a node in a binary tree.
- **`11-binary_tree_size.c`**: Function to measure the size of a binary tree.
- **`12-binary_tree_leaves.c`**: Function to count the leaves in a binary tree.
- **`13-binary_tree_nodes.c`**: Function to count the nodes with at least one child in a binary tree.
- **`14-binary_tree_balance.c`**: Function to measure the balance factor of a binary tree.
- **`15-binary_tree_is_full.c`**: Function to check if a binary tree is full.
- **`16-binary_tree_is_perfect.c`**: Function to check if a binary tree is perfect.
- **`17-binary_tree_sibling.c`**: Function to find the sibling of a node.
- **`18-binary_tree_uncle.c`**: Function to find the uncle of a node.
- **`binary_tree_print.c`**: Utility function to print a binary tree (provided).

## Usage

To compile the project, use the provided `gcc` command along with the necessary source files:

```bash
gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c <source_files> -o <output_executable>

```

Replace '<source_files>' with the list of source files you want to compile, and '<output_executable>' with the desired name for the executable.

To run individual test cases, compile the corresponding main file along with the required source files:

```bash
gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c <main_file> <source_files> -o <output_executable>

```

Replace '<main_file>' with the name of the main file containing the test cases.

# Contributions

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
