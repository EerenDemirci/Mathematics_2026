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

I want to make zeros under the diagonal. The operation "add a multiple of one row to another row" does not change the determinant.

Step 1: $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3+R_1$. The determinant does not change:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 6 & 5 \\
\end{pmatrix}
$$

Step 2: $R_3\leftarrow R_3+2R_2$. The determinant does not change:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 0 & -7 \\
\end{pmatrix}
$$

Step 3: now the matrix is triangular, so I multiply the diagonal:

$$
\det A=1\cdot(-3)\cdot(-7)=21
$$

**Answer:** $\det A=21$.

**Check:** I expand the start matrix along the first row:

$$
\det A=1\cdot(2-0)-2\cdot(4-0)+3\cdot(8+1)=2-8+27=21
$$
