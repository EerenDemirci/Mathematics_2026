# Exercise 1. From a System to a Matrix

## Question

Write the system

$$
\begin{cases}
2x-y+z=4, \\
x+3y-2z=1, \\
3x+y+z=7.
\end{cases}
$$

in the form $Ax=b$.
Identify the coefficient matrix, the vector of unknowns, and the right-hand side vector. Explain how each row of the matrix corresponds to one equation.

## Solution

Each equation gives one row of the matrix. The numbers in front of $x$, $y$, $z$ are the coefficients. So the system is $Ax=b$ with:

$$
A=
\begin{pmatrix}
2 & -1 & 1 \\
1 & 3 & -2 \\
3 & 1 & 1 \\
\end{pmatrix},\qquad x=
\begin{pmatrix}
x \\
y \\
z \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
4 \\
1 \\
7 \\
\end{pmatrix}
$$

$A$ is the coefficient matrix, $x$ is the vector of unknowns and $b$ is the right-hand side vector.

Row $i$ of $A$ times the vector $x$ gives the left side of equation $i$. For example, the first row gives $2x-y+z$, and this must be equal to the first number of $b$, which is 4.

**Answer:** $Ax=b$ with $A$, $x$ and $b$ above.

**Check:** I multiply all rows by $x$: $2x-y+z$, $x+3y-2z$, $3x+y+z$. These are exactly the left sides of the three equations, and $b=(4,1,7)^T$ has the right sides.
