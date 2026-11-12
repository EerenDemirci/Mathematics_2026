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

I write the augmented matrix and subtract the first row from the other rows:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 1 \\
1 & t & 1 & \mid & 2 \\
1 & 1 & t & \mid & 3 \\
\end{pmatrix}\ \longrightarrow\
\begin{pmatrix}
1 & 1 & 1 & \mid & 1 \\
0 & t-1 & 0 & \mid & 1 \\
0 & 0 & t-1 & \mid & 2 \\
\end{pmatrix}
$$

The next step is to divide by $t-1$. This step works only when $t-1\neq0$, so I look at two cases.

**Case $t\neq1$.** I can divide:

$$
y=\frac{1}{t-1},\qquad z=\frac{2}{t-1},\qquad x=1-y-z=1-\frac{3}{t-1}=\frac{t-4}{t-1}
$$

So there is exactly one solution.

**Case $t=1$.** The division is not allowed. The second and third rows become $0=1$ and $0=2$. This is not possible, so there is no solution.

**Answer:** $t\neq1$: exactly one solution (formulas above). $t=1$: no solution. Infinitely many solutions never happen.

**Check:** for $t=2$ the formulas give $x=-2$, $y=1$, $z=2$. Then $-2+1+2=1$, $-2+2+2=2$, $-2+1+4=3$. All equations are true.
