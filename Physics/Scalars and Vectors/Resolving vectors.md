We have previously added 2 forces (or other vectors) to find a resultant. We can also work backwards to **'resolve'** a vector into 2 components.

``` desmos-graph
left=-1; right=6;
top=6; bottom=-1;
---
y=x | y>0 | y<5
x=5 | y>0 | y<5 | red
y=0 | green | x>0 | x<5
(2.5, 2.5) | label:R
y=4 | x>3 | x<4 | blue
x=4 | y>3 | y<4 | blue
(2.5, 0)| label:X
(5, 2.5)| label:Y
(0, 0)| label:angle
```
This can be split into 2 components, the horizontal x component and the vertical y component. In other words, if you add x+y to get R

$$\text{x component}=R\cos\theta$$
$$\text{y component}=R\sin\theta$$
This is **not** in the data-sheet. A way to remember it is the CHAVS acronym: $\cos$ Horizontal and Vertical $\sin$

This technique is used in [[Connected Forces]], [[Forces on an incline plane]] and [[Projectiles]].
---
- **Subject map:** [[Physics|Physics]]
