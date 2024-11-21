# Binary Search Trees (BST)
1. A search tree is a tree whose elements are organized to facilitate finding a particular element when needed
2. A binary search tree is a binary tree that for each node n
	1. The left subtree of n contains elements less than the element stored in n
	2. The right subtree of n contains elements greater than or equal to the element stored in n 
3. To determine if a particular value exists in a tree
	1. start at the root
	2. compare target to element at current node
	3. move left from current node if target is less than element in the current node
	4. move right form current node if target is greater than element in the current node 
4. We eventually find the target or encounter the end of a path (target is not found)
5. The particular shape of a binary tree depends on the order in which the elements are added
6. The shape may also be dependent on any additional processing performed on the tree to reshape it
## Finding the Maximum and Minimum

## Successor
1. Given a node in a binary search tree, sometimes we need to finds its successor in the sorted order determined by an inorder tree walk
2. If all keys are distinct the successor of a node x is the node with the smallest key greater than x.key
3. The structure of a binary tree allows us to determine the successor of a node without even comparing keys
4. The procedure returns the successor of a node x in a binary search tree if it exists, and **null** if x has the largest key in the tree
### The Process (find successor of Node x)
1. For x, check if x has right sub-tree
	1. If right sub-tree exists, return the minimum node of the right sub-tree as the successor of x
2. If x is the left child of its parent, return x's parent as its successor
3. Return the parent of the last ancestor
## More
1. Case: if the right subtree of node x is empty and x has a successor y
2. The successor of the node with key 13 is the node with key 15. To find y, we simply go up from the tree form x until we encounter a node that is the left child of its parent
## Transplant
1. Replaces one subtree as a child of its parent with another subtree. When TRANSPLANT replaces the subtree rooted at node u with the subtree rooted at node v, node u's parent becomes node v's parent, and u's parent ends up having v as its appropriate child
# Balancing BSTs
1. As operations are performed on a BST, it could become highly unbalanced (a degenerate tree)
2. Our implementation does not ensure the BST stars balanced
3. Other approaches do, such as AVL trees and red/black trees
4. We will explore rotations - operations on binary search trees to assist in the process of keeping a tree balanced
5. Rotations do not solve all problems created by unbalanced trees, but show the basic algorithmic....
## Rotations
1. A right rotation can be performed at any level of a tree, around the root of any subtree
2. Corrects an imbalance caused by a long path in the left subtree of the left child of the root
3. To correct the imbalance
	1. Make the left child element of the root the new root element
	2. Make the former root element the right child element of the new root
	3. Make the right child of what was the left child of the former root the new left child of the former root