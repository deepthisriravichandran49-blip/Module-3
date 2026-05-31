# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
# Program to check if 'n' and 8 exist in a tuple

t = ('a', 'n', 5, 8, 'z')

if 'n' in t:
    print("'n' exists in the tuple")
else:
    print("'n' does not exist in the tuple")

if 8 in t:
    print("8 exists in the tuple")
else:
    print("8 does not exist in the tuple")
```
## Output
```
'n' exists in the tuple
8 exists in the tuple
```

## Result
The output has been verified successfully.
