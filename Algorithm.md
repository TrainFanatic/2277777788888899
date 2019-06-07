# Algorithm

This document is going to talk about the algorithm for finding the numbers with relatively high multiplicative persistence

## Rules

1. The length of one *element* of the number must be 1
2. No decimals

## The working

To find a number one layer higher than a number $x$, we need to find the factors of the number and then put those together in one big number

## Explanation

1. Say you want to break down 26. There is no way to do that as the factors will be 2,13 and thus no way to get to 26 by multiplying two numbers (as the interpreter only allows one number per character)
2. This doesn't make any difference and it's hard to input this into tools like ```bc```