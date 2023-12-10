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

# Calculate the factorial of 5
result = factorial(5)

# Print the result
print(f"The factorial of 5 is: {result}")
