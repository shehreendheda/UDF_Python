# User-Defined Functions in Python

Functions are blocks of code that can be called when needed, take in arguments, and return outputs. Python has built-in functions and user-defined functions. In this module, you will learn how to create user-defined functions in Python. The module consists of a video lesson that provides an overview of the syntax and code block of user-defined functions followed by a hands-on lab that walks you through steps to define a function

Prerequisite Knowledge: A basic understanding of data types, variables, operators, conditionals, and for loops in Python.

Note: This module does not cover arbitary arguments in functions.

## User-Defined Functions - Getting Started

<center><iframe width="700" height="531" src="https://www.youtube.com/embed/Zi7sStdRkCw?rel=0" frameborder="1" allowfullscreen></iframe></center>

### Recap:
In the video lesson, you learn about the syntax and code block of user-defined functions. 

1.	The `def` keyword is used at the start of the function definition.
2.	The function is given a unique name followed by parentheses and a colon `def myfunction():`
3.	Positional and optional parameters are listed in the parentheses. `def myfunction(a,b=3):`
4.	The code block is started on a new line and is indented by 4 spaces. The code block can include
a.	Variable assignments
b.	Operators
c.	Conditionals
d.	For loops
e.	Functions- built-in and UDFs
f.	And more
5.	The code block is ended with the return keyword followed by any output value to the stored and the semi-colon `return … ;`
6.	To call the function once it is defined, use the name and parentheses with positional and any desired) optional arguments `myfunction(2)`.

Let's create a user-defined function!

## Hands-on Lab

The following hands-on lab will walk you through creating a function that calculates and returns the sum of squares of a list of integers and checks if the sum is even or odd.

<iframe width="951" height="721" src="https://www.katacoda.com/embed/sdheda/udf_python" frameborder="0" allowfullscreen></iframe>
