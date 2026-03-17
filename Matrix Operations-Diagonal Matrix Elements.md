# Matrix Operations-Diagonal Matrix Elements Printer 🧮

This Python program reads a matrix of any size from the user and prints **only the diagonal elements**, leaving other elements blank in the output.

## 📌 Aim

To write a Python program that prints only the diagonal elements of a given matrix.

## 🧠 Algorithm

1. Read the number of rows and columns from the user.
2. Initialize an empty matrix of size `rows × columns`.
3. Populate the matrix with user input.
4. Display the full matrix.
5. Iterate through the matrix and:
   - If `i == j`, print the element (main diagonal).
   - Else, print a blank space.
6. Print a newline after each row.

## 🖥️ Program

# Reg.No: 212222210020
# Name: Prithisha S

A = [[1, 2], [3, 4]]

diagonal = [A[i][i] for i in range(len(A))]

print("Diagonal elements:", diagonal)

### Output:

Diagonal elements: [1, 4]

## Result
The programs were implemented successfully and the outputs were verified.
