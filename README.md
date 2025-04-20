# 🔢 LUWizard: A Gaussian Elimination Solver with Benchmarking

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)

An educational project implementing LU decomposition using **Gaussian Elimination with Partial Pivoting** from scratch in Python. This solver is benchmarked against SciPy’s built-in LU solver in terms of both speed and numerical accuracy.

---

## 📁 Project Structure


---

## 🚀 Features

- Implements LU decomposition with **partial pivoting** (no use of built-in LU routines)
- Handles pivot breakdown gracefully
- Computes:
  - Permutation matrix `P`
  - Lower triangular matrix `L`
  - Upper triangular matrix `U`
- Solves `Ax = b` using forward and backward substitution
- Benchmarks against SciPy's `lu_factor` and `lu_solve`
- Reports:
  - Time for LU decomposition
  - Time for solving the system
  - ‖PA − LU‖ (matrix norm)
  - ‖Ax₀ − b‖ (vector norm)

---

## 📊 Benchmarking

Tested with random square matrices of sizes:

n = 10,50,100,400,800,1000


Comparison tables summarize:
- LU factorization time
- Substitution time
- Matrix norm difference
- Vector norm difference
