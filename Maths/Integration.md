Integration is the inverse of [[Differentiation]].
## Integrable form
Before integrating, we need to get the equation into **integrable form**
i.e. no roots, no variables in denominators, no un-expanded brackets.
### Examples:
1. $\int \frac{4}{x^3}dx=\int{4}x^{-3}dx$
   $\underline{=\frac{4x^{-2}}{-2}+c}$
   $\underline{=-2x^{-2}+c}$
   $\underline{=-\frac{2}{x^2}+c}$
2. $\int \frac{dx}{x^7}=\int \frac{1}{x^7}dx$
   $=\int x^{-7}dx$
   $\underline{=\frac{x^{-6}}{-6}+c}$
   $\underline{=-\frac{1}{6x^6}+c}$
3. $\int \sqrt[3]{ x }~dx=\int x^\frac 13dx$
   $\underline{=\frac{x^{\frac{4}{3}}}{\frac 43}+c}$
   $\underline{=\frac{3}{4}x^{\frac{4}{3}}+c}$
4. $\int\frac{t^2+2}{\sqrt{ t }}dt=\int\left( \frac{t^2}{t^{\frac 12}}+\frac{2}{t^{\frac 12}} \right)dt$
   $=\int (t^{\frac 32}+2t^{-\frac 12})dt$
   $=\frac{t^{\frac 52}}{\frac{5}{2}}+\frac{2t^{\frac 12}}{\frac 12}+c$
   $=\frac{2t^{\frac 52}}{5}+4t^{\frac 12}$
5. $\int\frac{(x-5)(x+5)}{x^2}dx=\int\frac{x^2-25}{x^2}dx$
   $=\int\left( \frac{x^2}{x^2}-\frac{25}{x^2} \right)dx$
   $=\int(1-25x^{-2})dx$
   $\underline{=x-\frac{25}{-1}x^{-1}+c}$
   $=x+\frac{25}{x}+c$

## Basic integration
To integrate with respect to $x$:
![[Drawing 2026-11-18 13.56.11.excalidraw|520]]
**Steps:**
- ==🔴Increase power== by 1,
- ==🔵divide== by new power
- add "==🟢constant of integration=="

### Examples:
1. 
	1. Integrate $x^6$ with respect to $x$
	   $\int x^6dx\underline{=\frac{x^7}{7}+c}$
	2. Integrate $4x^5$ with respect to $x$
	   $\int4x^5dx\underline{=\frac{4x^6}{6}+c}$
	   $\underline{=\frac{2x^6}{3}+c}$
	3. Find $\int x^{-2}dx$
	   $\int x^{-2}dx\underline{=\frac{x^{-1}}{-1}+c}$
	   $=-\frac{1}{x}+c$

## Integrating multiple terms
When integrating multiple terms, integrate each one individually.
Find$\int\left( \frac{1}{2}x^3-3x^{-\frac12 }+6\right)dx$
$\underline{=\frac{1}{2}\times \frac{x^4}{4}-3\times \frac{x^{\frac12}}{\frac{1}{2}}+6x+c}$
$\underline{=\frac{x^4}{8}-6x^{\frac12}+6x+c}$

## Definite integrals
![[Drawing 2026-11-23 12.05.50.excalidraw|676]]
### Examples:
1. Evaluate $\int^4_{1}3x~dx$
   $=\left[ \frac{3x^2}{2} \right]^4_{1}$
   $=\frac{3}{2}(4)^2-\frac{3}{2}(1)^2$
   $=24-\frac{3}{2}$
   $=\frac{48}{2}-\frac{3}{2}$
   $\underline{=\frac{45}{2}}$
2. Evaluate $\int^3_{-1}(4x-3)~dx$
   $=[2x^2-3x]^3_{-1}$
   $=(2(3)^2-3(3))-(2(-1)^2-3(-1))$
   $=(18-9)-(2+3)$
   $\underline{=4}$

## Integrating $(ax+b)^n$
$$\int(ax+b)^ndx=\frac{1}{a(n+1)}(ax+b)^{n+1}+c$$
$n \neq -1$
### Examples:
1. $\int(5x+4)^3dx=\frac{1}{5\times{4}}(5x+4)^4+c$

---
- **Subject map:** [[Maths|Maths]]