---
author: "Kyle Jones"
date_published: "June 20, 2023"
date_exported_from_medium: "November 10, 2025"
canonical_link: "https://medium.com/@kyle-t-jones/getting-started-with-python-62f689a0fb2c"
---

# Getting started with Python Python is a high-level, interpreted programming language known for its
simplicity and readability. It emphasizes code readability with its...

### Getting started with Python
Python is a high-level, interpreted programming language known for its simplicity and readability. It emphasizes code readability with its clean syntax and uses indentation instead of braces. Python supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

Python offers a wide range of built-in data structures and libraries, making it versatile for various applications such as web development, data analysis, artificial intelligence, and scientific computing. Python's extensive standard library and a thriving community contribute to its popularity, providing developers with a vast ecosystem of tools and modules. Its ease of use, combined with its power and flexibility, makes Python a preferred choice for beginners and experienced programmers alike.

### Python Get Started
Python is a beginner-friendly, high-level programming language with a simple syntax and wide range of applications. Here's a "Hello, World!" code example to get started:

``` 
print("Hello, World!")
# output: Hello, World!
```

In this code, the print() function is used to display the message "Hello, World!" on the console. Python executes code sequentially, so this single line is sufficient to greet the world. Python's readability and concise syntax make it easy to understand and write code. With this simple example, beginners can quickly grasp the basics of Python and start exploring its powerful features and libraries.

### Python Syntax
Python syntax refers to the rules and structure that govern how Python code is written. Here are a few examples that highlight key elements of Python syntax:

1.  [Variables and Print Statement:]

``` 
name = "John"
age = 25
print("My name is ", name, " and I am ", age, " years old.")
# Output:  My name is John and I am 25 years old.
```

Variables are assigned values using the = operator. The print() function is used to display output. Strings can be concatenated with variables using commas.

1.  [Conditional Statement (if-else):]

``` 
x = 10
if x > 0:
  print("Positive number")
else: 
  print("Negative number")

# Output: Positive number
```

The if-else statement allows conditional execution of code. Indentation is used to define the block of code belonging to each branch.

1.  [Loops (for and while):]


The for loop iterates over elements in a sequence. The while loop executes code until a certain condition is met.

Python's syntax focuses on readability, utilizing indentation and minimal punctuation. These examples illustrate some fundamental aspects of Python syntax, allowing for clear and concise code expression.

### Python Comments
Comments in Python are lines of code that are ignored by the interpreter. They are used to add explanatory or descriptive text to the code, making it easier for developers to understand and maintain. Here's an example:


In this example, the comments provide additional information about the code. They start with the \# symbol and can be placed on a separate line or at the end of a line. Comments are invaluable for documenting code, making it more readable, and aiding collaboration among developers.

### Python Variables
Variables in Python are containers used to store values. They are dynamically typed, meaning their data type can change during runtime. Here are two examples of using variables in Python:

1.  [Assigning Values:]


In this example, name and age are variables assigned with the values "John" and 25, respectively. Python automatically determines the data type based on the assigned value.

1.  [Variable Reassignment:]


Here, the variable x is initially assigned the value 10. Later, it is reassigned with a new value, the result of adding 5 to its current value. The variable's value can change during execution.

Python variables provide flexibility and allow developers to store and manipulate data in their programs. They play a crucial role in writing dynamic and interactive code.

### Python Data Types
Python supports various data types that define the kind of values that can be stored and manipulated in variables. Here are two examples of commonly used data types in Python:


In this example, x is assigned an integer value of 5, and y is assigned a floating-point value of 2.7. Python provides separate data types for integers and floating-point numbers.

1.  [String Data Type:]


Here, name and message are assigned string values. Strings are sequences of characters enclosed in quotes (either single or double). They can contain letters, numbers, symbols, and whitespace.

These examples illustrate the numeric and string data types in Python. Understanding data types is crucial for performing operations and manipulating data effectively in Python programs.

### Python Numbers
Numbers in Python are used to represent numeric data and support mathematical operations. Here are two examples showcasing different types of numbers in Python:

1.  [Integer:]


In this example, x is assigned the value 5, and y is assigned the value -3. Integers are whole numbers without decimal points.

1.  [Floating-Point:]


Here, a and b are assigned floating-point values, which represent numbers with decimal points.

Python provides built-in support for various numerical operations like addition, subtraction, multiplication, division, and more. Understanding number types in Python helps in performing calculations and handling numerical data effectively.

### Python Casting
Casting in Python refers to the process of converting one data type into another. Here are two examples demonstrating casting in Python:

1.  [Integer to Float:]


In this example, the float() function is used to cast the integer value x into a float. The resulting value is assigned to y, and when printed, it shows 5.0 as a float.

1.  [String to Integer:]


Here, the int() function is used to cast the string value "10" into an integer. The resulting value is assigned to b, and when printed, it shows 10 as an integer.

