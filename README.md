Assignment 3
In this assignment, we calculate two things:
Calculate Factorial using a function
Use the Math module for various mathematical operations
---------------------------------------------------------------------------------------------------
Task 1: Calculate Factorial Using a Function 

#Calculate Factorial Using a Function 
def factorial(n):
    if n < 0:
        return "Factorial is not defined for negative numbers"
    elif n == 0 or n == 1:
        return 1
    else:
        result = 1
        for i in range(2, n + 1):
            result *= i
        return result
# Example usage
n = 5
result = factorial(n)
print(f"The factorial of {n} is {result}")

--------------------------------------------------------------------


Task 2: Using the Math Module for Calculations

# Using the Math Module for Calculations
import math

a = int(input("Enter a number: "))

# Find Square Root
SquareRoot = math.sqrt(a)
print(f"The square root of {a} is {SquareRoot}")

# Find Natural Logarithm (log base e)
NaturalLog = math.log(a)
print(f"The natural logarithm of {a} is {NaturalLog}")

# Find Sine of the number in radians
angle_radians = math.pi / 2  # 90 degrees in radians
SineValue = math.sin(angle_radians)
print(f"The sine of {angle_radians} radians is {SineValue}")

-------------------------------------------------------------------------

