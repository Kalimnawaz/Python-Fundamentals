# Day 5: Python Lists and Tuples

This notebook (`Day5.ipynb`) covers fundamental concepts related to Python list and tuple data types, focusing on their manipulation, organization, and usage in basic programming scenarios.

---

## Topics Covered

### 1. Lists in Python

- **Introduction to Lists**
  - Creation of lists
  - Printing and checking the type of a list

- **Organizing Lists**
  - Sorting lists alphabetically (A-Z, Z-A)
    - Temporary sorting: `sorted(list_name)`
    - Permanent sorting: `list_name.sort()`
  - Reversing lists: `list_name.reverse()`
  - Counting elements: `len(list_name)`

- **Slicing Lists**
  - Accessing sub-parts using slicing `[start:stop:step]`
  - Inclusive/exclusive nature of slicing
  - Examples of extracting elements or skipping steps

### 2. Tuples in Python

- **Introduction to Tuples**
  - Definition and immutability
  - Tuple creation and syntax
  - Differences between lists and tuples

- **Tuple Operations**
  - Accessing tuple elements by index
  - Attempting to modify tuples (and resulting errors)

---

## Learning Outcomes

By the end of this notebook, you will be able to:
- Organize, sort, and manipulate Python lists.
- Understand and perform slicing operations on lists.
- Grasp the concept of tuples, their immutability, and when to use them.

---

## How to Use

1. Open `Day5.ipynb` in Jupyter Notebook or any compatible Python environment.
2. Run each cell sequentially to practice and observe the results.
3. Modify the code and experiment with lists and tuples for deeper understanding.

---

## Example Snippets

```python
# List sorting (temporary)
cars = ['bmw', 'tata', 'suzuki', 'audi', 'toyota', 'benz']
print(sorted(cars))  # ['audi', 'benz', 'bmw', 'suzuki', 'tata', 'toyota']

# List slicing
students = ['anika', 'arpiat', 'bhushan', 'bhanu', 'chandra', 'cynthia', 'danish']
print(students[0:2])  # ['anika', 'arpiat']

# Tuple immutability
dimensions = (20, 50)
# dimensions[0] = 30  # This will raise a TypeError
```

---

## Additional Notes

- Lists are mutable (can be changed), while tuples are immutable (cannot be changed after creation).
- Use tuples for fixed data, lists for collections that may change.

---

Happy Coding!
