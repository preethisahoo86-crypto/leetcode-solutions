# Valid Parentheses

- **Difficulty:** Easy
- **Topic:** Stacks
- **LeetCode:** https://leetcode.com/problems/valid-parentheses/

## Approach

I used a stack to keep track of opening brackets. Whenever a closing bracket is found, I compare it with the most recently added opening bracket. If they do not match, the string is invalid. At the end, the stack must be empty for the brackets to be valid.

## Time Complexity

O(n)

## Space Complexity

O(n)

## Test Cases

### Test Case 1 - Typical Case

**Input:**
```text
"()[]{}"
