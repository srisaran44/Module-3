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
# Program to check if a string is palindrome using loops
def is_palindrome(s):
    length = len(s)
    for i in range(length // 2):
        if s[i] != s[length - i - 1]:
            return False
    return True

# Driver code
word = "google"
if is_palindrome(word):
    print(word, "is a Palindrome.")
else:
    print(word, "is not a Palindrome.")

Add code here

## Output
<img width="1115" height="856" alt="image" src="https://github.com/user-attachments/assets/e8efae13-714a-4003-8e90-7f627a0279ee" />


## Result
