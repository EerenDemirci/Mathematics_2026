# Exercise 3. Swapping Two Rows

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 3 & 1 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

## Solution

$$
\det A=(3+4+0)-(0+1+0)=6
$$

$B$ is $A$ with the first two rows swapped:

$$
B=
\begin{pmatrix}
0 & 3 & 1 \\
1 & 2 & 0 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

A row swap changes the sign of the determinant, so I expect $\det B=-6$. Calculation:

$$
\det B=(0+0+1)-(4+0+3)=-6
$$

The prediction was correct.
