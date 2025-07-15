# Day 3: String Datatype and Formatting in Python

This Jupyter Notebook (`Day3.ipynb`) is part of the **Python Fundamentals** series and focuses on understanding and manipulating strings in Python. The notebook covers a range of string operations, including formatting, whitespace management, and Pythonic best practices.

## Contents

- **Continuation with String Datatype:**  
  Introduction and further exploration of Python's string type.

- **F-Strings:**  
  - Introduction to f-strings for inline variable interpolation.
  - Examples showing how to combine variables (e.g., first name and last name) into a single formatted string.
  - Demonstrates the use of `.title()` for proper capitalization.

- **Custom Messages with F-Strings:**  
  - Creating personalized output messages using string formatting.

- **Whitespace Handling:**  
  - Adding newlines (`\n`) and tabs (`\t`) to string outputs.
  - Examples contrasting single-line and multi-line outputs.
  - Explanation and demonstration of `lstrip()`, `rstrip()`, and `strip()` for trimming whitespace from strings.

- **The Zen of Python:**  
  - Introduction to the guiding principles of Python (PEP 20).
  - How to access "The Zen of Python" within your environment.

## Example Topics from the Notebook

```python
firstname = 'dinesh'
lastname = 'kumar'
fullname = f"{firstname} {lastname}"
print(fullname.title())  # Output: Dinesh Kumar

# Adding whitespace and newlines
print("favourite_language:\n\tPython\n\tC\n\tjava\n\tC++\n\tswift\n\tjavascript")

# Stripping whitespace
name = " python "
print(name.strip())  # Output: python
```

## How to Use

1. **Open in Jupyter Notebook:**  
   - Launch Jupyter and open `Day3.ipynb` from the `Day3` folder.
2. **Run Cells Sequentially:**  
   - Execute each code cell to follow the lesson and observe outputs.
3. **Experiment:**  
   - Modify values and experiment with your own strings to reinforce learning.

## Prerequisites

- Python 3.x (recommended 3.13+)
- Jupyter Notebook or compatible environment

## Learning Goals

- Understand string formatting with f-strings.
- Use Python methods to manipulate and clean string data.
- Learn best practices and guiding principles for Python development.

---

**Happy Coding!**

_This notebook is part of the [Python-Fundamentals](https://github.com/Kalimnawaz/Python-Fundamentals) series by [Kalimnawaz](https://github.com/Kalimnawaz)._
