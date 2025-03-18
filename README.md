# Intro-to-Python-Assignment
def calculator():
    # Get user input for numbers and operation
    num1 = float(input("Enter the first number: "))
    operation = input("Enter the operation (+, -, *, /): ")
    num2 = float(input("Enter the second number: "))

    # Perform operation based on user input
    if operation == "+":
        result = num1 + num2
        print(f"{num1} + {num2} = {result}")
    elif operation == "-":
        result = num1 - num2
        print(f"{num1} - {num2} = {result}")
    elif operation == "*":
        result = num1 * num2
        print(f"{num1} * {num2} = {result}")
    elif operation == "/":
        if num2 != 0:
            result = num1 / num2
            print(f"{num1} / {num2} = {result}")
else:
            print("Error: Division by zero is not allowed.")
    else:
        print("Error: Invalid operation. Please enter +, -, *, or /.")

# Call the calculator function
calculator()

