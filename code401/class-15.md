# Trees

* Node => A Tree node is a component which may contain it’s own values, and references to other nodes
* Root => The root is the node at the beginning of the tree
* K => A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
* Left => A reference to one child node, in a binary tree
* Right => A reference to the other child node, in a binary tree
* Edge => The edge in a tree is the link between a parent and child node
* Leaf => A leaf is a node that does not have any children
* Height => The height of a tree is the number of edges from the root to the furthest leaf

**Binary-tree** each node has no more than 2 child.

**K-ary Trees** each node has k number child. Big O time = O(n)- Big O space = O(log(n))

**Binary Search tree** . In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.(Big O space = 1 and Big O time = O(n) or O(log(n))when reaching leaf in baanced tree and n when not blanced(which is the worst case) )

### Traversing a tree allows us to search for a node, print out the contents of a tree.

![tree](../img/tree-example.png)

1. Depth first traversal / use stack

  * Pre-order: A, B, D, E, C, F
  * In-order: D, B, E, A, F, C
  * Post-order: D, E, B, F, C, A

2. Breadth First / use queue
        => A, B, C, D, E, F
        But for k-ary trees
        Breadth First Traversal => enqueing cilds instead of parents(enqueueing parent , dequeue parent and enque childs ......)



## Recursion

The process in which a function calls itself directly or indirectly, and this solve too many problems. The idea is to represent a problem in terms of one or more smaller problems, and add one or more base conditions that stop the recursion. For example, we compute factorial n if we know factorial of (n-1). The base case for factorial would be n = 0. We return 1 when n = 0. 

A function fun is called direct recursive if it calls the same function fun. A function fun is called indirect recursive if it calls another function say fun_new and fun_new calls fun directly or indirectly.

Disadvantages => The recursive program has greater space requirements than iterative program as all functions will remain in the stack until the base case is reached. It also has greater time requirements because of function calls and returns overhead.

Advantages => Clean and simple

Reference:

* [Trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html).

* [Recursion](https://www.geeksforgeeks.org/recursion/)