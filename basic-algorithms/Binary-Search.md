# Binary Search

- **Difficulty:** Easy
- **Topic:** Basic Algorithms
- **LeetCode:** https://leetcode.com/problems/binary-search/

## Approach

I used the binary search technique because the input array is sorted. Two pointers, `left` and `right`, represent the current search range. I calculate the middle position and compare the middle element with the target. If the target is larger, I search the right half; if it is smaller, I search the left half. This continues until the target is found or the search range becomes empty.

## Time Complexity

O(log n)

## Space Complexity

O(1)

## Test Cases

### Test Case 1 - Typical Case

**Input:**
```text
nums = [-1, 0, 3, 5, 9, 12]
target = 9
