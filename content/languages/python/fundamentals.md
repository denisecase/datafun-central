+++
tags = ["python"]
title = "Python: Fundamentals"
+++

Here is a quick summary of some basic concepts to get started programming with Python.

## Human Languages

Python introductions are available in many human languages. See https://wiki.python.org/moin/Languages for more.

## Syntax
Python has a simple and consistent syntax which makes it easy to learn and read. 

**Indentation** is used to indicate a block of code, as opposed to curly braces or keywords like 'begin' and 'end' in other languages. 

Indentation matters! (a tab is not the same as spaces)

## Comments 

Comments are denoted by the hashtag or pound sign (`#`). 
Any text that follows the hashtag on the same line is c
onsidered a comment and is ignored by the Python interpreter. 
Comments can be used to provide additional information 
about the code or to temporarily disable 
parts of the code during development or testing.

## Variables

Variables are used to store values, like numbers or text strings. 
In Python, you can create a variable by assigning a value to it, like this:

```python
x = 5
```

## Data Types

Python has several built-in data types, including integers (whole numbers), floating point numbers, and strings (text). For example:

```python
x = 5         # an integer
y = 3.14      # a floating-point number
z = "hello"   # a string
```

## Basic Operations

Python supports basic mathematical operations like addition, subtraction, multiplication and division, use the following signs +, - , * , / respectively:

```python
x = 5
y = 3
print(x + y)   # prints 8
```

## Conditional Statements

Conditional statements allow you to check if certain conditions are true, and then run different code depending on the result. In Python, `elif` is used as the keyword for "else if". For example:

```python 
x = 5
if x > 0:
    print("x is positive")
elif x ==0:
    print("x is zero")
else:
    print("x is negative")
```

## Functions

Functions are blocks of code that can be reused throughout your program. They can take input values called parameters, and return one or more output values. For example:

```python 
def double(x):
    return x * 2

result = double(5)
print(result)  # prints 10
```

## Loops

Loops are used to repeat a block of code multiple times. Python has two types of loops: for loops and while loops. For example:

```python
for i in range(5):
    print(i) # will print 0, 1, 2, 3, 4

```

```python
x = 0
while x < 5:
    print(x)
    x += 1

```

## How To Learn

The best way to learn is by doing - experiment, type code, and build personal projects to gain skills. This is the only course in the program where we work through all the foundational topics. Other courses will jump right in to Python programming by example. It's best to take this course early in the program and master these basics early.

## Big Wins

Reddit comment on suggested "big wins in Python" - when you see these, know they're considered pretty useful skills. 

https://www.reddit.com/r/learnpython/comments/10ka2dm/comment/j5pciik/

- extended libraries (e.g. pandas, NumPy)
- context managers (with open() as file:)
- lambda functions, zip(), map(), filter(), enumerate()
- comprehensions (concise and very impressive/useful)
- regular expressions
- sorting (faker is pretty useful, too)
- type-hinting - easy and recommended!  No more wondering if x is a string or an int - make it so!  This is pretty new and valuable skill. It looks a lot like [Swift](https://docs.swift.org/swift-book/LanguageGuide/Functions.html).

