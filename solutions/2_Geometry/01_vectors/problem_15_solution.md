# Exercise 15. Comparing Directions Using the Cosine of the Angle

## Question

Given

$$
a=(1,2,1),\qquad b=(2,4,2),\qquad c=(2,0,3).
$$

For each pair, compute

$$
\frac{u\cdot v}{\|u\|\,\|v\|}.
$$

Order the pairs by increasing angle between the vectors. Explain why for $a$ and $b$ the value is $1$ even though the vectors have different lengths.

## Solution

First the lengths and dot products:

$$
\|a\|=\sqrt6,\qquad \|b\|=\sqrt{24}=2\sqrt6,\qquad \|c\|=\sqrt{13}
$$

$$
a\cdot b=2+8+2=12,\qquad a\cdot c=2+0+3=5,\qquad b\cdot c=4+0+6=10
$$

Now the cosines:

$$
\cos(a,b)=\frac{12}{\sqrt6\cdot2\sqrt6}=1,\qquad \cos(a,c)=\frac{5}{\sqrt6\sqrt{13}}=\frac{5}{\sqrt{78}}\approx0.566,\qquad \cos(b,c)=\frac{10}{2\sqrt6\sqrt{13}}=\frac{5}{\sqrt{78}}\approx0.566
$$

A bigger cosine means a smaller angle. So the order is: first $(a,b)$ with angle $0^\circ$, then $(a,c)$ and $(b,c)$ with the same angle, about $55.5^\circ$.

For $a$ and $b$ the value is 1 because $b=2a$, so they point in the same direction. The formula divides by both lengths, so the length does not matter, only the direction. This is also why $(a,c)$ and $(b,c)$ have the same angle.
