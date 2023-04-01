+++
tags = ["python"]
title = "Python: Basics"
weight = 10
+++


Python is a popular high-level programming language that is
easy to learn and widely used in data analysis,
machine learning, web development, and many other fields.

## Defining Variables

In Python,
we can define a variable and assign a value to it using the "=" operator.
For example:

```
x = 10
```

Here, we've defined a variable x and assigned it the value of 10.

## Performing Operations

We can also perform mathematical operations on variables:

```
y = 5
z = x + y
```

Here, we've defined a variable y and added it to x to create a new variable z.

## Expressions

Expressions are combinations of operators and operands that can be evaluated to produce a value.

Python allows us to use expressions to perform operations on variables.
For example:

```python
a = 2
b = 3
c = a * b + 1
```

Here, we've defined three variables: a, b, and c.
We've used the * operator to multiply a and b, and then added 1 to the result.

Expressions can also include functions:

```
import math
d = math.sqrt(a**2 + b**2)
```

Here, we've imported the math module and used the sqrt() function to calculate the square root of a^2 + b^2.

```python
product = x * y
quotient = x / y

# Print statements
print("x =", x)
print("y =", y)
print("x + y =", sum)
print("x - y =", difference)
print("x * y =", product)
print("x / y =", quotient)
```


```python
x = 10
y = 5
z = x + y
print(z)
```

This code will create two variables, x and y, assign them the values 10 and 5, respectively, and then add them together to create a new variable z with the value 15. Finally, the code prints the value of z.

## Statements

In Python, a **statement** is a line of code that performs an action or task.

Statements are the smallest unit of code that can be executed and
they represent an action or command.
Each statement performs a specific task, such as defining a variable,
calling a function, or creating a loop.

```python
x = 10
print("Hello, world!")
def add_numbers(a, b):
    return a + b
```

In the above example, the first line (x = 10) is a statement
that assigns the value 10 to the variable x.
The second line (print("Hello, world!")) is a statement
that prints the message "Hello, world!" to the console.
The third line defines a function add_numbers that takes two
arguments and returns their sum.

## Statements vs Expressions

Some expressions can be statements,
such as an assignment expression,
which assigns a value to a variable.

However, not all statements are expressions.
For example, a print statement does not evaluate to a value and cannot be used as part of an expression.

## Script

A Python script is simply a collection of statements
executed in order to achieve a desired outcome.

