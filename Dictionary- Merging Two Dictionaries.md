## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```python
def merge(dict1, dict2):
    merged = {**dict1, **dict2}
    print("Merged dictionary:", merged)

dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

merge(dict1, dict2)

```

## Output

![image](https://github.com/user-attachments/assets/da9ac727-bcaf-4611-854a-4c15110135c3)

## Result
Hence the program is executed successfully.
