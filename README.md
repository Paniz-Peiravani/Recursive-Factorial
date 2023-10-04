# Recursive Factorial Calculator in MIPS Assembly

This MIPS assembly code, developed in MARS IDE, is designed to calculate the factorial of a given integer. The program follows these steps:

1. Displays a prompt message asking the user to enter a number to find its factorial.
2. Reads the user's input integer.
3. Calls a recursive `factorialFunction` to calculate the factorial.
4. Displays the result in the I/O text field and stores it in the Data Segment.

## Recursive Factorial Function

The `factorialFunction` is a recursive function that calculates the factorial of an integer using a base case and recursion. It utilizes the stack to store local variables and return addresses during recursion.
 
## Code Explanation

- The program accepts user input, stores it in a global variable, and calls a factorial calculation function.
- The `factorialFunction` is a recursive function that calculates the factorial of an integer.
- The result is displayed using system calls and stored in a global variable for reference.

