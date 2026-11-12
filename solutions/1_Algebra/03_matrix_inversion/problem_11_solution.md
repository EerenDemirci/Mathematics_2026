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

First I find the determinant:

$$
\det A(t)=1\cdot1-t\cdot t=1-t^2
$$

The matrix is invertible when $1-t^2\neq0$, so when $t\neq1$ and $t\neq-1$.

For these $t$ I use the $2\times2$ formula:

$$
A(t)^{-1}=\frac{1}{1-t^2}
\begin{pmatrix}
1 & -t \\
-t & 1 \\
\end{pmatrix}
$$

For $t=1$ or $t=-1$ the number $1-t^2$ is 0, and the formula divides by 0, so it does not work. In these cases the inverse does not exist. For example, for $t=1$ both rows are $(1,1)$, so the rows are dependent.

**Answer:** $A(t)$ is invertible for $t\neq\pm1$, with the inverse above.

**Check:** for $t=2$ the formula gives $-\frac13$ times the matrix with rows $(1,-2)$ and $(-2,1)$. Then $A(2)$ times this matrix (without the factor) is:

$$
\begin{pmatrix}
1 & 2 \\
2 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & -2 \\
-2 & 1 \\
\end{pmatrix}=
\begin{pmatrix}
-3 & 0 \\
0 & -3 \\
\end{pmatrix}
$$

and with the factor $-\frac13$ this is $I$.
