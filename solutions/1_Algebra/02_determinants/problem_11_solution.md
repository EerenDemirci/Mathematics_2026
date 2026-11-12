# Exercise 11. Shortening the Calculation with Row Operations

## Question

Compute

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
1 & 3 & 4 \\
1 & 4 & 6 \\
\end{pmatrix}
$$

by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

## Solution

$R_2\leftarrow R_2-R_1$ and $R_3\leftarrow R_3-R_1$, then $R_3\leftarrow R_3-2R_2$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}
$$

The matrix is triangular, so $\det=1\cdot1\cdot1=1$.

I only added multiples of one row to another row. This kind of operation does not change the determinant.
