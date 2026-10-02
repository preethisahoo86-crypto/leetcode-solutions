# Best Time to Buy and Sell Stock

**Difficulty:** Easy

**Topic:** Arrays & Strings

**LeetCode:** https://leetcode.com/problems/best-time-to-buy-and-sell-stock/

## Approach

I use a single-pass approach to find the maximum possible profit.

While traversing the prices, I keep track of the minimum price seen so far. For each current price, I calculate the profit that could be obtained by selling at that price.

The maximum profit found during the traversal is returned.

## Time Complexity

**O(n)**

The prices array is traversed only once.

## Space Complexity

**O(1)**

Only a few variables are used, so no additional data structure is required.

## Test Cases

### Test Case 1 — Typical Case

**Input:**

```text
prices = [7,1,5,3,6,4]
