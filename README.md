# Python-program-to-implement-a-calculator-to-do-basic-operationsEnter two numbers
def add(x, y):
    print(x + y)

def subtract(x, y):
    print(x - y)

def multiply(x, y):
    print(x * y)

def divide(x, y):
    if y != 0:
        print(x / y)
    else:
        print("Error: Division by zero")

print("Enter two numbers")
n1 = input()
n2 = input()
print("Enter the operation +, -, *, /")
op = input()

if op == '+':
    add(int(n1), int(n2))
elif op == '-':
    subtract(int(n1), int(n2))
elif op == '*':
    multiply(int(n1), int(n2))
elif op == '/':
    divide(int(n1), int(n2))
else:
    print("Invalid entry")

5
3
Enter the operation +, -, *, /
*
Output:

15