Casting allows the conversion of values between different data types, enabling flexibility in Python programming and facilitating operations that require specific data types.

### Python Strings
Strings in Python are sequences of characters enclosed in quotes (single or double). They represent textual data and allow various operations. Here are two examples showcasing the use of strings in Python:

1.  [String Assignment:]


In this example, name is a string variable assigned the value "Alice". The message variable is created by concatenating strings using the + operator, resulting in "Hello, Alice!" when printed.

1.  [String Methods:]


In this example, upper() and capitalize() are string methods. upper() converts the string to uppercase, while capitalize() capitalizes the first character of the string.

Strings in Python are versatile and support a wide range of operations and methods, making them powerful tools for manipulating and working with textual data.

### Python Booleans
Booleans in Python represent truth values, either True or False. They are primarily used in conditional statements and control flow. Here are two examples showcasing the use of booleans in Python:

1.  [Boolean Assignment:]


In this example, is_valid is assigned the boolean value True, while is_greater is assigned the result of the comparison 5 \> 3, which evaluates to True.

1.  [Boolean Operators:]


Here, is_equal is assigned the result of the equality comparison x == y, which evaluates to False. is_greater_than is assigned the result of the comparison x \> y, which evaluates to True.

Booleans are fundamental for logical operations and decision-making in Python. They enable the creation of conditional statements and allow developers to control the flow of their programs based on truth values.

### Python Operators
Operators in Python are symbols or special keywords that perform operations on one or more operands. Here are two examples showcasing different types of operators in Python:

1.  [Arithmetic Operators:]


In this example, the + operator performs addition, and the / operator performs division.

1.  [Comparison Operators:]


Here, the \> operator checks if a is greater than b, and the != operator checks if a is not equal to b.

Python provides various operators, including arithmetic, comparison, assignment, logical, and more. These operators enable mathematical calculations, comparisons, assignments, and decision-making in Python programs.

### Python Lists
Lists in Python are ordered collections of items, enclosed in square brackets and separated by commas. They can store multiple values of different data types. Here are two examples showcasing the use of lists in Python:

1.  [List Creation and Access:]


In this example, a list named fruits is created with three elements. Elements in a list are indexed starting from 0. We access and print specific elements using their respective indices.

1.  [List Methods:]


Here, the append() method adds an element to the end of the list, while remove() method removes a specific element from the list. The modified list is printed to show the result.

Lists in Python are versatile and offer various methods for adding, removing, and manipulating elements. They are commonly used for storing and organizing collections of related data.

### Python Tuples
Tuples in Python are ordered collections of items, similar to lists, but they are immutable, meaning their elements cannot be modified once defined. Here are two examples showcasing the use of tuples in Python:

1.  [Tuple Creation and Access:]


In this example, a tuple named point is created with two elements. Elements in a tuple are indexed starting from 0. We access and print specific elements using their respective indices.

1.  [Tuple Packing and Unpacking:]


Here, a tuple named person is created with three elements. Tuple unpacking allows assigning individual elements of the tuple to separate variables, making it convenient to work with multiple values at once.

Tuples are useful for situations where data needs to be stored and accessed but should not be modified. They are commonly used for representing fixed collections of values.

### Python Sets
Sets in Python are unordered collections of unique elements. They are defined by enclosing elements in curly braces {} or using the set() function. Here are two examples showcasing the use of sets in Python:

1.  [Set Creation and Operations:]


In this example, a set named fruits is created with three elements. The add() method adds an element to the set, while the remove() method removes a specific element. The resulting set is printed.

1.  [Set Operations (Union, Intersection):]


Here, union() returns a new set containing all unique elements from both sets, while intersection() returns a new set containing common elements between the two sets.

Sets in Python provide a convenient way to work with collections of unique elements and perform set operations such as union, intersection, difference, and more.

### Python Dictionaries
Dictionaries in Python are unordered collections of key-value pairs. They are defined by enclosing elements in curly braces {} and separating them with colons. Here are two examples showcasing the use of dictionaries in Python:

1.  [Dictionary Creation and Access:]


In this example, a dictionary named student is created with three key-value pairs. We access specific values by using their corresponding keys.

1.  [Dictionary Methods:]


Here, the car dictionary is modified using dictionary methods. The car\["color"\] adds a new key-value pair, and del car\["model"\] removes a specific key-value pair. The resulting dictionary is printed.

Dictionaries in Python are useful for mapping unique keys to their corresponding values. They allow efficient retrieval and manipulation of data using key-based access.

### Python If...Else
The If...Else statement in Python allows for conditional execution of code blocks based on specified conditions. Here are two examples showcasing the use of If...Else in Python:

``` 
x = 12
if x > 10:
    # this code is executed only if the condition is True
    print("hello")
else:
    # otherwise, this code is executed
    print("world")
```

