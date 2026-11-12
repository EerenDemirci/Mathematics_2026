# Exercise 5. Row Operations

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 1 & 0 \\
-1 & 4 & 2 \\
\end{pmatrix}
$$

find $\det A$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

## Solution

$R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3+R_1$ (adding a multiple of a row, so the determinant does not change):

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 6 & 5 \\
\end{pmatrix}
$$

$R_3\leftarrow R_3+2R_2$ (also no change):

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 0 & -7 \\
\end{pmatrix}
$$

Now the matrix is triangular:

$$
\det A=1\cdot(-3)\cdot(-7)=21
$$
