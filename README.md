# New_add_numbers.py
add_numbers
# add_numbers.py

def add(num1, num2):
    """
    This function takes two numbers as input and returns their sum.
    """
    return num1 + num2

if __name__ == "__main__":
    print("Welcome to the number adder!")

    try:
        # Get input from the user
        input1 = float(input("Enter the first number: "))
        input2 = float(input("Enter the second number: "))

        # Call the add function
        sum_result = add(input1, input2)

        # Print the result
        print(f"The sum of {input1} and {input2} is: {sum_result}")

    except ValueError:
        print("Invalid input. Please enter valid numbers.")
