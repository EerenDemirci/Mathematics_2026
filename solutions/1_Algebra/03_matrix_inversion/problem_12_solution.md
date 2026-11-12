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

I use three properties of the inverse.

**$(3A)^{-1}$.** For a number $c\neq0$, $(cA)^{-1}=\frac1cA^{-1}$, because $(cA)\cdot\frac1cA^{-1}=AA^{-1}=I$:

$$
(3A)^{-1}=\frac13A^{-1}=
\begin{pmatrix}
\frac23 & -\frac13 \\
-1 & \frac23 \\
\end{pmatrix}
$$

**$(A^T)^{-1}$.** The inverse of the transpose is the transpose of the inverse, because $A^T(A^{-1})^T=(A^{-1}A)^T=I$:

$$
(A^T)^{-1}=(A^{-1})^T=
\begin{pmatrix}
2 & -3 \\
-1 & 2 \\
\end{pmatrix}
$$

**$(A^2)^{-1}$.** $(A^2)^{-1}=(A^{-1})^2$, because $AA\cdot A^{-1}A^{-1}=I$:

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

**Answer:** the three matrices above.

**Check:** $A$ is the inverse of $A^{-1}$. The determinant of $A^{-1}$ is $4-3=1$, so $A$ has rows $(2,1)$ and $(3,2)$. Then $A^2$ has rows $(7,4)$ and $(12,7)$, its determinant is $49-48=1$, and its inverse has rows $(7,-4)$ and $(-12,7)$. This is the same as above.
