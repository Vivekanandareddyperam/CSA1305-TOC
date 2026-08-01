# CHECKING WHETHER A STRING BELONGS TO A GRAMMAR

## AIM
To write a C program to check whether a string belongs to the grammar S -> 0 S 1 | ε

## ALGORITHM
1. Get the input string from the user.
2. Find the length of the string.
3. Check whether all the symbols in the input are either 0 or 1. If so, print “String is valid” and go to step 4. Otherwise print “String not valid” and quit the program.
4. Find the length of the string. If the length is odd, then print “String not accepted” and quit the program. If the length is even, then go to step 5.
5. Divide the string into two halves.
6. If the first half contains only 0s and the second half contains only 1s then print “String Accepted”. Otherwise print “String Not Accepted”

## RESULT
The C program to check whether a string belongs to the given grammar was executed successfully and the output was verified.
