**Examples of polynomials:**
$$x^3-5x+4$$$$x^4+4x^3+6x^2+4x+1$$$$(y+3)(y-5)-y^2-2y-15$$
A **polynomial** is an expression with only one variable.
The **degree** of a polynomial is its highest power.
In the polynomial $x^4+3x^3+6x^2+4x+1$, the **coefficient** of $x^3$ is $4$.
The **root** of a polynomial function is the value of the variable that makes the function zero - it is $a$ such that $f(a)=0$ 

## Polynomial division
#### Grid Method
1. Write two expressions for the area of the rectangle by first filling in the boxes with the equation, then filling the parts on the sides to 
   ![[Drawing 2026-10-09 09.11.26.excalidraw]]
2. Write the second expressions for the area of each of these rectangles.
   ![[Drawing 2026-10-09 09.16.36.excalidraw]]

We can use this method for any polynomial.
![[Drawing 2026-10-09 09.21.21.excalidraw]]

### Remainder Theorem
$$f(x)=(x-a)Q(x)+R$$
$$(x-a)=\text{divisor}~~~ Q=\text{quotient}~~~ R=\text{Remainder}$$

What happens if we put $x=a$?
$$f(a)=(a-a)Q(a)+R$$
$$f(a)=R$$
If a polynomial is divided by $(x-a)$, then the remainder is $f(a)$.

### Examples:
1. Find an expression for: 
   <u>$(x^3+9x^2+26x+30)\div(x+3)$</u>
   ![[Drawing 2026-10-09 09.33.28.excalidraw]]

## Factor theorem
If $(x-a)$ is a factor of $f(x)$ then the remainder when we divide by $(x-a)$ is zero.

If $(x-a)$ is a factor then $\color{blue}f(a)=0$.
If $f(a)=0$ then $\color{blue}(x-a)\text{ is a factor of }f(x)$.

### Examples:
1. Show that $(x+3)$ is a factor of $(x^3+9x^2+26x+24)$
   $f(-3)=(-3)^3+9(-3)^2+26(-3)+24$
   $~~~=-27+81-78+24$
   $~~~=0$
   $f(-3)=0 \therefore (x+3)$ is a factor of $f(x)$

2. Show that $(x+1)$ is a factor of
   $f(x)=(x^3+2x^2-5x-6)$ and fully factorise $f(x)$
   $f(-1)=(-1)^3+2(-1)^2-5(-1)-6$
   $~~~=-1+2+5-6$
   $~~~=0$
   $f(-1)=0 \therefore (x+1)$ is a factor of $f(x)$

## Factorising Polynomials

### Show that ... is a factor of ...
To show that something (e.g. $(x+1)$) is a factor, solve using the **grid method** and state that the **remainder** is **equal to 0**.
#### Examples:
1. Show that <u>$(x+1)$</u> is a factor of $x^3+2x^2-5x-6$ and factorise fully
   ![[Drawing 2026-10-21 15.07.05.excalidraw]]
   $\text{remainder}=0 \therefore (x+1) \text{ is a factor}$

### Factorise fully
1. Factorise fully $3x^3-2x^2-19x-6$
   We are **not** given any factors therefore we have to 'test' for different values of $a$ such that $f(a)=0$.
   $f(1)=3(1)^3-2(1)^2-19(1)-6 = -24$ ❌

## Solving polynomial equations
1. One solution of $x^3+3x^2-16x+48=0$ is $x=3$.
   Find the other solutions.
   ![[Drawing 2026-11-01 17.47.47.excalidraw]]
   $(x-3)(x^2-16)$
   $x=3$ or $x^2=16$
  $x=3$ or $x=\pm \sqrt{16}$
  <u>$x=3$ or $x=\pm{4}$</u> 

## Finding missing Coefficients
1. Find $k$ if $(x-3)$ is a factor of
   $f(x)=2x^3-9x^2+kx-3$
   ==🔴Root x=3==
   $f(3)=0$ since $(x=3)$ is a factor
   $f(3)=2(3)^3-9(3)^2+k(3)-3$
   $0=54-81+3k-3$
   $0=3k-30$
   $30=3k$
   $k=10$
2. Find $m$ and $n$ if $(x-1)$ and $(x+1)$ are factors of $2x^3+3x^2+mx+n$
   ==🔴Roots x=1, x=-1==
   $f(1)=2(1)^3+3(1)^2+m(1)+n$
   $0=2+3+m+n$
   $-5=m+n$
   
   $f(-1)=2(-1)^3+3(-1)^2+m(-1)+n$
   $0=-2+3-m+n$
   $-1=-m+n$
   
   Solve simultaneously:
   $-1=-m+n$
   $-5=m+n$
   
   $-6=2n$
   $n=-3$
   Substitute in:
   $-5=m-3$
   $m=-2$
---
- **Subject map:** [[Maths|Maths]]