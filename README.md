# Challenge 2 - Implement Merge Sort

## Overview
This project is a simple implementation of the **Merge Sort algorithm** written in **Java**.  
It demonstrates a correct application of the **divide, conquer, and merge** strategy to sort an array of integers.

The goal of this challenge is to:
- Implement merge sort **from scratch** (no built-in sort functions).
- Handle a wide range of test cases including negatives, duplicates, zeros, and empty arrays.
- Ensure time complexity **O(n log n)** with standard merge sort auxiliary space usage.

---

## Features
 Accepts **positive, negative, and zero** values  
 Handles **duplicates** correctly  
 Works for **already sorted**, **reverse sorted**, and **empty** arrays  
 Outputs sorted numbers in **non-decreasing order**  
 Implements **recursive merge sort** with clear separation of divide and merge steps  

---

## Algorithm Explanation
**Merge Sort** is a recursive algorithm that:
1. **Divides** the array into two halves.
2. **Recursively sorts** each half.
3. **Merges** the two sorted halves into a single sorted array.

### Pseudocode:
