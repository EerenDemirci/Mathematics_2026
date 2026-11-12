# Exercise 12. A Parameter Revealed by a Row Operation

## Question

For

$$
A(t)=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & t \\
0 & 1 & 1 \\
\end{pmatrix}
$$

find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation

$$
R_2\leftarrow R_2-2R_1
$$

and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

## Solution

After $R_2\leftarrow R_2-2R_1$ (no change of the determinant):

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 0 & t-6 \\
0 & 1 & 1 \\
\end{pmatrix}
$$

I swap the last two rows, so the sign changes, and the matrix becomes triangular with $1$, $1$, $t-6$ on the diagonal:

$$
\det A(t)=-(t-6)=6-t
$$

The matrix is not invertible for $t=6$. For $t=6$ the second row $(2,4,6)$ is two times the first row $(1,2,3)$, so the rows are dependent.
