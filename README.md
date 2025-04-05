# Python-1
Assignment 1
# Simple Calculator

# Ask the user for the first number
num1 = float(input("Enter the first number: "))

# Ask the user for the second number
num2 = float(input("Enter the second number: "))

# Ask the user for the operation they want to perform
operation = input("Enter operation (+, -, *, /): ")

# Perform the chosen operation and display the result
if operation == "+":  # Addition
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
elif operation == "-":  # Subtraction
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")
elif operation == "*":  # Multiplication
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")
elif operation == "/":  # Division
    if num2 == 0:  # Check if the second number is zero to avoid errors
        print("Error: Division by zero is not allowed.")
    else:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
else:
    print("Error: Invalid operation. Please enter +, -, * or /.")


     
