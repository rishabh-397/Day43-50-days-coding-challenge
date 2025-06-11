# Day43-50-days-coding-challenge

## 🌳 Problem 1: Kth Smallest Element in a BST

### ✅ Problem Statement:
Given a BST and integer k, return the k-th smallest element in the BST.

### 🧠 Approach:
- Perform **in-order traversal** of BST (returns sorted elements).
- Return the (k - 1)th index from the result list.

### 📘 Example:
Input: [3,1,4,null,2], k = 1 → Output: 1  
Input: [5,3,6,2,4,null,null,1], k = 3 → Output: 3

### 💡 Time Complexity:
- O(n) for full traversal
- O(h + k) for early stopping with optimization (h = tree height)

---

## 🔡 Problem 2: Zigzag Conversion

### ✅ Problem Statement:
Convert a string into a zigzag pattern on `numRows` rows and read it line by line.

### 🧠 Approach:
- Use an array of strings, one for each row.
- Traverse the input string, changing direction when reaching the top or bottom row.
- Append each character to the appropriate row index.

### 📘 Example:
Input: "PAYPALISHIRING", numRows = 3 → Output: "PAHNAPLSIIGYIR"  
Input: "PAYPALISHIRING", numRows = 4 → Output: "PINALSIGYAHRPI"

### 💡 Constraints:
- 1 <= s.length <= 1000
- 1 <= numRows <= 1000

---

## 🏁 Summary
- **Tree traversal** reveals the structure of data.
- **Pattern simulation** teaches control flow mastery.
