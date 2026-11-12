# Exercise 5. Row Echelon Form and Number of Solutions

## Question

For the augmented matrix

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 3 \\
0 & 1 & 2 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

## Solution

The matrix is already in row echelon form. The rows mean:

$$
\begin{cases}
x_1+2x_2-x_3=3, \\
x_2+2x_3=1, \\
0=0.
\end{cases}
$$

The last row $0=0$ is always true, so there is no contradiction. There are 3 unknowns and 2 pivots (leading numbers), so $3-2=1$ variable is free. The free variable is $x_3$, because its column has no pivot.

I put $x_3=t$. The second row gives $x_2=1-2t$. The first row gives:

$$
x_1=3-2x_2+x_3=3-2(1-2t)+t=1+5t
$$

**Answer:** infinitely many solutions:

$$
\begin{pmatrix}
x_1 \\
x_2 \\
x_3 \\
\end{pmatrix}=
\begin{pmatrix}
1+5t \\
1-2t \\
t \\
\end{pmatrix},\qquad t\in\mathbb{R}
$$

The number of free variables = number of unknowns − number of pivots = 1.

**Check:** for $t=1$ the point is $(6,-1,1)$. Then $6-2-1=3$ and $-1+2=1$. Both rows are true.
