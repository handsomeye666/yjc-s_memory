# Python Programming Basics

**Date**: 2024-01-10
**Source**: Online Python Course

## Overview

Python is a high-level, interpreted programming language known for its simplicity and readability. Great for beginners and powerful for experts.

## Key Concepts

### Variables and Data Types

```python
# Variables don't need type declaration
name = "John"  # String
age = 25       # Integer
height = 5.9   # Float
is_student = True  # Boolean
```

### Control Flow

```python
# If statements
if age >= 18:
    print("Adult")
else:
    print("Minor")

# Loops
for i in range(5):
    print(i)

while x < 10:
    x += 1
```

### Functions

```python
def greet(name):
    return f"Hello, {name}!"

result = greet("Alice")
print(result)  # Output: Hello, Alice!
```

### Lists and Dictionaries

```python
# Lists (ordered, mutable)
fruits = ["apple", "banana", "orange"]
fruits.append("grape")

# Dictionaries (key-value pairs)
person = {
    "name": "John",
    "age": 25,
    "city": "New York"
}
```

## Practice Exercises

- [x] Write a function to calculate factorial
- [x] Create a simple calculator program
- [ ] Build a to-do list application
- [ ] Practice with list comprehensions

## Resources

- [Python Official Documentation](https://docs.python.org/)
- [Real Python Tutorials](https://realpython.com/)
- [Python for Beginners](https://www.python.org/about/gettingstarted/)

## Next Steps

- Learn about classes and object-oriented programming
- Explore file handling
- Study Python libraries (NumPy, Pandas, etc.)
