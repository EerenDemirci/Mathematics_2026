# Exercise 12. Finding Inverses Without Starting from Scratch

## Question

It is known that

$$
A^{-1}=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}.
$$

Without finding $A$, compute $(3A)^{-1}$, $(A^T)^{-1}$, and $(A^2)^{-1}$. Justify each result using the appropriate property.

## Solution

$(3A)^{-1}=\frac13A^{-1}$, because $3A\cdot\frac13A^{-1}=I$:

$$
(3A)^{-1}=
\begin{pmatrix}
\frac23 & -\frac13 \\
-1 & \frac23 \\
\end{pmatrix}
$$

$(A^T)^{-1}=(A^{-1})^T$, because the transpose of $A^{-1}A=I$ is $A^T(A^{-1})^T=I$:

$$
(A^T)^{-1}=
\begin{pmatrix}
2 & -3 \\
-1 & 2 \\
\end{pmatrix}
$$

$(A^2)^{-1}=(A^{-1})^2$, because $AA\cdot A^{-1}A^{-1}=I$:

$$
(A^2)^{-1}=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}=
\begin{pmatrix}
7 & -4 \\
-12 & 7 \\
\end{pmatrix}
$$
