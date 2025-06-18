# Linked List

## 1. Reverse Linked List

**Question:** Given the `head` of a singly linked list, reverse the list, and return the reversed list.

**Input/Output:**
* **Input:** `head = [1,2,3,4,5]`
    **Output:** `[5,4,3,2,1]`
* **Input:** `head = [1,2]`
    **Output:** `[2,1]`
* **Input:** `head = []`
    **Output:** `[]`

---

## 2. Merge Two Sorted Lists

**Question:** You are given the heads of two sorted linked lists `list1` and `list2`. Merge the two lists in a one sorted list. The list should be made by splicing together the nodes of the first two lists. Return the head of the merged linked list.

**Input/Output:**
* **Input:** `list1 = [1,2,4]`, `list2 = [1,3,4]`
    **Output:** `[1,1,2,3,4,4]`
* **Input:** `list1 = []`, `list2 = []`
    **Output:** `[]`
* **Input:** `list1 = []`, `list2 = [0]`
    **Output:** `[0]`

---

## 3. Add Two Numbers

**Question:** You are given two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order, and each of their nodes contains a single digit. Add the two numbers and return the sum as a linked list. You may assume the two numbers do not contain any leading zero, except the number 0 itself.

**Input/Output:**
* **Input:** `l1 = [2,4,3]`, `l2 = [5,6,4]`
    **Output:** `[7,0,8]`
* **Input:** `l1 = [0]`, `l2 = [0]`
    **Output:** `[0]`
* **Input:** `l1 = [9,9,9,9,9,9,9]`, `l2 = [9,9,9,9]`
    **Output:** `[8,9,9,9,0,0,0,1]`

---

## 4. LRU Cache

**Question:** Design a data structure that follows the constraints of a Least Recently Used (LRU) cache. Implement the `LRUCache` class:
* `LRUCache(int capacity)` Initialize the LRU cache with positive size `capacity`.
* `int get(int key)` Return the value of the `key` if the key exists, otherwise return -1.
* `void put(int key, int value)` Update the value of the `key` if the `key` exists. Otherwise, add the `key-value` pair to the cache. If the number of keys exceeds the `capacity` from this operation, evict the least recently used key.

The functions `get` and `put` must each run in O(1) average time complexity.

**Input/Output:**
* **Input:**
  `["LRUCache", "put", "put", "get", "put", "get", "put", "get", "get", "get"]`
  `[[2], [1, 1], [2, 2], [1], [3, 3], [2], [4, 4], [1], [3], [4]]`
* **Output:**
  `[null, null, null, 1, null, -1, null, -1, 3, 4]`

---

## 5. Merge k Sorted Lists

**Question:** You are given an array of `k` linked-lists `lists`, each linked-list is sorted in ascending order. Merge all the linked-lists into one sorted linked-list and return it.

**Input/Output:**
* **Input:** `lists = [[1,4,5],[1,3,4],[2,6]]`
    **Output:** `[1,1,2,3,4,4,5,6]`
* **Input:** `lists = []`
    **Output:** `[]`
* **Input:** `lists = [[]]`
    **Output:** `[]`
