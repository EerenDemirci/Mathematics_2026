# Exercise 6. Solving a System Using the Inverse

## Question

Solve

$$
Ax=b,
$$

where

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix},
$$

using $x=A^{-1}b$. Then substitute the resulting vector back into the equation and check the result.

## Solution

$\det A=6-1=5$, so

$$
A^{-1}=\frac15
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix},\qquad x=A^{-1}b=\frac15
\begin{pmatrix}
15-7 \\
-5+14 \\
\end{pmatrix}=
\begin{pmatrix}
\frac85 \\
\frac95 \\
\end{pmatrix}
$$

Check: $2\cdot\frac85+\frac95=\frac{25}{5}=5$ and $\frac85+3\cdot\frac95=\frac{35}{5}=7$. So $Ax=b$.
