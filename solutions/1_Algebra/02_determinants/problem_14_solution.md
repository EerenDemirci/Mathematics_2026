# Exercise 14

**Steps**

$$
\det A=1\cdot4-2\cdot k=4-2k
$$

**Answer**

- $k\neq2$: $\det A\neq0$, exactly one solution for every $b$.
- $k=2$: the equations are $x_1+2x_2=b_1$ and $2x_1+4x_2=b_2$.
  - $b=(1,2)^T$: the second equation is $2\cdot$ the first, so there are infinitely many solutions ($x_1=1-2s$, $x_2=s$).
  - $b=(1,0)^T$: the first equation gives $2x_1+4x_2=2$, the second requires $0$, so there is no solution.

**Rule:** $\det A\neq0$ $\Longleftrightarrow$ unique solution for every $b$.

**Check:** $s=1$ gives $x=(-1,1)^T$: $-1+2=1$, $-2+4=2$.
