# Reverse String

- **Difficulty:** Easy
- **Topic:** Arrays & Strings
- **LeetCode:** https://leetcode.com/problems/reverse-string/

## Approach

I used the two-pointer technique. One pointer starts from the beginning of the array and the other starts from the end. The characters at these positions are swapped, and the pointers move toward the center until the entire string is reversed.

## Time Complexity

O(n)

## Space Complexity

O(1)

## Test Cases

### Test Case 1 - Typical Case

**Input:**
```text
['h', 'e', 'l', 'l', 'o']
