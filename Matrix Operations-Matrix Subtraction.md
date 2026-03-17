# # ➖ Matrix Operations-Matrix Subtraction in Python

## 🎯 AIM:
To write a Python program that reads two matrices from the user and performs matrix subtraction.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` for rows and columns
3. Get the values of `r` and `c` from the user
4. Define a function `create_matrix(n, m)` to:
   - Prompt user for each matrix element
   - Append each row to form a complete matrix
5. Call the `create_matrix()` function twice to read two matrices `A` and `B`
6. Define a loop to subtract the elements of matrix `B` from matrix `A`
7. Store the result in a new matrix `C`
8. Print the resulting matrix `C`
9. **Stop**

---

## 💻 PROGRAM:

# Reg.No: 212222210020
# Name: Prithisha S

A = [[1, 2], [3, 4]]
B = [[1, 1], [1, 1]]

result = [[A[i][j] - B[i][j] for j in range(2)] for i in range(2)]

print("Result:", result)

## OUTPUT:

Result: [[0, 1], [2, 3]]

## RESULT:
The programs were implemented successfully and the outputs were verified.
