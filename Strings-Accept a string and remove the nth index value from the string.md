# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
Add Code Here
~~~
def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ''
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a

string = input("Enter a string: ")
result = remove(string)
print("Result:", result)
~~~
## Output
![Screenshot 2025-05-20 110114](https://github.com/user-attachments/assets/704ef43c-7ce2-441a-8c26-aac6b77fd7be)

## Result
Thus the program has been successfully executed
