# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
# Program to check whether "google" is a palindrome

string = "google"

reverse = ""

for char in string:
    reverse = char + reverse

if string == reverse:
    print(string, "is a Palindrome")
else:
    print(string, "is Not a Palindrome")
```
## Output
```
google is Not a Palindrome
```

## Result
The output has been verified successfully.
