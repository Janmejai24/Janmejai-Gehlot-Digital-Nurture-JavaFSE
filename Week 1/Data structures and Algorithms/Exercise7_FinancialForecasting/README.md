# Exercise 7: Financial Forecasting

## Understanding Recursion

Recursion is a programming technique where a method calls itself repeatedly until a stopping condition is met.

It simplifies problems that can be divided into smaller subproblems.

Every recursive function consists of:

- Base Case
- Recursive Case

---

## Financial Forecasting

Suppose the present value is:

10000

Growth Rate:

10%

Years:

5

Formula:

Future Value = Current Value × (1 + Growth Rate)

Recursive relation:

FV(n) = FV(n−1) × (1 + r)

Base Case:

FV(0) = Initial Value

---

## Time Complexity

Simple Recursive Solution:

O(n)

Space Complexity:

O(n)

because recursive calls are stored in stack memory.

---

## Optimization

To avoid excessive computation:

• Memoization

• Dynamic Programming

• Iterative approach

can reduce memory overhead.

Iterative implementation gives:

Time Complexity:

O(n)

Space Complexity:

O(1)