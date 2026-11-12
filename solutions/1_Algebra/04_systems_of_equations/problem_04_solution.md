# Exercise 4. Infinitely Many Solutions

## Question

Solve

$$
\begin{cases}
x+y+z=2, \\
2x+2y+2z=4, \\
x-y+z=0.
\end{cases}
$$

Give the solution in parametric form, identify a free variable, and for one chosen parameter value check that the resulting point really satisfies the system.

## Solution

I write the augmented matrix:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
2 & 2 & 2 & \mid & 4 \\
1 & -1 & 1 & \mid & 0 \\
\end{pmatrix}
$$

I do $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
0 & 0 & 0 & \mid & 0 \\
0 & -2 & 0 & \mid & -2 \\
\end{pmatrix}
$$

The second row is all zeros, so the second equation gives no new information. The third row gives $-2y=-2$, so $y=1$. Then the first row gives $x+1+z=2$, so $x+z=1$.

There are 3 unknowns but only 2 real equations, so one variable is free. I choose $z=t$ as the free variable. Then $x=1-t$:

$$
\begin{pmatrix}
x \\
y \\
z \\
\end{pmatrix}=
\begin{pmatrix}
1-t \\
1 \\
t \\
\end{pmatrix},\qquad t\in\mathbb{R}
$$

**Answer:** infinitely many solutions $x=1-t$, $y=1$, $z=t$; the free variable is $z$.

**Check:** I choose $t=2$. The point is $(-1,1,2)$. Then $-1+1+2=2$, $-2+2+4=4$ and $-1-1+2=0$. All equations are true.
