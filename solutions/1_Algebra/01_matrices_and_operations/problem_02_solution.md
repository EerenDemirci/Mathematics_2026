# Exercise 2. Addition and Scalar Multiplication

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 \\
-1 & 3 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
4 & -2 \\
0 & 5 \\
\end{pmatrix}
$$

compute

$$
A+B,\qquad A-B,\qquad 3A-2B.
$$

Explain why matrix addition is possible only for matrices of the same size.

## Solution

Matrices of the same size are added and subtracted entry by entry. Both $A$ and $B$ are $2\times2$, so this is possible.

$$
A+B=
\begin{pmatrix}
1+4 & 2-2 \\
-1+0 & 3+5 \\
\end{pmatrix}=
\begin{pmatrix}
5 & 0 \\
-1 & 8 \\
\end{pmatrix},\qquad A-B=
\begin{pmatrix}
1-4 & 2+2 \\
-1-0 & 3-5 \\
\end{pmatrix}=
\begin{pmatrix}
-3 & 4 \\
-1 & -2 \\
\end{pmatrix}
$$

For $3A-2B$ I first multiply every entry by the number, and then I subtract:

$$
3A=
\begin{pmatrix}
3 & 6 \\
-3 & 9 \\
\end{pmatrix},\qquad 2B=
\begin{pmatrix}
8 & -4 \\
0 & 10 \\
\end{pmatrix},\qquad 3A-2B=
\begin{pmatrix}
-5 & 10 \\
-3 & -1 \\
\end{pmatrix}
$$

Addition needs the same size because every entry of $A$ needs a partner entry of $B$ in the same place. If the sizes are different, some places exist only in one matrix, so the sum is not defined.

**Answer:** the three matrices above.

**Check:** if I add $A+B$ and $A-B$, I must get $2A$:

$$
(A+B)+(A-B)=
\begin{pmatrix}
2 & 4 \\
-2 & 6 \\
\end{pmatrix}=2A
$$
