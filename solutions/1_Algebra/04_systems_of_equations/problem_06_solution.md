# Exercise 6. A System with a Parameter — Which Cases Actually Occur?

## Question

Analyze, depending on the parameter $a$, the system

$$
\begin{cases}
x+y=2, \\
ax+ay=4.
\end{cases}
$$

Among the three possibilities — exactly one solution, infinitely many solutions, no solution — determine which actually occur and for which values of $a$. If one type cannot occur, explain why.

## Solution

I do $R_2\leftarrow R_2-aR_1$:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
a & a & \mid & 4 \\
\end{pmatrix}\ \longrightarrow\
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & 0 & \mid & 4-2a \\
\end{pmatrix}
$$

The second row is always $0=4-2a$. Now I look at the cases.

If $a=2$, the second row is $0=0$. Only the equation $x+y=2$ is left, so there are infinitely many solutions: $x=2-s$, $y=s$.

If $a\neq2$, the second row is $0=4-2a$ with $4-2a\neq0$. This is not possible, so there is no solution.

Exactly one solution never happens. The reason is the determinant of the coefficients: $1\cdot a-1\cdot a=0$ for every $a$. The left side of the second equation is always $a$ times the left side of the first equation, so the two lines are parallel or the same line. They can never cross in only one point.

**Answer:** $a=2$: infinitely many solutions. $a\neq2$: no solution. One solution: impossible for every $a$.

**Check:** for $a=0$ the second equation is $0=4$, so there is no solution. For $a=2$ the second equation is $2x+2y=4$, which is the first equation times 2.
