# simple-calculator-in-c
### This is a simple calculator. It is a collaborative project to build our dev skills. 

The objectives for the calculator

* Only user defined functions and prototypes, main() function should only call the required functions and print out the answer. 

## Funtions & Prototypes
- main.c : will take two inputs of type float and parse to a function that checks for digits
- check_digit.c : checks if the inputs are valid numbers or not, then parse to operation if they are
- [Star] operation.c : prompts user if they want to add, subtract, divide, etc. Then calls the required function, e.g addition()
- addition.c : adds two values and parse answer to the display() and memory
- substract.c : substracts two values and parse answer to the display() and memory 
- divide.c : divide two values and parse answer to the display() and memory
- multiplication.c : multiplication two values and parse answer to the display() and memory
- percentage.c : percentage between two values and parse answer to the display() and memory
- [Nandi] memory.c : stores all answers and parse its value to display 
- display.c : display the answer and prompt user to run operations on the answer e.g Answer + 3, or end/clear calculation which displays all values in memory. 
- main.h : all prototypes included
