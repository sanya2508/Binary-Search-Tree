# Binary Search Tree
Search is an expensive operation in Binary Tree! Worst case complexity: O(n)


BST is a special kind of binary tree where elements are ordered such that all the elements smaller than the current node goes to the left side and all the elements greater or equal to the current node goes to the right side.

Each sub-tree should be a BST.
<hr/>

For efficient searching we can apply binary search! 
Average case: O(logn) or O(h) in case of Balanced Tree.
Worst case: O(n) in case of skewed case.
<hr/>

## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/BSTinsertAndBuild.cpp">BST: Insert and Build</a>

<hr/>

## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/BSTsearch.cpp">BST: Searching</a>

<hr/>

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
     
<hr/> 

## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/checkForBST.cpp">Check for BST</a>
 * root should lie in between the maximum value on the left and minimum value on the left, and the left and right sub-tree must be a BST.
 * Bottom-up approach
 * Top-down approach (in the link).

<hr/>

## <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/BSTtoSortedLinkedList.cpp">Flatten a BST</a>
*BST to sorted Linked List*
 * Break it recursively.
 * Get one linked list from LST, Get one linked list from RST, attach the tail of LST LL to head of root and head of RST LL to tail of root.
 * Case 1: No Right sub tree.
 * Case 2: No Left sub tree.
 * Case 3: Leaf node.
 * Case 4: Both non NULL sub trees.

<hr/>

## Construct a BST from Preorder
*in O(n) time.*

<hr/>

## Catalan Number (very important)
*Count number of BST's that can be formed using n number of nodes numbered from 1 to n.*
* Any ith node can become the root node.
* Reference: https://www.youtube.com/watch?v=0s20L4-chDA
* Number of binary tree= n!* Number of BST.
* Number of unlabelled binary tree= same as BST.

<hr/>

## Set STL
 * Set is a container used to store unique collection of elements.
 * By default it is ordered.
 * Uses tree like data structure.
 * Most operations are of O(log n) time.
 * You can't update elements. For upating of elements first you would have to remove an element and then insert another element.
 * We can use functions like upper_bound and lower_bound in set.
 * <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/Unique%20permutation%20using%20set%20stl.cpp">Unique Permutation using set STL</a>

<hr/>

## Multiset

  * Set like container that can contain multiple elements that have same value.
  * All elements are stored in a specific sorted order.
  * Values once inserted can't be modified.
  * Associative container - key!! (key and values are same).
  * Uses BST data structure.
  * ### <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/Multi%20set%20stl.cpp">Multiset Implementation </a>
  * ### <a href="https://github.com/sanya2508/Binary-Search-Tree/blob/master/Multiset%20for%20custom%20class.cpp"> Multiset Custom class</a>

 <hr/>


