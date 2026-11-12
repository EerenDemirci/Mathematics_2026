# Exercise 3. Swapping Two Rows

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 3 & 1 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

## Solution

First I find $\det A$ with Sarrus' rule:

$$
\det A=(1\cdot3\cdot1+2\cdot1\cdot2+0)-(0+1\cdot1\cdot1+0)=7-1=6
$$

Next I swap the first and the second row of $A$:

$$
B=
\begin{pmatrix}
0 & 3 & 1 \\
1 & 2 & 0 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

Prediction: when we swap two rows, the determinant changes its sign. So I expect $\det B=-6$.

Now I calculate $\det B$ with Sarrus' rule:

$$
\det B=(0+0+1\cdot1\cdot1)-(1\cdot2\cdot2+0+3\cdot1\cdot1)=1-7=-6
$$

**Answer:** $\det A=6$ and $\det B=-6$.

**Check:** the calculation gives $-6$, which is the same as the prediction.
