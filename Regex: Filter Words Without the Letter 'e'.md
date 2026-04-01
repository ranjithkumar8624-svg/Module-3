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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner'] z=[] s=set("e") for i in items: if not s
&set(i): z.append(i) print(z)
## Output
<img width="652" height="107" alt="image" src="https://github.com/user-attachments/assets/22aa31ac-167e-4630-9976-b5b4d4eb02f5" />

## Result
Thus the Python program that filters out and returns all elements from a list that do not
contain the letter 'e' , using regular expressions (regex) was successfully completed
