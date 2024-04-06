# Python for Data Analyst - Week 1

## What is Python?
Python is a computer programming language often used to build websites and software, automate tasks, and analyze data. Python is a general-purpose language, not specialized for any specific problems, and used to create various programmes.

## Python Data Types
an attribute associated with a piece of data that tells a computer system how to interpret its value. Understanding data types ensures that data is collected in the preferred format and the value of each property is as expected.
The following are the standard or built-in data types in Python:
### 1. Numeric
#### - Integer
To process integer data, it may be necessary to utilize mathematical operations such as addition, subtraction, division, multiplication, and various others.

![[integer]](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/8d83a638-1a3d-4f2e-9e5f-1c097329a8e4)

#### - Float 
The float data type will be closely related to numeric data in the form of fractions or decimals. In processing this data, we can also utilize math operations.

![Screenshot (686)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/5ae06108-2098-4431-9ef2-82e6799130dd)

#### - Complex
Expressing pairs of real and imaginary numbers

![Screenshot (687)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/e303a320-c8a4-453c-82f8-0979118b2f9d)

### 2. String
String data type is also called text data type, this data type is used to store text. String data must be enclosed in quotes, either single quotes (' ') or double quotes ("  ") after the equal character (=).

![Screenshot (688)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/35cbd99e-28ef-43c3-b4ae-da70e9352687)

### 3. Boolean
The boolean data type only stores two values; True and False. True values represent true statements, and False values represent false statements.

![Screenshot (689)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/d5474a4e-2262-482b-b03d-4612d20c986f)

## Python Data Structure
Python data structures are essentially containers for different kinds of data. The four main types are lists, sets, tuples and dictionaries.
### 1. List
This data type is capable of storing collections of data (objects/values), called list elements. List elements are stored in a certain order(sequence). 
In creating a list by using square brackets containing each element in the list and separated by a comma sign such as  [.. , .. , .. ]
List items are assigned indexed, the first item has index [0], the second item has index [1], etc.

![Screenshot (691)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/dcb91de2-b704-44eb-a61c-a0f9e1efb7ab)

### 2. Tuple
In Python, tuples are ordered, immutable collections of elements. They are similar to lists in terms of storing sequences of items, but with a key difference: 
Tuples cannot be modified after creation. This makes them ideal for situations where you need to ensure data integrity and prevent accidental changes. Like a list, we can do slicing.

![Screenshot (693)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/59c19a38-722b-4592-b940-411b403d14cf)

### 3. Set
A set is an unordered collection of elements that are unique. This means that a set cannot contain duplicate values. Sets are useful for several purposes. 
Sets in Python provide methods and operators for performing unions and intersections

![Screenshot (695)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/d7856551-4f47-4378-9427-0069a3723633)

1) Union: The union of two sets combines all unique elements from both sets.

![Screenshot (697)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/12769f54-4279-48b0-902e-dd4d8a4723bd)

3) Intersection: Intersection is a slice, where the intersection value of two sets.

![Screenshot (698)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/67927054-38ac-46b9-b0b6-8c9df18d7d57)

### 4. Dictionary
Python dictionary is like hash tables in any other language with the time complexity of O(1). It is an unordered collection of data values, used to store data values like a map, which, unlike other Data Types that hold only a single value as an element, Dictionary holds the key:value pair. Key-value is provided in the dictionary to make it more optimized. 

![Screenshot (701)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/93906eae-778c-4deb-8f79-b05171793bbe)

A nested dictionary is a dictionary that has one or more dictionaries as its values. This allows you to create hierarchical and complex data structures to organize information effectively.

![Screenshot (703)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/a480a2c9-0411-4f49-a6e5-06852933a9f8)

## Arithmetic Operators
Arithmetic operators in Python are symbols that perform basic mathematical operations on numerical data types like integers, floats, and complex numbers. 
### - Additional (+)
Addition (+) performs normal numeric addition.

![Screenshot (706)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/66f1902b-f390-49ea-a953-169200a83a24)

### - Substraction (-)
Subtraction (-) in strings cannot be done because an error will appear

![Screenshot (707)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/6a57e6eb-a451-4047-a353-7b44b05d0ae0)

### - Multiplication (*)
Multiplication (*) performs normal numeric multiplication.

![Screenshot (709)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/1bd2ffa1-7614-458f-b8ba-dd4e5d364319)

### - Division (/)
Division (/) performs division and returns a floating-point number (even if the result is a whole number).

![Screenshot (710)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/b76db963-039e-4564-9d5a-b2262e02cc9d)

