# Binary Search

## 1. Binary Search

**Question:** Given an array of integers `nums` which is sorted in ascending order, and an integer `target`, write a function to search `target` in `nums`. If `target` exists, then return its index. Otherwise, return `-1`. You must write an algorithm with `O(log n)` runtime complexity.

**Input/Output:**
* **Input:** `nums = [-1, 0, 3, 5, 9, 12]`, `target = 9`
    **Output:** `4`
* **Input:** `nums = [-1, 0, 3, 5, 9, 12]`, `target = 2`
    **Output:** `-1`

---

## 2. Search in Rotated Sorted Array

**Question:** There is an integer array `nums` sorted in ascending order (with distinct values). Prior to being passed to your function, `nums` is possibly rotated at an unknown pivot index `k` (`1 <= k < nums.length`) such that the resulting array is `[nums[k], nums[k+1], ..., nums[n-1], nums[0], nums[1], ..., nums[k-1]]` (0-indexed). For example, `[0,1,2,4,5,6,7]` might be rotated at pivot index 3 and become `[4,5,6,7,0,1,2]`. Given the array `nums` after the possible rotation and an integer `target`, return the index of `target` if it is in `nums`, or `-1` if it is not in `nums`. You must write an algorithm with `O(log n)` runtime complexity.

**Input/Output:**
* **Input:** `nums = [4, 5, 6, 7, 0, 1, 2]`, `target = 0`
    **Output:** `4`
* **Input:** `nums = [4, 5, 6, 7, 0, 1, 2]`, `target = 3`
    **Output:** `-1`
* **Input:** `nums = [1]`, `target = 0`
    **Output:** `-1`

---

## 3. Find Minimum in Rotated Sorted Array

**Question:** Suppose an array of length `n` sorted in ascending order is rotated between `1` and `n` times. For example, the array `nums = [0,1,2,4,5,6,7]` might become `[4,5,6,7,0,1,2]` (rotated 4 times) or `[0,1,2,4,5,6,7]` (rotated 7 times). Notice that rotating an array `[a[0], a[1], ..., a[n-1]]` 1 time results in the array `[a[n-1], a[0], a[1], ..., a[n-2]]`. Given the sorted rotated array `nums` of unique elements, return the minimum element of this array. You must write an algorithm that runs in `O(log n)` time.

**Input/Output:**
* **Input:** `nums = [3, 4, 5, 1, 2]`
    **Output:** `1`
* **Input:** `nums = [4, 5, 6, 7, 0, 1, 2]`
    **Output:** `0`
* **Input:** `nums = [11, 13, 15, 17]`
    **Output:** `11`

---

## 4. Median of Two Sorted Arrays

**Question:** Given two sorted arrays `nums1` and `nums2` of size `m` and `n` respectively, return the median of the two sorted arrays. The overall run time complexity should be `O(log (m+n))`.

**Input/Output:**
* **Input:** `nums1 = [1, 3]`, `nums2 = [2]`
    **Output:** `2.00000`
* **Input:** `nums1 = [1, 2]`, `nums2 = [3, 4]`
    **Output:** `2.50000`

---

## 5. Capacity To Ship Packages Within D Days

**Question:** A conveyor belt has packages that must be shipped from one port to another within `D` days. The `i`-th package on the conveyor belt has a weight of `weights[i]`. Each day, we load the ship with packages on the conveyor belt (in the order given by `weights`). We may not load more weight than the maximum weight capacity of the ship. Return the least weight capacity of the ship that will result in all the packages on the conveyor belt being shipped within `D` days.

**Input/Output:**
* **Input:** `weights = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`, `days = 5`
    **Output:** `15`
* **Input:** `weights = [3, 2, 2, 4, 1, 4]`, `days = 3`
    **Output:** `6`
* **Input:** `weights = [1, 2, 3, 1, 1]`, `days = 4`
    **Output:** `3`
