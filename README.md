- Dimensionality reduction
- Feature extraction
- Covariance matrix analysis

---

### 8. Solve Linear System

```python
np.linalg.solve(A, b)
```

Numerically solves the linear system:

\[
Ax = b
\]

For the given values:

\[
\begin{bmatrix}
2 & 1 \\
1 & 3
\end{bmatrix}
\begin{bmatrix}
x_1 \\
x_2
\end{bmatrix}
=
\begin{bmatrix}
1 \\
2
\end{bmatrix}
\]

The solution is:

\[
x =
\begin{bmatrix}
0.2 \\
0.6
\end{bmatrix}
\]

`np.linalg.solve(A, b)` is generally more numerically stable than calculating:

```python
np.linalg.inv(A).dot(b)
```

---

## OUTPUT

```text
Matrix A:
 [[2. 1.]
  [1. 3.]]

Transpose A^T:
 [[2. 1.]
  [1. 3.]]

Inverse A^-1:
 [[ 0.6 -0.2]
  [-0.2  0.4]]

Eigenvalues: [3.3028 1.6972]

Solve A x = b --> x: [0.2 0.6]
```

---

## RESULT

Students successfully performed concrete matrix computations using NumPy and learned how to solve linear systems.

The experiment also demonstrates the relationship between matrix operations and Machine Learning concepts such as **Linear Regression** and **Principal Component Analysis (PCA)**.

---

## THEORY

Linear algebra is an important mathematical foundation of Machine Learning.
