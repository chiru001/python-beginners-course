---

# 📚 Python Beginner Terminologies

This document covers the basic terminologies every beginner should know before learning Python.

---

## 1. Variable
- **Definition:** A name that stores a value.
- **Example:**
  ```python
  x = 10
  name = "Nani"
  ```

---

## 2. Data Types
- **Definition:** Types of data you can use.
- **Examples:**  
  - `int` (Integer): `5`
  - `float` (Decimal): `3.14`
  - `str` (String/Text): `"Hello"`
  - `bool` (Boolean): `True` or `False`
  - `list` (Collection): `[1, 2, 3]`

---

## 3. Function
- **Definition:** A reusable block of code that performs a task.
- **Example:**
  ```python
  def greet():
      print("Hello")
  ```

---

## 4. Method
- **Definition:** A function that belongs to an object.
- **Example:**
  ```python
  name = "nani"
  name.upper()
  ```
---

# 🛠️ Most Common Python Methods (For Daily Use)

---

## 📄 String Methods (for Text)

| Method | Use | Example |
|:------:|:---:|:-------:|
| `.lower()` | Convert text to lowercase | `"HELLO".lower()` → `"hello"` |
| `.upper()` | Convert text to uppercase | `"hello".upper()` → `"HELLO"` |
| `.strip()` | Remove spaces from start and end | `"  hello  ".strip()` → `"hello"` |
| `.replace(old, new)` | Replace part of a string | `"Hello World".replace("World", "Python")` → `"Hello Python"` |
| `.split(separator)` | Split a string into a list | `"a,b,c".split(",")` → `["a", "b", "c"]` |
| `.find(word)` | Find the position of a word | `"hello".find("e")` → `1` |

---

## 📦 List Methods (for Collections)

| Method | Use | Example |
|:------:|:---:|:-------:|
| `.append(item)` | Add item at the end | `fruits.append("mango")` |
| `.remove(item)` | Remove item from list | `fruits.remove("apple")` |
| `.pop()` | Remove last item | `fruits.pop()` |
| `.sort()` | Sort the list | `fruits.sort()` |
| `.reverse()` | Reverse the list | `fruits.reverse()` |

---

## 🧹 Dictionary Methods (for Key-Value Pairs)

| Method | Use | Example |
|:------:|:---:|:-------:|
| `.keys()` | Get all keys | `person.keys()` |
| `.values()` | Get all values | `person.values()` |
| `.items()` | Get key-value pairs | `person.items()` |
| `.get(key)` | Get value safely | `person.get("name")` |

---

## 🔢 Numeric Methods

| Method | Use | Example |
|:------:|:---:|:-------:|
| `round(number)` | Round a number | `round(3.14159, 2)` → `3.14` |
| `abs(number)` | Get absolute value | `abs(-5)` → `5` |

---

## 🎯 Utility Functions (Built-in)

| Function | Use | Example |
|:--------:|:---:|:-------:|
| `len()` | Get the number of items | `len(fruits)` |
| `type()` | Find the type of data | `type(5)` → `<class 'int'>` |
| `input()` | Take input from user | `input("Enter name: ")` |
| `print()` | Show output | `print("Hello")` |
| `range()` | Create a range of numbers | `range(5)` → `[0,1,2,3,4]` |

---
---

## 5. Argument
- **Definition:** A value you pass into a function or method.
- **Example:**
  ```python
  greet("nani")
  ```

---

## 6. Parameter
- **Definition:** A variable name used to accept an argument in a function.
- **Example:**
  ```python
  def greet(name):
      print("Hello", name)
  ```

---

## 7. String
- **Definition:** Text, written inside quotes.
- **Example:**
  ```python
  message = "Hello World"
  ```

---

## 8. List
- **Definition:** A collection of items, ordered and changeable.
- **Example:**
  ```python
  fruits = ["apple", "banana", "cherry"]
  ```

---

## 9. Dictionary
- **Definition:** A collection of key-value pairs.
- **Example:**
  ```python
  person = {"name": "nani", "age": 25}
  ```

---

## 10. Loop
- **Definition:** Repeats actions multiple times.
- **Example (for loop):**
  ```python
  for fruit in fruits:
      print(fruit)
  ```

---

## 11. Condition
- **Definition:** Makes decisions in code.
- **Example:**
  ```python
  if x > 0:
      print("Positive number")
  ```

---

## 12. Indentation
- **Definition:** Spaces at the beginning of a line to define code blocks.
- **Example:**
  ```python
  if True:
      print("Indented block")
  ```

---

## 13. Comment
- **Definition:** Notes for humans, ignored by Python.
- **Example:**
  ```python
  # This is a comment
  print("Hello")
  ```

---

## 14. Module
- **Definition:** A file containing Python code that you can use in your programs.
- **Example:**
  ```python
  import math
  print(math.sqrt(16))
  ```

---

## 15. Syntax
- **Definition:** The rules you must follow to write valid Python code.
- **Example:**  
  - Correct: `print("Hello")`
  - Incorrect: `print("Hello'`

---

## 16. Error (Exception)
- **Definition:** Problems that happen when you run your program.
- **Example:**
  ```python
  print(5 / 0)  # ZeroDivisionError
  ```

---

## 17. Boolean
- **Definition:** True or False values.
- **Example:**
  ```python
  is_active = True
  ```

---

## 18. Input
- **Definition:** Taking data from the user.
- **Example:**
  ```python
  name = input("Enter your name: ")
  ```

---

## 19. Output
- **Definition:** Displaying information to the user.
- **Example:**
  ```python
  print("Welcome!")
  ```

---

## 20. Class (OOP)
- **Definition:** A blueprint for creating objects.
- **Example:**
  ```python
  class Person:
      def __init__(self, name):
          self.name = name
  ```

---

# 🎯 Tip
> Practice by writing small programs for each concept!

---

# 📢 Learn More
Follow the full Python Beginner series on YouTube:  
**[DCR Tech Channel](https://www.youtube.com/@DCR-Tech)**

---

