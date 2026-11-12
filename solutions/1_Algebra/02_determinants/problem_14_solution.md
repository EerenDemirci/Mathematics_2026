# Exercise 14. A System of Equations and the Determinant

## Question

Consider the system $Ax=b$, where

$$
A=
\begin{pmatrix}
1 & 2 \\
k & 4 \\
\end{pmatrix}.
$$

For which values of $k$ does the system have exactly one solution for every $b$? For the remaining value, give an example of a right-hand side $b$ for which the system has infinitely many solutions, and an example for which it has no solution.

## Solution

$$
\det A=4-2k
$$

The system has exactly one solution for every $b$ when $\det A\neq0$, so when $k\neq2$.

For $k=2$ the second equation has the left side $2x_1+4x_2$, which is 2 times the first one.

- $b=(1,2)^T$: the second equation is just 2 times the first, so there are infinitely many solutions.
- $b=(1,0)^T$: the first equation gives $2x_1+4x_2=2$, but the second says $2x_1+4x_2=0$. So there is no solution.
