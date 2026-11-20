## Variables
Variables are used to store data in a program. Think of them as algebraic **variables** but for programming; they are a letter or word that has a value assigned to it. They are entered by the user or created as the result of a calculation.

Variables should have **meaningful variable names** so other programmers can understand what is stored in it and what it is being used for, e.g.
```
testScore = int(input())
# not
x = int(input())
```

## Data types

Every variable must have a data type; different data types must be used to store different kinds of data.

##### Char
Used to store a single character. e.g. 'T'

##### String
Used to store a **string** of characters e.g. "Brenden", "Red"

##### Integer 
Used to store a positive or negative whole number e.g. 12, -1234567890

##### Real
Used to store a positive or negative decimal number e.g. 45.23445435, 3.14159265

##### Boolean
Used to store a two-state variable. Can store either TRUE or FALSE


## Arrays

An array is a variable with multiple values in it. Like a variable, an array can be of any data type e.g. (Edinburgh, Dundee, Perth, Glasgow) or (1, 45, 34, 23, 55, 100). You can only have one type of data in each array. Each value in an array is called an element. You refer to the individual elements of the array using the array name and the **index** (0-indexed in most languages) e.g. to get the third city in the **cities** array you would use:
```
cities[2]
```
---
- **Subject map:** [[Computing|Computing]]