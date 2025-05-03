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
Developed by: Preethika N
REG NO : 212223040130
```
```
import re l1=[]
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items: 
  if not re.search(r"e",i): 
      l1.append(i) 
print(l1) 
```
## Output
![image](https://github.com/user-attachments/assets/253de63d-8e9f-40e0-bce1-baf808478af7)

## Result
Thus, the program has been successfully executed.
