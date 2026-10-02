# Valid Palindrome

**Difficulty:** Easy

**Topic:** Arrays & Strings

**LeetCode:** https://leetcode.com/problems/valid-palindrome/

## Approach

I used the two-pointer technique to check whether the string is a palindrome.

One pointer starts from the beginning of the string and another starts from the end. Non-alphanumeric characters are skipped, and characters are compared after converting them to lowercase.

If any pair of characters does not match, the string is not a palindrome. If all valid characters match, the string is a palindrome.

## Time Complexity

**O(n)**

The string is traversed using two pointers.

## Space Complexity

**O(1)**

Only a constant amount of extra space is used.

## Test Cases

### Test Case 1 — Typical Case

**Input:**

```text
A man, a plan, a canal: Panama
