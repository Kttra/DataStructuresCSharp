# Data Structures
Data structures in C#. This project will go over linked list, doubly linked list, and other types of data structures. Note that some of the data structures below isn't included in the source code because they already have been implemented in the System.Collections.Generic namespace.

**Linked List**
--------------------
A linked list is a linear collection of data/value elements where their order is not given by their physical placement in memory. Each element instead points to the next. It is a data structure consisting of a collection of nodes which together represent a sequence.

<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/163313907-1522e02b-b3e0-493f-b1c2-54a600e6a5f1.png"><img>
</p>

**Doubly Linked List**
--------------------
A doubly linked list is a linked data structure that has a set of linked nodes. Each node contains three elements: two link fields (pointing to the one behind and one in front) and one data field (usually an integer).

<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/163319019-cb3246a4-be1b-4b4e-b659-6ead75abc6d3.png"><img>
</p>

**Stacks**
-----------------
A stack is a linear data structure where it follows a particular order in which the operations are performed. The order are LIFO (Last In First Out) or FILO (First In Last Out).

<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/163494801-6b9aaa87-60b8-44c9-84b8-f2fc9ab41a54.png"><img>
</p>
  
**Queue**
-----------------
A queue is similar to a stack except it is FIFO. It is a list or collection that has a restriction where insertion can only be performed at the rear and deletion can only be performed at the front.

<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/163496502-98e219f1-e617-416f-8289-c98707263638.png"><img>
</p>

**Binary Search Tree**
-----------------
A Binary Search Tree or a BST is a rooted binary tree data structure with internal nodes that store a value greater than all the values in the node's left subtree and less than those in its right subtree. In other words, it has these properties:

- The value of the key of the left sub-tree is less than the value of its parent (root) node's key.
- The value of the key of the right sub-tree is greater than or equal to the value of its parent (root) node's key.
- The left child node has a value smaller than the parent node, and the child node in the right contains a value greater than the parent node.

<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/164086536-e2183329-56ca-4cd4-be2e-554657034a1a.png"><img>
</p>

**BST Traversals**
------------
Depth First Traversals: 
(a) Inorder (Left, Root, Right) : 4 2 5 1 3 
(b) Preorder (Root, Left, Right) : 1 2 4 5 3 
(c) Postorder (Left, Right, Root) : 4 5 2 3 1
Breadth-First or Level Order Traversal: 1 2 3 4 5 

<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/168935509-110879f5-02dd-457d-a59a-fb6fd4443682.png"><img>
</p>


**Hashtable**
-----------------
Hashtable stores key/value pair in hash table. In Hashtable we specify an object that is used as a key, and the value we want to associate to that key. The key is then hashed, and the resulting hash code is used as the index at which the value is stored within the table.

Key → Value Lookup

<p align="center">
<img src="https://user-images.githubusercontent.com/100814612/168933577-90d84edf-3f98-4935-b0b1-1f89d4a2d577.png" width = "600", height = "340"><img>
</p>


**Other Related Projects**
----------------
[Data Structures in C++](https://github.com/Kttra/DataStructures) - Similar to this project, except I go over examples of data structures in C++.

[C# Code Quick Reference](https://github.com/Kttra/CSharpCode) - A quick overview of concepts in C#.
