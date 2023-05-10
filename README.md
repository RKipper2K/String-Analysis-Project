# String-Analysis-Project
Some files related to a string analysis project I made in my 5th semester. The project's purpose was to teach us about string analysis, and it consisted of 3 parts:
- Finding a certain string inside of a text file
- Searching for palindromes
- Finding the longest common substring between 2 files

## Part 1 - Finding a String: [Knuth-Morris-Pratt algorithm](https://www.geeksforgeeks.org/kmp-algorithm-for-pattern-searching/) 
Unlike a naive approach where we would sequentially search position by position for our target pattern, the KMP algorithm optimizes by using a prefix table that allows it to skip characters that we know won't be a match and thus avoud unnecessary cycles.

## Part 2 - Finding the longest palindrome in a file: [Manacher Algorithm](https://www.geeksforgeeks.org/manachers-algorithm-linear-time-longest-palindromic-substring-part-1/)
The second task we were posed with was finding the largest palindrome in a text. We employed the Manacher algorithm, which considers the possibility of palindromes within palindromes and allowing us to skip unnecessary searches in certain occassicertain characters in our searches when we know they are already palindromes.

## Part 3 - Finding the longest common subrstring: [LCS Algorithm](https://www.geeksforgeeks.org/longest-common-subsequence-dp-4/)
For this algorithm we took advantage of dynamic programming by creating a 2d matrix in which we can run different scenarios and backtrack if necessary, which ultimately leads to finding the longest common substring between 2 texts.
