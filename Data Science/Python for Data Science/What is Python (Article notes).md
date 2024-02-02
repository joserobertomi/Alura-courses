# What is Python? (Article)

Python is a general proposing language able to create multiple applications. Some highlights:

- Interpreted language, so does not need compilation process. In python case, the interpretation happen in virtual machines, transforming python code in binary
- Easy syntax and simple, high level language
- Multiple paradigms:
    - Procedural
    - Funcional
    - Object oriented
- Dynamic semantic, does not need data type declared

## How Python have started?

The development of Python become in 1980 with Guido van Rossum, and have the first version published in 1991.  

## Why should I study Python?

Simple, agile and versatile, Python is a strong tool for Data Analysis, Machine Learning, Web Development and DevOps.  

## Python data types:

As mentioned in beginning, Python is dynamically typed language, so if we want to change de data type during the program, we can do it! The standard data types are: 

- Int
- Float
- Complex
- String

- Boolean
- List
- Tuple
- Dictionary

## Python conditional structures:

Used to control the program flow. 

### If

```python
score = 7
if score > 6.9:
	print(“Approved”)
```

### Else

```python
score = 5
if score < 4.9:
	print(“Approved”)
else:
    print(“Repproved”)
```

### If, elif, else

```bash
score = 6
if score < 5
print(“repproved”)
elif media > 5
media < 7
    print(“School recovery”)
else:
    print(“Approved”)
```

## Python loop structures:

Used to repeat many times a block of code. 

### For:

```python
for i in range(1,10):
    print(i)
```

### While:

```python
expenses = 0
spent_value = 0

while expenses < 1000:
    spent_value = int(input("Enter the spent amount: "))
    expenses = expenses + spent_value

print(expenses)
```

## Importing

Until now, we have only dealt with cases where the imported modules were in the **same directory level** as those that import them. **In other cases**, we need to understand **how the Python interpreter looks for modules** in other directories.

When an '**import**' statement is executed, the interpreter will first check if the required module is in the current directory. If it is, it will import it as we have seen in the example. Otherwise, the search will extend to the **PYTHONPATH**.

The PYTHONPATH is a **list of directories** where the Python interpreter will look for modules for import.

## Virtual Environments

Typically, Python applications utilize packages and modules that are not part of the standard installation. Some applications **may require a specific version of a library** because it addresses a particular issue or was written using an outdated version of the library interface.

This means that it might not be possible for a standard Python installation to meet all the necessary requirements. If application 'A' needs version 1.0 of a particular module, but application 'B' requires version 2.0, **the requirements will conflict**, and installing either version will cause one of the applications to fail.

The solution to this problem is to create a virtual environment, **a directory tree** that contains a **Python installation** for a specific Python version, along with a set of **additional packages**.

## The famous librarys and frameworks

For web development, the most used frameworks are:

- Django

- Flask

- FastAPI
