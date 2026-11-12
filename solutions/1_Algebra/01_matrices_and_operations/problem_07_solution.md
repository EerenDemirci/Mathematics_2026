# Exercise 7. Identity Matrix, Zero Matrix, and Powers

## Question

For

$$
A=
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

compute

$$
AI,\qquad IA,\qquad A+0,\qquad A^2,\qquad A^3.
$$

Explain the roles of the matrices $I$ and $0$, and describe the pattern you observe in successive powers of $A$.

## Solution

$I$ is the identity matrix and $0$ is the zero matrix:

$$
I=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad 0=
\begin{pmatrix}
0 & 0 \\
0 & 0 \\
\end{pmatrix}
$$

When I multiply $A$ by $I$, nothing changes, so $AI=IA=A$. When I add the zero matrix, nothing changes, so $A+0=A$. $I$ works like the number 1, and $0$ works like the number 0.

Next I compute the powers of $A$:

$$
A^2=
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}=
\begin{pmatrix}
4 & 4 \\
0 & 4 \\
\end{pmatrix},\qquad A^3=A^2A=
\begin{pmatrix}
8 & 12 \\
0 & 8 \\
\end{pmatrix}
$$

The numbers on the diagonal are $2^n$. The number in the upper right corner is $n\cdot2^{n-1}$. So the pattern is:

$$
A^n=
\begin{pmatrix}
2^n & n2^{n-1} \\
0 & 2^n \\
\end{pmatrix}
$$

**Answer:** $AI=IA=A$, $A+0=A$, and $A^2$, $A^3$ are given above.

**Check:** for $n=3$ the pattern gives $2^3=8$ and $3\cdot2^2=12$. This is the same as $A^3$.
