# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re

# Input list
items = ["apple", "banana", "grape", "kiwi", "mango", "pear"]

# Filter elements that do NOT contain 'e'
result = [item for item in items if not re.search("e", item)]

print("Original List:", items)
print("Elements without 'e':", result)
```
## Output
```
Original List: ['apple', 'banana', 'grape', 'kiwi', 'mango', 'pear']
Elements without 'e': ['banana', 'kiwi', 'mango']
```

## Result
The output has been verified successfully.
