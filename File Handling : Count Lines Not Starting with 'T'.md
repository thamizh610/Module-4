# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim:

To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm:

1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program:

```
count = 0
with open("story.txt", "r") as file:
    for line in file:
        if line.strip() and not line.lstrip().startswith('T'):
            count += 1
print("Sum :", count)
```

## Output:

<img width="395" height="167" alt="image" src="https://github.com/user-attachments/assets/c3996f86-2b7f-466f-8f0f-49dc514cac4f" />

## Result:
Thus, the program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T' was executed successfully.
