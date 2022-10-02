# React Docs - lists and keys
# what does .map() return?
## return a new array that has the same length of previous array

## If I want to loop through an array and display each value in JSX, how do I do that in React?
# use map(). Each list item needs a unique Key.

## What is the purpose of a key?
# help React identify which items have changed, are added, or are removed.


## The Spread Operator
## What is the spread operator?
# the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

## List 4 things that the spread operator can do.

# spreads the array into separate arguments
# Copying an array ,Concatenating or combining arrays
# Using Math functions
# Using an array as arguments


## Give an example of using the spread operator to combine two arrays. const firstName = [ "o","s","a","m","a"] const lastName = ["m","a","h","e","r"] const fullName = [...firstName,...lastName]


## Give an example of using the spread operator to add a new item to an array.

## const fruits = ['🍏','🍊','🍌'] const juicyFruits = ['🍉', '🍍','🍑' ...fruits] console.log(juicyFruits)

## Give an example of using the spread operator to combine two objects into one.
# const helloObj = {hello: "🙂"} const worldObj = {world: "😇"} const fullSen = {...helloObj, ...worldObj, love: "🥰"}