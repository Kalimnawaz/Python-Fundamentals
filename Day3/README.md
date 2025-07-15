String Data Type – Continuation
🔹 Unnecessary Spaces in Strings
Extra spaces in a string consume memory unnecessarily.

It's good practice to remove spaces when they are not required.

✂️ String Trimming Methods
lstrip()
Removes leading (left-side) spaces from a string.

Example:

python
Copy
Edit
s = "   hello"
print(s.lstrip())  # Output: "hello"
rstrip()
Removes trailing (right-side) spaces from a string.

Example:

python
Copy
Edit
s = "hello   "
print(s.rstrip())  # Output: "hello"
strip()
Removes spaces from both sides of the string.

Example:

python
Copy
Edit
s = "   hello   "
print(s.strip())  # Output: "hello"
🧘 Zen of Python
"The Zen of Python" is a collection of guiding principles for writing Pythonic code.

To view it in Python, run:

python
Copy
Edit
import this
