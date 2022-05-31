# project3


Level 2

We have a program that is able to solve a system of linear equations. The equation number must be equal to the variable number and all of the lines must include all of the variables. Also, our program works only with the matrix form of equations. In the text file that includes the system of equations, there can only be the coefficients and constant results. In addition, at the beginning of the program, it asks the user to write the text file’s name which has the equations. When all of the rules are followed properly, the program gets the result for all of the variables. 

First of all, with the “how_many_lines” function, the program counts the line number in the text file and equals it to the equation number. The “allocmatrix” function allocates memory to store the coefficients, free terms, and the solution. Then the “readmatrix” function reads the coefficients in the equations from the text file. Then, “printmatrix” function prints equations in order to show the user in the terminal how the process progresses. “Diagonal” function is designed to avoid zeroes in the matrix, except for the results, to avoid dividing any number by zero in the process. The “printresult” function is, as its name says, prints the result of the system of equations into the terminal. “Freematrix” function is to make the memories which are allocated before empty in the program. “cls” function does the cleaning job of the terminal in the beginning. In the last part, the “main” function gathers and starts all of the functions defined before. 
