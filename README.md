# FACTORIAL CALCULATOR
Description
The Factorial Calculator is a simple C program that computes the factorial of a user-provided integer using recursion. The program prompts the user for an integer input and displays the calculated factorial.

Features
Prompts the user to enter a non-negative integer.
Uses a recursive function to calculate the factorial of the input number.
Displays the result to the user.
How It Works
The program starts by displaying a welcome message.
It prompts the user to enter an integer.
The program reads the input and calls the fact function, which calculates the factorial recursively:
If the input number is 0, the function returns 1 (since 0! = 1).
Otherwise, it calls itself with the argument n-1 and multiplies the result by n.
The calculated factorial is then printed to the console.
