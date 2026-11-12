# Exercise 2. Determinant of a 3×3 Matrix

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
2 & 1 & 5 \\
\end{pmatrix}
$$

compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

## Solution

I use Sarrus' rule. I add the three products that go down to the right:

$$
1\cdot3\cdot5+2\cdot4\cdot2+(-1)\cdot0\cdot1=15+16+0=31
$$

Then I add the three products that go up to the right:

$$
(-1)\cdot3\cdot2+1\cdot4\cdot1+2\cdot0\cdot5=-6+4+0=-2
$$

The determinant is the first sum minus the second sum:

$$
\det A=31-(-2)=33
$$

**Answer:** $\det A=33$.

**Check:** the row operation $R_3\leftarrow R_3-2R_1$ does not change the determinant. It gives the new third row $(0,-3,7)$. Now the first column has only one number that is not zero, so:

$$
\det A=1\cdot(3\cdot7-4\cdot(-3))=21+12=33
$$
