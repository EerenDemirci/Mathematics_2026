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

By definition, $B=A^{-1}$ when $AB=I$ and $BA=I$. So I compute both products.

$$
AB=
\begin{pmatrix}
2\cdot1+1\cdot(-1) & 2\cdot(-1)+1\cdot2 \\
1\cdot1+1\cdot(-1) & 1\cdot(-1)+1\cdot2 \\
\end{pmatrix}=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

$$
BA=
\begin{pmatrix}
1\cdot2+(-1)\cdot1 & 1\cdot1+(-1)\cdot1 \\
-1\cdot2+2\cdot1 & -1\cdot1+2\cdot1 \\
\end{pmatrix}=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

Both products are the identity matrix $I$. This is exactly the definition of the inverse.

**Answer:** yes, $B=A^{-1}$.

**Check:** $AB=I$ and $BA=I$, so $B$ undoes $A$ from both sides.
