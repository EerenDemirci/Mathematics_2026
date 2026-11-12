# Exercise 4. Matrix Multiplication and Noncommutativity

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
3 & 1 \\
\end{pmatrix}
$$

compute $AB$ and $BA$. Is $AB=BA$? Use this example to explain what noncommutativity of matrix multiplication means.

## Solution

I multiply rows by columns:

$$
AB=
\begin{pmatrix}
2+6 & 0+2 \\
0+3 & 0+1 \\
\end{pmatrix}=
\begin{pmatrix}
8 & 2 \\
3 & 1 \\
\end{pmatrix},\qquad BA=
\begin{pmatrix}
2+0 & 4+0 \\
3+0 & 6+1 \\
\end{pmatrix}=
\begin{pmatrix}
2 & 4 \\
3 & 7 \\
\end{pmatrix}
$$

So $AB\neq BA$. For numbers the order does not matter, but for matrices it can change the result. This is what noncommutativity means.
