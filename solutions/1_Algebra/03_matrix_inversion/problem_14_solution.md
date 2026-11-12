# Exercise 14. A Matrix That Is Its Own Inverse

## Question

Assume that a square matrix $A$ satisfies

$$
A^2=I.
$$

Show that

$$
A^{-1}=A.
$$

Then give an example of a $2\times2$ matrix different from $I$ and $-I$ that satisfies this condition, and verify it by multiplication.

## Solution

$A^2=I$ means $A\cdot A=I$. The inverse is the matrix that gives $I$ when we multiply it with $A$, and here $A$ itself does this. So $A^{-1}=A$.

Example:

$$
A=
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix},\qquad A^2=
\begin{pmatrix}
0+1 & 0+0 \\
0+0 & 1+0 \\
\end{pmatrix}=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

This matrix is not $I$ or $-I$, and $A^2=I$.
