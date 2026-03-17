# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:

# Reg.No: 212222210020
# Name: Prithisha S

A = [[1, 2], [3, 4]]

transpose = [[A[j][i] for j in range(len(A))] for i in range(len(A[0]))]

print("Transpose:", transpose)

## OUTPUT:

Transpose: [[1, 3], [2, 4]]

## RESULT:
The programs were implemented successfully and the outputs were verified.


