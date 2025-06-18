# Tries

## 1. Implement Trie (Prefix Tree)

**Question:** A trie (pronounced as "try") or prefix tree is a tree data structure used to efficiently store and retrieve keys in a dataset of strings. There are various applications of this data structure, such as autocomplete and spellchecker. Implement the Trie class:
* `Trie()` Initializes the trie object.
* `void insert(String word)` Inserts the string `word` into the trie.
* `boolean search(String word)` Returns `true` if the string `word` is in the trie (i.e., was inserted before), and `false` otherwise.
* `boolean startsWith(String prefix)` Returns `true` if there is a previously inserted string `word` that has the prefix `prefix`, and `false` otherwise.

**Input/Output:**
* **Input:**
  `["Trie", "insert", "search", "search", "startsWith", "insert", "search"]`
  `[[], ["apple"], ["apple"], ["app"], ["app"], ["app"], ["app"]]`
* **Output:**
  `[null, null, true, false, true, null, true]`

---

## 2. Replace Words

**Question:** In English, we have a concept called root, which can be followed by some other word to form another longer word - let's call this word successor. For example, when the root `"an"` is followed by the successor word `"other"`, we can form a new word `"another"`. Given a `dictionary` consisting of many roots and a `sentence` consisting of words separated by spaces, replace all the successors in the sentence with the root forming it. If a successor can be replaced by more than one root, replace it with the root that has the shortest length. Return the sentence after the replacement.

**Input/Output:**
* **Input:** `dictionary = ["cat","bat","rat"]`, `sentence = "the cattle was rattled by the battery"`
    **Output:** `"the cat was rat by the bat"`
* **Input:** `dictionary = ["a","b","c"]`, `sentence = "aadsfasf absbs bbab cadsfafs"`
    **Output:** `"a a b c"`

---

## 3. Word Search II

**Question:** Given an `m x n` `board` of characters and a list of strings `words`, return all words on the board. Each word must be constructed from letters of sequentially adjacent cells, where adjacent cells are horizontally or vertically neighboring. The same letter cell may not be used more than once in a word.

**Input/Output:**
* **Input:** `board = [["o","a","a","n"],["e","t","a","e"],["i","h","k","r"],["i","f","l","v"]]`, `words = ["oath","pea","eat","rain"]`
    **Output:** `["eat","oath"]`
* **Input:** `board = [["a","b"],["c","d"]]`, `words = ["abcb"]`
    **Output:** `[]`

---

## 4. Longest Word in Dictionary

**Question:** Given an array of strings `words` representing an English Dictionary, return the longest word in `words` that can be built one character at a time by other words in `words`. If there is more than one possible answer, return the longest word with the smallest lexicographical order. If there is no answer, return the empty string.

**Input/Output:**
* **Input:** `words = ["w","wo","wor","worl","world"]`
    **Output:** `"world"`
* **Input:** `words = ["a","banana","app","appl","ap","apply","apple"]`
    **Output:** `"apple"`

---

## 5. Palindrome Pairs

**Question:** Given a list of unique words, return all the pairs of the distinct indices `(i, j)` in the given list, so that the concatenation of the two words `words[i] + words[j]` is a palindrome.

**Input/Output:**
* **Input:** `words = ["abcd","dcba","lls","s","sssll"]`
    **Output:** `[[0,1],[1,0],[3,2],[2,4]]`
* **Input:** `words = ["bat","tab","cat"]`
    **Output:** `[[0,1],[1,0]]`
* **Input:** `words = ["a",""]`
    **Output:** `[[0,1],[1,0]]`
