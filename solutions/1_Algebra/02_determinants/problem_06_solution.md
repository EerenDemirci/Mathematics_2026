# Exercise 6. Parameter and Invertibility

## Question

For

$$
A(t)=
\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}
$$

find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

## Solution

First I find the determinant of $A(t)$:

$$
\det A(t)=t\cdot t-1\cdot2=t^2-2
$$

A matrix is not invertible when its determinant is 0. So I solve this equation:

$$
t^2-2=0\quad\Longrightarrow\quad t=\sqrt2\quad\mathrm{or}\quad t=-\sqrt2
$$

For all other values of $t$ the determinant is not 0, so the matrix is invertible.

**Answer:** $A(t)$ is not invertible for $t=\sqrt2$ and $t=-\sqrt2$.

**Check:** for $t=\sqrt2$ the rows are $(\sqrt2,1)$ and $(2,\sqrt2)$. If I multiply the first row by $\sqrt2$, I get the second row. The rows are dependent, so the determinant must be 0.
