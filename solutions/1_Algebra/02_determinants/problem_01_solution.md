# Exercise 1. Determinant of a 2×2 Matrix

## Question

Compute

$$
\det
\begin{pmatrix}
3 & -2 \\
5 & 4 \\
\end{pmatrix},\qquad \det
\begin{pmatrix}
1 & 7 \\
2 & 14 \\
\end{pmatrix}.
$$

Which matrix is invertible? Justify your answer.

## Solution

For a $2\times2$ matrix the determinant is $ad-bc$. I use this formula for both matrices:

$$
\det
\begin{pmatrix}
3 & -2 \\
5 & 4 \\
\end{pmatrix}=3\cdot4-(-2)\cdot5=22,\qquad \det
\begin{pmatrix}
1 & 7 \\
2 & 14 \\
\end{pmatrix}=1\cdot14-7\cdot2=0
$$

A matrix is invertible only when its determinant is not zero. The first determinant is 22, so the first matrix is invertible. The second determinant is 0, so the second matrix is not invertible.

**Answer:** the determinants are 22 and 0. Only the first matrix is invertible.

**Check:** in the second matrix the second row is two times the first row: $(2,14)=2\cdot(1,7)$. Rows like this always give determinant 0.
