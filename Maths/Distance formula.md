The formula to calculate the distance between two points on the same line is:
$$d=\sqrt{ (y_{2}-y_{1})^2+(x_{2}-x_{1})^2 }$$
This equation uses the principle of $a^2+b^2=c^2$, the first bracket in the square root finds the $\Delta y$, and same for the $\Delta x$ in the next bracket. In this equation, the $\Delta x$ and $\Delta y$ are our $a$ and $b$, and $d$ is our $c$. The brackets are squared and put into a square root, as that leaves us with the equivalent of $c=\sqrt{ a^2+b^2 }$, but in our case it is $d=\sqrt{ (\Delta y)^2+(\Delta x)^2 }$.

### Example:
**Given two points:** A(2, 3) and B(8, 7)

**Apply the formula:**

$$d = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}$$

$$d = \sqrt{(8-2)^2 + (7-3)^2} = \sqrt{6^2 + 4^2} = \sqrt{36+16} = \sqrt{52}$$

$$d = 2\sqrt{13} \approx 7.21$$

**So the distance between A and B is 2√13 (about 7.21 units).**

Quick sanity check: the horizontal gap is 6, the vertical gap is 4 — the straight-line distance has to be longer than either of those alone (since it's the hypotenuse of a right triangle with legs 6 and 4), and 7.21 is indeed bigger than both 6 and 4. That's a fast way to catch an arithmetic slip.

(Related: the [[Midpoint formula]] finds the point halfway between the same two points.)

---
- **Subject map:** [[Maths|Maths]]
