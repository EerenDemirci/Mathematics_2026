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

$R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
0 & 0 & 0 & \mid & 0 \\
0 & -2 & 0 & \mid & -2 \\
\end{pmatrix}
$$

The second equation gives nothing new. The third gives $y=1$, and then $x+z=1$. So $z$ is free. With $z=t$:

$$
x=1-t,\qquad y=1,\qquad z=t
$$

Check with $t=2$: the point $(-1,1,2)$ gives $-1+1+2=2$, $-2+2+4=4$ and $-1-1+2=0$.
