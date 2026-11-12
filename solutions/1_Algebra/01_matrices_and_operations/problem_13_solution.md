# Exercise 13. A Recurrence Written in Matrix Form

## Question

Let

$$
F=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}.
$$

Compute $F^2$, $F^3$, $F^4$, and $F^5$. Compare the numbers obtained with the sequence

$$
0,1,1,2,3,5,8,\ldots
$$

and describe the relationship you observe. Then compute

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}
$$

and explain how this multiplication performs one recurrence step: it creates the sum of two consecutive terms and keeps one of them for the next step.

## Solution

I multiply by $F$ again and again:

$$
F^2=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\qquad F^3=
\begin{pmatrix}
3 & 2 \\
2 & 1 \\
\end{pmatrix},\qquad F^4=
\begin{pmatrix}
5 & 3 \\
3 & 2 \\
\end{pmatrix},\qquad F^5=
\begin{pmatrix}
8 & 5 \\
5 & 3 \\
\end{pmatrix}
$$

All these numbers are in the sequence $0,1,1,2,3,5,8,\ldots$ Each matrix $F^n$ has three numbers of the sequence that come one after another. For example $F^5$ has 8, 5 and 3.

Now I multiply $F$ by a vector:

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}=
\begin{pmatrix}
a+b \\
a \\
\end{pmatrix}
$$

If $a$ and $b$ are two terms of the sequence, then $a+b$ is the next term. The second entry keeps $a$ for the next step. So one multiplication by $F$ moves one step forward in the sequence.

**Answer:** the entries of $F^n$ are terms of the sequence $0,1,1,2,3,5,8,\ldots$, and $F(a,b)^T=(a+b,a)^T$ is one step of the rule "next term = sum of the last two terms".

**Check:** $\det F=-1$, so $\det F^5$ must be $(-1)^5=-1$. Indeed $8\cdot3-5\cdot5=-1$.
