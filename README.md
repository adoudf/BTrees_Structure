#Balanced B-Tree Implementation

This C++ program implements a balanced B-tree data structure with basic operations like insertion and range search.
 
 To compile: make all
 To execure: make run
 To clean: make clean
 
Note use valgrind to verify proper memory deallocation


## Introduction
This program defines a balanced B-tree structure and provides methods for insertion and searching within a specified range. The B-tree is a self-balancing tree data structure that maintains sorted data and allows searches, sequential access, insertions, and deletions in logarithmic time. The tree is built while generating the keys.

## Usage
To use this implementation, include the necessary header files and use the `BalancedTree` class to perform operations on the B-tree.

## Methods
### `BalancedTree`
- Constructor: Initializes the B-tree with a null root.

### `~BalancedTree`
- Destructor: Frees memory allocated for the tree nodes.

### `insert(int key)`
- Inserts a new key into the B-tree.

### `searchForKeys(int smallest, int largest)`
- Searches for keys within a specified range and returns a vector of matching keys.

### `displayTree()`
- Displays the keys of the B-tree in sorted order.

