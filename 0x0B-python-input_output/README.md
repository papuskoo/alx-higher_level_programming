0x0B. Python - Input/Output
Description

This repository contains solutions to the tasks in the "0x0B. Python - Input/Output" project of the ALX Software Engineering program. In this project, we explored file input/output operations in Python, including reading from and writing to text files, working with JSON data, and serialization/deserialization.
Learning Objectives

    Understand the fundamentals of file input/output operations in Python
    Learn how to read from and write to text files
    Explore JSON serialization and deserialization in Python
    Practice working with Python's built-in functions and data structures

Requirements

    Allowed editors: vi, vim, emacs
    All Python scripts should be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
    All Python scripts should use the #!/usr/bin/python3 shebang line at the top
    All Python files should end with a new line
    All Python scripts must be executable
    The length of the Python files will be tested using wc
    All test files should be text files with a .txt extension
    All tests should be executed by running the command python3 -m doctest ./tests/*
    All modules should have documentation accessible using python3 -c 'print(__import__("my_module").__doc__)'
    All classes should have documentation accessible using python3 -c 'print(__import__("my_module").MyClass.__doc__)'
    All functions (inside and outside a class) should have documentation accessible using python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
    A documentation should be a real sentence explaining the purpose of the module, class, or method

Files

    0-read_file.py: Python script that contains a function to read a text file and print its contents to the standard output.
    1-write_file.py: Python script that contains a function to write a string to a text file and returns the number of characters written.
    2-append_write.py: Python script that contains a function to append a string to the end of a text file and returns the number of characters added.
    3-to_json_string.py: Python script that contains a function to return the JSON representation of an object (string).
    4-from_json_string.py: Python script that contains a function to return an object (Python data structure) represented by a JSON string.
    5-save_to_json_file.py: Python script that contains a function to write an object to a text file using JSON representation.
    6-load_from_json_file.py: Python script that contains a function to create an object from a JSON file.
    7-add_item.py: Python script that adds all command-line arguments to a Python list and saves them to a file in JSON format.
    8-class_to_json.py: Python script that contains a function to return the dictionary description with simple data structure (list, dictionary, string, integer, and boolean) for JSON serialization of an object.
    9-student.py: Python script that defines a class Student with attributes first_name, last_name, and age, and a method to_json() that retrieves a dictionary representation of a Student instance.
    10-student.py: Python script that defines a class Student similar to 9-student.py, but with an additional method to_json() that retrieves a dictionary representation of a Student instance with filtered attributes based on a list of strings.
    11-student.py: Python script that defines a class Student similar to 10-student.py, but with an additional method reload_from_json() that replaces all attributes of the Student instance.
    12-pascal_triangle.py: Python script that contains a function to return a list of lists of integers representing Pascal's triangle of a given size.

How to Use

    Clone this repository to your local machine.
    Navigate to the directory containing the Python scripts.
    Run each Python script individually using Python 3. For example:

    bash

    python3 0-read_file.py

    Follow the instructions or observe the output as specified in the project description.

Authors

This project is authored by Guillaume for ALX Software Engineering.
Acknowledgments

Special thanks to the ALX mentors and peers for their support and guidance throughout this project.

