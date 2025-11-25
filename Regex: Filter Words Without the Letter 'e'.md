# Regex in Python: Filter Words Without the Letter 'e'

## Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

pattern = re.compile("^[^e]+$")

result = [word for word in items if pattern.match(word)]
print(result)
```

## Output

<img width="412" height="157" alt="image" src="https://github.com/user-attachments/assets/a1a09019-b5ac-4c85-a01d-58340d4cb93d" />

## Result

Thus the output is executed successfully.
