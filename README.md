Name : Prajakta Haridas Mathe
Company : CODTECH IT SOLUTIONS
ID : CT08DS1495
Domain : Java Programming
Duration : 1st JUNE 2024 to 30Th JULY 2024
Mentor : G.SRAVANI

Project Overview: Basic Calculator in Java

Objective:
The goal of this project is to create a simple command-line calculator in Java. It prompts the user to enter two numbers and choose an operation (addition, subtraction, multiplication, or division), then performs the selected operation and displays the result.

Technologies Used:

1) Java Programming Language:

Used for coding the logic of the calculator program.
Java provides platform independence and object-oriented programming features, making it suitable for a wide range of applications.

2) Integrated Development Environment (IDE):

An IDE is Eclipse, used for writing, debugging, and running Java code.
IDEs provide features like code completion, syntax highlighting, and debugging tools, which streamline development.

Key Components:

1) User Input Handling:

Uses Scanner class from java.util package to read user input for numbers and operation choice.
Prompts the user to enter two numbers (num1 and num2).
Prompts the user to select an operation using a menu with options (1 for addition, 2 for subtraction, 3 for multiplication, 4 for division).

2) Arithmetic Operations:

Uses a switch statement to perform the selected operation:
Addition (+): Computes num1 + num2.
Subtraction (-): Computes num1 - num2.
Multiplication (*): Computes num1 * num2.
Division (/): Computes num1 / num2. Includes a check to prevent division by zero.

3) Output:

Displays the calculated result based on the chosen operation.
Handles basic error checking for division by zero.

4) Program Flow:

Begins execution in the main method.
Continues prompting the user for input until an operation is successfully performed or the program encounters an error.

5) User Interaction:

Provides clear prompts and messages to guide the user through the process of entering numbers and selecting an operation.
Ensures user input is properly validated for correctness (e.g., numeric input for numbers, valid operation choices).

6) Exception Handling:

Includes basic error handling for potential exceptions such as input mismatch or division by zero.

7) Resource Management:

Properly closes the Scanner object after use to free up system resources.
