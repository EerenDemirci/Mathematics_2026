# Exercise 2. Formula for a 2×2 Matrix

## Question

Find the inverse of

$$
A=
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
$$

using the formula for a $2\times2$ matrix. At the end, check the result by computing one product with $A$.

## Solution

For a $2\times2$ matrix with entries $a,b,c,d$ the formula is: swap $a$ and $d$, change the sign of $b$ and $c$, and divide by the determinant.

First I find the determinant:

$$
\det A=3\cdot4-2\cdot5=2
$$

It is not 0, so the inverse exists. Now I use the formula:

$$
A^{-1}=\frac12
\begin{pmatrix}
4 & -2 \\
-5 & 3 \\
\end{pmatrix}=
\begin{pmatrix}
2 & -1 \\
-\frac52 & \frac32 \\
\end{pmatrix}
$$

**Answer:** $A^{-1}$ is the matrix above.

**Check:** I multiply $A$ by $A^{-1}$ and I must get $I$:

$$
AA^{-1}=
\begin{pmatrix}
3\cdot2+2\cdot(-\frac52) & 3\cdot(-1)+2\cdot\frac32 \\
5\cdot2+4\cdot(-\frac52) & 5\cdot(-1)+4\cdot\frac32 \\
\end{pmatrix}=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$
