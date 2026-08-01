# CHECKING WHETHER A STRING BELONGS TO A GRAMMAR

## AIM
To write a C program to check whether a string belongs to the grammar S -> 0 S 0 | A, A -> 1 A | ε

## ALGORITHM
1. Get the input string from the user.
2. Find the length of the string.
3. Check whether all the symbols in the input are either 0 or 1. If so, print “String is valid” and go to step 4. Otherwise print “String not valid” and quit the program.
4. Read the input string character by character
5. Count the number of 0’s in the front and store it in the variable count1
6. Skip all 1’s
7. Count the number of 0’s in the end and store it in the variable count2
8. If count1==count2, print “String Accepted”. Otherwise print “String Not Accepted”

## RESULT
The C program to check whether a string belongs to the given grammar was executed successfully and the output was verified.
