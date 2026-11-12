# Exercise 12. Formula for a Matrix Power

## Question

Let

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}.
$$

Compute $A^2$, $A^3$, and $A^4$, and use them to formulate a conjecture for $A^n$. Then do not stop after checking one more case: assume the formula is true for $n$, multiply by $A$, and explain why you obtain exactly the formula for $n+1$.

## Solution

I compute the first powers of $A$:

$$
A^2=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad A^3=
\begin{pmatrix}
1 & 3 \\
0 & 1 \\
\end{pmatrix},\qquad A^4=
\begin{pmatrix}
1 & 4 \\
0 & 1 \\
\end{pmatrix}
$$

Only the upper right number changes, and it is equal to the power. So my conjecture is:

$$
A^n=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
$$

Now I show that the formula works for the next power. I assume it is true for $n$ and multiply by $A$:

$$
A^{n+1}=A^nA=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}=
\begin{pmatrix}
1 & n+1 \\
0 & 1 \\
\end{pmatrix}
$$

This is the same formula with $n+1$. The formula is also true for $n=1$, so by induction it is true for every $n$.

**Answer:** $A^n$ has 1 on the diagonal, 0 in the lower left corner and $n$ in the upper right corner.

**Check:** for $n=4$ the formula gives the same matrix as the direct computation of $A^4$.
