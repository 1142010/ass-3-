# ass-3-
# ass-3
#task 1.py
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

# Sample run
num = int(input("Enter a number: "))
print(f"Factorial of {num} is: {factorial(num)}")

 task 2.py
 mport math
# Ask the user for a number
num = float(input("Enter a number: "))

# Calculations using math module
square_root = math.sqrt(num)
logarithm = math.log(num)  # Natural log (base e)
sine_value = math.sin(num)  # Assumes the number is in radians

# Display results
print(f"Square root: {square_root}")
print(f"Logarithm: {logarithm}")
print(f"Sine: {sine_value}")
