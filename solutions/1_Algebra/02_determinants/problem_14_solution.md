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

First I find the determinant of $A$:

$$
\det A=1\cdot4-2\cdot k=4-2k
$$

The system has exactly one solution for every $b$ when $A$ is invertible, so when $\det A\neq0$. This means $4-2k\neq0$, so $k\neq2$.

For $k=2$ the system is:

$$
\begin{cases}
x_1+2x_2=b_1, \\
2x_1+4x_2=b_2.
\end{cases}
$$

The left side of the second equation is two times the left side of the first equation.

If $b=(1,2)^T$, the second equation is just two times the first equation. So there is only one real equation, $x_1+2x_2=1$, and it has infinitely many solutions, for example $x_1=1-2s$, $x_2=s$.

If $b=(1,0)^T$, the first equation gives $2x_1+4x_2=2$, but the second equation says $2x_1+4x_2=0$. This is not possible, so there is no solution.

**Answer:** for $k\neq2$ there is exactly one solution for every $b$. For $k=2$: $b=(1,2)^T$ gives infinitely many solutions and $b=(1,0)^T$ gives no solution.

**Check:** for $k=2$, $b=(1,2)^T$ and $s=1$ we get $x=(-1,1)^T$. Then $-1+2=1$ and $-2+4=2$, so it is a solution.
