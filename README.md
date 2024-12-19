# raindrops-closure
A Clojure implementation of the Raindrops challenge, where numbers are converted into corresponding raindrop sounds based on their divisors.

# Raindrops in Clojure

A Clojure implementation of the **Raindrops** challenge, which is an interesting twist on the classic FizzBuzz problem. The task involves converting a number into specific sounds based on its divisors.

## Problem Statement

For a given number, apply the following rules to produce the result:

1. If the number is divisible by 3, add `"Pling"` to the result.
2. If the number is divisible by 5, add `"Plang"` to the result.
3. If the number is divisible by 7, add `"Plong"` to the result.
4. If the number is not divisible by any of these, return the number as a string.

### Examples

| Input | Output       |
|-------|--------------|
| 28    | `"Plong"`    |
| 30    | `"PlingPlang"` |
| 34    | `"34"`       |

