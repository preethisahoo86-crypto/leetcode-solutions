# Reverse Linked List

- **Difficulty:** Easy
- **Topic:** Linked Lists
- **LeetCode:** https://leetcode.com/problems/reverse-linked-list/

## Approach

I used three pointers: `prev`, `current`, and `next`. The `current` node's link is changed to point to the previous node. This process is repeated until all nodes are reversed.

## Time Complexity

O(n)

## Space Complexity

O(1)

## Test Cases

### Test Case 1 - Typical Case

**Input:**
```text
1 -> 2 -> 3 -> 4 -> 5
