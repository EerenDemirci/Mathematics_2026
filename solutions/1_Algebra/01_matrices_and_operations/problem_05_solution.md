# Exercise 5. Matrix Times Vector

## Question

Let

$$
A=
\begin{pmatrix}
2 & -1 \\
1 & 3 \\
\end{pmatrix},\qquad x=
\begin{pmatrix}
4 \\
2 \\
\end{pmatrix}.
$$

Compute $Ax$. Then express $Ax$ as a linear combination of the columns of $A$, with coefficients coming from the vector $x$.

## Solution

First I multiply each row of $A$ by the vector $x$:

$$
Ax=
\begin{pmatrix}
2\cdot4+(-1)\cdot2 \\
1\cdot4+3\cdot2 \\
\end{pmatrix}=
\begin{pmatrix}
6 \\
10 \\
\end{pmatrix}
$$

The same result is a combination of the columns of $A$. The numbers from $x$ (4 and 2) are the coefficients:

$$
Ax=4
\begin{pmatrix}
2 \\
1 \\
\end{pmatrix}+2
\begin{pmatrix}
-1 \\
3 \\
\end{pmatrix}=
\begin{pmatrix}
8 \\
4 \\
\end{pmatrix}+
\begin{pmatrix}
-2 \\
6 \\
\end{pmatrix}=
\begin{pmatrix}
6 \\
10 \\
\end{pmatrix}
$$

So a matrix times a vector is a linear combination of the columns of the matrix.

**Answer:** $Ax=(6,10)^T=4\cdot(2,1)^T+2\cdot(-1,3)^T$.

**Check:** the two methods give the same vector $(6,10)^T$.
