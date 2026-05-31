# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
# Program to find the sum of all elements in a list

n = int(input("Enter the number of elements: "))

numbers = []

for i in range(n):
    num = int(input("Enter element: "))
    numbers.append(num)

total = sum(numbers)

print("The list is:", numbers)
print("Sum of all elements =", total)
```
## Output
```
Enter the number of elements: 5
Enter element: 10
Enter element: 20
Enter element: 30
Enter element: 40
Enter element: 50

The list is: [10, 20, 30, 40, 50]
Sum of all elements = 150
```

## Result
The output has been verified successfully.
