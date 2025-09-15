# Python Practice for refresh 

## Day 1: Python installation

```
https://www.python.org/downloads/
```

## Python Indentation

- Indentation refers to the spaces at the beginning of a code line.
- Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.
- Python uses indentation to indicate a block of code.

```
if 10 > 6:
    print('Ten is greater than six')
```

- Output
```
Ten is greater than six

```

## Day 2: A basic program to print a message

- Write the basic code in sample.py
```  
  vim sample.py
  print ("Hellow World!")
```
- Then execute the python script to know the output
```
- $ python sample.py

    Hellow World!
```
```
- Function is a set of tasks that can be done. We need to call functions. There are several functions in Python like the print() function.
- Round brackets are used with a function to pass a parameter in it.
- We can define our own functions as well.
```


## Day 3: A basic python program for operators and printer (addition, subtraction, devide & multiplication)

- We do addition, subtraction and multiplication with integer values, and then it gives us answers also in integer data type.
- But when performing division with integer values then it gives us an answer in float data type.
- Float stands for Floating Point Representation.

- Addition 
```
2+3
```
 Output 

```
5
```

- Subtraction 
```
9-5
```
 Output 

```
4
```
- Devide

```
5/2
```
 Output 

```
# Floating number
2.5 
```


- If you want to get only the quotient part or the integer part of the answer and want to neglect the decimal value, it can be done with the help of (//).
- // (double slash) is used for division when you want to return only an integer value in the answer.
- // is also called Integer Division or Floor Division.
- Devide


```

5//2
```
 Output 

```
#integer
2
```
- Multiplication

```
2*2
```
 Output 

```
4
```

- How to square a number in Python, you can use the ** Operator?
- Double asterisks (**) is used to find the power of a number. 
        number ** power =  2**2 = 2*2

```
2**2

```
 Output

```
4
```

- In Python, int and float are two distinct numeric data types used to represent different kinds of numbers.
  
**1. Definition:**
**int (Integer):**
Represents whole numbers, both positive and negative, without any fractional or decimal part. Examples include 5, -10, 0, 1000.

**float (Floating-Point Number):**
Represents real numbers that can have a fractional or decimal part. Examples include 3.14, -0.5, 1.0, 2.718


- To get the remainder, we use the modulus operator (%).

```
10%3
```
 Output 

```
1
```

- Concatenation is used to combine two things like we can convert two strings into one using concatenation.
- Concatenation is done using the (+) operator.
  Ex: 'nani' + 'nani'

- Repetition is used to print a single value multiple times like we can print a string like "nani" multiple times.
- Repetition is done using the (*) operator.
  Ex:  'nani ' * 5


- (\n) has a special meaning in Python. It is used to enter a new line.
- To print the original string or to neglect the meaning of \n, we have to use a Raw String.
- Raw string is a string that returns it as it is without making any changes to it. 
- We have to specify (r) before the quote to print the same string that is present inside the quotes.


## Day 4: A basic variable in python

- Variable in python:

Variable: It is a container where we can put our value



## Day 5: Built-in Data Types

In programming, data type is an important concept.

Variables can store data of different types, and different types can do different things.

Python has the following data types built-in by default, in these categories:

```
Text Type:	str
Numeric Types: int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview
None Type:	NoneType

```

