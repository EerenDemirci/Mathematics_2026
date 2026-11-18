# Exercise 3. Vector Normalization

## Question

For $v=(3,4)$ find a unit vector $e$ with the same direction and orientation. Check that $\|e\|=1$, reconstruct $v$ in the form $v=\|v\|e$, and explain what changes during normalization and what remains unchanged.

## Solution

To get a unit vector, I divide the vector by its length:

$$
\|v\|=\sqrt{3^2+4^2}=5,\qquad e=\frac{v}{\|v\|}=\left(\frac35,\frac45\right)
$$

Check that the length is 1:

$$
\|e\|=\sqrt{\frac{9}{25}+\frac{16}{25}}=\sqrt{1}=1
$$

And $\|v\|e=5\cdot\left(\frac35,\frac45\right)=(3,4)=v$.

Normalization changes only the length (from 5 to 1). The direction and the orientation stay the same, because I divide by a positive number.
