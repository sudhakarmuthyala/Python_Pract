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

## Day 6: Types of operators in Python:
1. Arithmetic operators
2. Assignment operators
3. Relational operators
4. Logical operators
5. Unary operators
Arithmetic operators are used to perform mathematical operations like addition, subtraction, multiplication, division, etc.
Assignment operation is performed with the help of equal to(=), in which we can assign a value to the variable.
We can also do the assignment by short-hand which means performing an arithmetic operation and then assigning the value both at the same time.
We can also assign the values in one line for two variables.
 a,b = 5,6
Unary operator takes a single operand in an expression or a statement.
Comparison can be performed with the help of relational operators.
Comparison operators return a boolean value or True or False.

#2
If you want to combine two or more conditions and then check the relation between them, then logical operators are used.
Logical operators include And, Or and Not.
Logical operators follow the truth table for And,  Or, and Not operators.
And the operator returns True when both conditions are true otherwise returns False. 
Or the operator returns True when any of the conditions or both the conditions are True otherwise it returns False.
Not the operator reverses the value of the output.

Github :- https://github.com/navinreddy20/Python-

## Day 7: Number system in Python
In programming, the number system is a way of representing numbers using different bases.
The most commonly used number systems in programming are the decimal (base 10), 
binary (base 2), octal (base 8), and hexadecimal (base 16) systems.

a)Decimal system: This is the number system we use in our everyday lives. It uses 10 digits (0-9) 
to represent numbers.

b)Binary system: This system uses only two digits (0 and 1) to represent numbers. It is commonly 
used in computer systems because digital devices work with binary signals.

c)Octal system: This system uses 8 digits (0-7) to represent numbers. It's often used in computer programming 
because it's a compact way to represent binary numbers.

d)Hexadecimal system: This system uses 16 digits (0-9 and A-F) to represent numbers. It's commonly used in computer programming 
and web development to represent colors and memory addresses.

Converting  different number systems:

Decimal to binary: Divide the decimal number by 2 and write down the remainder. Keep dividing by 2 and writing down the remainders until 
you get to 0 at quotient. Then, read the remainders in reverse order to get the binary number.
e.g 51
    2|51 |1
    2|25 |1
    2|12 |0
    2|6  |0
    2|3  |1
    2|1  |1
     |0  |1
reverse order: 110011
Binary to decimal: Multiply each digit in the binary number by the corresponding power of 2 
(starting with 2^0 on the right). Add up the results to get the decimal number.

e.g 11011
    2^4 2^3 2^2 2^1 2^0
    1*16 1*8 0*4 1*2 1*1
    16+8+0+2+1=27
It is Same for octal and hexadecimal(Not in this lecture but for your knowledge)

Decimal to octal: Divide the decimal number by 8 and write down the remainder. Keep dividing by 8 and 
writing down the remainders until you get to 0. Then, read the remainders in reverse order to get the 
octal number.
e.g 
    51
    8|51 |3
    8|6  |6
    8|0  |0
    reverse order: 360
Octal to decimal: Multiply each digit in the octal number by the corresponding power of 8 (starting with 8^0 on the right). 
Add up the results to get the decimal number.
e.g 
    360
    8^2 8^1 8^0
    3*64 6*8 0*1
    192+48+0=240

Decimal to hexadecimal: Divide the decimal number by 16 and write down the remainder. If the remainder is 
greater than 9, replace it with the corresponding letter (A-F). Keep dividing by 16 and writing down the remainders 
until you get to 0. Then, read the remainders in reverse order to get the hexadecimal number.
e.g 
    51
    16|51 |3
    16|3  |3
    16|0  |0
    reverse order: 33

Hexadecimal to decimal: Multiply each digit in the hexadecimal number by the corresponding power of 16 (starting with 16^0 on the right). 
If a digit is a letter, replace it with the corresponding value (A=10, B=11, etc.). Add up the results to get the decimal number.
e.g 
    33
    16^1 16^0
    3*16 3*1
    48+3=51


Converting from octal to binary and binary to octal can be done using a simple method.
Conversion from Octal to Binary:

To convert an octal number to binary, we can simply replace each digit in the octal number with its equivalent three-digit binary number. 
Here are the octal-to-binary conversions for each octal digit:
0 = 000
1 = 001
2 = 010
3 = 011
4 = 100
5 = 101
6 = 110
7 = 111
For example, to convert the octal number 725 to binary:
7 = 111
2 = 010
5 = 101
So, 725 in octal is equivalent to 111010101 in binary.
Conversion from Binary to Octal:
To convert a binary number to octal, you can group the binary digits into sets of three (starting from the right) 
and replace each set with its equivalent octal digit. Here are the binary-to-octal conversions for each set of three binary digits:
000 = 0
001 = 1
010 = 2
011 = 3
100 = 4
101 = 5
110 = 6
111 = 7
For example, to convert the binary number 101011011 to octal:
1 0 1   0 1 1    0 1 1
|- - - ||- - - | |- - - |
 5       3        3
we get 533 in octal.

Use of method in python to direclty convert number system:
Decimal to binary: bin()
e.g 
    bin(51)
    '0b110011' # 0b represent binary formate
binary to decimal: int()
e.g 
    int('0b110011',2)
    51

Decimal to octal: oct()
e.g 
    oct(51)
    '0o63'  # 0o represent octal formate
octal to decimal: int()
e.g 
    int('0o63',8)
    51

Decimal to hexadecimal: hex()
e.g 
    hex(51)
    '0x33'  # 0x represent hexadecimal formate
hexadecimal to decimal: int()
e.g 
    int('0x33',16)
    51

