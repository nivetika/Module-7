# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
```
def sad(num):
    if num==0:
        return num
    return (num%10+sad(num//10))

num=int(input())
print(sad(num))
```

## OUTPUT
<img width="321" height="240" alt="image" src="https://github.com/user-attachments/assets/7fc82e30-1b90-4c2d-9754-9f5c273878fc" />


## RESULT
Thus to write a python program to calculate the **sum of all digits** in a number using **recursion** is created and executed successfully.
