# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program

```python
list1 = [10, 20, 30]

try:
    index = int(input("Enter the index you want to access: "))
    print("Value at index", index, "is", list1[index])
except IndexError:
    print("You're out of list range")

```

## Output

![image](https://github.com/user-attachments/assets/cb3270c3-1822-4213-89a3-2596f2f24185)

## Result
Hence the program is executed successfully.
