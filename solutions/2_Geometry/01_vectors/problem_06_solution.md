# Exercise 6. Projection and Perpendicular Component

## Question

Find the projection of $u=(4,2)$ onto the direction $v=(1,1)$. Then compute

$$
r=u-\mathrm{proj}_v\,u
$$

and verify that $r\cdot v=0$. Explain this result geometrically.

## Solution

The projection of $u$ onto the direction $v$ is:

$$
\mathrm{proj}_v\,u=\frac{u\cdot v}{v\cdot v}\,v=\frac{4+2}{1+1}(1,1)=3(1,1)=(3,3)
$$

The rest of $u$ is:

$$
r=u-\mathrm{proj}_v\,u=(4,2)-(3,3)=(1,-1)
$$

Check: $r\cdot v=1\cdot1+(-1)\cdot1=0$.

So $u$ is split into two parts: $(3,3)$ goes along $v$, and $r=(1,-1)$ is perpendicular to $v$. The projection is like the shadow of $u$ on the line of $v$, and $r$ is the vertical drop from the end of $u$ to that line. This is why $r\cdot v=0$.
