# Trees (BST, Binary Tree, Traversals)

## 1. Maximum Depth of Binary Tree

**Question:** Given the `root` of a binary tree, return its maximum depth. A binary tree's maximum depth is the number of nodes along the longest path from the root node down to the farthest leaf node.

**Input/Output:**
* **Input:** `root = [3,9,20,null,null,15,7]`
    **Output:** `3`
* **Input:** `root = [1,null,2]`
    **Output:** `2`

---

## 2. Diameter of Binary Tree

**Question:** Given the `root` of a binary tree, return the length of the diameter of the tree. The diameter of a binary tree is the length of the longest path between any two nodes in a tree. This path may or may not pass through the root. The length of a path between two nodes is represented by the number of edges between them.

**Input/Output:**
* **Input:** `root = [1,2,3,4,5]`
    **Output:** `3`
* **Input:** `root = [1,2]`
    **Output:** `1`

---

## 3. Validate Binary Search Tree

**Question:** Given the `root` of a binary tree, determine if it is a valid binary search tree (BST). A valid BST is defined as follows:
* The left subtree of a node contains only nodes with keys less than the node's key.
* The right subtree of a node contains only nodes with keys greater than the node's key.
* Both the left and right subtrees must also be binary search trees.

**Input/Output:**
* **Input:** `root = [2,1,3]`
    **Output:** `true`
* **Input:** `root = [5,1,4,null,null,3,6]`
    **Output:** `false`

---

## 4. Lowest Common Ancestor of a BST

**Question:** Given a binary search tree (BST), find the lowest common ancestor (LCA) of two given nodes in the BST. According to the definition of LCA on Wikipedia: “The lowest common ancestor is defined between two nodes `p` and `q` as the lowest node in `T` that has both `p` and `q` as descendants (where we allow a node to be a descendant of itself).”

**Input/Output:**
* **Input:** `root = [6,2,8,0,4,7,9,null,null,3,5]`, `p = 2`, `q = 8`
    **Output:** `6`
* **Input:** `root = [6,2,8,0,4,7,9,null,null,3,5]`, `p = 2`, `q = 4`
    **Output:** `2`

---

## 5. Serialize and Deserialize Binary Tree

**Question:** Serialization is the process of converting a data structure or object into a sequence of bits so that it can be stored in a file or memory buffer, or transmitted across a network connection link to be reconstructed later in the same or another computer environment. Design an algorithm to serialize and deserialize a binary tree. There is no restriction on how your serialization/deserialization algorithm should work. You just need to ensure that a binary tree can be serialized to a string and this string can be deserialized to the original tree structure.

**Input/Output:**
* **Input:** `root = [1,2,3,null,null,4,5]`
    **Output:** `[1,2,3,null,null,4,5]`
* **Input:** `root = []`
    **Output:** `[]`
