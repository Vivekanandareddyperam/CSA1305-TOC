# CHECKING WHETHER A STRING BELONGS TO A GRAMMAR

## AIM
To write a C program to check whether a string belongs to the grammar S -> A 1 0 1 A, A -> 0 A | 1 A | ε

## ALGORITHM
1. Get the input string from the user.
2. Find the length of the string.
3. Check whether all the symbols in the input are either 0 or 1. If so, print “String is valid” and go to step 4. Otherwise print “String not valid” and quit the program.
4. Read the input string character by character
5. If the ith input symbol is 1, check whether (i+1)th symbol is 0 and (i+2)th symbol is 1. If so, the string has the substring 101. So print “String Accepted”. Otherwise, print “String Not Accepted”

## RESULT
The C program to check whether a string belongs to the given grammar was executed successfully and the output was verified.
