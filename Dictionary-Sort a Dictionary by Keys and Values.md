# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program

# Dictionary - Sort by Keys and Values

d = {'b': 3, 'a': 1, 'd': 4, 'c': 2}

# Sort by keys

sorted_by_keys = dict(sorted(d.items()))

# Sort by values

sorted_by_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original Dictionary:", d)

print("Sorted by Keys:", sorted_by_keys)

print("Sorted by Values:", sorted_by_values)

## Sample Output

<img width="640" height="469" alt="Screenshot 2026-05-31 112143" src="https://github.com/user-attachments/assets/a2e82ca3-c960-4eae-9e94-c86ae764a0b3" />

## Result
Thus, the Python program to sort a dictionary by keys and values was written and executed successfully.

