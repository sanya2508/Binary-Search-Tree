# Binary Search Tree
Search is an expensive operation in Binary Tree! Worst case complexity: O(n)


BST is a special kind of binary tree where elements are ordered such that all the elements smaller than the current node goes to the left side and all the elements greater or equal to the current node goes to the right side.

Each sub-tree should be a BST.

For efficient searching we can apply binary search! 
Average case: O(logn) or O(h) in case of Balanced Tree.
Worst case: O(n) in case of skewed case.

## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/BSTinsertAndBuild.cpp">BST: Insert and Build</a>


## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/BSTsearch.cpp">BST: Searching</a>


## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/BSTdeletion.cpp">BST: Deletion</a>
 * 3 types of nodes:
   1. Leaf node(no child)
      * Come to that node, delete and return NULL.
   2. One child
      * Either left child will not be NULL, or right child will not be NULL.
      * Return the child of the node to be deleted to the parent of the node to be deleted.
   3. Two child
      * We need someone who can replace the node to be deleted.
      * Root node should be replaced by immediate predecessor or successor.
      

## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/checkForBST.cpp">Check for BST</a>


## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/BSTtoSortedLinkedList.cpp">BST to sorted Linked List</a>
