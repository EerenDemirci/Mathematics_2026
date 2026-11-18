# Exercise 8. Linear Combination and Checking the Result

## Question

Check whether $w=(5,1)$ can be written as

$$
w=au+bv,
$$

where $u=(1,1)$ and $v=(2,-1)$. If so, find $a,b$, reconstruct $w$ from them, and explain the geometric meaning of the existence of such coefficients.

## Solution

I write $w=au+bv$ coordinate by coordinate:

$$
\begin{cases}
a+2b=5, \\
a-b=1.
\end{cases}
$$

Subtracting the second equation from the first gives $3b=4$, so $b=\frac43$. Then $a=1+b=\frac73$.

Check:

$$
\frac73(1,1)+\frac43(2,-1)=\left(\frac73+\frac83,\ \frac73-\frac43\right)=(5,1)=w
$$

The vectors $u$ and $v$ are not parallel, so together they cover the whole plane. That is why such numbers $a,b$ exist. They are the "coordinates" of $w$ if we use $u$ and $v$ as the directions of the grid.
