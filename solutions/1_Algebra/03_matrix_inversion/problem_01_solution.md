# Exercise 1. Definition of the Inverse

## Question

For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

check, without using a formula, whether $B=A^{-1}$. Compute $AB$ and $BA$ and relate the result to the definition of the inverse.

## Solution

$$
AB=
\begin{pmatrix}
2-1 & -2+2 \\
1-1 & -1+2 \\
\end{pmatrix}=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad BA=
\begin{pmatrix}
2-1 & 1-1 \\
-2+2 & -1+2 \\
\end{pmatrix}=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

Both products give $I$. The inverse is defined as the matrix with $AB=BA=I$, so $B=A^{-1}$.
