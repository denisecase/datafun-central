+++
tags = ["python"]
title = "Python: Organization"
+++
This page provides an overview of the fundamental building blocks of Python code organization.

### Variable

A variable is a named memory location that holds a value.

### Expression

An expression is a combination of operators (e.g. +) and operands (e.g. 1 or age) that resolves to a value.

### Statement

A statement is the smallest unit of a Python script. All scripts are made up of statements. Some statements are expressions, while others are not (e.g. print("hello")).

### Function

A function is a reusable block of code that performs a specific task. Functions help to break up large programs into smaller, more manageable pieces, and can be reused across different parts of a program or across different programs.

### Class

A class is a blueprint for creating objects in Python. Classes define the attributes (data fields) and methods (functions) that all objects of a certain type will have. Using classes, we can create multiple instances (objects) of a certain type, each with their own unique attributes.

In Python, classes are optional, but many modules use an object-oriented approach to organizing code. 

### Object

An object is a specific instance of a class that holds real data. For example, if we have a `Dog` class, we can create two objects, `sam = Dog("Sam", 3)` and `fido = Dog("Fido", 4)`, each with their own name and age attributes.

### File / Module

In Python, a module is a file containing Python definitions and statements. Each .py file is a Python script and, by definition, a Python file is also a module. The name of the module is the same as the name of the file, without the .py extension.

### Package

A package is a way of organizing related modules together. 
Packages allow us to group together related functionality 
in a way that is easy to import and use. 
A package is simply a directory that contains one or more Python modules.

### Library

A library is a collection of packages and modules that 
provides a set of pre-written code for specific tasks. 
For example, the Python Standard Library is a large collection of libraries 
that are included with Python and provide a wide range of functionality, f
rom file input/output to regular expressions to networking.

## Python Distribution Methods

Python also has some special entities related to 
distributing Python code to users.

## Python Distributions

A **distribution** is a bundle of Python software, 
which typically includes the Python interpreter, 
the Python standard library, 
and various additional packages and tools.

There are several popular Python distributions available, 
such as Anaconda, which includes many data science packages and tools, 
and Python(x,y), which is geared towards scientific computing.

Python distributions can make it easier to set up and manage 
a Python environment, especially for beginners, 
and come with many pre-installed packages and tools.

## Python Wheels

A **wheel** is a self-contained installation executable that can be used to 
easily distribute and install Python packages across different systems.

Wheels are different from source distributions or packages, 
which are typically distributed as source code and 
must be compiled or built before they can be installed.

A wheel is essentially a ZIP archive that contains the files and dependencies 
necessary for a Python package to be installed on a system. 
It makes installation faster and easier, as the package does not need 
to be built from source code each time it is installed on a new system.

Wheels are platform-specific, 
meaning that a wheel built on one operating system or architecture 
may not work on another system with a different operating system or 
architecture. 
To address this, Python has a system of tags to identify which platforms 
a wheel is compatible with, 
so the correct version of the wheel 
can be downloaded and installed on each system.

## Understanding Organization

Understanding the fundamental building blocks of Python organization 
and distribution 
is essential for employing available Python tools and 
writing clean, well-structured code that is 
easy to read, maintain, and reuse.
