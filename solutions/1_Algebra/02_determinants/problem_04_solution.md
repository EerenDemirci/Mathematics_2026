# Exercise 4. Triangular Matrix

## Question

Without expanding the determinant, compute

$$
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}.
$$

State the rule for an arbitrary triangular matrix and explain it using this example.

## Solution

The matrix is triangular, so the determinant is the product of the numbers on the diagonal:

$$
\det=2\cdot(-3)\cdot7=-42
$$

This works for every triangular matrix. If I expand along the first column, only the 2 is not zero, so I get $2$ times the small determinant with $-3$ and $7$ on the diagonal. All other terms have a zero in them.
