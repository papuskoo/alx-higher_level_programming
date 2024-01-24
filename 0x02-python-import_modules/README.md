Project 0x02: Python - import & modules
Overview
Welcome to Project 0x02! This project focuses on the basics of Python programming, specifically on importing and using modules. It covers topics such as command line arguments, creating modules, using the dir() function, preventing code execution when imported, and more.

Learning Objectives
After completing this project, you should be able to:

Understand the awesomeness of Python programming.
Import functions from another file.
Use imported functions.
Create a module.
Utilize the built-in function dir().
Prevent code in your script from being executed when imported.
Use command line arguments with your Python programs.
Copyright - Plagiarism
Remember that you are expected to come up with solutions for the tasks on your own. Plagiarism is strictly forbidden, and any form of copying and pasting someone else's work is not allowed. Respect the guidelines and ensure originality in your code.

Requirements
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
All your files should end with a new line.
The first line of all your files should be exactly #!/usr/bin/python3.
A README.md file, at the root of the folder of the project, is mandatory.
Your code should use the pycodestyle (version 2.8.*) style guide.
All your files must be executable.
The length of your files will be tested using wc.
Tasks
0. Import a simple function from a simple file
Write a program that imports the function def add(a, b): from the file add_0.py and prints the result of the addition 1 + 2 = 3.

Example:

bash
Copy code
$ cat add_0.py
#!/usr/bin/python3
def add(a, b):
    """My addition function

    Args:
        a: first integer
        b: second integer

    Returns:
        The return value. a + b
    """
    return (a + b)

$ ./0-add.py
1 + 2 = 3
$ cat 0-import_add.py
__import__("0-add")
$ python3 0-import_add.py
1. My first toolbox!
Write a program that imports functions from the file calculator_1.py, performs some mathematical operations, and prints the result.

Example:

bash
Copy code
$ cat calculator_1.py
#!/usr/bin/python3
def add(a, b):
    """My addition function

    Args:
        a: first integer
        b: second integer

    Returns:
        The return value. a + b
    """

    return (a + b)


def sub(a, b):
    """My subtraction function

    Args:
        a: first integer
        b: second integer

    Returns:
        The return value. a - b
    """

    return (a - b)


def mul(a, b):
    """My multiplication function

    Args:
        a: first integer
        b: second integer

    Returns:
        The return value. a * b
    """

    return (a * b)


def div(a, b):
    """My division function

    Args:
        a: first integer
        b: second integer

    Returns:
        The return value. a / b
    """

    return int(a / b)

$ ./1-calculation.py
10 + 5 = 15
10 - 5 = 5
10 * 5 = 50
10 / 5 = 2
2. How to make a script dynamic!
Write a program that prints the number and list of its arguments.

Example:

bash
Copy code
$ ./2-args.py 
0 arguments.
$ ./2-args.py Hello
1 argument:
1: Hello
$ ./2-args.py Hello Welcome To The Best School
6 arguments:
1: Hello
2: Welcome
3: To
4: The
5: Best
6: School
3. Infinite addition
Write a program that prints the result of the addition of all arguments.

Example:

bash
Copy code
$ ./3-infinite_add.py
0
$ ./3-infinite_add.py 79 10
89
$ ./3-infinite_add.py 79 10 -40 -300 89 
-162
4. Who are you?
Write a program that prints all the names defined by the compiled module hidden_4.pyc.

Example:

bash
Copy code
$ curl -Lso "hidden_4.pyc" "https://github.com/alx-tools/0x02.py/raw/master/hidden_4.pyc"
$ ./4-hidden_discovery.py | sort
my_secret_santa
print_hidden
print_school
5. Everything can be imported
Write a program that imports the variable a from the file variable_load_5.py and prints its value.

Example:

bash
Copy code
$ cat variable_load_5.py
#!/usr/bin/python3
a = 98
"""Simple variable
"""

$ ./5-variable_load.py
98
