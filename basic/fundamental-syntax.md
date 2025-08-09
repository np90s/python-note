```mermaid
mindmap
  root((Python Syntax))
    Variables & Data Types
      Variables
        "x = 10"
      Data Types
        "int, float, str, bool, list, tuple, dict, set"
        "name = 'Alice'"
    Operators
      Arithmetic
        "+, -, *, /, //, %, **"
        "result = 5 ** 2"
      Comparison
        "==, !=, >, <, >=, <="
        "x > y"
      Logical
        "and, or, not"
        "if x > 0 and y > 0:"
    Control Flow
      if-elif-else
        "if x>0:\n    print('Positive')\nelse:\n    print('Negative')"
      for loop
        "for i in range(5):\n    print(i)"
      while loop
        "while x<5:\n    x+=1"
      break & continue
        "break → thoát vòng lặp"
    Functions
      Defining
        "def greet(name):\n    return 'Hello '+name"
      Default Parameters
        "def add(x, y=10):\n    return x+y"
      Lambda
        "square = lambda x: x**2"
    Data Structures
      List
        "numbers = [1,2,3]"
        "numbers.append(4)"
      Tuple
        "coords = (10, 20)"
      Dict
        "person = {'name':'Bob', 'age':25}"
      Set
        "items = {1,2,3}"
    Modules & Imports
      Importing
        "import math"
      From Import
        "from math import sqrt"
    Exceptions
      Try-Except
        "try:\n    x = 1/0\nexcept ZeroDivisionError:\n    print('Error')"
      Finally
        "finally: cleanup()"
    File Handling
      Read
        "with open('file.txt') as f:\n    data = f.read()"
      Write
        "with open('out.txt', 'w') as f:\n    f.write('Hello')"
    Classes & OOP
      Class Definition
        "class Dog:\n    def __init__(self, name):\n        self.name = name"
      Inheritance
        "class Puppy(Dog): pass"
    Misc
      List Comprehension
        "[x**2 for x in range(5)]"
      F-strings
        "f'Hello {name}'"
      With Statement
        "with resource as r:\n    pass"
