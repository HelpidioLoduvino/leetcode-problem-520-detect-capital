# leetcode-problem-520-detect-capital
This repository includes a solution for LeetCode problem 520, "Detect Capital," implemented in PHP. The problem involves determining whether the usage of capital letters in a given word follows one of three rules:

1 - All letters in the word are capital letters. 
2 - All letters in the word are lowercase letters. 
3 - Only the first letter is uppercase, and the rest are lowercase.

# Problem Description: 
A string word consisting of uppercase and lowercase English letters. Output: true if the usage of capitals in the word is correct according to the rules mentioned above, otherwise false.

Example Input: "USA" Output: true

Input: "FlaG" Output: false

# Solution 

The provided PHP function detectCapitalUse checks the capital usage in a given word based on the following conditions:

It returns true if all characters are uppercase. It returns true if all characters are lowercase. It returns true if only the first character is uppercase and the rest are lowercase. It returns false otherwise.

