# Exercise 10. A Polynomial Through Three Points

## Question

Find a polynomial $p(x)=ax^2+bx+c$ whose graph passes through $(0,1)$, $(1,3)$, and $(2,9)$. Reduce the problem to a system of equations and check the result by substituting all three points.

## Solution

Every point gives one equation $p(x_0)=y_0$:

$$
\begin{cases}
c=1, \\
a+b+c=3, \\
4a+2b+c=9.
\end{cases}
$$

With $c=1$: $a+b=2$ and $4a+2b=8$, so $2a+b=4$. Subtracting gives $a=2$ and then $b=0$.

$$
p(x)=2x^2+1
$$

Check: $p(0)=1$, $p(1)=3$, $p(2)=8+1=9$.
