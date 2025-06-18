# Greedy & Sorting

## 1. Assign Cookies

**Question:** Assume you are an awesome parent and want to give your children some cookies. But, you should give each child at most one cookie. Each child `i` has a greed factor `g[i]`, which is the minimum size of a cookie that the child will be content with; and each cookie `j` has a size `s[j]`. If `s[j] >= g[i]`, we can assign the cookie `j` to the child `i`, and the child `i` will be content. Your goal is to maximize the number of your content children and output the maximum number.

**Input/Output:**
* **Input:** `g = [1,2,3]`, `s = [1,1]`
    **Output:** `1`
* **Input:** `g = [1,2]`, `s = [1,2,3]`
    **Output:** `2`

---

## 2. Non-overlapping Intervals

**Question:** Given an array of intervals `intervals` where `intervals[i] = [starti, endi]`, return the minimum number of intervals you need to remove to make the rest of the intervals non-overlapping.

**Input/Output:**
* **Input:** `intervals = [[1,2],[2,3],[3,4],[1,3]]`
    **Output:** `1`
* **Input:** `intervals = [[1,2],[1,2],[1,2]]`
    **Output:** `2`
* **Input:** `intervals = [[1,2],[2,3]]`
    **Output:** `0`

---

## 3. Jump Game

**Question:** You are given an integer array `nums`. You are initially positioned at the array's first index, and each element in the array represents your maximum jump length at that position. Return `true` if you can reach the last index, or `false` otherwise.

**Input/Output:**
* **Input:** `nums = [2,3,1,1,4]`
    **Output:** `true`
* **Input:** `nums = [3,2,1,0,4]`
    **Output:** `false`

---

## 4. Task Scheduler

**Question:** Given a characters array `tasks`, representing the tasks a CPU needs to do, where each letter represents a different task. Tasks could be done in any order. Each task is done in one unit of time. For each unit of time, the CPU could complete either one task or just be idle. However, there is a non-negative integer `n` that represents the cooldown period between two same tasks (the same letter in the array), that is that there must be at least `n` units of time between any two same tasks. Return the least number of units of times that the CPU will take to finish all the given tasks.

**Input/Output:**
* **Input:** `tasks = ["A","A","A","B","B","B"]`, `n = 2`
    **Output:** `8`
* **Input:** `tasks = ["A","A","A","B","B","B"]`, `n = 0`
    **Output:** `6`
* **Input:** `tasks = ["A","A","A","A","A","A","B","C","D","E","F","G"]`, `n = 2`
    **Output:** `16`

---

## 5. Candy

**Question:** There are `n` children standing in a line. Each child is assigned a rating value given in the integer array `ratings`. You are giving candies to these children subjected to the following requirements:
* Each child must have at least one candy.
* Children with a higher rating get more candies than their neighbors.
Return the minimum number of candies you need to have to distribute the candies to the children.

**Input/Output:**
* **Input:** `ratings = [1,0,2]`
    **Output:** `5`
* **Input:** `ratings = [1,2,2]`
    **Output:** `4`
