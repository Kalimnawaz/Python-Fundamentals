
# 📘 Python Training – Day 2 & Day 3 Setup and Basics

## 🛠️ Day 2 – Environment Setup

### ✅ Software Needed
1. [Anaconda](https://www.anaconda.com) – to use **Jupyter Notebook**
2. [GitHub](https://www.github.com) – for **code version control**

---

### 🔧 Installing Anaconda (Jupyter Notebook)

**Steps:**
1. Open [www.anaconda.com](https://www.anaconda.com)
2. Click on the **Download** option available on the screen.
3. Go to the Downloads folder and **run the `.exe` file**  
   Click:
   ```
   next → next → next
   ```
4. A shortcut will be created on your desktop named **Anaconda Navigator**
5. Open **Anaconda Navigator**
6. Choose **Jupyter Notebook** and click **Launch**
7. It will open in your default web browser.

---

### 🌐 Setting up GitHub (Code Versioning System)

**Steps:**
1. Open [www.github.com](https://www.github.com)
2. Sign up and create your GitHub account
3. Log in to GitHub
4. Create a repository (e.g., `python-fundamentals`)
5. Upload your code files into the repository
6. Commit the code to save your changes

---

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
