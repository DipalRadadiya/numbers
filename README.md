# numbers
Create a Python program that checks if a given number is positive, negative, or zero and prints an appropriate message
# Get the number as input from the user
user_number = float(input("Enter a number: "))

# Check if the number is positive, negative, or zero
if user_number > 0:
    print("The number is positive.")
elif user_number < 0:
    print("The number is negative.")
else:
    print("The number is zero.")


Enter a number: -1
The number is negative.
Enter a number: 8
The number is positive.
Enter a number: 0
The number is zero.
