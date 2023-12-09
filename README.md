def factorial(n):
  """
  This function calculates the factorial of a non-negative integer.

  Args:
      n: The non-negative integer whose factorial is to be calculated.

  Returns:
      The factorial of n.
  """
  
  if n == 0:
    return 1
  else:
    result = 1
    for i in range(1, n + 1):
      result *= i
    return result

# Get number from user
number = int(input("Enter a number: "))

# Calculate and print the factorial
if number >= 0:
  print(f"The factorial of {number} is: {factorial(number)}")
else:
  print("Factorial is not defined for negative numbers.")
