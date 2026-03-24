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
<img width="523" height="175" alt="image" src="https://github.com/user-attachments/assets/1a4d56c9-1df2-4c17-88f0-661f1adfda0e" />

## Output
<img width="193" height="43" alt="image" src="https://github.com/user-attachments/assets/4acde6d2-a3dd-4c22-b548-349212781799" />

## Result
Thus, the program has been successfully executed.
