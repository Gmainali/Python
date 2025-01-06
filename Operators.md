# Python Operators: A Fun Guide to Getting Things Done!

Python provides a wide range of operators to help you with basic math, comparisons, logical operations, and more! Let's dive in and explore these operators in a fun and easy way! 🚀

## 1. Arithmetic Operators: The Basic Math Wizards

These operators are used to perform basic math operations like addition, subtraction, multiplication, etc. 🧮

- `+` : **Addition** (Adding stuff up!)
- `-` : **Subtraction** (Take stuff away!)
- `*` : **Multiplication** (Multiplying the magic!)
- `/` : **Division** (Splitting it down the middle!)
- `//` : **Floor division** (Round down the result!)
- `%` : **Modulus** (Getting the remainder)
- `**` : **Exponentiation** (Raising things to the power of!)

### Example:
```python
a = 10
b = 3
print(a + b)  # Output: 13 (Addition)
print(a - b)  # Output: 7 (Subtraction)
print(a * b)  # Output: 30 (Multiplication)
print(a / b)  # Output: 3.3333 (Division)
print(a // b) # Output: 3 (Floor Division)
print(a % b)  # Output: 1 (Modulus)
print(a ** b) # Output: 1000 (Exponentiation)
```

### 2. Comparison Operators: The Truth Seekers

These operators help you compare values to check if they are equal, not equal, or which one is greater/lesser. ⚖️

- `==` : **Equal to**
- `!=` : **Not equal to**
- `>` : **Greater than**
- `<` : **Less than**
- `>=` : **Greater than or equal to**
- `<=` : **Less than or equal to**

### Example:
```python
a = 10
b = 20
print(a == b)  # Output: False (Equal to)
print(a != b)  # Output: True (Not equal to)
print(a > b)   # Output: False (Greater than)
print(a < b)   # Output: True (Less than)
print(a >= b)  # Output: False (Greater than or equal to)
print(a <= b)  # Output: True (Less than or equal to)
```

## 3. Logical Operators: The Decision Makers

These operators help you make logical decisions between conditions. 🤔

- `and` : **Returns True if both conditions are true**
- `or` : **Returns True if at least one condition is true**
- `not` : **Inverts the truth value**

### Example:
```python
a = 10
b = 20
c = 30
print(a < b and b < c)  # Output: True (Both conditions are true)
print(a > b or b < c)   # Output: True (At least one condition is true)
print(not(a < b))       # Output: False (Inverts the condition)
```

## 4. Assignment Operators: The Value Assigners

These operators assign values to variables and update them! 📈

- `=` : **Assign value**
- `+=` : **Add and assign**
- `-=` : **Subtract and assign**
- `*=` : **Multiply and assign**
- `/=` : **Divide and assign**
- `//=` : **Floor divide and assign**
- `%=` : **Modulus and assign**
- `**=` : **Exponentiate and assign**

### Example:
```python
a = 5
a += 3  # a = a + 3, so a becomes 8
print(a)  # Output: 8
a *= 2  # a = a * 2, so a becomes 16
print(a)  # Output: 16
```

### 5. Bitwise Operators: The Bitwise Brawlers

Bitwise operators allow you to perform operations on bits (binary numbers). 🧑‍💻

- `&` : **Bitwise AND (1 if both bits are 1, else 0)**
- `|` : **Bitwise OR (1 if at least one bit is 1)**
- `^` : **Bitwise XOR (1 if one bit is 1, but not both)**
- `~` : **Bitwise NOT (Inverts the bits)**
- `<<` : **Left Shift (Shifts bits to the left)**
- `>>` : **Right Shift (Shifts bits to the right)**


### Example:
```python
a = 5  # Binary: 0101
b = 3  # Binary: 0011
print(a & b)  # Output: 1 (Binary AND: 0101 & 0011 = 0001)
print(a | b)  # Output: 7 (Binary OR: 0101 | 0011 = 0111)
print(a ^ b)  # Output: 6 (Binary XOR: 0101 ^ 0011 = 0110)
print(~a)     # Output: -6 (Binary NOT: 0101 becomes 1010, negative value)
print(a << 1) # Output: 10 (Left shift: 0101 << 1 = 1010)
print(a >> 1) # Output: 2 (Right shift: 0101 >> 1 = 0010)
```
Bitwise operators work by manipulating the individual bits of binary numbers. Here's a cool breakdown:

- `AND (&)`: 1 if both bits are 1, otherwise 0.
- `OR (|)`: 1 if at least one bit is 1.
- `XOR (^)`: 1 if exactly one of the bits is 1.
- `NOT (~)`: Flips all the bits, changing 1s to 0s and 0s to 1s.
- `Left Shift (<<)`: Shifts all bits to the left, essentially multiplying by 2.
- `Right Shift (>>)`: Shifts all bits to the right, essentially dividing by 2.

### 6. Membership Operators: The "Is It In There?" Checkers

These operators check if a value exists within a container, like a list or string. 🔍

- `in` : **Returns True if the value is found in the iterable**
- `not in` : **Returns True if the value is not found in the iterable**

### Example:
```python
a = [1, 2, 3, 4, 5]
print(3 in a)       # Output: True (3 is in the list)
print(6 not in a)   # Output: True (6 is not in the list)
```

### 7. Identity Operators: The Memory Location Inspectors

These operators check whether two objects are the same object in memory! 🧠

- `is` : **Returns True if both objects refer to the same memory location**
- `is not` : **Returns True if both objects do not refer to the same memory location**

### Example:
```python
a = [1, 2, 3]
b = a
c = [1, 2, 3]
print(a is b)    # Output: True (a and b refer to the same object)
print(a is c)    # Output: False (a and c are different objects)
print(a is not c) # Output: True (a and c are different objects)
```

### 8. Unary Operators: The One-Operand Wonders

Unary operators work on single operands and can either modify the value or return its negation. 🔄

- `+` : **Unary plus (Returns the value itself)**
- `-` : **Unary minus (Negates the value)**
- `not` : **Logical NOT (Inverts the boolean value)**
- `~` : **Bitwise NOT (Inverts all bits)**

### Example:
```python
a = 10
print(+a)  # Output: 10 (Unary plus, no change)
print(-a)  # Output: -10 (Unary minus, negates the value)
print(~a)  # Output: -11 (Bitwise NOT)
```
### 9. Lambda Operators: The Magic Function Makers

Lambda functions are small anonymous functions you can use on the fly. ⚡

- `lambda` : **Creates a function without a name, useful for simple tasks**

### Example:
```python
add = lambda x, y: x + y
print(add(3, 5))  # Output: 8
```

### Summary of Python Operators:
Operator Type	Examples

- `Arithmetic`	+, -, *, /, //, %, **
- `Comparison`	**==, !=, >, <, >=, <=**
- `Logical`	**and, or, not**
- `Assignment`	**=, +=, -=, *=, /=, //=, %=**
- `Bitwise`	**&, `**
- `Membership`	**in, not in**
- `Identity`	**is, is not**
- `Unary`	**+, -, not, ~**
- `Lambda`	**lambda**

