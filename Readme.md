main(int argc, char *argv[]):
Entry point of the program.
Declares variables valueOne, valueTwo, operator, and answer.
Prompts the user to enter a calculation in the format valueOne operator valueTwo.
Reads user input using scanf.
Uses a switch statement to determine the operation based on the operator provided:
/: Performs division.
*: Performs multiplication.
+: Performs addition.
-: Performs subtraction.
^: Calculates valueOne raised to the power of valueTwo using the pow function from math.h.
(space): Calculates the square root of valueTwo using the sqrt function from math.h.
Default: Jumps to the fail label if the operator is not recognized.
Prints the result of the calculation.
Jumps to the exit label to end the program.
fail label prints "Fail." if the operator is invalid.
exit label marks the end of the program and returns 0.
