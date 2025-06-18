# Heap & Priority Queue

## 1. Kth Largest Element in an Array

**Question:** Given an integer array `nums` and an integer `k`, return the `k`th largest element in the array. Note that it is the `k`th largest element in the sorted order, not the `k`th distinct element.

**Input/Output:**
* **Input:** `nums = [3,2,1,5,6,4]`, `k = 2`
    **Output:** `5`
* **Input:** `nums = [3,2,3,1,2,4,5,5,6]`, `k = 4`
    **Output:** `4`

---

## 2. Top K Frequent Words

**Question:** Given a non-empty list of words, return the `k` most frequent elements. Your answer should be sorted by frequency from highest to lowest. If two words have the same frequency, then the word with the lower alphabetical order comes first.

**Input/Output:**
* **Input:** `words = ["i", "love", "leetcode", "i", "love", "coding"]`, `k = 2`
    **Output:** `["i", "love"]`
* **Input:** `words = ["the", "day", "is", "sunny", "the", "the", "the", "sunny", "is", "is"]`, `k = 4`
    **Output:** `["the", "is", "sunny", "day"]`

---

## 3. Merge k Sorted Lists

**Question:** You are given an array of `k` linked-lists `lists`, each linked-list is sorted in ascending order. Merge all the linked-lists into one sorted linked-list and return it.

**Input/Output:**
* **Input:** `lists = [[1,4,5],[1,3,4],[2,6]]`
    **Output:** `[1,1,2,3,4,4,5,6]`
* **Input:** `lists = []`
    **Output:** `[]`
* **Input:** `lists = [[]]`
    **Output:** `[]`

---

## 4. Find Median from Data Stream

**Question:** The median is the middle value in an ordered integer list. If the size of the list is even, there is no middle value. So the median is the mean of the two middle values. Design a data structure that supports the following two operations:
* `void addNum(int num)` - Add an integer number from the data stream to the data structure.
* `double findMedian()` - Return the median of all elements so far.

**Input/Output:**
* **Input:**
  `["MedianFinder", "addNum", "addNum", "findMedian", "addNum", "findMedian"]`
  `[[], [1], [2], [], [3], []]`
* **Output:**
  `[null, null, null, 1.5, null, 2.0]`

---

## 5. Reorganize String

**Question:** Given a string `s`, rearrange the characters of `s` so that any two adjacent characters are not the same. Return any possible rearrangement of `s` or return `""` if not possible.

**Input/Output:**
* **Input:** `s = "aab"`
    **Output:** `"aba"`
* **Input:** `s = "aaab"`
    **Output:** `""`
