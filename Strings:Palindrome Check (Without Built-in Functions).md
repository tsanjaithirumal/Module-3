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
n=input()
pal=n[::-1]
if n==pal:
    print("The given number",n,"is a Palindrome")
else:
    print("The given number",n,"is not a palindrome")
```
## Output
<img width="1178" height="201" alt="Screenshot 2025-11-03 143831" src="https://github.com/user-attachments/assets/17dab01a-4acc-4f7e-98b2-38a72dd9a795" />

## Result
Thus,the program is executed successfull
