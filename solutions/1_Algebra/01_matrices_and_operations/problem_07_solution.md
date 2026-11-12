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

Multiplying by $I$ does not change $A$, and adding the zero matrix does not change $A$:

$$
AI=IA=A,\qquad A+0=A
$$

So $I$ works like the number 1 and $0$ works like the number 0.

$$
A^2=
\begin{pmatrix}
4 & 4 \\
0 & 4 \\
\end{pmatrix},\qquad A^3=A^2A=
\begin{pmatrix}
8 & 12 \\
0 & 8 \\
\end{pmatrix}
$$

Pattern: on the diagonal there is $2^n$, and in the upper right corner there is $n\cdot2^{n-1}$ (for example $3\cdot4=12$).
