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

Add code here
~~~
s = "google"
reversed_s = s[::-1]

if s == reversed_s:
    print("Result: The string is a palindrome.")
else:
    print("Result: The string is not a palindrome.")
~~~
## Output
![Screenshot 2025-05-20 111129](https://github.com/user-attachments/assets/26d18fc5-a6fd-45f3-a1f1-604912a9af9f)

## Result
Thus the program has been successfully executed
