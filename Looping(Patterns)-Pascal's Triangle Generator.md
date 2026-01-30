# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
# Pascal's Triangle

n = int(input("Enter number of rows: "))

for i in range(n):
    # print spaces
    for space in range(n - i - 1):
        print(" ", end="")

    value = 1
    for j in range(i + 1):
        print(value, end=" ")
        value = value * (i - j) // (j + 1)
    print()


```

## Sample Output
<img width="420" height="160" alt="image" src="https://github.com/user-attachments/assets/15ddc96f-98ba-43d8-8e54-963247d9b5b6" />


## Result
the code is executed successfully

