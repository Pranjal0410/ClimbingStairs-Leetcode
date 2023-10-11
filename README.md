# Climbing Stairs - LeetCode Solution (Python)

## Problem Description

You are climbing a staircase. It takes `n` steps to reach the top. Each time you can either climb `1` or `2` steps. In how many distinct ways can you climb to the top?

LeetCode Problem Link: [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)

## Solution

I've provided a Python solution to this problem in the file `climbing_stairs.py`. The solution uses a dynamic programming approach to efficiently calculate the number of distinct ways to climb the stairs.

The main function in the solution is `climbStairs(n)`, which takes an integer `n` as input and returns the number of distinct ways to climb `n` stairs.

## Usage

To use the solution, you can call the `climbStairs(n)` function, where `n` is the number of stairs you want to climb. Here's an example of how to use it:

```python
from climbing_stairs import climbStairs

n = 5
ways = climbStairs(n)
print(f"Number of distinct ways to climb {n} stairs: {ways}")
