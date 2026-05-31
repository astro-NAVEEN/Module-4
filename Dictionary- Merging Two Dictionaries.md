## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

# Dictionary Operations in Python: Merging Two Dictionaries

def merge(dict1, dict2):

    return {**dict1, **dict2}

dict1 = {'a': 1, 'b': 2}

dict2 = {'b': 5, 'c': 3}

result = merge(dict1, dict2)

print("Merged Dictionary:", result)

## Output
<img width="571" height="324" alt="Screenshot 2026-05-31 111809" src="https://github.com/user-attachments/assets/33c2fb75-6244-4c22-aef8-4758456a78b2" />


## Result
Thus, the Python program to merge two dictionaries using the unpacking operator was written and executed successfully.
