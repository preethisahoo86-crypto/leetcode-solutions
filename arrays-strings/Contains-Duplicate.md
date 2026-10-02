# Contains Duplicate

- **Difficulty:** Easy
- **Topic:** Arrays & Strings
- **LeetCode:** https://leetcode.com/problems/contains-duplicate/

## Approach

I used a HashSet to keep track of the numbers that have already appeared. For each number, I check whether it is already present in the set. If it is present, the array contains a duplicate and I return true. Otherwise, I add the number to the set.

## Time Complexity

O(n)

## Space Complexity

O(n)

## Test Cases

### Test Case 1 - Typical Case

**Input:**
```text
[1, 2, 3, 1]
