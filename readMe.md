# Binary Search Tree Implementation

This Python code provides a basic implementation of a Binary Search Tree (BST) along with essential operations such as insertion, lookup, breadth-first search, and recursive breadth-first search.

## Code Overview

### `Node` Class

The `Node` class represents a node in the Binary Search Tree. Each node contains a value (`val`), a left child (`left`), and a right child (`right`).

```python
class Node:
  def __init__(self, val):
    self.val = val
    self.left = None
    self.right = None
```

### `BinarySearchTree` Class

The `BinarySearchTree` class is the main implementation of the Binary Search Tree. It includes methods for inserting a value, looking up a value, performing breadth-first search, and recursively performing breadth-first search.

```python
class BinarySearchTree:
  def __init__(self):
    self.root = None

  def insert(self, val):
    # ... (insertion logic)

  def lookup(self, val):
    # ... (lookup logic)

  def breadthfirstsearch(self):
    # ... (breadth-first search logic)

  def recursivebfs(self, queue, mylist):
    # ... (recursive breadth-first search logic)
```

### Usage Example

The code includes a usage example demonstrating how to create a Binary Search Tree, insert values, and perform various operations.

```python
tree = BinarySearchTree()
tree.insert(9)
tree.insert(4)
tree.insert(6)
tree.insert(20)
tree.insert(170)
tree.insert(15)
tree.insert(1)

x = tree.lookup(170)
print(x)
print(tree.breadthfirstsearch())
print(tree.recursivebfs([tree.root], []))
```

