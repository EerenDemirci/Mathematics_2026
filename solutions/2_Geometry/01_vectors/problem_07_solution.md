# Exercise 7. Linear Dependence Without Heavy Computation

## Question

Given

$$
u=(1,2,3),\qquad v=(2,4,6),\qquad w=(0,1,1).
$$

Identify a specific relation between $u$ and $v$, decide whether the three vectors can be linearly independent, and explain why no long calculation is needed.

## Solution

I compare $u$ and $v$:

$$
v=(2,4,6)=2\cdot(1,2,3)=2u
$$

So $2u-v+0\cdot w=0$. This is a combination equal to zero where not all numbers are 0, so the three vectors are linearly dependent. They cannot be independent.

No long calculation is needed, because if one vector is a multiple of another, the set is already dependent. The vector $w$ does not change this.
