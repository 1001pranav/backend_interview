# Graphs (DFS, BFS, Union-Find, Dijkstra)

## 1. Number of Islands

**Question:** Given an `m x n` 2D binary grid `grid` which represents a map of `'1'`s (land) and `'0'`s (water), return the number of islands. An island is surrounded by water and is formed by connecting adjacent lands horizontally or vertically. You may assume all four edges of the grid are all surrounded by water.

**Input/Output:**
* **Input:** `grid = [
  ["1","1","1","1","0"],
  ["1","1","0","1","0"],
  ["1","1","0","0","0"],
  ["0","0","0","0","0"]
]`
    **Output:** `1`
* **Input:** `grid = [
  ["1","1","0","0","0"],
  ["1","1","0","0","0"],
  ["0","0","1","0","0"],
  ["0","0","0","1","1"]
]`
    **Output:** `3`

---

## 2. Clone Graph

**Question:** Given a reference of a node in a connected undirected graph. Return a deep copy (clone) of the graph. Each node in the graph contains a value ( `int`) and a list ( `List[Node]`) of its neighbors.

**Input/Output:**
* **Input:** `adjList = [[2,4],[1,3],[2,4],[1,3]]`
    **Output:** `[[2,4],[1,3],[2,4],[1,3]]`
* **Input:** `adjList = [[]]`
    **Output:** `[[]]`

---

## 3. Course Schedule

**Question:** There are a total of `numCourses` courses you have to take, labeled from `0` to `numCourses - 1`. You are given an array `prerequisites` where `prerequisites[i] = [ai, bi]` indicates that you must take course `bi` first if you want to take course `ai`. For example, the pair `[0, 1]`, indicates that to take course `0` you have to first take course `1`. Return `true` if you can finish all courses. Otherwise, return `false`.

**Input/Output:**
* **Input:** `numCourses = 2`, `prerequisites = [[1,0]]`
    **Output:** `true`
* **Input:** `numCourses = 2`, `prerequisites = [[1,0],[0,1]]`
    **Output:** `false`

---

## 4. Pacific Atlantic Water Flow

**Question:** You are given an `m x n` integer matrix `heights` representing the height of each unit cell in a continent. The Pacific ocean touches the continent's left and top edges, and the Atlantic ocean touches the continent's right and bottom edges. Water can only flow in four directions (up, down, left, or right) from a cell to an adjacent cell with height equal or lower. Find a list of grid coordinates where water can flow to both the Pacific and Atlantic oceans.

**Input/Output:**
* **Input:** `heights = [[1,2,2,3,5],[3,2,3,4,4],[2,4,5,3,1],[6,7,1,4,5],[5,1,1,2,4]]`
    **Output:** `[[0,4],[1,3],[1,4],[2,2],[3,0],[3,1],[4,0]]`
* **Input:** `heights = [[2,1],[1,2]]`
    **Output:** `[[0,0],[0,1],[1,0],[1,1]]`

---

## 5. Word Ladder

**Question:** A transformation sequence from word `beginWord` to `endWord` using a dictionary `wordList` is a sequence of words `beginWord -> s1 -> s2 -> ... -> sk` such that:
* Every adjacent pair of words differs by a single letter.
* Every `si` for `1 <= i <= k` is in `wordList`. Note that `beginWord` does not need to be in `wordList`.
* `sk == endWord`
Given two words, `beginWord` and `endWord`, and a dictionary `wordList`, return the number of words in the shortest transformation sequence from `beginWord` to `endWord`, or `0` if no such sequence exists.

**Input/Output:**
* **Input:** `beginWord = "hit"`, `endWord = "cog"`, `wordList = ["hot","dot","dog","lot","log","cog"]`
    **Output:** `5`
* **Input:** `beginWord = "hit"`, `endWord = "cog"`, `wordList = ["hot","dot","dog","lot","log"]`
    **Output:** `0`
