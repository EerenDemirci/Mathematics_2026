# Exercise 14. Closest Point on a Line

## Question

Given a point $P=(4,1)$ and a line through the origin with direction $v=(1,2)$. Using projection, find the closest point on the line, the distance from $P$ to the line, and verify that the appropriate vector is perpendicular to the direction of the line.

## Solution

The closest point $Q$ is the projection of $P$ onto the line:

$$
Q=\frac{P\cdot v}{v\cdot v}\,v=\frac{4+2}{1+4}(1,2)=\left(\frac65,\frac{12}{5}\right)
$$

The vector from $Q$ to $P$:

$$
r=P-Q=\left(\frac{14}{5},-\frac75\right)
$$

The distance from $P$ to the line is the length of $r$:

$$
d=\sqrt{\frac{196}{25}+\frac{49}{25}}=\frac{\sqrt{245}}{5}=\frac{7\sqrt5}{5}
$$

Check: $r\cdot v=\frac{14}{5}-\frac{14}{5}=0$. So $r$ is perpendicular to the line, which is exactly why $Q$ is the closest point.
