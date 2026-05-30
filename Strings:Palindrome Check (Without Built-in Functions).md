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
string = "google"

rev = string[::-1]

if string == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
```

## Output
<img width="203" height="48" alt="image" src="https://github.com/user-attachments/assets/d37e18c0-efd6-493f-a23e-fd5907c362e9" />

## Result
Thus, the Python program to check whether the string "google" is a palindrome or not was executed successfully and the output was verified.
