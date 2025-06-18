# Recursion & Backtracking

## 1. Subsets

**Question:** Given an integer array `nums` of unique elements, return all possible subsets (the power set). The solution set must not contain duplicate subsets. Return the solution in any order.

**Input/Output:**
* **Input:** `nums = [1, 2, 3]`
    **Output:** `[[],[1],[2],[1,2],[3],[1,3],[2,3],[1,2,3]]`
* **Input:** `nums = [0]`
    **Output:** `[[],[0]]`

---

## 2. Permutations

**Question:** Given an array `nums` of distinct integers, return all the possible permutations. You can return the answer in any order.

**Input/Output:**
* **Input:** `nums = [1, 2, 3]`
    **Output:** `[[1,2,3],[1,3,2],[2,1,3],[2,3,1],[3,1,2],[3,2,1]]`
* **Input:** `nums = [0, 1]`
    **Output:** `[[0,1],[1,0]]`
* **Input:** `nums = [1]`
    **Output:** `[[1]]`

---

## 3. Word Search

**Question:** Given an `m x n` grid of characters `board` and a string `word`, return `true` if `word` exists in the grid. The word can be constructed from letters of sequentially adjacent cells, where adjacent cells are horizontally or vertically neighboring. The same letter cell may not be used more than once.

**Input/Output:**
* **Input:** `board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]]`, `word = "ABCCED"`
    **Output:** `true`
* **Input:** `board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]]`, `word = "SEE"`
    **Output:** `true`
* **Input:** `board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]]`, `word = "ABCB"`
    **Output:** `false`

---

## 4. Sudoku Solver

**Question:** Write a program to solve a Sudoku puzzle by filling the empty cells. A sudoku solution must satisfy all of the following rules:
1. Each of the digits `1-9` must occur exactly once in each row.
2. Each of the digits `1-9` must occur exactly once in each column.
3. Each of the digits `1-9` must occur exactly once in each of the 9 `3x3` sub-boxes of the grid.
The `.` character indicates empty cells.

**Input/Output:**
* **Input:** `board = [["5","3",".",".","7",".",".",".","."],["6",".",".","1","9","5",".",".","."],[".","9","8",".",".",".",".","6","."],["8",".",".",".","6",".",".",".","3"],["4",".",".","8",".","3",".",".","1"],["7",".",".",".","2",".",".",".","6"],[".","6",".",".",".",".","2","8","."],[".",".",".","4","1","9",".",".","5"],[".",".",".",".","8",".",".","7","9"]]`
    **Output:** `[["5","3","4","6","7","8","9","1","2"],["6","7","2","1","9","5","3","4","8"],["1","9","8","3","4","2","5","6","7"],["8","5","9","7","6","1","4","2","3"],["4","2","6","8","5","3","7","9","1"],["7","1","3","9","2","4","8","5","6"],["9","6","1","5","3","7","2","8","4"],["2","8","7","4","1","9","6","3","5"],["3","4","5","2","8","6","1","7","9"]]`

---

## 5. N-Queens

**Question:** The n-queens puzzle is the problem of placing `n` queens on an `n x n` chessboard such that no two queens attack each other. Given an integer `n`, return all distinct solutions to the n-queens puzzle. You may return the answer in any order. Each solution contains a distinct board configuration of the n-queens' placement, where `'Q'` and `'.'` both indicate a queen and an empty space, respectively.

**Input/Output:**
* **Input:** `n = 4`
    **Output:** `[[".Q..","...Q","Q...","..Q."],["..Q.","Q...","...Q",".Q.."]]`
* **Input:** `n = 1`
    **Output:** `[["Q"]]`
