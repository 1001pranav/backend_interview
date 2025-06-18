# Stack, Queue

## 1. Valid Parentheses

**Question:** Given a string `s` containing just the characters `(`, `)`, `{`, `}`, `[` and `]`, determine if the input string is valid.

An input string is valid if:
1.  Open brackets must be closed by the same type of brackets.
2.  Open brackets must be closed in the correct order.

**Input/Output:**
* **Input:** `s = "()"`
    **Output:** `true`
* **Input:** `s = "()[]{}"`
    **Output:** `true`
* **Input:** `s = "(]"`
    **Output:** `false`

---

## 2. Min Stack

**Question:** Design a stack that supports push, pop, top, and retrieving the minimum element in constant time.

Implement the `MinStack` class:
* `MinStack()` initializes the stack object.
* `void push(int val)` pushes the element `val` onto the stack.
* `void pop()` removes the element on the top of the stack.
* `int top()` gets the top element of the stack.
* `int getMin()` retrieves the minimum element in the stack.

**Input/Output:**
* **Input:**
  `["MinStack","push","push","push","getMin","pop","top","getMin"]`
  `[[],[-2],[0],[-3],[],[],[],[]]`
* **Output:**
  `[null,null,null,null,-3,null,0,-2]`

---

## 3. Daily Temperatures

**Question:** Given a list of daily temperatures `T`, return a list such that, for each day in the input, tells you how many days you would have to wait until a warmer temperature. If there is no future day for which this is possible, put `0` instead.

**Input/Output:**
* **Input:** `T = [73, 74, 75, 71, 69, 72, 76, 73]`
    **Output:** `[1, 1, 4, 2, 1, 1, 0, 0]`
* **Input:** `T = [30, 40, 50, 60]`
    **Output:** `[1, 1, 1, 0]`
* **Input:** `T = [30, 60, 90]`
    **Output:** `[1, 1, 0]`

---

## 4. Implement Queue using Stacks

**Question:** Implement a first in first out (FIFO) queue using only two stacks. The implemented queue should support all the functions of a normal queue (`push`, `peek`, `pop`, and `empty`).

**Input/Output:**
* **Input:**
  `["MyQueue", "push", "push", "peek", "pop", "empty"]`
  `[[], [1], [2], [], [], []]`
* **Output:**
  `[null, null, null, 1, 1, false]`

---

## 5. Largest Rectangle in Histogram

**Question:** Given an array of integers `heights` representing the histogram's bar height where the width of each bar is 1, return the area of the largest rectangle in the histogram.

**Input/Output:**
* **Input:** `heights = [2, 1, 5, 6, 2, 3]`
    **Output:** `10`
* **Input:** `heights = [2, 4]`
    **Output:** `4`
