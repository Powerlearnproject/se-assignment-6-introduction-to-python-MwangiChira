[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15237416&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
  What is Python?
Python is a high-level, interpreted programming language known for its readability and simplicity. Key features include dynamic typing, automatic memory management, and a comprehensive standard library. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming [1].

Use Cases:
Python is effective in:

Web Development: Using frameworks like Django and Flask.
Data Analysis and Machine Learning: With libraries such as Pandas, NumPy, and TensorFlow.
Automation and Scripting: For tasks like file operations and web scraping.
Software Development: For building desktop applications and games.
2. Installing Python:
Steps to Install on Windows:

Download Python from the official Python website.
Run the installer and ensure "Add Python to PATH" is checked.
Follow the installation prompts.
Verify installation by opening Command Prompt and typing python --version.
Steps to Install on macOS:

Open Terminal.
Install Homebrew if not installed: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install Python using Homebrew: brew install python.
Verify by typing python3 --version.
Setting Up a Virtual Environment:

Open Command Prompt or Terminal.
Create a virtual environment: python -m venv myenv.
Activate the virtual environment: .\myenv\Scripts\activate (Windows) or source myenv/bin/activate (macOS/Linux).
3. Python Syntax and Semantics:
Simple Program:

Copy code
print("Hello, World!")
print(): A function that outputs text to the console.
"Hello, World!": A string literal enclosed in double quotes.
4. Data Types and Variables:
Basic Data Types:

int: Integer numbers.
float: Floating-point numbers.
str: Strings (text).
bool: Boolean values (True or False).
list: Ordered, mutable collections.
dict: Key-value pairs, unordered and mutable.
Script:


Copy code
age = 30           # int
height = 5.9       # float
name = "Alice"     # str
is_student = True  # bool

print(age, height, name, is_student)
5. Control Structures:
Conditional Statement:


Copy code
age = 18
if age >= 18:
    print("Adult")
else:
    print("Minor")
For Loop:


Copy code
for i in range(5):
    print(i)
6. Functions in Python:
Definition and Use:
Functions are reusable blocks of code that perform a specific task. They help in organizing code and reducing redundancy.

Example Function:


Copy code
def add(a, b):
    return a + b

result = add(5, 3)
print(result)  # Output: 8
7. Lists and Dictionaries:
Differences:

Lists: Ordered collections, accessed by index.
Dictionaries: Unordered collections, accessed by key.
Script:

python
Copy code
numbers = [1, 2, 3, 4, 5]  # List
print(numbers[0])          # Access by index

info = {"name": "Alice", "age": 30}  # Dictionary
print(info["name"])        # Access by key
8. Exception Handling:
Concept:
Exception handling allows you to manage errors gracefully without crashing the program.

Example:

python
Copy code
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Execution completed.")
9. Modules and Packages:
Modules: Files containing Python code (e.g., .py files) that can be imported and used in other scripts.

Packages: Collections of modules in directories with a special __init__.py file.

Example Using math Module:

python
Copy code
import math

print(math.sqrt(16))  # Output: 4.0
10. File I/O:
Reading a File:

python
Copy code
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
Writing to a File:

python
Copy code
lines = ["First line", "Second line", "Third line"]

with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + "\n")

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


