+++
title = "Intermediate"
weight = 2
+++

This page provides an overview of **intermediate** skills for working with Python in the context of data analysis.


## External Libraries

- **NumPy**:  Know how to work with arrays, manipulate data, and perform mathematical operations.

- **pandas**: Know how to work with data frames and manipulate data for exploratory data analysis.

- **Matplotlib**: Know how to create customized visualizations for data analysis.

## Data Cleaning

- Merging and joining data frames: Know how to combine data from multiple sources.

- Handling missing data: Know how to identify missing data and impute it using various methods.

- Data normalization and scaling: Know how to standardize data and scale it to compare across different variables.

## Data Analysis

- Descriptive statistics: Know how to calculate basic summary statistics like mean, median, and standard deviation.

- Inferential statistics: Know how to perform hypothesis testing and confidence intervals.

- Regression analysis: Know how to perform linear regression and interpret regression coefficients.

## Workflow and Collaboration

- Version control with Git: Know how to use Git for version control and collaborate with others on code.

- Unit testing and debugging: Know how to write and run unit tests and debug code.

- Code organization and project structure: Know how to structure a Python project for scalability and reproducibility.

## Type Hints

- Type hints: Know how to use type hints in Python to specify function argument types, return types, and class attributes. 

Employing important new features such as type hints shows a deeper understanding of Python and a commitment to writing clean, maintainable, and efficient code. 

By using type hints, developers improve the documentation of their code, 
catch errors more easily, 
and help other developers understand how to use their code.

With the increasing adoption of type hints in the Python community, 
it is becoming an essential intermediate to advanced skill for those
working on larger projects or collaborating with other developers. 

```python
def add_numbers(x: int, y: int) -> int:
    return x + y
```

The type hints are specified using the `: ` syntax, 
where `x: int` means that x is of type int. 
The `-> int` syntax after the function arguments 
specifies the return type of the function as int.

Type hints are not enforced by the Python interpreter, 
but are used by static analysis tools and linters to catch 
type-related errors early in the development process.