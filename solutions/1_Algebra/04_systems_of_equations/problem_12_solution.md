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

$R_2\leftarrow R_2-2R_1$ makes the second row zero, and $R_3\leftarrow R_3-R_1$ gives $-3y+3z=0$, so $y=z$.

With $z=t$: $y=t$ and $x=-2y+z=-t$.

$$
(x,y,z)=t\cdot(-1,1,1)
$$

$(0,0,0)$ is always a solution, because when all unknowns are 0, every left side is 0, and all right sides are 0 too.
