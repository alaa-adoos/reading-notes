# **Big O Notation**
## Big O notation is used in Computer Science to describe the performance or complexity of an algorithm. 

- **O(1)  describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set**


- **O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set**


- **O(N²) presents an algorithm whose performance is directly proportional to the square of the size of the input data set**



- **O(2^N)    denotes an algorithm whose growth doubles with each addition to the input data set.** 


## **Binary search**
### is a technique used to search sorted data sets. It works by selecting the middle element of the data set, essentially the median, and compares it against a target value. If the values match, it will return success. If the target value is higher than the value of the probe element, it will take the upper half of the data set and perform the same operation against it. Likewise, if the target value is lower than the value of the probe element, it will perform the operation against the lower half. It will continue to halve the data set with each iteration until the value has been found or until it can no longer split the data set.
