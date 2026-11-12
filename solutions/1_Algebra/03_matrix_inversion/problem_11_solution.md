# Exercise 11. Parameter and Invertibility

## Question

For

$$
A(t)=
\begin{pmatrix}
1 & t \\
t & 1 \\
\end{pmatrix}
$$

find all $t$ for which the matrix is invertible, and then give a formula for $A(t)^{-1}$. Explain what happens to this formula at the excluded values.

## Solution

$$
\det A(t)=1-t^2
$$

The matrix is invertible when $1-t^2\neq0$, so for $t\neq1$ and $t\neq-1$. Then:

$$
A(t)^{-1}=\frac{1}{1-t^2}
\begin{pmatrix}
1 & -t \\
-t & 1 \\
\end{pmatrix}
$$

For $t=\pm1$ we would divide by 0, so the formula does not work and there is no inverse. For example for $t=1$ both rows are $(1,1)$.
