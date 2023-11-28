Project 0x00 - Python: Hello, World
Overview
Welcome to Project 0x00 - Python: Hello, World! This project is part of the ALX Higher Level Programming curriculum and aims to introduce you to Python programming basics. In this project, you will create Python scripts to perform various tasks and explore fundamental concepts of the Python language.

Table of Contents
Project Description
Author's Disclaimer
Resources
Learning Objectives
Requirements
Tasks
Task 0: Run Python File
Task 1: Run Inline
Task 2: Hello, Print
Task 3: Print Integer
Task 4: Print Float
Task 5: Print String
Task 6: Play with Strings
Task 7: Copy - Cut - Paste
Task 8: Create a New Sentence
Task 9: Easter Egg
Task 10: Linked List Cycle
Project Description
The project aims to introduce you to Python programming, covering basic concepts such as printing, string manipulation, and understanding Python's Zen philosophy. It includes a series of tasks that progressively build your Python skills.

Author's Disclaimer
Welcome to the Python world! The initial projects are designed to be simple and straightforward, focusing on core concepts. Don't worry; more advanced and exciting Python tasks will come your way. Python offers various ways to accomplish tasks, similar to C, but with a more flexible syntax.

Remember, Python follows a style guide called PEP8 (formerly known as PyCode). It is analogous to Betty for C. Enjoy the journey!

Guillaume
Resources
Read or watch the following resources to aid your learning:

The Python Tutorial (First Three Chapters)
Whetting Your Appetite
Using the Python Interpreter
An Informal Introduction to Python (Read up until "3.1.2. Strings" included)
How To Use String Formatters in Python 3
Learn to Program
Pycodestyle – Style Guide for Python Code
The Zen of Python
Learning Objectives
After completing this project, you should be able to explain the following concepts to anyone without using Google:

General
Why Python programming is awesome
Who created Python
Who is Guido van Rossum
Where does the name 'Python' come from
What is the Zen of Python
How to use the Python interpreter
How to print text and variables using print
How to use strings
What are indexing and slicing in Python
What is the official Python coding style and how to check your code with Pycodestyle
Requirements
Python Scripts
Allowed editors: vi, vim, emacs
All files interpreted/compiled on Ubuntu 20.04 LTS using Python 3 (version 3.8.5)
All files should end with a new line
The first line of all files should be exactly #!/usr/bin/python3
A README.md file at the root of the repo, containing a description of the repository
Your code should use Pycodestyle (version 2.8.*)
All files must be executable
The length of your files will be tested using wc
Shell Scripts
Allowed editors: vi, vim, emacs
All scripts tested on Ubuntu 20.04 LTS
All scripts should be exactly two lines long (wc -l file should print 2)
All files should end with a new line
The first line of all files should be exactly #!/bin/bash
All files must be executable
C Scripts
Allowed editors: vi, vim, emacs
All files compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All files should end with a new line
Your code should use the Betty style, checked using betty-style.pl and betty-doc.pl
You are not allowed to use global variables
No more than 5 functions per file
Prototypes of all functions should be included in your header file called lists.h
Don't forget to push your header file
All header files should be include guarded
Tasks
Task 0: Run Python File
Write a Shell script that runs a Python script. The Python file name will be saved in the environment variable $PYFILE.

bash
Copy code
#!/bin/bash
./0-run
Task 1: Run Inline
Write a Shell script that runs Python code. The Python code will be saved in the environment variable $PYCODE.

bash
Copy code
#!/bin/bash
./1-run_inline
Task 2: Hello, Print
Write a Python script that prints exactly "Programming is like building a multilingual puzzle," followed by a new line.

python
Copy code
#!/usr/bin/python3
print("Programming is like building a multilingual puzzle")
Task 3: Print Integer
Complete the source code to print the integer stored in the variable number, followed by "Battery street," and a new line.

python
Copy code
#!/usr/bin/python3
number = 98
print(f"{number} Battery street")
Task 4: Print Float
Complete the source code to print the float stored in the variable number with a precision of 2 digits.

python
Copy code
#!/usr/bin/python3
number = 3.14159
print(f"Float: {number:.2f}")
Task 5: Print String
Complete the source code to print the string stored in the variable str three times, followed by its first 9 characters.

python
Copy code
#!/usr/bin/python3
str = "Holberton School"
print(f"{str}{str}{str}")
print(f"{str[:9]}")
Task 6: Play with Strings
Complete the source code to print "Welcome to Holberton School!"

python
Copy code
#!/usr/bin/python3
