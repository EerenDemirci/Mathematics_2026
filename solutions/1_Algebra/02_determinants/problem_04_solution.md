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

This matrix is upper triangular, because all numbers under the diagonal are 0. For a triangular matrix the determinant is the product of the numbers on the diagonal:

$$
\det=2\cdot(-3)\cdot7=-42
$$

Why does this work? If I expand along the first column, only the number 2 is not zero:

$$
\det=2\cdot\det
\begin{pmatrix}
-3 & 5 \\
0 & 7 \\
\end{pmatrix}=2\cdot(-3)\cdot7
$$

All other terms have a 0 in them. The same idea works for every triangular matrix.

**Answer:** $\det=-42$. Rule: the determinant of a triangular matrix is the product of its diagonal entries.

**Check:** in Sarrus' rule every product except the main diagonal contains a 0, so only $2\cdot(-3)\cdot7=-42$ is left.
