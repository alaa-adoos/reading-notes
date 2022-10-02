# Big O Notation
## a way to measure an algorithm's efficiency It helps you determine when your algorithm is getting faster or slower
- O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.
- O(n) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set.
- O(n²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set.
- O(2^n) denotes an algorithm whose growth doubles with each addition to the input data set.



# Python names and values


## A variable allows you to store a value by assigning it to a name,To assign a variable, use one equals sign

~~ x=10 ~~

# Variable Names
## Certain restrictions apply in regard to the characters that may be used in Python variable names. The only characters that are allowed are letters, numbers, and underscores. Also, they can't start with numbers. Not following these rules results in errors.

## Variables can be reassigned as many times as you want, in order to change their value. In Python, variables don't have specific types, so you can assign a string to a variable, and later assign an integer to the same variable.


# Awesome Python Environment
## Coding in Python is awesome and is getting more awesome with every new release!
### available libraries, its readability, and the recently introduced type annotations.

# list of python environment
# 1)The Interpreter:
- Pyenv is a set of three tools,  that are pyenv (used to install python) and pyenv-virtualenv (used to configure your global tools)

## to install a python interpreter:

### pyenv install VERSION_YOU_WOULD_LIKE_TO_INSTALL

## to  list out all versions available via pyenv
### pyenv install --list

# 2)Consistent Formatting and Readability
## ensures readability and understandability.
## use Black
### Black is a tool for python that allows you to focus on what is necessary, the content
### to add black:
### poetry add --dev black=19.3b0

# 3)Type-Correctness
## type annotations are part of the standard library
## your code becomes better to understand, maintain, and less prone to errors
## use mypy!
### Mypy is a static type checker for python code, that finds errors before they appear
### to add mypy!
### poetry add --dev mypy

------

# Python 3 Module of the Week

## PyMOTW-3 is a series of articles o demonstrate how to use the modules of the Python 3 standard library.

## version of Python and tools used:
### Text:
- string — Text Constants and Templates:
### Functions:
#### capwords() capitalizes all of the words in a string.
#### split(), capitalizing the words in the resulting list,
#### join() to combine the results.
- Data Structures
### enum – Enumeration Type:defines an enumeration type with iteration and comparison capabilities
###  Iteration:Iterating over the enum class produces the individual members of the enumeration.

- The File System:
###  Purpose:	Parse, build, test, and otherwise work on filenames and paths.

