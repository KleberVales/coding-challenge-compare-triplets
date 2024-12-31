# coding-challenge-compare-triplets

The challenge "Compare the Triplets" involves comparing two triplets of integers that represent scores given to Alice and Bob in three categories: clarity, originality, and difficulty. Here's a concise description:

## Problem Statement:

You are given two triplets:

- a = [a[0], a[1], a[2]] for Alice's scores.
- b = [b[0], b[1], b[2]] for Bob's scores.

For each category i:

- If a[i] > b[i], Alice earns 1 point.
- If a[i] < b[i], Bob earns 1 point.
- If a[i] == b[i], no points are awarded.

The goal is to calculate the total points for Alice and Bob and return them as an array [Alice's points, Bob's points].

## Function Details:

- Function Name: compareTriplets
- Parameters: Two integer arrays of size 3, a and b.
- Returns: An integer array of size 2, where:
  * The first element is Alice's total points.
  * The second element is Bob's total points.

## Input Format:

1. Three integers representing Alice's triplet.
2. Three integers representing Bob's triplet.

## Example:

Input:
``` css
a = [5, 6, 7]
b = [3, 6, 10]

```
Output:
```
[1, 1]

```
