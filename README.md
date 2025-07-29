# Python Calculator 🧮

This is a simple Python calculator that takes two numbers and performs basic math operations:  
➕ Addition  
➖ Subtraction  
✖️ Multiplication  
➗ Division  

Great for beginners learning Python input, conditionals, and basic math logic.

## 🧪 How to Run
Just copy the code into any Python environment (like PyCharm or Replit) and run it.

## 🧠 Skills used
- `input()`
- `float()`
- `if-elif-else` statements




operator = input("Choose operation")
num1 = float(input("Enter your number"))
num2 = float(input("Enter another number"))

if operator == "+":
    print(num1 + num2)
elif operator == "-":
    print(num1 - num2)
elif operator == "*":
    print(num1 * num2)
elif operator == "/":
    print(num1 / num2)
else:
    print("Invalid operation")
