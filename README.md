# Initialize variables
sum = 0
average = 0

# Loop 5 times to get 5 numbers
for i in range(5):
  # Get input from the user as a string
  number = input(f"Enter number {i + 1}: ")

  # Try converting the input to a float
  try:
    number = float(number)
  except ValueError:
    print("Invalid input. Please enter a number.")
    continue

  # Add the number to the sum
  sum += number

# Calculate the average
average = sum / 5

# Print the sum and average
print(f"The sum of the 5 numbers is: {sum}")
print(f"The average of the 5 numbers is: {average}")
