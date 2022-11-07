# Automation

## Python Regular Expression:
### expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of
```
import re
```
### The re library in Python provides several functions that make it a skill worth mastering.

## Basic Patterns: Ordinary Characters:
### Examples are :
- 'A', 'a', 'X', '5'.
## Ordinary characters can be used to perform simple exact matches:
```
pattern = r"Cookie"
sequence = "Cookie"
if re.match(pattern, sequence):
    print("Match!")
else: print("Not a match!")
```
## shutil — High-level File Operations
### The shutil module includes high-level file operations such as copying and archiving.
## Copying Files
### copyfile() copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.
```
import glob
import shutil

print('BEFORE:', glob.glob('shutil_copyfile.*'))

shutil.copyfile('shutil_copyfile.py', 'shutil_copyfile.py.copy')

print('AFTER:', glob.glob('shutil_copyfile.*'))
```



