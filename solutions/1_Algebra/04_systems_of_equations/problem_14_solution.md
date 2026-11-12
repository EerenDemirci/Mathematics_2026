# Exercise 14. A Small Change in the Right-Hand Side

## Question

Compare the systems

$$
\begin{cases}
x+y=2, \\
2x-y=1, \\
3x=3
\end{cases}
$$

and

$$
\begin{cases}
x+y=2, \\
2x-y=1, \\
3x=3.1.
\end{cases}
$$

Check the consistency of each system and explain why a small change in one number can change the type of the system.

## Solution

Both systems have the same first two equations. I add them:

$$
(x+y)+(2x-y)=2+1\quad\Longrightarrow\quad 3x=3\quad\Longrightarrow\quad x=1
$$

Then $y=2-x=1$. So the first two equations already give only one point, $(1,1)$.

**First system.** The third equation is $3x=3$. For $x=1$ it is true. So the system is consistent and has exactly one solution, $(1,1)$.

**Second system.** The third equation is $3x=3.1$. But the first two equations say $3x=3$. With elimination, $R_3-R_1-R_2$ gives $0=0.1$, which is not possible. So the system is inconsistent and has no solution.

Why can a small change matter? There are 3 equations and only 2 unknowns. The first two lines already meet in one point. The third line must go exactly through this point. If I change one number even a little, the third line moves and misses the point.

**Answer:** first system: one solution $(1,1)$. Second system: no solution.

**Check:** $(1,1)$ in the first system: $1+1=2$, $2-1=1$, $3\cdot1=3$. In the second system: $3\cdot1=3\neq3.1$.
