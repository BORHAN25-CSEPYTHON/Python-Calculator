
# Python-Calculator
# Simple Python Calculator A basic terminal-based calculator in Python that performs +, -, *, and / operations.
# calculator.py

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "Cannot divide by zero!"

print("Simple Python Calculator")
print("Operations: +  -  *  /")

num1 = float(input("Enter first number: "))
op = input("Enter operation (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if op == '+':
    result = add(num1, num2)
elif op == '-':
    result = subtract(num1, num2)
elif op == '*':
    result = multiply(num1, num2)
elif op == '/':
    result = divide(num1, num2)
else:
    result = "Invalid operation!"

print("Result:", result)

# 🧮 Simple Python Calculator

A beginner-friendly calculator written in Python. Supports:

- ➕ Addition
- ➖ Subtraction
- ✖️ Multiplication
- ➗ Division

## 🚀 How to Run

Make sure Python is installed.

```bash
python calculator.py
