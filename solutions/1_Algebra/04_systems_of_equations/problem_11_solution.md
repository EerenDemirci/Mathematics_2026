# Exercise 11. A Parameter in a System of Three Equations

## Question

Analyze the number of solutions depending on $t$:

$$
\begin{cases}
x+y+z=1, \\
x+ty+z=2, \\
x+y+tz=3.
\end{cases}
$$

Use elimination and separately analyze the parameter values for which a standard calculation step ceases to be valid.

## Solution

I subtract the first row from the other two:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 1 \\
0 & t-1 & 0 & \mid & 1 \\
0 & 0 & t-1 & \mid & 2 \\
\end{pmatrix}
$$

Now I need to divide by $t-1$, and this is only allowed when $t\neq1$.

If $t\neq1$: $y=\frac{1}{t-1}$, $z=\frac{2}{t-1}$ and $x=1-y-z=\frac{t-4}{t-1}$. There is exactly one solution.

If $t=1$: the rows become $0=1$ and $0=2$, so there is no solution.
