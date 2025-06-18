# Dynamic Programming

## 1. Climbing Stairs

**Question:** You are climbing a staircase. It takes `n` steps to reach the top. Each time you can either climb 1 or 2 steps. In how many distinct ways can you climb to the top?

**Input/Output:**
* **Input:** `n = 2`
    **Output:** `2`
* **Input:** `n = 3`
    **Output:** `3`

---

## 2. House Robber

**Question:** You are a professional robber planning to rob houses along a street. Each house has a certain amount of money stashed, the only constraint stopping you from robbing each of them is that adjacent houses have security systems connected and it will automatically contact the police if two adjacent houses were broken into on the same night. Given an integer array `nums` representing the amount of money of each house, return the maximum amount of money you can rob tonight without alerting the police.

**Input/Output:**
* **Input:** `nums = [1,2,3,1]`
    **Output:** `4`
* **Input:** `nums = [2,7,9,3,1]`
    **Output:** `12`

---

## 3. Longest Increasing Subsequence

**Question:** Given an integer array `nums`, return the length of the longest strictly increasing subsequence. A subsequence is a sequence that can be derived from an array by deleting some or no elements without changing the order of the remaining elements. For example, `[3,6,2,7]` is a subsequence of the array `[0,3,1,6,2,2,7]`.

**Input/Output:**
* **Input:** `nums = [10,9,2,5,3,7,101,18]`
    **Output:** `4`
* **Input:** `nums = [0,1,0,3,2,3]`
    **Output:** `4`
* **Input:** `nums = [7,7,7,7,7,7,7]`
    **Output:** `1`

---

## 4. Coin Change

**Question:** You are given an integer array `coins` representing coins of different denominations and an integer `amount` representing a total amount of money. Return the fewest number of coins that you need to make up that amount. If that amount of money cannot be made up by any combination of the coins, return `-1`. You may assume that you have an infinite number of each kind of coin.

**Input/Output:**
* **Input:** `coins = [1,2,5]`, `amount = 11`
    **Output:** `3`
* **Input:** `coins = [2]`, `amount = 3`
    **Output:** `-1`
* **Input:** `coins = [1]`, `amount = 0`
    **Output:** `0`

---

## 5. Edit Distance

**Question:** Given two strings `word1` and `word2`, return the minimum number of operations required to convert `word1` to `word2`. You have the following three operations permitted on a word:
* Insert a character
* Delete a character
* Replace a character

**Input/Output:**
* **Input:** `word1 = "horse"`, `word2 = "ros"`
    **Output:** `3`
* **Input:** `word1 = "intention"`, `word2 = "execution"`
    **Output:** `5`