### - Exponentiation (**)
Exponentiation (**) performs exponentiation.
### - Floor Division (//)
Floor division (//) performs integer division and discards the remainder.
### - Modulo (%)
Modulo (%) returns the remainder after division.

![Screenshot (712)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/48d19a75-6919-4583-97ad-932edb8489b0)

## Input and Output
Input and output, often abbreviated as I/O, are fundamental concepts in programming that involve interacting with the external world. In Python, input refers to the process of receiving data from the user or from an external source, while output refers to displaying data to the user or sending data to an external destination.
### - Variable
In Python, a variable is a name that refers to a value stored in the computer's memory. It's like a container that holds data that can be manipulated and referenced within a program. Variables allow programmers to store and manipulate data dynamically during program execution.
inserts a variable value in a string : you can directly concatenates variables in the print() statement or Using the "%" operator which is then added with "argument specifiers". Some examples of common argument specifiers are as follows:
"%s" for string
"%d" for integer
"%f" for decimal

![Screenshot (718)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/594267a7-9ee5-423c-ae90-33bd1751d588)

### - Input 
In Python, input() is a built-in function used to prompt the user to enter input from the keyboard. It reads a line of input from the user as a string and returns that string. The input() function is commonly used for interactive programs where the user needs to provide data to the program during its execution. 

![Screenshot (716)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/67f47193-c5e9-4dc7-83c5-da52634df023)


![Screenshot (714)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/5194d111-14a1-432c-a56e-3e3d800932ec)

## Conditional Expressions
In Python, conditional expressions, also known as ternary expressions, provide a concise way to express conditional logic in a single line of code. They allow you to evaluate a condition and return one of two values based on whether the condition is true or false.
### 1. If
In Python, if is a keyword used to implement conditional statements. Conditional statements allow you to execute certain code blocks based on whether a specified condition evaluates to True or False.

![Screenshot (722)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/ae033401-4f43-4d3c-89fd-fda0bedae1da)

### 2. Else
In Python, else is a keyword used in conjunction with the if statement to define a block of code that should be executed when the condition associated with the if statement evaluates to False.

![Screenshot (723)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/539f606d-f46e-4975-b0c8-df984bd2a65b)

### 3. Elif
In Python, elif is a keyword
 used in conjunction with the if statement to define additional conditions to be checked if the condition associated with the if statement evaluates to False. elif stands for "else if".

![Screenshot (725)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/ef354520-40f3-4efb-854f-187acc8a77af)

## Iteration
Iteration in Python refers to the process of repeating a set of instructions or steps multiple times. It allows you to execute a block of code repeatedly, typically based on certain conditions, until a specific condition is met. Python provides several ways to perform iteration, including loops and comprehensions.

### 1. For
For loops are used to iterate over a sequence (such as a list, tuple, string, or range) or any iterable object. The loop continues until all items in the sequence have been processed.

![Screenshot (727)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/d6aae2cd-8e09-4f6f-95a0-dcf2d32be32e)

- Else after for
![Screenshot (731)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/f1632923-3640-49c9-92b3-6d911a2a00b1)

### 2. Nested Loop
In Python, a nested loop, also known as a "for bertingkat", is a programming construct where one loop (inner loop) is completely enclosed within another loop (outer loop). The inner loop executes a certain number of times for each iteration of the outer loop. This allows you to iterate through multidimensional data structures like matrices or grids, performing operations or calculations on elements that have relationships across two or more dimensions.

![Screenshot (729)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/9b31983f-9304-4eb6-8156-81be4aa7f6eb)

### 3. Break
The break statement is a control flow statement that you can use within loops (while and for) to prematurely exit the loop. This means that the loop's normal iteration stops, and the program control jumps to the line of code immediately following the loop.

![Screenshot (733)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/6efb6c16-63d2-45d0-8496-18f51f5a336a)

### 4. Continue
The continue statement in Python is another control flow statement used within loops (while and for). Unlike break which exits the loop entirely, continue skips the remaining code block of the current iteration and moves on to the next iteration of the loop.

![Screenshot (735)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/717f07fc-16b9-41fc-bef4-58ed2ba18884)

### 5. While
In a programming context, "while" is often used as part of a loop structure to execute a series of commands as long as a condition is met.

![Screenshot (737)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/7ffab932-45d6-4908-856c-209ec312981c)

-Else after while
![Screenshot (739)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/4a5a1981-7749-4123-9278-7f6f96d7ab04)

## List Comprehension
One way to generate a new list based on a pre-existing list or iterables (such as a list, tuple, or string), apply an expression or operation on each element, and automatically build a new list with the results.

![Screenshot (741)](https://github.com/dindafatimahsarah/python_learning1/assets/134476980/7448dfa1-bfe5-403a-adac-adc08c5a5f94)
