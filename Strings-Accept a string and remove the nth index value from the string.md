# Module-3
# Strings-Remove Nth Index Character from a String

## Aim
To write a Python program that accepts a string and removes the character at a specified index.

## Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

def remove(s):
    n = int(input("Enter index: "))
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a

string = input("Enter a string: ")
print(remove(string))
```

## Output

<img width="960" height="207" alt="image" src="https://github.com/user-attachments/assets/224ad028-f01e-414a-a636-9cc2e05211da" />


<img width="958" height="201" alt="image" src="https://github.com/user-attachments/assets/87cc18c8-0639-443c-854f-449ed092b9ef" />

## Result

Thus the output is executed successfully.
