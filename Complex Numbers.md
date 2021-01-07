

# Complex Numbers

[TOC]

[All Mathematics Formula by Abhyas here](./README.md)

Please see [README](./README.md#README) if this is the first time you are here.


## Definition

A number in the form $\mathbb{Z}=a+\iota b$ is a complex number

Here, $\iota=\sqrt{-1}$ and is read as iota.

$Re(z) \rightarrow$ Real part of $\mathbb{Z}$
$Im(z) \rightarrow$ Imaginary part of $\mathbb{Z}$

If $\mathbb{Z}= a$ then it is purely real
If $\mathbb{Z}=\iota b$ then it is purely imaginary

Set of all complex numbers: $\mathbb{C}=\{a+\iota b \,|\,a, b \in \mathbb{R}$ and $\iota = \sqrt{-1}\}$

## Inequality

Comparision between two complex numbers for inequality is not possible

## Plotting of a complex number

<iframe src="https://www.desmos.com/calculator/ltst0eahmt?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameborder=0></iframe>

Complex number is drawn on a Argand plane/complex plane/ argand phone.

It is at a point given by $(x, y)$ where $x = Re(\mathbb{Z})$ and $y = Im(\mathbb{Z})$ without $\iota$.

## Multiplication of imaginary terms

$\sqrt{-a} \times \sqrt{-b} \ne \sqrt{ab}$

$\sqrt{-a} \times \sqrt{-b} = -\sqrt{ab}$

Proof: 

LHS $= \sqrt{-a}\times \sqrt{-b}$
$=\sqrt{-1}\times\sqrt{a}\times\sqrt{-1}\times\sqrt{b}\\
=\iota\sqrt{a}\times\iota\sqrt{b}\\
=\iota^2\sqrt{ab}$
$=-\sqrt{ab}=$ RHS

## Integral power of $\iota$

$\because\iota=\sqrt{-1}$
$\therefore \iota^2 = -1\\
\therefore \iota^3 = -\iota \\
\therefore \iota^4 = 1$

### Sum of 4 consecutive terms

$\therefore \iota + \iota^2 + \iota^3 + \iota^4 = \iota -1- \iota+1=0$

Also, $\iota^n + \iota^{n+1} + \iota^{n+2} + \iota^{n+3}\\
=\iota^n(1 + \iota + \iota^2 + \iota^3)\\
= \iota^n(1 + \iota -1- \iota)\\
=0$

$\therefore$ Sum of 4 consecutive powers of $\iota$ is $0$

### Any index of $\iota$

If $n=4m+r$ where $n>4$ and $0\le r \lt 4$ then,
$\iota^n \\
= \iota^{4m+r}\\
=\iota^{4m}\times\iota^r\\
=(\iota^4)^m\times\iota^r\\
=1^m\times\iota^r\\
=\iota^r$

## Algebra of Complex numbers

Let $\mathbb{Z}_1 = a_1+\iota b_1$ and $\mathbb{Z}_2 = a_2+\iota b_2$

1. $\mathbb{Z}+0=0+\mathbb{Z}=\mathbb{Z}$
    0 is an additive identity
2. $\mathbb{Z}\times1=1\times\mathbb{Z}=\mathbb{Z}$
    1 is a multiplicative identity
3. Addition:
    $\mathbb{Z}_1 +\mathbb{Z}_2 = (a_1 + \iota b_1)+(a_2+ \iota b_2)\\
    =(a_1 + a_2) + \iota(b_1 + b2)$
4. Subtraction:
    $\mathbb{Z}_1 -\mathbb{Z}_2 = (a_1 + \iota b_1)-(a_2+ \iota b_2)\\
    =(a_1 - a_2) + \iota(b_1 - b2)$
5. Multiplication:
    $\mathbb{Z}_1\mathbb{Z}_2=(a_1 + \iota b_1)\times (a_2 + \iota b_2)\\
    =a_1a_2 + \iota a_1b_2 + \iota a_2b_1 - b_1b_2\\
    =(a_1a_2 + b_1b_2)+\iota(a_1b_2+a_2b_1)$
6. $Re(\mathbb{Z}_1\mathbb{Z}_2)= a_1a_2 + b_1b_2$
    $Im(\mathbb{Z}_1\mathbb{Z}_2)=a_1b_2+a_2b_1$
7. $\mathbb{Z}\overline{\mathbb{Z}}\\
    =(a+\iota b)(a - \iota b)\\
    =a^2-\iota^2b^2\\
    =a^2+b^2$
8. Reciprocal or multiplicative inverse: $\frac{1}{\mathbb{Z}}$

## Conjugate of Complex Numbers

If $\mathbb{Z}=a+\iota b$ is a complex number then conjugate of $\mathbb{Z}=\overline{\mathbb{Z}}=a-\iota b$

It takes the reflection about the real axis.

<iframe src="https://www.desmos.com/calculator/8ir7suogef?embed" width="300px" height="300px" style="border: 1px solid #ccc" frameborder=0></iframe>

### Properties 

1. $\overline{\overline{\mathbb{Z}}}=\mathbb{Z}$
2. $\mathbb{Z}+\overline{\mathbb{Z}}=2Re(\mathbb{Z})$
3. $\mathbb{Z}-\overline{\mathbb{Z}}=2Im(\mathbb{Z})$
4. If $\mathbb{Z}=\overline{\mathbb{Z}}$ then $\mathbb{Z}$ is purely real
5. If $\mathbb{Z}=-\overline{\mathbb{Z}}$ then $\mathbb{Z}$ is purely imaginary
6. If $\mathbb{Z} + \overline{\mathbb{Z}}=0$ then $\mathbb{Z}$ is purely imaginary
7. $\mathbb{Z}\overline{\mathbb{Z}}=a^2+b^2=Re^2(\mathbb{Z})+Im^2(\mathbb{Z})=|\mathbb{Z}|^2$
8. $\overline{\mathbb{Z}_1\pm\mathbb{Z}_2}=\overline{\mathbb{Z}_1}\pm\overline{\mathbb{Z}_2}$
9. $\overline{\mathbb{Z}_1\mathbb{Z}_2}=\overline{\mathbb{Z}_1}\,\overline{\mathbb{Z}_2}$
10. $\overline{(\frac{\mathbb{Z}_1}{\mathbb{Z}_2})}=\frac{\overline{\mathbb{Z}_1}}{\overline{\mathbb{Z}_2}}$ 
11. If $\mathbb{Z}=f(\mathbb{Z}_1, \mathbb{Z}_2)$, then $\overline{\mathbb{Z}}=f(\overline{\mathbb{Z}_1}, \overline{\mathbb{Z}_2})$
12. $\overline{(\mathbb{Z}^n)}=(\overline{\mathbb{Z}})^n$
13. $\mathbb{Z}_1\overline{\mathbb{Z}_2}+\overline{\mathbb{Z}_1}\mathbb{Z}_2=2Re(\mathbb{Z}_1\overline{\mathbb{Z}_2})=2Re(\overline{\mathbb{Z}_1}\mathbb{Z}_2)$
14. $\overline{re^{i\theta}}=re^{-i\theta}$
15. If $\mathbb{Z}=x+\iota y$ then $x=\frac{\mathbb{Z}+\overline{\mathbb{Z}}}{2}$ and $y=\frac{\mathbb{Z}-\overline{\mathbb{Z}}}{2\iota}$

## Modulus of Complex Numbers

If $\mathbb{Z}=a+\iota b$ then,
$|\mathbb{Z}|=\sqrt{a^2+b^2}=\sqrt{Re^2({\mathbb{Z}})+Im^2(\mathbb{Z})}$

It gives the distance of $\mathbb{Z}$ from the origin. 

For $\mathbb{Z}_1$ and $\mathbb{Z}_2$
$|\mathbb{Z}_1-\mathbb{Z}_2|$ gives the distance between $\mathbb{Z}_1$ and $\mathbb{Z}_2$

### Properties

Let $\mathbb{Z}_1$, $\mathbb{Z}_2$, $\mathbb{Z}_3$ are complex numbers

1. If $|\mathbb{Z}|=0$ then $\mathbb{Z}=0 + \iota 0$
2. $|\mathbb{Z}_1-\mathbb{Z}_2|$ is the distance between $\mathbb{Z}_1$ and $\mathbb{Z}_2$
3. $|\mathbb{Z}|$ = $|\overline{\mathbb{Z}_1}|$=$|-\mathbb{Z}_1|$=$|-\overline{\mathbb{Z}_1}|$
4. $\mathbb{Z}\overline{\mathbb{Z}}=|\mathbb{Z}|^2$
5. $-|\mathbb{Z}|\le Re(\mathbb{Z})$ or $Im(\mathbb{Z})\le |\mathbb{Z}|$
6. $|\mathbb{Z}_1\mathbb{Z}_2\mathbb{Z}_3...\mathbb{Z}_n|=|\mathbb{Z}_1||\mathbb{Z}_2||\mathbb{Z}_3|...|\mathbb{Z}_n|$
7. $\begin{vmatrix}\frac{\mathbb{Z}_1}{\mathbb{Z}_2}\end{vmatrix}=\frac{|\mathbb{Z}_1|}{|\mathbb{Z}_2|}$ when $\mathbb{Z}_2\ne 0$
8. $|\mathbb{Z}_1\pm\mathbb{Z}_2|^2=|\mathbb{Z}_1|^2+|\mathbb{Z}_2|^2\pm2Re(\mathbb{Z}_1\overline{\mathbb{Z}_2})$
9. Adding result 8 for both plus and minus
    $|\mathbb{Z}_1+\mathbb{Z}_2|^2+|\mathbb{Z}_1-\mathbb{Z}_2|^2=2(|\mathbb{Z}_1|^2+|\mathbb{Z}_2|^2)$
10. Using 8 and 9
    $a, b \in \mathbb R$
    $|b\mathbb{Z}_1+a\mathbb{Z}_2|^2+|a\mathbb{Z}_1-b\mathbb{Z}_2|^2=(a^2+b^2)(|\mathbb{Z}_1|^2+|\mathbb{Z}_2|^2)$
11. $|\mathbb{Z}_1+\mathbb{Z}_2|<|\mathbb{Z}_1|+|\mathbb{Z}_2|$ Third side is less than the sum of 2 sides
12. $|\mathbb{Z}_1-\mathbb{Z}_2|<|\mathbb{Z}_1|+|\mathbb{Z}_2|$
13. $|\mathbb{Z}_1+\mathbb{Z}_2|>|\mathbb{Z}_1|-|\mathbb{Z}_2|$
14. $|\mathbb{Z}_1-\mathbb{Z}_2|>|\mathbb{Z}_1|-|\mathbb{Z}_2|$

11-14 are triangle inequalities. 
## Licensing and Links

[All Mathematics Formula by Abhays here](./README.md)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.



