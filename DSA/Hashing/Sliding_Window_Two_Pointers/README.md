# Sliding Window, Two Pointers

## 1. Maximum Average Subarray I

**Question:** You are given an integer array `nums` consisting of `n` elements, and an integer `k`. Find a contiguous subarray whose length is equal to `k` that has the maximum average value and return this value. Any answer with a calculation error less than 10-5 will be accepted.

**Input/Output:**
* **Input:** `nums = [1, 12, -5, -6, 50, 3]`, `k = 4`
    **Output:** `12.75000`
* **Input:** `nums = [5]`, `k = 1`
    **Output:** `5.00000`

---

## 2. Longest Repeating Character Replacement

**Question:** You are given a string `s` and an integer `k`. You can choose any character of the string and change it to any other uppercase English character. You can perform this operation at most `k` times. Return the length of the longest substring containing the same letter you can get after performing the above operations.

**Input/Output:**
* **Input:** `s = "ABAB"`, `k = 2`
    **Output:** `4`
* **Input:** `s = "AABABBA"`, `k = 1`
    **Output:** `4`

---

## 3. Permutation in String

**Question:** Given two strings `s1` and `s2`, return `true` if `s2` contains a permutation of `s1`, or `false` otherwise. In other words, return `true` if one of `s1`'s permutations is the substring of `s2`.

**Input/Output:**
* **Input:** `s1 = "ab"`, `s2 = "eidbaooo"`
    **Output:** `true`
* **Input:** `s1 = "ab"`, `s2 = "eidboaoo"`
    **Output:** `false`

---

## 4. Minimum Size Subarray Sum

**Question:** Given an array of positive integers `nums` and a positive integer `target`, return the minimal length of a contiguous subarray [numsl, numsl+1, ..., numsr-1, numsr] of which the sum is greater than or equal to `target`. If there is no such subarray, return 0 instead.

**Input/Output:**
* **Input:** `target = 7`, `nums = [2, 3, 1, 2, 4, 3]`
    **Output:** `2`
* **Input:** `target = 4`, `nums = [1, 4, 4]`
    **Output:** `1`
* **Input:** `target = 11`, `nums = [1, 1, 1, 1, 1, 1, 1, 1]`
    **Output:** `0`

---

## 5. Sliding Window Maximum

**Question:** You are given an array of integers `nums`, there is a sliding window of size `k` which is moving from the very left of the array to the very right. You can only see the `k` numbers in the window. Each time the sliding window moves right by one position. Return the max sliding window.

**Input/Output:**
* **Input:** `nums = [1, 3, -1, -3, 5, 3, 6, 7]`, `k = 3`
    **Output:** `[3, 3, 5, 5, 6, 7]`
* **Input:** `nums = [1]`, `k = 1`
    **Output:** `[1]`
