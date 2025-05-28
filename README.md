# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
items=[1,2,-8]
s=0
for i in items:
    s+=i
print(s)
```
## Output
![image](https://github.com/user-attachments/assets/2981708f-b891-4166-a2dc-e5d92370ab29)

## Result
Thus the program that calculates the sum of all elements in a list has been executed successfully.

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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1,l2=[],[]
for i in items:
    for x in i:
        if x=="e":
            l1.append(i)
            break
for a in items:
    if a not in l1:
        l2.append(a)
print(l2)
```
## Output
![image](https://github.com/user-attachments/assets/ec8e8b14-5130-4599-8469-c78f0b9ddddf)

## Result
Thus the program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) has been executed successfully.

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
```
def remove(s):
    new_string = s[:3] +s[4:]
    print(new_string)
```
## Output
![image](https://github.com/user-attachments/assets/815af042-1af5-4214-ba49-25bbc06509b0)

## Result
Thus the program that accepts a string and removes the character at a specified index has been executed successfully.

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
def palindrome(a):
    l=[]
    for i in a:
        l.append(i)
    l2=l[::-1]
    if l==l2:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
s=input() 
palindrome(s)
```

## Output
![image](https://github.com/user-attachments/assets/f6aa6a64-f9bb-4af5-b8ff-ada94a5b153d)

## Result
Thus the program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions has been executed successfully.

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
t = ("s", 8, "a", "v", "n", "g", "u", "r", "c", "e")
print(8 in t)
print('n' in t)
```
## Output
![image](https://github.com/user-attachments/assets/63832f72-e6e4-4029-a988-50201630d0e5)

## Result
Thus the program that checks if the element 'n' and the element 8 exist within a given tuple has been executed successfully.
