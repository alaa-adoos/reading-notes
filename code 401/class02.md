# Tests
## Unit tests and TDD
### Unit tests: are some pieces of code to exercise the input, the output and the behaviour of your code

### with TDD we need to think about tests first

### what is the AAA?
- Arrange: you need to organize the data needed to execute that piece of code (input);
- Act: here you will execute the code being tested (exercise the behaviour);
- Assert: after executing the code, you will check if the result (output) is the same as you were expecting.

### The Cycle: made by three steps
- Write a unit test and make it fail
- Write the feature and make the test pass!
- Refactor the code


#  if __name__ == “__main__”: do?

### If the python interpreter is running that module (the source file) as the main program, it sets the special __name__ variable to have a value “__main__”.

### If this file is being imported from another module, __name__ will be set to the module’s name.
## Advantages : 
- Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions

- If you import this script as a module in another script, the __name__ is set to the name of the script/module

- Python files can act as either reusable modules, or as standalone programs

- is used to execute some code only if the file was run directly, and not imported.

# Recursion 
### The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function

## Need of Recursion
### Recursion is an amazing technique with the help of which we can reduce the length of our code and make it easier to read and write.

## Properties of Recursion:
- Performing the same operations multiple times with different inputs.

- In every step, we try smaller inputs to make 
the problem smaller.

- Base condition is needed to stop the recursion otherwise infinite loop will occur.