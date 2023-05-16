def factorial(number):
    if number <= 1:
        return 1

    fact = 1
    for i in range(2, number + 1):
        fact *= i

    return fact

# Prompt the user to enter a number
number = int(input("Enter a positive integer: "))

# Calculate the factorial of the number
result = factorial(number)

# Display the result
print("The factorial of", number, "is", result)
