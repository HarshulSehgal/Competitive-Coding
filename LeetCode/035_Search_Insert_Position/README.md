# 35. Search Insert Position

## Problem Information

- **Platform:** LeetCode
- **Problem Number:** 35
- **Difficulty:** Easy
- **Language:** C++
- **Topics:** Array, Binary Search

## Problem Link

https://leetcode.com/problems/search-insert-position/

## Approach

Use Binary Search to locate the target in the sorted array.

- If the target is found, return its index.
- If the target is not found, return the position where it should be inserted to maintain the sorted order.

This satisfies the required **O(log n)** time complexity.

## Complexity

- **Time Complexity:** O(log n)
- **Space Complexity:** O(1)

## Files

- `Solution.cpp` — C++ solution