Notice the indentations (tabs) after the "if" and "else" lines. Tabs are important in Python as their placement often affects how code is executed. In an if statement, the tabs determine when the if/else sections end.

1.  [Simple If...Else:]


In this example, the code checks if x is greater than 0. If the condition is true, it executes the code block under the if statement. Otherwise, it executes the code block under the else statement.

1.  [Nested If...Else:]


Here, multiple conditions are evaluated using the if, elif (short for "else if"), and else statements. The code checks if x is positive, negative, or zero and executes the corresponding code block based on the first true condition.

If...Else statements provide a way to make decisions and control the flow of a program based on specific conditions, enabling dynamic and responsive code execution.

### Python While Loops
While loops in Python allow for repeated execution of a block of code as long as a specified condition remains true. Here are two examples showcasing the use of while loops in Python:

1.  [Simple While Loop:]


In this example, the code prints the value of count and increments it by 1 in each iteration until the condition count \< 5 becomes false.

1.  [Infinite While Loop with Break:]


Here, the loop continues indefinitely until the user enters "quit". The break statement is used to exit the loop and end the program.

While loops allow for repetitive execution of code until a condition is no longer satisfied, providing a flexible way to handle iterative tasks in Python.

### Python For Loops
For loops in Python allow for iterating over a sequence (such as a list, tuple, or string) or other iterable objects. Here are two examples showcasing the use of for loops in Python:

1.  [Iterate over a List:]


In this example, the for loop iterates over each element in the fruits list and prints it.

Another example. In this version, we print out each value in the list. Notice that the list includes a mix of data types.

``` 
mylist = [3,6,1,6,3,7,3,7,3,99,3,'alpha']

for e in mylist:
    # this code executes multiple times, once for each element in the list
    # on each iteration, the variable e changes to the next value
    print(e)
```

1.  [Iterate over a Range:]


Here, the range function generates a sequence of numbers from 0 to 4. The for loop iterates over each number in the range and prints it.

For loops provide a convenient way to iterate over sequences and perform repetitive tasks. They simplify code structure and enhance the readability of programs.

#### List comprehensions
This concept is harder for begginers but it is more "pythonic." List comprehensions are a convention in Python that allows us to avoid writing loops or conditions. In practice, I avoid loops and use list comprehensions whenever possible.

``` 
### Basic conditional statement ###
x = 12
if x > 10:
    # this code is executed only if the condition is True
    print("hello")
else:
    # otherwise, this code is executed
    print("world")

### List comprehension version ###

# The above condition could be written as a list comprehension this way
x = [12]
print("{word}".format(word = ["hello" if x > 10 else "world" for x in x]))

# The For Loop would be written this way
mylist = [3,6,1,6,3,7,3,7,3,99,3,'alpha']
print("{item}".format(item = mylist))
```

### Functions
Tabs are important again here. Functions are defined based on the lines of code that are indented below the "def" line.

```python
def firstfunc():
    print("Hello World!")
    print("This is my first function.")
firstfunc()
# Output: Hello World!
# Output: This is my first function.
```

That function isn't very useful. So let's make one that can do some math for us.

```python
def times(x,y):  # variables inside parenthesis are the "parameters"
    z = x*y
    return z

# note that x and y are defined local to function (in its "scope")
# Why does this line error?
a = times()
# run the function and capture the value it returns by assigning it to the variable c
c = times(4,5)
print(c)
```

#### Things you can try
1.  [Create a string variable of your first and last names and call it "name"]
2.  [Use a slice (square bracket notation \[a:b\]) on the string "name" to print only your first name]
3.  [Create a list, named "num", of numbers between 1 and 10, inclusive]
4.  [Calculate the sum of all numbers in "num"]
5.  [Create a function called "sum_numbers" that returns the sum of the numbers in a list \[hint 1: parameter should be the list; hint 2: make sure you are returning the value, not just printing it\]]
6.  [Print only the even numbers in num \[hint1: calculate remainder with '%'; [hint2](https://levelup.gitconnected.com/15-ways-to-print-even-numbers-in-python-60d4916c3d04)\]]
7.  [Create a function "product" that finds the product of all numbers in a list \[[hint](https://www.geeksforgeeks.org/python-multiply-numbers-list-3-different-ways/)\]]

### SUMMARY
In this tutorial, you were introduced to the Python programming language. Specifically, you learned:

- The structure of Python as a programming language
- How to do basic operations like addition and subtraction
- The various data types available in Python
- How to use loops and conditional statements

### Related Stories
- [[Intermediate Python samples](https://medium.com/@kylejones_47003/intermediate-python-sam-87f652402606)]
- [[Python for Business Analysis: A Beginner's Guide (part 1)](https://medium.com/@kylejones_47003/python-for-business-analysis-a-beginners-guide-part-1-50dc74a912e8)]
- [[Why analytics is hard](https://medium.com/@kylejones_47003/why-analytics-is-hard-4c4b8c164821)]
