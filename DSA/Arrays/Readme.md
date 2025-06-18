# Arrays

## 1. Two Sum

**Question:** Given an array of integers `nums` and an integer `target`, return *indices of the two numbers such that they add up to `target`*. You may assume that each input would have **exactly one solution**, and you may not use the *same* element twice. You can return the answer in any order.

**Input/Output:**
* **Input:** `nums = [2, 7, 11, 15]`, `target = 9`
    **Output:** `[0, 1]`
* **Input:** `nums = [3, 2, 4]`, `target = 6`
    **Output:** `[1, 2]`
* **Input:** `nums = [3, 3]`, `target = 6`
    **Output:** `[0, 1]`

---

## 2. Best Time to Buy and Sell Stock

**Question:** You are given an array `prices` where `prices[i]` is the price of a given stock on the `i`th day. You want to maximize your profit by choosing a **single day** to buy one stock and choosing a **different day in the future** to sell that stock. Return the maximum profit you can achieve from this transaction. If you cannot achieve any profit, return 0.

**Input/Output:**
* **Input:** `prices = [7, 1, 5, 3, 6, 4]`
    **Output:** `5`
* **Input:** `prices = [7, 6, 4, 3, 1]`
    **Output:** `0`

---

## 3. Maximum Subarray (Kadane's Algorithm)

**Question:** Given an integer array `nums`, find the contiguous subarray (containing at least one number) which has the largest sum and return its sum.

**Input/Output:**
* **Input:** `nums = [-2, 1, -3, 4, -1, 2, 1, -5, 4]`
    **Output:** `6`
* **Input:** `nums = [1]`
    **Output:** `1`
* **Input:** `nums = [5, 4, -1, 7, 8]`
    **Output:** `23`

---

## 4. Product of Array Except Self

**Question:** Given an integer array `nums`, return an array `answer` such that `answer[i]` is equal to the product of all the elements of `nums` except `nums[i]`. The product of any prefix or suffix of `nums` is guaranteed to fit in a 32-bit integer. You must write an algorithm that runs in O(n) time and without using the division operation.

**Input/Output:**
* **Input:** `nums = [1, 2, 3, 4]`
    **Output:** `[24, 12, 8, 6]`
* **Input:** `nums = [-1, 1, 0, -3, 3]`
    **Output:** `[0, 0, 9, 0, 0]`

---

## 5. Merge Intervals

**Question:** Given an array of `intervals` where `intervals[i] = [starti, endi]`, merge all overlapping intervals, and return *an array of the non-overlapping intervals that cover all the intervals in the input*.

**Input/Output:**
* **Input:** `intervals = [[1, 3], [2, 6], [8, 10], [15, 18]]`
    **Output:** `[[1, 6], [8, 10], [15, 18]]`
* **Input:** `intervals = [[1, 4], [4, 5]]`
    **Output:** `[[1, 5]]`

---

## 6. Trapping Rain Water

**Question:** Given `n` non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it can trap after raining.

**Input/Output:**
* **Input:** `height = [0, 1, 0, 2, 1, 0, 1, 3, 2, 1, 2, 1]`
    **Output:** `6`
* **Input:** `height = [4, 2, 0, 3, 2, 5]`
    **Output:** `9`
