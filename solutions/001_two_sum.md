# LeetCode 001 – Two Sum

## 📌 Problem
Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to the target.

---

## 🧠 Solution Summary

- Method: Hash Map
- Time complexity: O(n)
- Space complexity: O(n)

We use a dictionary to store each number and its index as we iterate.  
For each number, we compute the complement (target - current), and check if it's already in the map.  
If so, we return the pair of indices.

---

## 🗣️ Explanation

**S – Situation**  
We are given an array of numbers and a target value. The goal is to find two numbers that add up to the target and return their indices.

**T – Task**  
I need to find a pair of elements in the array whose sum equals the target, and return their positions.

**A – Action**  
I used a hash map to store previously seen numbers and their indices.  
As I iterate through the array, I calculate the difference between the target and the current number.  
If the difference exists in the map, I return the pair of indices.  
Otherwise, I add the current number and its index to the map.

**R – Result**  
This method runs in O(n) time and passed all test cases efficiently.

---

✅ First solved on: 2025-06-19  
🧸 By: Cecilia 💗
