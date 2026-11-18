# Exercise 13. Do Four Points Lie in One Plane?

## Question

Given

$$
A=(0,0,0),\qquad B=(1,2,0),\qquad C=(0,1,1),\qquad D=(2,5,1).
$$

1. Construct $\overrightarrow{AB}$ and $\overrightarrow{AC}$.
2. Find $n=\overrightarrow{AB}\times\overrightarrow{AC}$.
3. Construct $\overrightarrow{AD}$ and check whether $\overrightarrow{AD}\cdot n=0$.
4. Based on this, decide whether $D$ lies in the plane determined by $A,B,C$, and justify the criterion.

## Solution

**Part 1.**

$$
\overrightarrow{AB}=(1,2,0),\qquad \overrightarrow{AC}=(0,1,1)
$$

**Part 2.**

$$
n=\overrightarrow{AB}\times\overrightarrow{AC}=(2\cdot1-0\cdot1,\ 0\cdot0-1\cdot1,\ 1\cdot1-2\cdot0)=(2,-1,1)
$$

**Part 3.**

$$
\overrightarrow{AD}=(2,5,1),\qquad \overrightarrow{AD}\cdot n=4-5+1=0
$$

**Part 4.** $n$ is perpendicular to the plane of $A,B,C$. A vector that starts at $A$ lies in this plane exactly when it is perpendicular to $n$. Since $\overrightarrow{AD}\cdot n=0$, the point $D$ lies in the plane.

Extra check: $2\overrightarrow{AB}+\overrightarrow{AC}=(2,4,0)+(0,1,1)=(2,5,1)=\overrightarrow{AD}$, so $\overrightarrow{AD}$ is made from the two vectors of the plane.
