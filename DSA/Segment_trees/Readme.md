# Segment Trees

## 1. Range Sum Query - Immutable

**Question:** Given an integer array `nums`, handle multiple queries of the following type:
1.  Calculate the sum of the elements of `nums` between indices `left` and `right` inclusive where `left <= right`.
Implement the `NumArray` class:
* `NumArray(int[] nums)` Initializes the object with the integer array `nums`.
* `int sumRange(int left, int right)` Returns the sum of the elements of `nums` between indices `left` and `right` inclusive (i.e. `nums[left] + nums[left + 1] + ... + nums[right]`).

**Input/Output:**
* **Input:**
  `["NumArray", "sumRange", "sumRange", "sumRange"]`
  `[[[-2, 0, 3, -5, 2, -1]], [0, 2], [2, 5], [0, 5]]`
* **Output:**
  `[null, 1, -1, -3]`

---

## 2. Range Sum Query - Mutable

**Question:** Given an integer array `nums`, handle multiple queries of the following types:
1. Update the value of an element in `nums`.
2. Calculate the sum of the elements of `nums` between indices `left` and `right` inclusive where `left <= right`.
Implement the `NumArray` class:
* `NumArray(int[] nums)` Initializes the object with the integer array `nums`.
* `void update(int index, int val)` Updates the value of `nums[index]` to be `val`.
* `int sumRange(int left, int right)` Returns the sum of the elements of `nums` between indices `left` and `right` inclusive (i.e., `nums[left] + nums[left + 1] + ... + nums[right]`).

**Input/Output:**
* **Input:**
  `["NumArray", "sumRange", "update", "sumRange"]`
  `[[[1, 3, 5]], [0, 2], [1, 2], [0, 2]]`
* **Output:**
  `[null, 9, null, 8]`

---

## 3. Count of Smaller Numbers After Self

**Question:** Given an integer array `nums`, return an integer array `counts` where `counts[i]` is the number of smaller elements to the right of `nums[i]`.

**Input/Output:**
* **Input:** `nums = [5,2,6,1]`
    **Output:** `[2,1,1,0]`
* **Input:** `nums = [-1]`
    **Output:** `[0]`
* **Input:** `nums = [-1,-1]`
    **Output:** `[0,0]`

---

## 4. Range Minimum Query

**Question:** Given an integer array `A`, you are asked to process `q` queries of the form `(i, j)`, where you need to find the minimum value in the subarray `A[i...j]`.

**Input/Output:**
* **Input:** `A = [1, 3, 2, 7, 9, 11]`, `queries = [(1, 3), (0, 5)]`
    **Output:** `[2, 1]`

---

## 5. Maximum Sum Queries

**Question:** You are given two 0-indexed integer arrays `nums1` and `nums2`, both of length `n`, and a 2D array `queries` where `queries[i] = [xi, yi]`. For the `i`th query, find the maximum value of `nums1[j] + nums2[j]` among all indices `j` `(0 <= j < n)` where `nums1[j] >= xi` and `nums2[j] >= yi`. If no such `j` exists, the answer is `-1`. Return an array `answer` where `answer[i]` is the answer to the `i`th query.

**Input/Output:**
* **Input:** `nums1 = [4,3,1,2]`, `nums2 = [2,4,9,5]`, `queries = [[4,1],[1,3],[2,5]]`
    **Output:** `[6,10,7]`
* **Input:** `nums1 = [3,2,5]`, `nums2 = [2,3,4]`, `queries = [[4,4],[3,2],[1,1]]`
    **Output:** `[9,9,9]`
* **Input:** `nums1 = [2,1]`, `nums2 = [2,4]`, `queries = [[3,1],[3,3],[3,5]]`
    **Output:** `[-1,-1,-1]`