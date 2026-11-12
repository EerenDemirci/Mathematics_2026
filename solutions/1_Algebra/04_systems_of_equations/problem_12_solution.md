# Exercise 12. Homogeneous System

## Question

Solve

$$
\begin{cases}
x+2y-z=0, \\
2x+4y-2z=0, \\
x-y+2z=0.
\end{cases}
$$

Give all solutions in parametric form and explain why $(0,0,0)$ always satisfies a homogeneous system.

## Solution

All right sides are 0, so I only need the coefficient matrix:

$$
\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & -2 \\
1 & -1 & 2 \\
\end{pmatrix}
$$

I do $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 0 \\
0 & -3 & 3 \\
\end{pmatrix}
$$

The second row is all zeros. The third row gives $-3y+3z=0$, so $y=z$. I choose $z=t$. Then $y=t$, and the first row gives $x=-2y+z=-2t+t=-t$:

$$
\begin{pmatrix}
x \\
y \\
z \\
\end{pmatrix}=t
\begin{pmatrix}
-1 \\
1 \\
1 \\
\end{pmatrix},\qquad t\in\mathbb{R}
$$

The vector $(0,0,0)$ is always a solution of a homogeneous system. If all unknowns are 0, every left side is 0, and every right side is also 0.

**Answer:** all solutions are $x=-t$, $y=t$, $z=t$ (with $t=0$ we get $(0,0,0)$).

**Check:** for $t=1$ the point is $(-1,1,1)$. Then $-1+2-1=0$, $-2+4-2=0$ and $-1-1+2=0$.
