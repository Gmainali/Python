
## Simplified Code:
float() handles both integers and floating-point numbers

```python
## Asking the user for two numbers
num1 = float(input('Please enter your first number: '))
num2 = float(input('Please enter your second number: '))

## Calculating the sum
sum = num1 + num2

## Printing out the result
print('The sum of your numbers is:', sum)
```

### Output:
```
Please enter your first number: 1
Please enter your second number: 2.1
The sum of your numbers is: 3.1
```


## Complex: Takes input of two numbers and performs the summation.
```python
# Declaring Variables
first_number = 1
second_number = 2.1

# Adding the numbers
total_sum = first_number + second_number

# Printing out the message
print('This script adds declared integers:')
print('Total Sum of the numbers are: ', + total_sum)
# Adding block differentiator
print("=" * 45)
```

## Seeking input from user for two integer numbers
```python
print('This script only handles integers:')
first_number = input('Input your first number for sum? ')
second_number = input('Input your second number for sum? ')

# Convert the input strings to integers
# input() function in Python returns values as strings
first_number = int(first_number)
second_number = int(second_number)

# Adding the numbers
total_sum = first_number + second_number

# Printing out the message
print('Total Sum of the numbers are: ', total_sum)
# Adding block differentiator
print("=" * 45)
```

## Seeking input from user for two numbers can be integer or float
```python
# Function to safely convert input to a number (either int or float)
def get_number_input(prompt):
    while True:
        user_input = input(prompt)
        try:
            # Try to convert to float first (since float can handle both integers and decimals)
            return float(user_input)
        except ValueError:
            # If conversion fails, prompt the user again
            print("Invalid input. Please enter a valid number.")

# Seeking input from user for two numbers (either integer or float)
print('This script handles both integers and floats:')
first_number = get_number_input('Input your first number for sum? ')
second_number = get_number_input('Input your second number for sum? ')

# Adding the numbers
total_sum = first_number + second_number

# Printing out the message
print('Total Sum of the numbers are: ', total_sum)

# Adding block differentiator
print("=" * 45)
```

### Output:
```
This script adds declared integers:
Total Sum of the numbers are:  3.1
=============================================
This script only handles integers:
Input your first number for sum? 21
Input your second number for sum? 21
Total Sum of the numbers are:  42
=============================================
This script handles both integers and floats:
Input your first number for sum? 2.3
Input your second number for sum? 21
Total Sum of the numbers are:  23.3
=============================================
```

