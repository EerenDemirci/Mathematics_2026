# Exercise 15. Associativity of Multiplication and Different Calculation Paths

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\quad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix},\quad C=
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}.
$$

Compute $(AB)C$ and $A(BC)$. Compare the results and the number of intermediate operations. Explain what associativity of matrix multiplication means in this example.

## Solution

First path: I compute $AB$ first, and then I multiply by $C$:

$$
AB=
\begin{pmatrix}
5 & 2 \\
1 & 4 \\
\end{pmatrix},\qquad (AB)C=
\begin{pmatrix}
10 & 3 \\
2 & -3 \\
\end{pmatrix}
$$

Second path: I compute $BC$ first, and then I multiply $A$ by it:

$$
BC=
\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4 \\
\end{pmatrix},\qquad A(BC)=
\begin{pmatrix}
10 & 3 \\
2 & -3 \\
\end{pmatrix}
$$

Both paths give the same matrix. This is associativity: $(AB)C=A(BC)$. The brackets do not change the result, but they change the amount of work. A product of an $m\times n$ and an $n\times q$ matrix needs $m\cdot n\cdot q$ multiplications:

| Path | First product | Second product | Total |
|---|---|---|---|
| $(AB)C$ | $2\cdot3\cdot2=12$ | $2\cdot2\cdot2=8$ | 20 |
| $A(BC)$ | $3\cdot2\cdot2=12$ | $2\cdot3\cdot2=12$ | 24 |

**Answer:** $(AB)C=A(BC)$ is the matrix above. The first path needs 20 multiplications and the second path needs 24.

**Check:** I computed the two paths separately and got the same matrix.
