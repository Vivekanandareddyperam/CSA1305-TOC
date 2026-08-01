# CHECKING WHETHER A STRING BELONGS TO A GRAMMAR

## AIM
To write a C program to check whether a string belongs to the grammar S -> 0 S 0 | 1 S 1 | 0 | 1 | ε

## ALGORITHM
1. Get the input string from the user.
2. Find the length of the string. Let it be n.
3. Check whether all the symbols in the input are either 0 or 1. If so, print “String is valid” and go to step 4. Otherwise print “String not valid” and quit the program.
4. If the 1st symbol and nth symbol are the same, 2nd symbol and (n-1)th symbol are the same and so on, then the given string is palindrome. So, print “String accepted”. Otherwise, print “String not accepted”

## RESULT
The C program to check whether a string belongs to the given grammar (Palindrome) was executed successfully and the output was verified.
