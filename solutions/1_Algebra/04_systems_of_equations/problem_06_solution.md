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

$R_2\leftarrow R_2-aR_1$ gives the row $(0,0\mid4-2a)$, so the second equation becomes $0=4-2a$.

- If $a=2$: $0=0$, so only $x+y=2$ is left and there are infinitely many solutions.
- If $a\neq2$: $0=4-2a\neq0$, so there is no solution.

Exactly one solution is not possible for any $a$. The left side of the second equation is always $a$ times the left side of the first, so the lines are parallel or the same line.
