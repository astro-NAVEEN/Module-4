# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program

# Create sample file (for testing)

with open("story.txt", "w") as file:

    file.write("Today is a sunny day.\n")
    file.write("The weather is nice.\n")
    file.write("This is a simple story.\n")
    file.write("There are many lines in this file.\n")
    file.write("Text processing is easy in Python.\n")

# Count lines not starting with 'T'

count = 0

with open("story.txt", "r") as file:

    for line in file:
        if line and line[0] != 'T':
            count += 1

print("Number of lines not starting with 'T':", count)

## Output
<img width="660" height="340" alt="Screenshot 2026-05-31 112648" src="https://github.com/user-attachments/assets/e2b1d4d1-084b-406b-9b37-3ac4aabb001d" />


## Result
Thus, the Python program to count the number of lines in a file that do not start with the letter 'T' was written and executed successfully.
