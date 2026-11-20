Integration is the inverse of [[Differentiation]].
## Integrable form
Before integrating, we need to get the equation into **integrable form**
i.e. no roots, no variables in denominators, no un-expanded brackets.
### Examples:
1. $\int \frac{4}{x^3}dx=\int{4}x^{-3}dx$
   $=\frac{4x^{-2}}{-2}+c$
   $=-2x^{-2}+c$
   $=-\frac{2}{x^2}+c$
2. $\int \frac{dx}{x^7}=\int \frac{1}{x^7}dx$
   $=\int x^{-7}dx$
   $=\frac{x^{-6}}{-6}+c$
   $=-\frac{1}{6x^6}+c$
3. $\int \sqrt[3]{ x }dx=\int x^{\frac 13}dx$
   $=\frac{x^{\frac 43}}{\frac 43}+c$
   $\frac{3}{4}x^{\frac 43}+c$
   
   
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
	   $\int x^6dx=\frac{x^7}{7}+c$
	2. Integrate $4x^5$ with respect to $x$
	   $\int4x^5dx=\frac{4x^6}{6}+c$
	   $=\frac{2x^6}{3}+c$
	3. Find $\int x^{-2}dx$
	   $\int x^{\frac 12}dx=\frac{x^{-1}}{-1}+c$
	   $=-\frac{1}{x}+c$

### Integrating multiple terms
When integrating multiple terms, integrate each one individually.
Find$\int\left( \frac{1}{2}x^3-3x^{-\frac12 }+6\right)dx$
$=\frac{1}{2}\times \frac{x^4}{4}-3\times \frac{x^{\frac12}}{\frac{1}{2}}+6x+c$
$=\frac{x^4}{8}-5x^{\frac12}+6x+c$
