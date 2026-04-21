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
Add code here
import re

# Function to filter words without 'e'
def filter_without_e(words):
    # Regex: ^[^eE]*$ → matches strings with no 'e' or 'E'
    pattern = re.compile(r'^[^eE]*$')
    return [word for word in words if pattern.match(word)]

# Driver code
words_list = ["apple", "banana", "grape", "kiwi", "mango", "fig", "plum"]
result = filter_without_e(words_list)

print("Original list:", words_list)
print("Filtered list (no 'e'):", result)


## Output
<img width="1110" height="734" alt="image" src="https://github.com/user-attachments/assets/b3263694-6c8a-4eb7-8005-235de1c9e540" />


## Result
