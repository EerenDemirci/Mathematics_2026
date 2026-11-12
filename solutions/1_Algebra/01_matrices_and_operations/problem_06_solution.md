# Exercise 6. Transpose

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix}
$$

compute $A^T$, $B^T$, and $AB$. Then verify in this example that

$$
(AB)^T=B^TA^T.
$$

## Solution

The transpose changes rows into columns. So the first row of $A$ becomes the first column of $A^T$:

$$
A^T=
\begin{pmatrix}
1 & 4 \\
2 & 5 \\
3 & 6 \\
\end{pmatrix},\qquad B^T=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 1 & 3 \\
\end{pmatrix}
$$

$A$ is $2\times3$ and $B$ is $3\times2$, so $AB$ is a $2\times2$ matrix. I multiply rows of $A$ by columns of $B$:

$$
AB=
\begin{pmatrix}
1+4-3 & 0+2+9 \\
4+10-6 & 0+5+18 \\
\end{pmatrix}=
\begin{pmatrix}
2 & 11 \\
8 & 23 \\
\end{pmatrix}
$$

Now I compare both sides of the property. On the left side I transpose $AB$. On the right side I multiply $B^T$ by $A^T$:

$$
(AB)^T=
\begin{pmatrix}
2 & 8 \\
11 & 23 \\
\end{pmatrix},\qquad B^TA^T=
\begin{pmatrix}
1+4-3 & 4+10-6 \\
0+2+9 & 0+5+18 \\
\end{pmatrix}=
\begin{pmatrix}
2 & 8 \\
11 & 23 \\
\end{pmatrix}
$$

**Answer:** $A^T$, $B^T$ and $AB$ are given above, and $(AB)^T=B^TA^T$ is true in this example.

**Check:** the order of the factors changes. $A^TB^T$ would be $3\times3$, so it cannot be equal to $(AB)^T$, which is $2\times2$.
