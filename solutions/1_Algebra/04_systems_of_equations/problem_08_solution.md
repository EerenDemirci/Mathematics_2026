# Exercise 8. Two Systems with the Same Coefficient Matrix

## Question

Solve by elimination the two systems

$$
\begin{cases}
2x+y=5, \\
x-y=1,
\end{cases}
$$

$$
\begin{cases}
2x+y=1, \\
x-y=4.
\end{cases}
$$

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

## Solution

Both systems have the same left side, so they have the same coefficient matrix. I write both right-hand sides in one augmented matrix:

$$
\begin{pmatrix}
2 & 1 & \mid & 5 & 1 \\
1 & -1 & \mid & 1 & 4 \\
\end{pmatrix}
$$

I do $R_2\leftarrow 2R_2-R_1$. This is the same step for both systems:

$$
\begin{pmatrix}
2 & 1 & \mid & 5 & 1 \\
0 & -3 & \mid & -3 & 7 \\
\end{pmatrix}
$$

First system (first right column): $-3y=-3$, so $y=1$. Then $2x+1=5$, so $x=2$.

Second system (second right column): $-3y=7$, so $y=-\frac73$. Then $2x-\frac73=1$, so $2x=\frac{10}{3}$ and $x=\frac53$.

The elimination steps depend only on the coefficient matrix. So the steps are the same for both systems, and only the numbers on the right side are different. This is why I can solve both systems at the same time.

**Answer:** first system $x=2$, $y=1$; second system $x=\frac53$, $y=-\frac73$.

**Check:** first system: $4+1=5$ and $2-1=1$. Second system: $\frac{10}{3}-\frac73=1$ and $\frac53+\frac73=4$.
