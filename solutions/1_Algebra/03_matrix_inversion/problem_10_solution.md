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

For a diagonal matrix, the determinant is the product of the diagonal numbers. A diagonal matrix is invertible only when no number on the diagonal is 0.

$D$ has $2,-3,5$ on the diagonal. None of them is 0, so $D$ is invertible ($\det D=-30$).

$E$ has a 0 on the diagonal. Its second row is all zeros, so $\det E=0$ and $E$ is not invertible.

The inverse of $D$ has the reciprocal $\frac1d$ of each diagonal number $d$:

$$
D^{-1}=
\begin{pmatrix}
\frac12 & 0 & 0 \\
0 & -\frac13 & 0 \\
0 & 0 & \frac15 \\
\end{pmatrix}
$$

**Answer:** $D$ is invertible with $D^{-1}$ above. $E$ is not invertible.

**Check:** $DD^{-1}$ is diagonal with $2\cdot\frac12=1$, $(-3)\cdot(-\frac13)=1$ and $5\cdot\frac15=1$, so $DD^{-1}=I$.
