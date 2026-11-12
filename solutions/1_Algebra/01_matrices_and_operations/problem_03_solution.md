# Exercise 3. When Can Matrices Be Multiplied?

## Question

The matrix sizes are

$$
A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.
$$

For the products

$$
AB,\ BA,\ BC,\ CB,\ AC,\ CA,\ AD,\ DA
$$

determine whether they are defined. If so, state the size of the result. Justify each decision using the dimension compatibility condition.

## Solution

The product $XY$ of $X_{m\times n}$ and $Y_{p\times q}$ is defined only when $n=p$. This means the number of columns of the left matrix must be equal to the number of rows of the right matrix. Then the result has size $m\times q$.

I check every product with this rule:

| Product | Inner sizes | Defined? | Size of result |
|---|---|---|---|
| $AB$ | $3=3$ | yes | $2\times4$ |
| $BA$ | $4\neq2$ | no | — |
| $BC$ | $4=4$ | yes | $3\times2$ |
| $CB$ | $2\neq3$ | no | — |
| $AC$ | $3\neq4$ | no | — |
| $CA$ | $2=2$ | yes | $4\times3$ |
| $AD$ | $3\neq2$ | no | — |
| $DA$ | $2=2$ | yes | $2\times3$ |

**Answer:** $AB$, $BC$, $CA$ and $DA$ are defined. $BA$, $CB$, $AC$ and $AD$ are not defined.

**Check:** one entry of a product is a row times a column. A row of the left matrix and a column of the right matrix must have the same length, so the rule is correct. The table also shows that $AB$ can exist when $BA$ does not.
