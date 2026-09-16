# Reverse a String

## Problem
Write a function that reverses a string in-place.

## Difficulty
Easy

## LeetCode
https://leetcode.com/problems/reverse-string/

## Approach
I used two pointers, one starting from the beginning and the other from the end of the string.
I swapped the characters at both positions and moved the pointers toward the center until the string was reversed.

## Complexity
- Time: O(n)
- Space: O(1)

## Notes
Tested locally with two test cases:
- "hello" → "olleh"
- "a" → "a"

Both test cases passed successfully.