# Exercise 10. A Polynomial Through Three Points

## Question

Find a polynomial $p(x)=ax^2+bx+c$ whose graph passes through $(0,1)$, $(1,3)$, and $(2,9)$. Reduce the problem to a system of equations and check the result by substituting all three points.

## Solution

The graph passes through a point $(x_0,y_0)$ when $p(x_0)=y_0$. So every point gives one equation:

$$
\begin{cases}
p(0)=c=1, \\
p(1)=a+b+c=3, \\
p(2)=4a+2b+c=9.
\end{cases}
$$

The first equation gives $c=1$. I put it into the other two equations:

$$
\begin{cases}
a+b=2, \\
4a+2b=8.
\end{cases}
$$

I divide the second equation by 2 and get $2a+b=4$. Then I subtract $a+b=2$ and get $a=2$. So $b=0$.

**Answer:** $p(x)=2x^2+1$.

**Check:** $p(0)=1$, $p(1)=2+1=3$, $p(2)=8+1=9$. All three points are on the graph.
