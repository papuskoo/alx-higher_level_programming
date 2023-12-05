0x03. Python - Data Structures: Lists, Tuples
Project Overview
This project covers various aspects of Python data structures, specifically lists and tuples. The tasks aim to reinforce the understanding of these concepts and their applications.

Learning Objectives
Upon completing this project, you should be able to:

Understand the fundamentals of Python programming.
Use and manipulate lists in Python.
Differentiate between strings and lists, understanding their similarities and differences.
Apply common methods of lists.
Utilize lists as stacks and queues.
Implement list comprehensions.
Understand tuples and their usage.
Make decisions between using tuples or lists based on specific scenarios.
Comprehend the concept of sequences.
Understand tuple packing and sequence unpacking.
Utilize the del statement in Python.
Project Requirements
Python Scripts
Allowed editors: vi, vim, emacs.
All scripts will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.8.5.
Files should end with a new line.
The first line of all files should be #!/usr/bin/python3.
A README.md file at the root of the project folder is mandatory.
Code should adhere to PEP 8 style (checked using pycodestyle).
All files must be executable.
The length of files will be tested using wc.
C
Allowed editors: vi, vim, emacs.
All C files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5).
Files should end with a new line.
Code should use the Betty style, checked using betty-style.pl and betty-doc.pl.
Not allowed to use global variables.
No more than 5 functions per file.
Prototypes of all functions should be included in the header file lists.h.
Don't forget to push the header file.
All header files should be include guarded.
Task Descriptions
0. Print a list of integers
Write a function that prints all integers of a list.

Prototype: def print_list_integer(my_list=[]):
Format: one integer per line.
1. Secure access to an element in a list
Write a function that retrieves an element from a list.

Prototype: def element_at(my_list, idx):
If idx is negative, return None.
If idx is out of range, return None.
Not allowed to use try/except.
2. Replace element
Write a function that replaces an element of a list at a specific position.

Prototype: def replace_in_list(my_list, idx, element):
If idx is negative or out of range, return the original list.
Not allowed to use try/except.
3. Print a list of integers... in reverse!
Write a function that prints all integers of a list, in reverse order.

Prototype: def print_reversed_list_integer(my_list=[]):
Format: one integer per line.
4. Replace in a copy
Write a function that replaces an element in a list at a specific position without modifying the original list.

Prototype: def new_in_list(my_list, idx, element):
If idx is negative or out of range, return a copy of the original list.
Not allowed to use try/except.
5. Can you C me now?
Write a function that removes all characters 'c' and 'C' from a string.

Prototype: def no_c(my_string):
Return the new string.
Not allowed to use str.replace().
6. Lists of lists = Matrix
Write a function that prints a matrix of integers.

Prototype: def print_matrix_integer(matrix=[[]]):
Format: see example.
Not allowed to use any module.
7. Tuples addition
Write a function that adds 2 tuples.

Prototype: def add_tuple(tuple_a=(), tuple_b=()):
Returns a tuple with the sum of corresponding elements.
If a tuple is smaller than 2, use the value 0 for each missing integer.
If a tuple is bigger than 2, use only the first 2 integers.
8. More returns!
Write a function that returns a tuple with the length of a string and its first character.

Prototype: def multiple_returns(sentence):
If the sentence is empty, the first character should be None.
Not allowed to use len().
9. Find the max
Write a function that finds the biggest integer in a list.

Prototype: def max_integer(my_list=[]):
If the list is empty, return None.
Not allowed to use max().
10. Only by 2
Write a function that finds all multiples of 2 in a list.

Prototype: def divisible_by_2(my_list=[]):
Return a new list with True or False, depending on whether the integer at the same position in the original list is a multiple of 2.
11. Delete at
Write a function that deletes the item at a specific position in a list.

Prototype: def delete_at(my_list=[], idx=0):
If idx is negative or out of range, return the same list.
Not allowed to use pop().
12. Switch
Complete the source code to switch the values of variables a 
