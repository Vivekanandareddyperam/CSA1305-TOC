# NON-DETERMINISTIC FINITE AUTOMATA (NFA)

## AIM
To write a C program to simulate a Non-Deterministic Finite Automata.

## ALGORITHM
1. Get the following as input from the user.
   i. Number of states in the NFA
   ii. Number of symbols in the input alphabet and the symbols
   iii. Number of final states and their names
2. Declare a 3-dimensional matrix to store the transitions and initialize all the entries with -1
3. Get the transitions from every state for every input symbol from the user and store it in the matrix.
4. Get the input string from the user.
5. Find the length of the input string.
6. Read the input string character by character.
7. Repeat step 8 for every character
8. Refer the transition table for the entry corresponding to the present state and the current input symbol and update the next state. As there can be more than one transition, the next state will be an array.
9. From every state in the next state array, find the list of new transitions and update the next state array.
10. When we reach the end of the input, if at least one of the final states is present in the next state array, it means there is a path to a final state. So the input is accepted. Otherwise the input is not accepted.

## RESULT
The C program to simulate a Non-Deterministic Finite Automata was executed successfully and the output was verified.
