# project3

Level 1

First we determined how our equations would look like based on the project that was assigned. We wrote two functions: one with the result equal to 0 and one with the result equal to a number except 0.
Our functions worked with return function easily. After identifying the functions, we created an input data for user. First user would decide wether he or she wants to solve equations with two or three unknons.
With using switch(Selection) function, according to the user's choice we created two cases: two onknowns and three unknowns.
First case is ax + b = 0 and second one is ax + b = c. 
After choosing the equation, the user will be asked to write the values in the eqaution. 
If the value for "a" in case 1 (ax + b = 0) is 0 our program will say: "There is no solution for this equation. Please try another!" 
Also if the user chooses the second case: ax + b = c and enters 0 for c, our program will warn the user and says: "Please select the right equation type!!" Because it will be same with the case 1 if she enters 0 for c. 
The user will have countless tries to enter the values she want to enter. 
Both of the cases will end with break to prevent the loop. 


Level 2

We have a program that is able to solve a system of linear equations. The equation number must be equal to the variable number and all of the lines must include all of the variables. Also, our program works only with the matrix form of equations. In the text file that includes the system of equations, there can only be the coefficients and constant results. In addition, at the beginning of the program, it asks the user to write the text file’s name which has the equations. When all of the rules are followed properly, the program gets the result for all of the variables. 

First of all, with the “how_many_lines” function, the program counts the line number in the text file and equals it to the equation number. The “allocmatrix” function allocates memory to store the coefficients, free terms, and the solution. Then the “readmatrix” function reads the coefficients in the equations from the text file. Then, “printmatrix” function prints equations in order to show the user in the terminal how the process progresses. “Diagonal” function is designed to avoid zeroes in the matrix, except for the results, to avoid dividing any number by zero in the process. The “printresult” function is, as its name says, prints the result of the system of equations into the terminal. “Freematrix” function is to make the memories which are allocated before empty in the program. “cls” function does the cleaning job of the terminal in the beginning. In the last part, the “main” function gathers and starts all of the functions defined before. 
