# Tutedude-Python-Programing-Task-1-module-2
# Do Simple mathamatic calculation
# Step 1: Take two numbers as input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2
division = num1 / num2
print("\nResults:")
print(f"Addition: {num1} + {num2} = {addition}")
print(f"Subtraction: {num1} - {num2} = {subtraction}")
print(f"Multiplication: {num1} * {num2} = {multiplication}")
print(f"Division: {num1} / {num2} = {division}")
''''''
#creat a personal greeting Message
# Step 1: Take user's first and last name as input
first_name = input("Enter your first name: ").strip()
last_name = input("Enter your last name: ").strip()

# Step 2: Concatenate to form full name
full_name = f"{first_name} {last_name}"

# Step 3: Print personalized greeting
print(f"\nHello, {full_name}! Welcome to the Python Program.")
