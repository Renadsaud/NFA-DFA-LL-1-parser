# NFA-DFA-LL-1-parser

# What is NFA?
NFA is a type of finite automata that can follow multiple paths based on the input it is currently processing at any given time. The main reason it is called non-deterministic is that there is more than one possible next state for a given input.

Non-deterministic finite automata consist of a set of five tuples and are represented as M = (Q, Σ, δ, q0, F)
Q: It represents the finite set of states
Σ: It represents the finite set of the input symbol
q0: It represents the initial state
F: It represents the final state
δ: It represents the transition function

# What is DFA? 
 DFA is a type of finite automata that will always transition to the same next state, regardless of the current state, for any given input symbol. The main reason why it is called deterministic is that, for each input symbol, the DFA will have an actual next state.

Deterministic finite automata also consist of a set of five tuples and are represented as M = (Q, Ʃ, δ, q0, F)
Q: It represents the set of final states
Σ: It represents the finite set known as alphabets.
q0: It represents an initial state or starts state of DFA.
F: It represents the set of final states of DFA.
δ: It represents a transition function defined over transitions of FA for 


# This project consists of 2 parts:
 Part 1 
- 1- We have built an NFA from a given regular expression
<br/>
- 2- We have converted a giving NFA into a DFA 
<br/>
- 3- We have Built a DFA from a given regular expression directly
<br/>
----------------------------------------------------------------------------
 Part 2 
- 1- We were given a grammar that we modify (see the pdf)
<br/>
- 2- We Re-write the grammar such that it can be parsed by an LL(1) parser
<br/>
- 3- We used the re-written grammar as a base to implement LL(1) parser
<br/>
- 4- Test your code with correct and incorrect input code
<br/>
-Both have a GUI.

# The programming language used
Part 1 was written in Java language, and Part 2 was written in Python language



