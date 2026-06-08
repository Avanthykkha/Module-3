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
s = "google"


reversed_s = s[::-1]


if s == reversed_s:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

## Output
<img width="799" height="119" alt="image" src="https://github.com/user-attachments/assets/88b70d9a-b03f-4c81-bf7e-527326fc349b" />

## Result
The a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions is executed successfully.
