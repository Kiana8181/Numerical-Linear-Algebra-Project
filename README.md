# Numerical Linear Algebra Project

## Overview
This project focuses on solving systems of linear equations using numerical methods, specifically the LU decomposition method and Gaussian elimination with pivoting. The project is implemented in Python and uses NumPy for matrix operations.

## Live Demo
[Live Demo of the Project](https://kiana8181.github.io/Numerical-Linear-Algebra-Project/)

## Project Structure
The project consists of two main parts:

1. **LU Decomposition Method**
2. **Gaussian Elimination with Pivoting Method**

### Part 1: LU Decomposition Method

This part involves solving the system \(AX = b\) using LU decomposition, where \(A\) is an \(n \times n\) matrix. The process includes checking if LU decomposition is possible, performing the decomposition, and solving the system using forward and backward substitution.

#### Functions

- `is_lu_possible(A)`: Checks if LU decomposition is possible for matrix \(A\) by verifying that all leading principal minors are non-zero.
- `lu_decomposition(A)`: Performs LU decomposition on matrix \(A\) if possible, returning lower triangular matrix \(L\) and upper triangular matrix \(U\).
- `solve_lu(L, U, b)`: Solves the system of equations using forward and backward substitution given matrices \(L\), \(U\), and vector \(b\).

### Part 2: Gaussian Elimination with Pivoting Method

This part focuses on solving the system \(AX = b\) using Gaussian elimination with partial pivoting. The method involves converting input matrices to `float64`, creating an augmented matrix, performing forward elimination with partial pivoting, and conducting backward substitution to find the solution vector.

#### Function

- `gaussian_elimination_pivoting(A, b)`: Solves the system of equations \(AX = b\) using Gaussian elimination with partial pivoting. It prints intermediate steps, including pivot rows and elimination, and returns the solution vector \(x\).

## Conclusion

This project demonstrates the implementation of two fundamental numerical linear algebra techniques to solve systems of linear equations. The provided examples illustrate how to use the defined functions to achieve the desired solutions.

## Date
December 29, 2023

