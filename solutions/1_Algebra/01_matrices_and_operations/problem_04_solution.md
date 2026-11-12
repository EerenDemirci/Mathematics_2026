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

To multiply two matrices, I multiply a row of the first matrix by a column of the second matrix.

$$
AB=
\begin{pmatrix}
1\cdot2+2\cdot3 & 1\cdot0+2\cdot1 \\
0\cdot2+1\cdot3 & 0\cdot0+1\cdot1 \\
\end{pmatrix}=
\begin{pmatrix}
8 & 2 \\
3 & 1 \\
\end{pmatrix}
$$

Now I change the order and compute $BA$ in the same way:

$$
BA=
\begin{pmatrix}
2\cdot1+0\cdot0 & 2\cdot2+0\cdot1 \\
3\cdot1+1\cdot0 & 3\cdot2+1\cdot1 \\
\end{pmatrix}=
\begin{pmatrix}
2 & 4 \\
3 & 7 \\
\end{pmatrix}
$$

The two results are different. This is noncommutativity: for numbers $ab=ba$, but for matrices the order matters and in general $AB\neq BA$.

**Answer:** $AB$ and $BA$ are the matrices above, and $AB\neq BA$.

**Check:** the determinants must be equal to $\det A\cdot\det B=1\cdot2=2$. Indeed $\det(AB)=8-6=2$ and $\det(BA)=14-12=2$.
