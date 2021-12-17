# Final_Python_MiniProject
Justin Tung's Python Mini Project

#Purpose of the Code
The purpose of the Python code is to create a calculator that can do simple math. The calculator can add, subtract, 
multiply, and divide two numbers. Additionally, the calculator can find the sine, cosine, and reciprocal of a number.
Finally, the calculator can also display past calculations that were conducted by the calculator.

The calculator includes an add, subtract, multiply, and divide functions. These functions take two numbers from the 
user as inputs and conducts the math on the two numbers. These functions have a check that ensures that the two inputs
are numbers and not letters or other strings. The divide function checks that the user is not dividing by zero, or else
there is an error displayed. Additionally, the addition, subtraction, and multiplication functions check that the output
is not an overflow error.

The calculator can also the the reciprocal of an input. This function ensures the input is not zero or else there would
be an indeterminate answer. Additionally, the calculator can also take the sine and cosine of a number, in radians, by 
importing functions from the Math library. 

When the code runs, the user is asked to input numbers that correspond to the action they want to take. Inputs 1-7 correspond
to mathematical calculation. An input of 8 displays the past calculations done by the calculator by displaying a list that was
appended with values from each calculation. An input of 9 leads to the exit of the calculator and the end of the code.
