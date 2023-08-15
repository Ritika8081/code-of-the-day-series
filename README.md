# code-of-the-day-series
# Code Overview
The code can be divided into the following functions and sections:

## isVowel(char ch):

## Input: A character ch.
# Functionality: Checks if the given character is a vowel (either in uppercase or lowercase).
Output: Returns true if the character is a vowel, otherwise false.
countVowel(string str, int n):

Input: A string str and an integer n representing the current index.
Functionality: Recursively counts the number of vowels up to the n-th character of the string.
Output: Returns the count of vowels up to the n-th character.
main():

# Hardcodes a string str as "abcod".
Computes the number of vowels in the string using countVowel.
Computes the number of consonants by subtracting the number of vowels from the total length.
Prints the count of consonants followed by the count of vowels.
Usage
Simply compile and run the program. As the string "abcod" is hardcoded, the program will output the number of consonants and vowels present in this string.

Output
The output will be:
3
2
This indicates that there are 3 consonants and 2 vowels in the string "abcod".

