# Exercise 7. Inverse of a Product

## Question

For

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}
$$

compute $(AB)^{-1}$ and $B^{-1}A^{-1}$. Check that the results are the same and explain the meaning of the reversed order.

## Solution

First I compute $AB$ and its inverse:

$$
AB=
\begin{pmatrix}
2 & 3 \\
0 & 3 \\
\end{pmatrix},\qquad \det(AB)=6,\qquad (AB)^{-1}=\frac16
\begin{pmatrix}
3 & -3 \\
0 & 2 \\
\end{pmatrix}=
\begin{pmatrix}
\frac12 & -\frac12 \\
0 & \frac13 \\
\end{pmatrix}
$$

Now I find $A^{-1}$ and $B^{-1}$. For the diagonal matrix $B$ I take the reciprocal $\frac1d$ of each diagonal number $d$:

$$
A^{-1}=
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix},\qquad B^{-1}=
\begin{pmatrix}
\frac12 & 0 \\
0 & \frac13 \\
\end{pmatrix}
$$

Then I multiply in the reversed order:

$$
B^{-1}A^{-1}=
\begin{pmatrix}
\frac12 & -\frac12 \\
0 & \frac13 \\
\end{pmatrix}
$$

The results are the same. The order is reversed because $ABx$ means "first $B$, then $A$". To go back, I must first undo the last step ($A$) and then undo $B$. It is like putting on socks and then shoes: to take them off, you remove the shoes first.

**Answer:** $(AB)^{-1}=B^{-1}A^{-1}$, both equal to the matrix above.

**Check:** $(AB)(AB)^{-1}$ has entries $2\cdot\frac12=1$, $2\cdot(-\frac12)+3\cdot\frac13=0$, $0$, $3\cdot\frac13=1$, so it is $I$.
