---
title: "Python"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/python
venue: "Fujian Normal University, CPEE"
date: 2021-01-01
location: "FuZhou, China"
---

**Python** is one of the most widely-used programming languages worldwide, renowned for its simplicity and versatility across multiple domains.

# Introduction to "Python Programming" Course

**Python**, created by Guido van Rossum in 1991, is a high-level programming language renowned for its **simplicity**, **readability**, and **versatility**. Its design philosophy emphasizes code clarity through concise syntax and indentation-based block structures. As a dynamically typed, interpreted, and cross-platform language, Python supports multiple programming paradigms, including object-oriented, functional, and procedural approaches. Its extensive standard library and rich ecosystem of third-party frameworks (e.g., Django, Flask, Pandas, PyTorch, Matplotlib, and other frameworks for building deep learning models) make it adaptable to diverse applications.

## Popularity & Applications

Ranked consistently among the **top programming languages** in the TIOBE Index and Stack Overflow surveys, Python has become a cornerstone of modern technology. It powers:

- **AI** (PyTorch, Keras, etc.)
- **Data Science** (Pandas, NumPy, Matplotlib)
- **Web Development** (Django, Flask)
- **Automation & Scripting**
- **Scientific Computing** (NumPy, SciPy, Sympy, etc.)
- **Education**

Major organizations leverage Python for its rapid prototyping capabilities and developer-friendly nature.

## Course Content

This course covers:

1. **Fundamentals**:  
   - Syntax, data types, control structures  
   - Error handling and basic algorithms  

2. **Core Concepts**:  
   - Functions, modules, and file I/O  
   - Object-oriented programming (OOP)  

3. **Applications**:  
   - Introductory web development with Flask, Django  
   - Data analysis using Pandas, Numpy, Matpltlib  

4. **Best Practices**:  
   - **Modular Programming**: Imports, packages, standard libraries (`sys`, `os`, `json`)  
   - **File Operations**: Reading/writing files, context managers, serialization  
   - **GUIs**: Basics of GUI development (e.g., Tkinter)  
   - **Databases**: SQLite integration, CRUD operations with Python DB-API
   - **Deep Learning**: Design neural networks with PyTorch (tensors, autograd, CNN/RNN, et. implementation, and training pipelines)  

## Learning Objectives

By course completion, students will:
- Develop functional Python programs for real-world scenarios  
- Understand software engineering principles and debugging techniques  
- Gain hands-on experience through projects and collaborative coding  
- Build a foundation for advanced specialization in **AI**, **DevOps**, or **Data Science**

## Recommended Textbook

  Hetland, Magnus Lie. *Python Basics: A Practical Introduction to Python 3*. 3rd ed., Revised, translated by Yuan Guozhong, People's Posts and Telecommunications Press, 2017.
  Ramalho, Luciano. *Fluent Python: Clear, Concise, and Effective Programming*. O'Reilly Media, 2015.

---

## Below is an example illustrating Python's applications:

## Quick & Easy to Learn

Experienced programmers in any other language can pick up Python very quickly, and beginners find the clean syntax and indentation structure easy to learn. Whet your appetite with our Python 3 overview.

```python
# Simple output (with Unicode)
>>> print("Hello, I'm Python!")
Hello, I'm Python!
# Input, assignment
>>> name = input('What is your name?\n')
What is your name?
Python
>>> print(f'Hi, {name}.')
Hi, Python.
```

## All the Flow You’d Expect

Python knows the usual control flow statements that other languages speak — if, for, while and range — with some of its own twists, of course. More control flow tools in Python 3
```python
# For loop on a list
>>> numbers = [2, 4, 6, 8]
>>> product = 1
>>> for number in numbers:
...    product = product * number
... 
>>> print('The product is:', product)
The product is: 384
```

## Intuitive Interpretation

Calculations are simple with Python, and expression syntax is straightforward: the operators +, -, * and / work as expected; parentheses () can be used for grouping. More about simple math functions in Python 3.

```python
# Python 3: Simple arithmetic
>>> 1 / 2
0.5
>>> 2 ** 3
8
>>> 17 / 3  # classic division returns a float
5.666666666666667
>>> 17 // 3  # floor division
5
```

## Compound Data Types

Lists (known as arrays in other languages) are one of the compound data types that Python understands. Lists can be indexed, sliced and manipulated with other built-in functions. More about lists in Python 3

```python
# Python 3: List comprehensions
>>> fruits = ['Banana', 'Apple', 'Lime']
>>> loud_fruits = [fruit.upper() for fruit in fruits]
>>> print(loud_fruits)
['BANANA', 'APPLE', 'LIME']
# List and the enumerate function
>>> list(enumerate(fruits))
[(0, 'Banana'), (1, 'Apple'), (2, 'Lime')]
```

## Functions Defined

The core of extensible programming is defining functions. Python allows mandatory and optional arguments, keyword arguments, and even arbitrary argument lists. More about defining functions in Python 3
```python
# Python 3: Fibonacci series up to n
>>> def fib(n):
>>>     a, b = 0, 1
>>>     while a < n:
>>>         print(a, end=' ')
>>>         a, b = b, a+b
>>>     print()
>>> fib(1000)
0 1 1 2 3 5 8 13 21 34 55 89 144 233 377 610 987
```

