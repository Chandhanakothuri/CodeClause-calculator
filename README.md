# CodeClause-calculator
# It is a simple calculator used to perform arithmetic operations on numbers.


def add(num1, num2):
    return num1 + num2
def subtract(num1, num2):
    return num1 - num2
def multiply(num1, num2):
    return num1 * num2
def divide(num1, num2):
    return num1 / num2
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
print("Choose an operation:")
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")
choice = int(input("Enter your choice (1-4): "))
if choice == 1:
    print(num1, "+", num2, "=", add(num1, num2))
elif choice == 2:
    print(num1, "-", num2, "=", subtract(num1, num2))
elif choice == 3:
    print(num1, "*", num2, "=", multiply(num1, num2))
elif choice == 4:
    print(num1, "/", num2, "=", divide(num1, num2))
else:
    print("Invalid input")
