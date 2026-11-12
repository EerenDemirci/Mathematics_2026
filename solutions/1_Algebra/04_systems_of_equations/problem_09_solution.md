# Exercise 9. A System from a Sum Condition

## Question

Find numbers $x,y$ satisfying

$$
x+y=10,\qquad 2x+5y=32.
$$

Solve the system and explain geometrically why the solution is unique.

## Solution

I multiply the first equation by 2 and subtract it from the second equation:

$$
(2x+5y)-(2x+2y)=32-20\quad\Longrightarrow\quad 3y=12\quad\Longrightarrow\quad y=4
$$

Then from $x+y=10$ I get $x=6$.

In geometry, each equation is a line in the plane. The solution is the point where the lines meet. The first line has slope $-1$ and the second line has slope $-\frac25$. The slopes are different, so the lines are not parallel and they meet in exactly one point. The same follows from the determinant: $1\cdot5-1\cdot2=3\neq0$.

**Answer:** $x=6$, $y=4$. The solution is unique because the two lines cross in one point.

**Check:** $6+4=10$ and $2\cdot6+5\cdot4=12+20=32$.
