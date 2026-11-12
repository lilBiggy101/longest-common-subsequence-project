# Longest Common Subsequence (LCS)
## Overview
A C++ project built for my CS315 Algorithm Design class which implements the Longest Common Subsequence algorithm using dynamic programming. It finds the longest ordered sequence shared by two DNA strings. 

## How It Works
1. Build a 2D table where each cell holds the LCS length for a pair of prefixes of the two strings.
2. Fill the table from smaller subproblems to larger ones.
3. Trace back through the table to reconstruct the actual subsequence.

## Concepts
- Dynamic programming
- 2D arrays and tables
- String comparison
- Sequence reconstruction

## Complexity
- Time: O(m x n)
- Space: O(m x n)

where m and n are the lengths of the two strings.

## Project Structure
- `LCS.cpp`: the algorithm
- `dna.txt`: input DNA sequences

## How to Run
```bash
git clone https://github.com/lilBiggy101/longest-common-subsequence-project.git
cd longest-common-subsequence-project
g++ -g LCS.cpp -o LCS
./LCS
```

## Technologies
- C++

## What I Learned
How to solve a problem by breaking it into overlapping subproblems and storing results in a table instead of recomputing them.
