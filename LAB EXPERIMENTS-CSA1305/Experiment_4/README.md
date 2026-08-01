# CHECKING WHETHER A STRING BELONGS TO A GRAMMAR

## AIM
To write a C program to check whether a string belongs to the grammar S -> 0 A 1, A -> 0 A | 1 A | ε

## ALGORITHM
1. Get the input string from the user.
2. Find the length of the string.
3. Check whether all the symbols in the input are either 0 or 1. If so, print “String is valid” and go to step 4. Otherwise print “String not valid” and quit the program.
4. If the first symbol is 0 and the last symbol is 1, print “String accepted”. Otherwise, print “String not accepted”

## RESULT
The C program to check whether a string belongs to the given grammar was executed successfully and the output was verified.
