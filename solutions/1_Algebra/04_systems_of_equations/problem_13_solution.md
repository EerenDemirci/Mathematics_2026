# Exercise 13. Does Every Equation Add New Information?

## Question

Consider the system

$$
x_1+x_2=10,\qquad x_2+x_3=8,\qquad x_1-x_3=2.
$$

Solve it and check whether all three equations are independently necessary to describe the solution set. If one follows from the others, show this by calculation.

## Solution

I subtract the second equation from the first equation:

$$
(x_1+x_2)-(x_2+x_3)=10-8\quad\Longrightarrow\quad x_1-x_3=2
$$

This is exactly the third equation. So the third equation follows from the first two and does not add new information. Only two equations are really needed.

With elimination I see the same: $R_3\leftarrow R_3-R_1+R_2$ makes the third row $(0,0,0\mid0)$.

So there are 3 unknowns and 2 real equations, and one variable is free. I choose $x_3=t$. Then:

$$
x_2=8-t,\qquad x_1=10-x_2=2+t
$$

**Answer:** infinitely many solutions $x_1=2+t$, $x_2=8-t$, $x_3=t$. The third equation is not needed, because it is the first equation minus the second.

**Check:** for $t=0$ the point is $(2,8,0)$: $2+8=10$, $8+0=8$, $2-0=2$. All three equations are true.
