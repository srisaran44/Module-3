# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
Add Code Here
# Program to remove character at a given index
def remove_char_at_index(s, index):
    if index < 0 or index >= len(s):
        print("Invalid index!")
        return s
    # Slice before and after the index
    return s[:index] + s[index+1:]

# Driver code
user_string = input("Enter a string: ")
pos = int(input("Enter the index to remove: "))

result = remove_char_at_index(user_string, pos)
print("String after removal:", result)


## Output
<img width="1196" height="612" alt="image" src="https://github.com/user-attachments/assets/f6f99c67-d556-4a16-86d8-c164a1b1c7c5" />


## Result
