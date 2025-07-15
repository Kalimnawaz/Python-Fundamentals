## 📘 Day 3 – Python Basics: Data Types, Variables & I/O

This notebook covers foundational Python concepts such as data types, variables, and user input/output.

---

### 🧠 Topics Covered:

#### ✅ 1. Python Variables

- Variables are used to store data in memory.
- No need to declare data type; Python is dynamically typed.

```python
x = 10
name = "Alice"
pi = 3.14
```

---

#### ✅ 2. Data Types

- **int** – Integer numbers (e.g., `10`, `-5`)
- **float** – Decimal numbers (e.g., `3.14`)
- **str** – Strings or text (e.g., `"Hello"`)
- **bool** – Boolean values (`True` or `False`)

```python
a = 5            # int
b = 2.5          # float
c = "Python"     # str
d = True         # bool
```

---

#### ✅ 3. Type Checking

Use the `type()` function to check data type:

```python
type(a)   # Output: <class 'int'>
```

---

#### ✅ 4. Input and Output

- `input()` is used to take input from the user.
- `print()` is used to display output.

```python
name = input("Enter your name: ")
print("Hello", name)
```

> **Note**: Input is always returned as a string.

---

#### ✅ 5. Type Casting

Convert from one data type to another:

```python
x = int("10")        # str to int
y = float("3.5")     # str to float
z = str(100)         # int to str
```

---

### 💡 Tips

- Python variable names are case-sensitive.
- Variable names should start with a letter or underscore (`_`).
- Avoid using reserved keywords as variable names.
