# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```
def even(n):
    if n==0:
        return
    even(n-1)
    if n%2==0:
        print(n,end=" ")
n=int(input())
even(n)
```
## OUTPUT

<img width="1027" height="270" alt="image" src="https://github.com/user-attachments/assets/12f9bdc7-1046-4003-b685-15ec06f3343f" />


## RESULT
Thus, the program demonstrates how to print all even numbers from 1 to n using a recursive function and has been executed successfully.


