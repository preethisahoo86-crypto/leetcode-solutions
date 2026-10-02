# Two Sum

**Difficulty:** Easy

**Topic:** Arrays & Strings

**LeetCode:** https://leetcode.com/problems/two-sum/

## Approach

I used a HashMap to store each number and its index while traversing the array.

For every element, I calculate its complement using:

`target - current number`

If the complement is already present in the HashMap, the two required indices are returned. Otherwise, the current number and its index are added to the HashMap.

This allows the solution to find the answer in a single traversal of the array.

## Time Complexity

**O(n)**

The array is traversed once, and HashMap operations take O(1) average time.

## Space Complexity

**O(n)**

The HashMap can store up to n elements.

## Test Cases

### Test Case 1 — Typical Case

**Input:**

```text
nums = [2,7,11,15]
target = 9
