# Day 1A

## Problem Statement

Given all the entries:
    - Find two entries that sum to `2020`
    - Return their total

## Input format

Numbers are provided as newline-separated list.

## Output format

Integer (product of the two numbers)

## Approaches
- Brute force
    - Sum the cartesian product of all integers and find the pair that returns 2000
    - O(n^2) runtime
- Efficient force
    - subtract each number from 2020, then filter list for match
    - O(2n) runtime
- Other improvements
    - Sort list first, then work towards middle
    - Worst case is O(n log n) + O(n)
