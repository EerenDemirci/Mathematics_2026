# Exercise 10. Columns of a Matrix Product

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 2 \\
-1 & 0 \\
3 & 1 \\
\end{pmatrix}.
$$

Denote the columns of $B$ by $b_1,b_2$.

1. Compute $Ab_1$ and $Ab_2$.
2. Compute the matrix $AB$.
3. Compare the results and explain why the columns of $AB$ are exactly the vectors $Ab_1$ and $Ab_2$.

## Solution

The columns of $B$ are $b_1=(1,-1,3)^T$ and $b_2=(2,0,1)^T$. First I multiply $A$ by each column:

$$
Ab_1=
\begin{pmatrix}
1-2+0 \\
0-1+3 \\
\end{pmatrix}=
\begin{pmatrix}
-1 \\
2 \\
\end{pmatrix},\qquad Ab_2=
\begin{pmatrix}
2+0+0 \\
0+0+1 \\
\end{pmatrix}=
\begin{pmatrix}
2 \\
1 \\
\end{pmatrix}
$$

Then I compute the full product with rows times columns:

$$
AB=
\begin{pmatrix}
-1 & 2 \\
2 & 1 \\
\end{pmatrix}
$$

The first column of $AB$ is $Ab_1$ and the second column is $Ab_2$. This is always true, because column $j$ of $AB$ uses only column $j$ of $B$.

**Answer:** $Ab_1=(-1,2)^T$, $Ab_2=(2,1)^T$, and $AB$ is the matrix above.

**Check:** the columns of $AB$ are exactly the two vectors from the first part.
