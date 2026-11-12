# Exercise 15. Two Methods for Solving the Same System

## Question

For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}
$$

solve $Ax=b$ in two ways:

1. using $A^{-1}b$,
2. using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

## Solution

Method 1, with the inverse ($\det A=5$):

$$
x=A^{-1}b=\frac15
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}=\frac15
\begin{pmatrix}
13 \\
9 \\
\end{pmatrix}
$$

Method 2, with elimination. I swap the rows and do $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
0 & -5 & \mid & -9 \\
\end{pmatrix}
$$

So $y=\frac95$ and $x=8-\frac{27}{5}=\frac{13}{5}$.

Both methods give $x=\frac{13}{5}$, $y=\frac95$. Elimination had fewer steps (one row operation and back substitution), so it was simpler here. The inverse needs the determinant, the inverse matrix and one more multiplication.
