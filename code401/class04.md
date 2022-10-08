# **Reading and Writing Files in Python**

## Files on most modern file systems are composed of three main parts:
- Header: metadata about the contents of the file (file name, size, type, and so on)

- Data: contents of the file as written by the creator or editor

- End of file (EOF): special character that indicates the end of the file

## **File Paths**
### The file path is a string that represents the location of a file
- Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)

- File Name: the actual name of the file

- Extension: the end of the file path pre-pended with a period (.) used to indicate the file type

## **Opening and Closing a File in Python**
**file = open('dog_breeds.txt')**

**file.close()**

| Character | Meaning|
| --- | ----------- |
| 'r'| Open for reading (default)|
| 'w'|Open for writing, truncating (overwriting) the file first |
| 'rb' or 'wb'   | Open in binary mode (read/write using byte  data) |



# **Python Exception**
#### an error can be a syntax error or an exception
- Syntax errors occur when the parser detects an incorrect statement

- exception error. This type of error occurs whenever syntactically correct Python code results in an error

## **Raising an Exception**
#### use raise to throw an exception if a condition occur

## **The AssertionError Exception**
#### assert that a certain condition is met. If this condition turns out to be True, then that is excellent! The program can continue. If the condition turns out to be False, you can have the program throw an AssertionError exception.

## **The try and except Block: Handling Exceptions**
#### The try and except block in Python is used to catch and handle exceptions. Python executes code following the try statement as a “normal” part of the program. The code that follows the except statement is the program’s response to any exceptions in the preceding try clause.
