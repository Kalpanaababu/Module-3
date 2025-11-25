# Strings-Palindrome Check in Python (Without Built-in Functions)

## Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

def palindrome(a):
  
    mid = (len(a)-1)//2    
    start = 0              
    last = len(a)-1
    flag = 0
 
    
    # Add your code here
    if flag == 0:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
        
        
string =input()
palindrome(string)
```

## Output

<img width="874" height="206" alt="image" src="https://github.com/user-attachments/assets/8f12491b-afa9-4904-9fdf-7386b2a7dfe2" />

## Result

Thus the output is executed successfully.
