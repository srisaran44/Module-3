# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
# Program to calculate sum of list elements
def sum_of_list(lst):
    total = 0
    for item in lst:
        total += item
    return total

# Driver code
numbers = [10, 20, 30, 40, 50]   # Example list
print("List:", numbers)
print("Sum of list elements:", sum_of_list(numbers))

Add code here

## Output
<img width="872" height="602" alt="image" src="https://github.com/user-attachments/assets/7b77571c-b58c-4b5c-aa8b-3729c4758085" />

## Result
