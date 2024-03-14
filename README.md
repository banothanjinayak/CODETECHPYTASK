# CODETECHPYTASK

Task Documentation: Simple Calculator in Python

1. Objective:

The objective of this task is to create a simple calculator program in Python that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. Additionally, the program should handle invalid inputs and provide an option to quit the calculator when the user desires.
2. Implementation:

The calculator program is implemented using Python programming language.
The program consists of several functions, including functions for each arithmetic operation (addition, subtraction, multiplication, division) and a main function to run the calculator.
Each arithmetic operation is implemented as a separate function to maintain modularity and readability.
The main function (calculator()) guides the user through the menu options, takes user input, and calls the appropriate arithmetic function based on the user's choice.
The program ensures graceful handling of invalid inputs and prevents division by zero errors.
The program continues running until the user chooses to quit by entering '5'.
3. Functions:

add(x, y):
Adds two numbers x and y and returns the result.
subtract(x, y):
Subtracts the second number y from the first number x and returns the result.
multiply(x, y):
Multiplies two numbers x and y and returns the result.
divide(x, y):
Divides the first number x by the second number y and returns the result.
If y is 0, returns an error message to avoid division by zero.
calculator():
The main function to run the calculator program.
Displays menu options for the user to select an arithmetic operation or quit.
Takes user input and calls the corresponding arithmetic function based on the user's choice.
Handles invalid inputs by displaying an error message and prompts the user to enter a valid option.
Continues running until the user chooses to quit the calculator.
4. Usage:

To use the calculator, execute the Python script containing the provided code.
Follow the on-screen instructions to select an arithmetic operation or quit the calculator.
Enter valid numerical inputs when prompted.
The calculator will perform the selected operation and display the result.
Repeat the process to perform more calculations or quit the calculator by selecting the quit option.
5. Error Handling:

The program handles division by zero error by checking if the divisor is zero before performing division.
Invalid inputs, such as non-numeric choices or non-numeric operands, are handled by displaying an error message and prompting the user to enter a valid option or operands.
6. Conclusion:

The implemented simple calculator program provides basic arithmetic functionalities and additional features such as error handling and graceful termination.
Users can perform arithmetic calculations conveniently using this calculator while ensuring accurate results and preventing runtime errors.




