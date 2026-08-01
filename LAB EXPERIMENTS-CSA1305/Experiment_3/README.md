# FINDING ε-CLOSURE FOR NFA WITH ε-MOVES

## AIM
To write a C program to find ε-closure of a Non-Deterministic Finite Automata with ε-moves

## ALGORITHM
1. Get the following as input from the user.
   i. Number of states in the NFA
   ii. Number of symbols in the input alphabet including ε
   iii. Input symbols
   iv. Number of final states and their names
2. Declare a 3-dimensional matrix to store the transitions and initialize all the entries with -1
3. Get the transitions from every state for every input symbol from the user and store it in the matrix.
4. Initialize a two-dimensional matrix e_closure with -1 in all the entries.
5. ε-closure of a state q is defined as the set of all states that can be reached from state q using only ε-transitions.
6. For every state i, find ε-closure as follows: If there is an ε-transition from state i to state j, add j to the matrix e_closure[i]. Call the recursive function find_e_closure(j) and add the other states that are reachable from i using ε
7. For every state, print the ε-closure values

## RESULT
The C program to find ε-closure of a Non-Deterministic Finite Automata with ε-moves was executed successfully and the output was verified.
