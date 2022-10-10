# **Classes and Objects**

## what is the different between objcet and classes
|Object|Classs|
|---| ----------- |
|Object is an instance of a class|Class is a blueprint or template from which objects are created.|
|Object is a real world entity such as pen|Class is a group of similar objects.|
|Object is created many times as per requirement|Class is declared once|


## **example ↩**
```
class MyClass:
    variable = "I love python"

    def function(self):
     print("This is a message inside the class.")
myobjectx = MyClass()

print(myobjectx.variable) #output:I love python
```

## **init() function**
### is a special function that is called when the class is being initiated. It's used for assigning values in a class.

## **example ↩**
```
class NumberHolder:

   def __init__(self, number): 
       self.number = number

   def returnNumber(self):
       return self.number

var = NumberHolder(7)
print(var.returnNumber()) #Prints '7'

```

# **Thinking Recursively in Python**
![GreenRoots Blog](https://miro.medium.com/max/640/1*__jhoWXEa_INM44V5jx30w.jpeg)

###  A recursive function is a function defined in terms of itself via self-referential expressions


### All recursive functions share a common structure made up of two parts: base case and recursive case

## **example ↩**

```
def factorial_recursive(n):
    # Base case: 1! = 1
    if n == 1:
        return 1

    # Recursive case: n! = n * (n-1)!
    else:
        return n * factorial_recursive(n-1)
factorial_recursive(5) # print 125    
 ```
 # **pytest: Fixtures and Coverage**

 ## **Fixtures**:
 ### you define fixtures using a combination of the  ```pytest.fixture ```
 ### rather than defining global variables in your test file, you can create a fixture that'll provide your test with the appropriate object at the right time.

## **example ↩** 
```
@pytest.fixture
def simple_file():
   return StringIO('\n'.join(['abc', 'def', 'ghi', 'jkl']))
```
## **Coverage**
###  give you a greater degree of confidence in the code and the fact that it has been run at least on
### how can you include code coverage with pytest? 
```
pytest --cov=mymul .
```
