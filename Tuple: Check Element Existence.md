# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
Add code here
# Program to check existence of elements in a tuple
def check_elements(tup):
    if 'n' in tup:
        print("'n' exists in the tuple.")
    else:
        print("'n' does not exist in the tuple.")
    
    if 8 in tup:
        print("8 exists in the tuple.")
    else:
        print("8 does not exist in the tuple.")

# Driver code
my_tuple = ('a', 'b', 'n', 5, 8, 12)
print("Tuple:", my_tuple)
check_elements(my_tuple)


## Output
<img width="1109" height="711" alt="image" src="https://github.com/user-attachments/assets/a9d52369-ae34-45b4-bc48-fdbc85836b8c" />


## Result
