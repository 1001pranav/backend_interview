# Strings

## 1. Valid Anagram

**Question:** Given two strings `s` and `t`, return `true` *if `t` is an anagram of `s`, and `false` otherwise*. An Anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.

**Input/Output:**
* **Input:** `s = "anagram"`, `t = "nagaram"`
    **Output:** `true`
* **Input:** `s = "rat"`, `t = "car"`
    **Output:** `false`

---

## 2. Longest Substring Without Repeating Characters

**Question:** Given a string `s`, find the length of the **longest substring** without repeating characters.

**Input/Output:**
* **Input:** `s = "abcabcbb"`
    **Output:** `3`
* **Input:** `s = "bbbbb"`
    **Output:** `1`
* **Input:** `s = "pwwkew"`
    **Output:** `3`

---

## 3. Longest Palindromic Substring

**Question:** Given a string `s`, return the longest palindromic substring in `s`.

**Input/Output:**
* **Input:** `s = "babad"`
    **Output:** `"bab"`
* **Input:** `s = "cbbd"`
    **Output:** `"bb"`

---

## 4. Regular Expression Matching

**Question:** Given an input string `s` and a pattern `p`, implement regular expression matching with support for `'.'` and `'*'` where: `.` Matches any single character and `*` Matches zero or more of the preceding element. The matching should cover the **entire input string** (not partial).

**Input/Output:**
* **Input:** `s = "aa"`, `p = "a"`
    **Output:** `false`
* **Input:** `s = "aa"`, `p = "a*"`
    **Output:** `true`
* **Input:** `s = "ab"`, `p = ".*"`
    **Output:** `true`

---

## 5. Minimum Window Substring

**Question:** Given two strings `s` and `t` of lengths `m` and `n` respectively, return the **minimum window substring** of `s` such that every character in `t` (including duplicates) is included in the window. If there is no such substring, return the empty string `""`.

**Input/Output:**
* **Input:** `s = "ADOBECODEBANC"`, `t = "ABC"`
    **Output:** `"BANC"`
* **Input:** `s = "a"`, `t = "a"`
    **Output:** `"a"`
* **Input:** `s = "a"`, `t = "aa"`
    **Output:** `""`
