# Hashing (Map, Set)

## 1. Contains Duplicate

**Question:** Given an integer array `nums`, return `true` if any value appears **at least twice** in the array, and return `false` if every element is distinct.

**Input/Output:**
* **Input:** `nums = [1, 2, 3, 1]`
    **Output:** `true`
* **Input:** `nums = [1, 2, 3, 4]`
    **Output:** `false`
* **Input:** `nums = [1, 1, 1, 3, 3, 4, 3, 2, 4, 2]`
    **Output:** `true`

---

## 2. Group Anagrams

**Question:** Given an array of strings `strs`, group **the anagrams** together. You can return the answer in **any order**.

**Input/Output:**
* **Input:** `strs = ["eat", "tea", "tan", "ate", "nat", "bat"]`
    **Output:** `[["bat"], ["nat", "tan"], ["ate", "eat", "tea"]]`
* **Input:** `strs = [""]`
    **Output:** `[[""]]`
* **Input:** `strs = ["a"]`
    **Output:** `[["a"]]`

---

## 3. Top K Frequent Elements

**Question:** Given an integer array `nums` and an integer `k`, return the `k` most frequent elements. You may return the answer in any order.

**Input/Output:**
* **Input:** `nums = [1, 1, 1, 2, 2, 3]`, `k = 2`
    **Output:** `[1, 2]`
* **Input:** `nums = [1]`, `k = 1`
    **Output:** `[1]`

---

## 4. Subarray Sum Equals K

**Question:** Given an array of integers `nums` and an integer `k`, return the total number of continuous subarrays whose sum equals to `k`.

**Input/Output:**
* **Input:** `nums = [1, 1, 1]`, `k = 2`
    **Output:** `2`
* **Input:** `nums = [1, 2, 3]`, `k = 3`
    **Output:** `2`

---

## 5. Longest Consecutive Sequence

**Question:** Given an unsorted array of integers `nums`, return the length of the longest consecutive elements sequence. You must write an algorithm that runs in O(n) time.

**Input/Output:**
* **Input:** `nums = [100, 4, 200, 1, 3, 2]`
    **Output:** `4`
* **Input:** `nums = [0, 3, 7, 2, 5, 8, 4, 6, 0, 1]`
    **Output:** `9`
