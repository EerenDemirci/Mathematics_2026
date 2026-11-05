# Exercise 10

**Answer:** $R_2=2R_1$, because $(2,4,6)=2\cdot(1,2,3)$, so $\det=0$.

**Steps:** $R_2\leftarrow R_2-2R_1$ does not change $\det$ and makes row 2 equal to $(0,0,0)$. A matrix with a zero row has $\det=0$.

**Rule:** dependent rows $\Longrightarrow$ $\det=0$ $\Longrightarrow$ the matrix is not invertible.

**Check:** $x=(7,-5,1)^T$ is a nonzero solution of $Mx=0$: $7-10+3=0$, $14-20+6=0$, $-5+5=0$.
