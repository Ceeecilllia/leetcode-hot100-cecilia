# 002. Add Two Numbers

## 🧠 Problem
You are given two non-empty linked lists representing two non-negative integers.  
The digits are stored in **reverse order**, and each node contains a single digit.  
Add the two numbers and return the sum as a linked list (also in reverse).

---

## ⭐️ Solutions

- **S**ituation: Add two reversed numbers stored as linked lists.
- **T**ask: Simulate digit-by-digit addition with carry.
- **A**ction:
  - Use a dummy node to build the new list.
  - Use a loop while `l1` or `l2` or `carry`.
  - Use `total % 10` for the digit, `total // 10` for the carry.
- **R**esult: Time O(n), Space O(n), 1569 testcases passed ✅

---


## 📝 Example Trace

```text
l1 = 2 → 4 → 3 (342)
l2 = 5 → 6 → 4 (465)

Step 1: 2 + 5 = 7   → output [7]
Step 2: 4 + 6 = 10  → output [7 → 0], carry = 1
Step 3: 3 + 4 + 1 = 8 → output [7 → 0 → 8]

Result = 7 → 0 → 8
yaml
Copy
Edit
