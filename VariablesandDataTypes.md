## Python Learning Labs

Welcome to my Python Learning Labs repository! This repository contains code examples and exercises to help you learn Python and understand its basic concepts, such as variables, data types, and more.

## Lab 1: Exploring Python Variables and Data Types

In this lab, we explore different Python data types and print their values and types.

### Code

```python
# Printing out the Hello World
print('Hello World!,','Python Variables')
print("=========================")

# Declaring Numeric Types
my_integer = 10 # -12
my_float = 3.14
my_complex_number = 2 + 3j
my_list = [1, 2, 3, 4, 5]
my_tuple = (1, 2, 3)
my_range = range(5)
my_string = "Hello, World!"
my_dict = {"name": "Alice", "age": 25}
my_set = {1, 2, 3, 4}
my_frozenset = frozenset([1, 2, 3])
is_active = True
my_bytes = b"Hello"
my_bytearray = bytearray([65, 66, 67])
my_memoryview = memoryview(b"Hello")
x = None

# Printing out the Variables and it's Type classes
print(my_integer)
print(type(my_integer))
print(type(my_float))
print(type(my_complex_number))
print(type(my_list))
print(type(my_tuple))
print(type(my_range))
print(type(my_string))
print(type(my_dict))
print(type(my_set))
print(type(my_frozenset))
print(type(is_active))
print(type(my_bytes))
print(type(my_bytearray))
print(type(my_memoryview ))
print(type(x))
print("=========================")

'''
This is a multi-line comment in Python
'''
```


## Output
```
Hello World!, Python Variables
=========================
10
<class 'int'>
<class 'float'>
<class 'complex'>
<class 'list'>
<class 'tuple'>
<class 'range'>
<class 'str'>
<class 'dict'>
<class 'set'>
<class 'frozenset'>
<class 'bool'>
<class 'bytes'>
<class 'bytearray'>
<class 'memoryview'>
<class 'NoneType'>
=========================
```
