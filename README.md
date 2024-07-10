# Assignment-1
Introduction assignment 

Palindrome Checker Task
Task Overview
Create a program to check whether a given input string is a palindrome, ignoring spaces, punctuation, and capitalization.

Steps to Complete the Task
Input the String

Action: Read a string from the user.
Objective: Capture the user's input to be analyzed.
Preprocess the Input

Action: Remove all spaces from the string.
Action: Convert all characters in the string to lowercase.
Objective: Normalize the string so that the check is case-insensitive and not affected by spaces.
Filter Out Non-Alphabetic Characters

Action: Create a new string that includes only alphabetic characters from the processed string.
Objective: Exclude any characters that are not letters (e.g., punctuation, numbers) to focus only on the relevant content.
Check for Palindrome

Action: Determine the length of the filtered string.
Condition: If the string length is 1, it is a palindrome.
Condition: If the string length is greater than 1:
Action: Compare each character from the start with the corresponding character from the end.
Condition: If any characters do not match, it is not a palindrome.
Action: If all characters match, it is a palindrome.
Condition: If the string length is 0, it is not a palindrome.
Objective: Assess whether the string reads the same forward and backward.
Output the Result

Action: Print whether the input string is a palindrome or not.
Objective: Provide the user with the result of the palindrome check.
Example
For the input "A man, a plan, a canal: Panama":

Input: "A man, a plan, a canal: Panama"
Preprocess: "amanaplanacanalpanama"
Filter: "amanaplanacanalpanama"
Check: Compare "amanaplanacanalpanama" with its reverse; both are the same.
Output: It is a palindrome.

Reference:
https://www.dictionary.com/e/palindromic-word/

IMPORTANT! 

Usage of external libraries/packages is forbidden. You are just to add code in the specific area, so that it'd update 'IsPalindrome' variable that checkes whether or not a string is Palindrome or not
