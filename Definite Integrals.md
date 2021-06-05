# Definite Integrals

[TOC]

$\int_a^bf(x)dx=F(b)-F(a)$

## Propertise

1. $\int_a^b\mathbf{cf(x)dx}=\mathbf{c}\int_a^bf(x)dx$

2. $\mathbf{\int_a^b}f(x)dx=\mathbf{-\int_b^a}f(x)dx$ used to remove $-$ve sign and when $a<b$

3. $\int_a^bf(x)dx=\int_a^bf(t)dt=\int_a^bf(u)du$ integral is independent of the variable of integration

4. $\int_0^af(x)dx=\mathbf{\int_0^af(a-x)dx}$ 

   Results:

   - $\int_0^a \frac{f(x)}{f(x)+f(a-x)}dx=\frac{a}{2}$ 

   - $\int_0^\frac{\pi}{2}\log{\tan x}\,dx=\int_0^\frac{\pi}{2}\log{\cot x}\,dx=0$

5. $\int_a^bf(x)dx=\mathbf{\int_a^bf(a+b-x)dx}$ 

   Result: 

   - $\int_a^b \frac{f(x)}{f(x)+f(a+b-x)}dx=\frac{b-a}{2}$

6. $\mathbf{\int_{-a}^af(x)\,dx} = \left\{\begin{array}{ll}
   	2\int_0^af(x)\,dx & \text{when } f(x) \text{ is even  i.e. } f(-x) =f(x)\\
   	0 &\text{when } f(x) \text{ is odd i.e. } f(-x) = -f(x) 	\\
   	\int_{-a}^af(-x)\,dx & \text{always true} 
   \end{array}\right.$

    All even powered functions are always even functions. No need to check.

7. $\mathbf{\int_0^{2a}f(x)\,dx}=\left\{\begin{array}{ll}
   	2\int_0^af(x)\,dx & \text{when } f(2a-x)=f(x)\\
   	0 & \text{when }f(2a-x)=-f(x) 
   \end{array} \right.$

8. $\mathbf{\int_0^axf(x)\,dx}=\begin{array}{ll}\frac{a}{2}\int_0^af(x)\,dx&\text{when} f(a-x)=f(x)\end{array}$ 

### Period Property

$\int_0^{na}f(x)dx=n\int_0^af(x)dx$
where $f(x)$ is periodic function and period of function is $a$ i.e. $f(a+x)=f(x)$

### Chain Rule

$\int_a^bf(x)dx=\int_a^cf(x)dx\int_c^bf(x)$ where $a\le c\le b$

In general $\int_a^bf(x)\,dx=\int_a^{c_1}f(x)\,dx\int_{c_1}^{c_2}f(x)\,dx \int_{c_2}^{c_3}f(x)\,dx\dots \int_{c_n}^bf(x)\,dx$
where $a\le c_1 \le c_2 \le \dots \le c_n \le b$

Use this method in Modulus Function, Greatest Integer Function and Some Special Function

See examples from notes and numbe line technique.

## Reduction Formulae

$\int_0^\frac{\pi}{2}\cos^nx=\int_0^\frac{\pi}{2}\sin^nx\,dx=\left\{\begin{array}{ll}
	\begin{bmatrix}\frac{(n-1)(n-3)(n-5)\dots}{n(n-2)(n-4)\dots}\end{bmatrix} & \text{when } n \text{ is odd}\\
	\begin{bmatrix}\frac{(n-1)(n-3)(n-5)\dots}{n(n-2)(n-4)\dots}\end{bmatrix}\frac{\pi}{2} & \text{when } n \text{ is even}
\end{array}\right.$

$\int_0^\frac{\pi}{2}\sin^nx\cos^mxdx=\left\{\begin{array}{ll}
	\frac{[(n-1)(n-3)\dots][(m-1)(m-3)\dots]}{[(m+n)(m+n-2)(m+n-4)\dots]} & \text{when } n \text{ or } m \text{ is/are odd}\\
	\frac{[(n-1)(n-3)\dots][(m-1)(m-3)\dots]}{[(m+n)(m+n-2)(m+n-4)\dots]}\frac{\pi}{2} & \text{when } n \text{ and } m \text{ both are even}
\end{array}\right.$

## $\mathbb{I}_1>\mathbb{I}_2$

$\mathbb{I}_1=\int_a^bf(x)\,dx\text{ and }\mathbb{I}_2=\int_a^bg(x)\,dx\\
\text{if } f(x) >g(x)\,\forall\, x\in(a,b)\\
\implies\mathbb{I}_1>\mathbb{I}_2$ 

Note: only same limit can be compared in this way.

$x\in(0,1)\\
\implies x>x^2>x^3>x^4>\dots\\
x\in(1,\infty)\\
\implies x<x^2<x^3<\dots$



