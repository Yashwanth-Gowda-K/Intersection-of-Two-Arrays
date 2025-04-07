# Intersection-of-Two-Arrays
Intersection of Two Arrays - LeetCode Problem #349
This repository contains the solution to **LeetCode Problem 349: Intersection of Two Arrays**, implemented in Python.
 🧩 Problem Statement

Given two integer arrays `nums1` and `nums2`, return an array of their **intersection**.  
Each element in the result must be **unique**, and the result can be returned in **any order**.
 🧪 Examples
 ✅ Example 1
Input: nums1 = [1, 2, 2, 1], nums2 = [2, 2] Output: [2]

✅ Example 2
Input: nums1 = [4, 9, 5], nums2 = [9, 4, 9, 8, 4] Output: [9, 4] # or [4, 9]


We use Python’s built-in `set` data structure:

1. Convert both arrays to sets to **remove duplicates**.
2. Use `set1 & set2` (or `set1.intersection(set2)`) to get the **common unique elements**.
3. Convert the result back to a list.

This method is both clean and efficient.
