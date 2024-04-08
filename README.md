# Binary-Search-Tree
This shows the implementation of a Binary Search Tree
A number of methods in the "Tree" class such as
insert() - this method takes an int parameter, it checks if the root node is empty first, if empty, it adds the value as the root node, if not, it checks if it is lesser or greater than the root node and adds to the keft node or right node accordingly

find() - returns a boolean value indicating whether or not the valie you're searching for is in the Tree. It follows a Pre-order trasversal paradigm as it checks the root node first before going to the left and right nodes.

The Trasverse merthods - traversePreOrder(),  traverseInOrder(), traversePostOrder()
are just demonstrations of Depth First Trasversal, using print methods
Side note - They all operate in O(n) time complexity.
