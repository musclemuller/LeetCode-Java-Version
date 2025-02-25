# [Word Search](https://leetcode.com/problems/word-search/)

Given an `m x n` grid of characters `board` and a string `word`, return `true` *if* `word` *exists in the grid*.

The word can be constructed from letters of sequentially adjacent cells, where adjacent cells are horizontally or vertically neighboring. The same letter cell may not be used more than once.

---

## Examples

### Example 1
![ex1](../../Image/79-1.png)
> **Input:** `board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "ABCCED"`  
> **Output:** `true`

### Example 2
![ex2](../../Image/79-2.png)
> **Input:** `board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "SEE"`  
> **Output:** `true`

### Example 3
![ex3](../../Image/79-3.png)
> **Input:** `board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]], word = "ABCB"`  
> **Output:** `false`

---

## Constraints
- `m == board.length`
- `n = board[i].length`
- `1 <= m, n <= 6`
- `1 <= word.length <= 15`
- `board` and `word` consists of only lowercase and uppercase English letters 

---

## Follow up
Could you use search pruning to make your solution faster with a larger `board`?





