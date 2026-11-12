# Exercise 10. Inverse of a Diagonal Matrix

## Question

Given

$$
D=
\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix},\qquad E=
\begin{pmatrix}
2 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}.
$$

Without using Gauss–Jordan elimination, decide which matrix is invertible. For the invertible matrix, give the inverse and check the result by multiplication.

## Solution

A diagonal matrix is invertible only if there is no 0 on the diagonal. $D$ has $2,-3,5$, so it is invertible. $E$ has a 0, so it is not invertible.

$$
D^{-1}=
\begin{pmatrix}
\frac12 & 0 & 0 \\
0 & -\frac13 & 0 \\
0 & 0 & \frac15 \\
\end{pmatrix}
$$

Check: $DD^{-1}$ has $2\cdot\frac12=1$, $(-3)\cdot(-\frac13)=1$ and $5\cdot\frac15=1$ on the diagonal, so it is $I$.
