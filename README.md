# Number-guessing-game
Introduction:

    This project is a simple number guessing game implemented in Python. 
    The program generates a random number between 1 and 100, and the player has to guess the number. 
    The program provides feedback on whether the guessed number is too low or too high until the correct number is guessed.

Prerequisites:
           
           *Basic understanding of Python programming.
           *Familiarity with loops, conditional statements, and user input.


Learning Objectives:

           *Learn how to use the random module to generate random numbers.
           *Understand how to take user input and provide interactive feedback.
           *Develop a simple command-line game in Python.

The objective of this project is to build a simple number guessing game that challenges the user to identify a randomly selected number within a specified range.
The game begins by allowing the user to define a range by entering a lower and an upper bound (for example, from A to B). 
Once the range is set, the system randomly selects an integer that falls within this user-defined interval. 
The user's task is then to guess the chosen number using as few attempts as possible. 
The game provides feedback after each guess, helping the user refine their next guess based on whether their previous attempt was too high or too low.

How the Game Works:

         To understand how the number guessing game functions, let’s walk through two practical scenarios. These examples demonstrate how narrowing down the range intelligently—similar to a binary search—can help guess the number efficiently.


