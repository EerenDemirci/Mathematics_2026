# Exercise 10. Triangle Area from Vectors

## Question

The points $A=(0,0,0)$, $B=(2,1,0)$, and $C=(1,3,2)$ form a triangle. Construct $\overrightarrow{AB}$ and $\overrightarrow{AC}$, compute the area of the parallelogram using the cross product, and then find the area of the triangle. Explain the factor $\frac12$.

## Solution

$$
\overrightarrow{AB}=(2,1,0),\qquad \overrightarrow{AC}=(1,3,2)
$$

$$
\overrightarrow{AB}\times\overrightarrow{AC}=(1\cdot2-0\cdot3,\ 0\cdot1-2\cdot2,\ 2\cdot3-1\cdot1)=(2,-4,5)
$$

The length of the cross product is the area of the parallelogram made by the two vectors:

$$
P=\sqrt{4+16+25}=\sqrt{45}=3\sqrt5
$$

The triangle is half of this parallelogram:

$$
S=\frac12\cdot3\sqrt5=\frac{3\sqrt5}{2}
$$

The factor $\frac12$ is there because the diagonal $BC$ cuts the parallelogram into two equal triangles, and $ABC$ is one of them.
