+++
title = "Python Tools"
+++

When you first install Python, you have access to the Standard Library. 

However, to expand your capabilities and work with various Python projects, 
you want to install additional packages and dependencies.

Python offers a range of tools that make it easy to install, manage, 
and maintain these packages and dependencies.

We introduce just some of the popular tools along with recommendations for new
personal projects. 

## Recommanded Approach

Since our goal is to get you started quickly, here's the recommended way
to help maximize these benefits from the beginning. 

In each new project, create a pyproject.toml file that's configured to use the 
following tools. We provide an example file that you can customize. 

Don't get too attached to preferences - each workplace will likely have their
own standard set of preferred tools and processes. 

### ⭐ Configure with pyproject.toml ⭐

Use Pyproject.toml for configuration. 
It can help remind us to set our virtual environment,
 install our dependencies, 
 and format and lint our files for correctness and ease of use.

The pyproject.toml file can be used to configure these recommended tools. 

- build-system: Hatch is a dependency management tool that can be used to publish Python packages to PyPI. Hatchling is a build backend for Hatch that is used to build packages. Both tools use the pyproject.toml file to configure the package's metadata and dependencies.

- tool.black: Black is a Python code formatter that uses a pyproject.toml file to configure its behavior. You can specify options such as line length and whether to use single or double quotes in the pyproject.toml file.

- tool.pyright: Pyright is a static type checker for Python that can use a pyproject.toml file to configure its behavior. You can specify options such as which files to include or exclude from type checking, and which Python version to use in the pyproject.toml file.

- tool.ruff: Ruff is a Python build tool that uses a pyproject.toml file to specify tasks and dependencies for your project. You can define tasks such as building documentation or running tests, and specify the dependencies required for each task 
in the tools.ruff section of the 
[pyproject.toml](https://beta.ruff.rs/docs/configuration/#using-pyprojecttoml) file.

## Package Managers 

Package managers allow you to fetch and install packages from the 
internet into your Python environment. Two widely used package managers in Python are pip and conda.

### ⭐ pip ⭐

pip is the default package manager for Python and makes it easy to 
install, update, and manage Python packages and dependencies. 
It is an essential tool for working with Python projects.

### conda

conda is another popular package manager for Python, 
often used with the Anaconda or Miniconda distributions. 
It can be used alongside or as an alternative to pip.

## Environment Managers

Python projects often require different versions of Python and different 
packages, making it essential to maintain and activate different environments 
as we work. Python offers two environment managers: venv and conda.

### ⭐ venv ⭐

venv is the default environment manager for Python and allows you 
to create and manage virtual environments within a Python project.

### conda

conda can also be used as an environment manager in addition to its role 
as a package manager. 
It automatically activates a base environment upon installation and 
allows you to create and manage other environments as needed.

## Python Formatters

Formatters are tools that help ensure consistent 
and readable code by automatically formatting 
Python code according to predefined styles and standards.

Many work environments will specify the tools and formats they prefer. 
Some may automatically apply formatting rules when 
code is pushed to a repository. 
The following recommendations are for personal projects.

### ⭐ Format with black ⭐

Black is a popular and highly-regarded Python formatter that aims 
to provide a simple and opinionated approach to code formatting. 
It reformats entire files in place, making it easy to integrate 
into automated workflows.

### isort

Isort is a Python library and command-line tool that helps e
nsure Python imports are properly sorted and formatted. 
It can automatically group imports by type and 
optimize the order of imports to reduce conflicts and improve readability.
The Ruff linter includes isort functionality. 

## Python Linters

Linters are tools that analyze code and report on potential errors, 
style violations, and other issues. 
These tools help ensure that code is well-written, maintainable, 
and conforms to best practices.

### ⭐ Lint with Ruff ⭐

A new Python linter, Ruff, is gaining popularity. 
Ruff is a Rust-powered linter that aims to be faster 
and more reliable than traditional linters like Pylint and Flake8. 
It uses a Rust library called syntect for syntax highlighting 
and parsing, and leverages Rust's memory safety and concurrency 
features to provide a faster and more reliable analysis.

Ruff offers several features 
that make it a promising option for Python developers, 
including integration with editors like VS Code, 
support for custom rule sets, and an easy-to-use command-line interface.

Ruff is configured using the standard pyproject.toml file and includes isort
functionality. 

## Python Type Checkers

Type checkers are tools that analyze your code and attempt 
to find type-related errors before code runs. 
This helps catch errors earlier in the development process 
and can improve the overall quality of your code.

### ⭐ Typecheck with Pyright  ⭐

Pyright is a popular type-checking tool for Python 
that uses static analysis to identify type-related 
errors in your code. 
Pyright supports Python 3.6 and above, 
and can be used in a variety of development environments, 
including VS Code and other editors.

When used in VS Code, Pyright provides real-time feedback 
and suggestions as you code, 
helping you catch errors and improve the overall quality of your code. 
Pyright also supports type annotations, allowing you to provide 
additional information about the types of variables and 
function arguments in your code.

## Package Development and Distribution

### ⭐ Hatch and Hatchling ⭐

Hatch is a command-line tool for managing dependencies and environment isolation for Python developers. It allows developers to easily configure, version, specify dependencies for, and publish packages to PyPI. Hatch can be used to create new Python packages, add dependencies, and manage virtual environments.

Hatchling is a build backend for Hatch that is used to build Python packages. It provides a simple, declarative configuration file format that allows developers to specify the dependencies, entry points, and other package metadata. Hatchling can be used to build packages in different formats, including source distributions and wheels, and to upload them to PyPI or other package repositories.

### Setuptools

Setuptools is a package development and distribution tool for Python 
that provides features such as package metadata, package installation, 
and dependency management. 
Setuptools is widely used and integrates with many other Python tools 
and frameworks, making it a popular choice for package 
development and distribution.

### Flit

Flit is a lightweight tool for building and publishing Python packages. 
Flit provides features such as dependency management, 
virtual environments, and metadata management, 
and is designed to be simple and easy to use. 
Flit also supports building wheels for distribution,
 making it a good choice for creating packages that can be easily 
 installed on different systems.

## Python Build Tools

Using a build tool or command line runner in Python 
can help new analysts and developers automate repetitive tasks, 
streamline their workflow, and avoid having to retype complex commands. 

There are several build tools available for Python projects that help 
automate the build process and manage dependencies. 

### Make

One such tool is [Make](https://en.wikipedia.org/wiki/Make_(software)), 
an older and widely used 
build tool that automates the building and testing of software. 
It is a powerful and flexible tool that can be used 
to manage complex build processes with many dependencies.

### ⭐ Build with Just ⭐

Another popular tool is [Just](https://github.com/casey/just), 
a newer command runner written in Rust. 
It uses a simple YAML configuration file called justfile.yaml 
to define tasks and their dependencies, 
and is designed to be fast and easy to use. 
Just is particularly useful for smaller projects 
that don't require a full-fledged build system.
