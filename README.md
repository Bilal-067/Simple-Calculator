The task is to do a simple calculator that can perform basic arithmetic operations: addition, subtraction, multiplication, and division. Here's a detailed description of its functionality:

1. Function Definition: calculator()
The main functionality of the calculator is wrapped inside the calculator() function.

The function begins by printing a welcome message and the available operations (+, -, *, /).

2. User Input
The user is prompted to enter two numbers (num1 and num2), which are read as strings and then converted to floating-point numbers using float().

The user is then asked to choose an operation from the available options: addition (+), subtraction (-), multiplication (*), or division (/).

3. Operation Logic
The function uses a series of if-elif statements to determine which operation the user wants to perform:

Addition (+): If the operation is +, the function adds the two numbers.

Subtraction (-): If the operation is -, the function subtracts num2 from num1.

Multiplication (*): If the operation is *, the function multiplies the two numbers.

Division (/): If the operation is /, the function checks if num2 is zero. If it is, an error message is displayed indicating that division by zero is not allowed. If num2 is not zero, it performs the division.

If the user enters an invalid operation (i.e., not one of the predefined options), the program prints an error message.

4. Error Handling
Invalid Input (Non-Numeric): The code handles cases where the user does not enter a valid number by using a try-except block. If the user inputs a non-numeric value for num1 or num2, a ValueError is raised, and an error message ("Invalid input. Please enter numeric values.") is displayed.

Division by Zero: In the case of division, a check is performed to ensure that num2 is not zero. If num2 is zero, a specific error message ("Error: Division by zero is not allowed.") is printed and the function returns early, preventing the division from taking place.

5. Displaying the Result
After the operation is performed, the result is printed to the screen in a user-friendly format: "Result: {result}".

6. Main Program Execution
The line if __name__ == "__main__": ensures that the calculator() function is only called if the script is executed directly (not imported as a module). This is a common practice to allow the script to be both reusable and executable.

Key Features:
Basic Arithmetic: The calculator performs basic arithmetic operations: addition, subtraction, multiplication, and division.

Error Handling: The code handles errors such as invalid input types (non-numeric values) and division by zero, providing informative error messages.

User-Friendly Output: Clear prompts are given for user inputs, and the result of the operation is clearly displayed.

This code provides a simple and functional calculator program that handles basic arithmetic operations and errors. It uses fundamental Python features like input(), try-except, and conditional statements to achieve its functionality.

Output->

![Project2](https://github.com/user-attachments/assets/40c9b802-0ffe-48e0-8652-f702380ac4a8)
