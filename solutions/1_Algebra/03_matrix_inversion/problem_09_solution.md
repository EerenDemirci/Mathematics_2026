# Exercise 9. Matrix Equation

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}.
$$

Solve the equation $AX=B$ for $X$. Before calculating, decide on which side of the equation $A^{-1}$ must be used. Then check the result by computing $AX$.

## Solution

In $AX=B$ the matrix $A$ is on the left side of $X$. So I must multiply by $A^{-1}$ from the left on both sides:

$$
A^{-1}AX=A^{-1}B\quad\Longrightarrow\quad X=A^{-1}B
$$

($XA^{-1}$ or $BA^{-1}$ would be wrong, because matrices do not commute.)

The determinant of $A$ is 1, so:

$$
A^{-1}=
\begin{pmatrix}
1 & -2 \\
0 & 1 \\
\end{pmatrix}
$$

Now I compute $X$:

$$
X=A^{-1}B=
\begin{pmatrix}
1 & -2 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}=
\begin{pmatrix}
3-4 & 1-8 \\
2 & 4 \\
\end{pmatrix}=
\begin{pmatrix}
-1 & -7 \\
2 & 4 \\
\end{pmatrix}
$$

**Answer:** $X=A^{-1}B$ is the matrix above.

**Check:**

$$
AX=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
-1 & -7 \\
2 & 4 \\
\end{pmatrix}=
\begin{pmatrix}
-1+4 & -7+8 \\
2 & 4 \\
\end{pmatrix}=
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}=B
$$
