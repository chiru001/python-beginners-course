# 📚 Python Basic Terminologies (with Super Simple Examples)

---

### 1. **Variable**  
- **Meaning:** A name that stores a value.  
- **Example:**  
  ```python
  x = 5
  name = "Alice"
  ```
- **How to identify:** If you see a name **=** something, that's a variable.

---

### 2. **Function**  
- **Meaning:** A reusable block of code that does something.  
- **Example:**  
  ```python
  def greet():
      print("Hello")
  ```
- **How to identify:**  
  - It starts with `def` keyword.
  - It has parentheses `()` after the name.

---

### 3. **Method**  
- **Meaning:** A function that belongs to an object.  
- **Example:**  
  ```python
  name = "Alice"
  name.upper()  # 'upper' is a method
  ```
- **How to identify:**  
  - It's written like `something.method()`.
  - The method acts **on** an object (like a string or list).

---

### 4. **Argument**  
- **Meaning:** The value you **pass into** a function or method.  
- **Example:**  
  ```python
  def greet(name):
      print("Hello", name)

  greet("Bob")  # "Bob" is the argument
  ```
- **How to identify:**  
  - Inside the parentheses `()`, the actual values given are arguments.

---

### 5. **Parameter**  
- **Meaning:** The name used **inside** the function to accept a value.  
- **Example:**  
  ```python
  def greet(name):
      print("Hello", name)
  ```
- **How to identify:**  
  - Inside the function `def greet(name):`, the `name` is the parameter.

---
   
### 6. **String**  
- **Meaning:** Text data, written inside quotes.  
- **Example:**  
  ```python
  message = "Hello World"
  ```
- **How to identify:**  
  - Anything inside `' '` or `" "` is a string.

---

### 7. **List**  
- **Meaning:** A collection of items, ordered and changeable.  
- **Example:**  
  ```python
  fruits = ["apple", "banana", "cherry"]
  ```
- **How to identify:**  
  - It uses square brackets `[]`.

---

### 8. **Loop**  
- **Meaning:** Repeat actions multiple times.  
- **Example:**  
  ```python
  for fruit in fruits:
      print(fruit)
  ```
- **How to identify:**  
  - Look for `for` or `while` keywords.

---

### 9. **Condition**  
- **Meaning:** Decision making (if something is true, do this).  
- **Example:**  
  ```python
  if x > 0:
      print("Positive number")
  ```
- **How to identify:**  
  - Look for `if`, `else`, or `elif`.

---

### 10. **Indentation**  
- **Meaning:** Spaces at the beginning of a line to show code blocks.  
- **Example:**  
  ```python
  if True:
      print("This is indented")
  ```
- **How to identify:**  
  - After `:` (colon), next line moves **right** with spaces.

---

### 11. **Comment**  
- **Meaning:** Notes in code, ignored by Python.  
- **Example:**  
  ```python
  # This is a comment
  print("Hello")
  ```
- **How to identify:**  
  - Starts with `#`.

---


