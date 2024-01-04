**0x1D. C - Binary trees**

0. New node: 

* C function that creates a binary tree node with a given parent and value.
* Returns a pointer to the new node, or NULL on failure.

1. Insert left:

* C function that inserts a node as the left-child of another.
* Returns a pointer to the new node, or NULL on failure.
* If the given parent already contains a left node, the new node takes its place and the old left-child becomes the left-child of the new node.

2. Insert right:

* C function that inserts a node as the right-child of another.
* Returns a pointer to the new node, or NULL on failure.
* If the given parent already contains a right node, the new node takes its place and the old right-child becomes the right-child of the new node.

3. Delete:

* C function that deletes an entire binary tree.

4. Is leaf:

* C function that checks if a given node is a leaf.
* Returns 1 if the node is a leaf, 0 otherwise.

5. Is root:

* C function that checks if a given node is a root.
* Returns 1 if the node is a root, 0 otherwise.

6. Pre-order traversal:

* C function that traverse a tree using pre-order traversal.

7. In-order traversal:

* C function that traverses a tree using in-order traversal.

8. Post-order traversal:

* C function that traverses a tree using post-order traversal.

9. Height:

* C function that returns the height of a binary tree.

10. Depth: 

* C function that returns the depth of a given node in a binary tree.

11. Size:

* C function that returns the size of a binary tree.

12. Leaves:

* C function that returns the number of leaves in a binary tree.

13. Nodes:

* C function that returns the number of nodes in a binary tree with at least one child.

14. Blance factor:

* C function that returns the balance factor of a binary tree.

15. Is full:

* C function that checks if a binary tree is full.
* Returns 1 if a tree is full, 0 otherwise.

16. Is perfect:

* C function that checks if a binary tree is perfect.
* Returns 1 if a tree is perfect, 0 otherwise.

17. Sibling:

* C function that returns a pointer to the sibling of a given node in a binary tree.
* Returns NULL if no sibling is found.

18. Uncle:

* C function that returns a pointer to the uncle of a given node in a binary tree.
* Returns NULL if no uncle is found.

19. Lowest common ancestor:

* C function that returns a pointer to the lowest common ancestor node of two given nodes in a binary tree.
* Returns NULL if no common ancestor is found.

20. Level-order traversal:

* C function that traverses a binary tree using level-order traversal.

21. Is complete:

* C function that checks if a binary tree is complete.
* Returns 1 if the tree is complete, 0 otherwise.

22. Rotate Left:

* C function that performs a left-rotation on a binary tree.
* Returns a pointer to the new root node of the tree after rotation.

23. Rotate Right:

* C function that performs a right-rotation on a binary tree.
* Returns a pointer to the new root node of the tree after rotation.

24. Is BST:

* C function that checks if a binary tree is a valid binary search tree.
* Returns 1 if the tree is a valid BST, 0 otherwise.

25. BST- Insert:

* C function that inserts a value into a binary search tree.
* Returns a pointer to the new node, or NULL on failure.
* If the tree is NULL, the value becomes the root node.
* The value is ignored if it is already present in the tree.

26. BST - Array to BST:

* C function that builds a binary search tree from an array.
* Returns a pointer to the root node of the created tree, or NULL on failure.

27. BST - Search:

* C function that searches for a value in a binary search tree.
* If the value is matched in the BST, returns a pointer to the matched node.
* Otherwise, returns NULL.

28. BST - Remove:

* C function that removes a node from a binary search tree.
* Returns a pointer to the new root node of the tree after deletion.
* If the node to be deleted has two children, it is replaced with its first in-order successor.

29. Big O #BST:

* Text file containing the average time complexities of binary search tree operations (one answer per line):
* Inserting the value n.
* Removing the node with the value n.
* Searching for a node in a BST of size n.

36. Is Binary heap:

37. Heap - Insert:

38. Heap - Array to Binary Heap:

39. Heap - Extract:

40. Heap - Sort:

41. Big O #Binary Heap:

* Text file containing the average time complexities of binary heap opeartions (one answer per line):
* Inserting the value n.
* Extracting the root node.
* Searching for a node in a binary heap of size n.