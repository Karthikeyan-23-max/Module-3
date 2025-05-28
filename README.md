# List Operations in Python: Sum of List Items
## NAME : Karthikeyan C
## REG NO: 212224040152
## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
 L=[153,147,124,102] 
print(sum(L)))
```

## Output
![Screenshot (139)](https://github.com/user-attachments/assets/d732e3a8-dadb-4ab4-91c7-c4c18b31bd03)

## Result
Thus, the program has been executed successfully.



# Regex in Python: Filter Words Without the Letter 'e'

## NAME : Karthikeyan C
## REG NO: 212224040152
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
import re l1=[] 
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] for i in 
items: 
if not re.search(r"e",i): 
l1.append(i) 
print(l1)
```
## Output
![Screenshot (140)](https://github.com/user-attachments/assets/f2d132bc-1988-4d51-957a-ca53442d39e9)

## Result
Thus,the program has been executed successfully.
