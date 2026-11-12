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

**Method 1: $x=A^{-1}b$.** The determinant is $2\cdot3-1\cdot1=5$:

$$
A^{-1}=\frac15
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix},\qquad x=\frac15
\begin{pmatrix}
21-8 \\
-7+16 \\
\end{pmatrix}=
\begin{pmatrix}
\frac{13}{5} \\
\frac95 \\
\end{pmatrix}
$$

**Method 2: Gaussian elimination.** I swap the rows so that the first number is 1, and then I do $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
2 & 1 & \mid & 7 \\
\end{pmatrix}\ \longrightarrow\
\begin{pmatrix}
1 & 3 & \mid & 8 \\
0 & -5 & \mid & -9 \\
\end{pmatrix}
$$

So $y=\frac95$, and $x=8-3\cdot\frac95=\frac{13}{5}$.

Both methods give the same solution. Method 1 needs three steps: determinant, inverse matrix, and a matrix-vector product. Method 2 needs one row operation and back substitution. For one system, elimination was simpler. The inverse is better when we have many systems with the same $A$.

**Answer:** $x=\frac{13}{5}$, $y=\frac95$. Elimination was simpler here.

**Check:** $2\cdot\frac{13}{5}+\frac95=\frac{35}{5}=7$ and $\frac{13}{5}+3\cdot\frac95=\frac{40}{5}=8$.
