# Sequence & Series

[TOC]

[All Mathematics Formula by Abhyas here](README.md)

Please see [README](README.md#README) if this is the first time you are here.

## Formula List

|Arithmatic Progression||
|:-|:-|
|General Term|$T_n=a+(n-1)d$|
|Sum of $n$ terms |$S_n=\frac{n}{2}[2a+(n-1)d]=\frac{n}{2}[a+l]$|
|$a, b, c \rightarrow$ AP|$2b=a+c$|
|AM B/w two terms $a$ and $b$|$b=\frac{a+c}{2}$|
|AM of $n$ terms|$\frac{a_1+ a_2+ _3+ ...+a_n}{n}$|
|Inserting $n$ AM between $a$ and $b$|$A_n= a+nd$|

|Geometric Progression||
|:-|:-|
|General Term|$T_n = ar^{n-1}$|
|Sum of $n$ terms|$S_n=\frac{a(r^n-1)}{r-1}$|
|Sum of $\infty$ terms|$S_\infty=\frac{a}{(1-r)}(\begin{vmatrix}r\end{vmatrix}<1)$|
|$a, b, c \rightarrow$ GP|$b^2=ac$|
|GM B/w two terms $a$ and $b$|$b=\sqrt{ac}; a \, \&\, b>0\\b=-\sqrt{ac}; a \, \&\, b<0$|
|GM of $n$ terms|$(a_1.a_2.a_3....a_n)^{\frac{1}{n}}$|
|Inserting $n$ GM between $a$ and $b$|$G_n=ar^n$|

|Harmonic Progression||
|:-|:-|
|HM B/w two terms $a$ and $b$|$b=\frac{2ac}{a+c}$| 
|HM of $n$ terms|$\frac{n}{\frac{1}{a_1}+\frac{1}{a_2}+\frac{1}{a_3}+...+\frac{1}{a_n}}$|
|Inserting $n$ HM between $a$ and $b$|$(\frac{1}{H_n})^{-1}=(\frac{1}{a}+nd)^{-1}$|

|Relation B/w A, G & H||
|:-|:-|
|Relation|$G^2=AH$|
|If $a, b \in \mathbb{R^+}$|$AM>GM>HM$|
|If $a, b \in \mathbb{R^-}$|$AM<GM<HM$|
|If $a, b \in \mathbb{R}$ and $a=b$ |$AM=GM=HM$|

|Arithmetic Geometric Progression||
|:-|:-|
|Sum of $n$ terms|Put $S =$ sum; <br> take $rS$; <br> Subtract $S-rS$; <br>Solve for $S$  |

|Important Summations |
|:-|
|$\sum{1}=n$|
|$\sum{n}=\frac{n(n+1)}{2}$|
|$\sum{n^2}=\frac{n(n+1)(2n+1)}{6}$|
|$\sum{n^3}=\left(\frac{n(n+1)}{2}\right) ^2$|

|Difference Method||
|-|-|
|$n$^th^ term from sum|$T_n=S_n-S_{n-1}$|

## Arithmetic Progression (AP)

AP is a sequence whose terms increase or decrease by a _fixed number_. This fixed number is called the _common difference_.

eg. $1, 4, 7, 10, 13, ...$

### General Term

If $a$ is the first term and $d$ the common difference then series is:
$a, (a+d), (a+2d), (a+3d), ...$

General term = 
|$T_n=a+(n-1)d$|
|-|

### Sum of n Terms

|$S_n=\frac{n}{2}[2a+(n-1)d]=\frac{n}{2}[a+l]$|
|-| 
 where $l$ is the last term
 
 Proof:
$S_n=T_1+T_2+T_3+...+T_n$
$S_n=a+(a+d)+(a+2d)+...+\{a+(n-1)d\}$ ---(1)
$S_n=\{a+(n-1)d\}+\{a+(n-2)d\}+...+a$ ---(2) By reversing (1)
Adding (1) and (2)
$\therefore2S_n=\{2a+(n-1)d\}+\{2a+(n-1)d\}+...+\{2a+(n-1)d\}$ 
$\therefore2S_n=n[2a+(n-1)d]$
$\therefore S_n=\frac{n}{2}[2a+(n-1)d]=\frac{n}{2}[a+l]$

### n^th^ term from Sum

|$T_n=S_n-S_{n-1}$|
|-|

Proof:
$S_5=T_1+T_2+T_3+T_4+T_5$
$S_4=T_1+T_2+T_3+T_4$
$\therefore S_5-S_4=T_5$

### Properties of AP

1. The common difference can be zero , positive  or negative.
2. If $a, b, c$ in AP then 

    |$2b=a+c$|
    |-|
    Proof:
    $a, b, c$ are in AP 
    $\therefore (b-a)=(c-b)\\
    b+b=a+c\\
    2b=a+c$

3. The sum of the terms of an AP equidistant from the beginning & end is constant and equal to the sum of first & last terms
4. If each term of an AP is increased, decreased, multiplied or divided by the same non-zero number, then the resulting sequence is also an AP.

    

### Considering number in AP

|3 Numbers: $(a-d), a, (a+d)$|
|-|

|4 Numbers: $(a-2d), (a-d), (a+d), (a+2d)$|
|-|

|5 Numbers: $(a-2d), (a-d), a, (a+d), (a+2d)$|
|-|

### Common AP

1. Sum of First n natural numbers

    |$\frac{n(n-1)}{2}$|
    |-|

### Arithmetic Mean

#### AM between two terms 

If three terms are in AP then the middle term is called AM between the other two, so if $a, b, c$ are in AP. $b$ is AM of $a$ and $c$

|$b=\frac{a+c}{2}$|
|-|

#### AM for n terms

AM for any $n$ positive number $a_1, a_2, a_3, ..., a_n$ is

|$A=\frac{a_1+ a_2+ a_3, ..., a_n}{n}$|
|-|

#### Inserting n AM between two terms

 
Inserting n AM between $a$ and $b$. The new AP is

$a, A_1, A_2, A_3, ..., A_n, b$

First Term $= a=T_1$
Second Term $=A_1=T_2$
...
Last Term $=b=T_{n+2}$

Use $T_{n+2}=b=a+(n+1)d$ to find $d$

All inserted means can be found using $a$ and $d$ as
$A_1=a+d\\
A_2=a+2d\\
A_n=a+nd$

## Geometric Progression (GP)

GP. is a sequence of numbers whose first term is non zero & each of the succeeding terms is equal to the proceeding terms multiplied by a constant.

eg. $1, 2, 4, 8, 16, ...$

### General Term

If $a$ if the first term and $r$ the common ratios then series is:
$a, ar, ar^2, a^3, .$

General term =
|$T_n=ar^{n-1}$|
|-|

### Sum of n Terms

|$S_n=\frac{a(1-r^n)}{1-r}$|
|-|
where $r\ne 1$ 

Proof:
$\, \, \, \, S_n=a+ar+ar^2+...+ar^{n-1}$ ---(1)
$rS_n=\quad\quad ar+ar^2+...+ar^{n-1}+ar^n$ ---(2)
Taking (1)-(2)
$S_n-rS_n= a-ar^n$
$S_n(1-r)=a(1-r^n)$
$S_n=\frac{a(1-r^n)}{1-r}$

### Sum of infinite Terms

|$S_\infty=\frac{a}{(1-r)}(\begin{vmatrix}r\end{vmatrix}<1)$|
|-|

Proof: 
$1, \frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \frac{1}{16}, \frac{1}{32}, ...$ here $r=\frac{1}{2}$

If $|r|<1$ then it is an infinite series

$\because S_n=\frac{a(1-r^n)}{(1-r)}$

$\therefore S_\infty=\frac{a(1-r^\infty)}{(1-r)}$

$\because r$ is a fraction $\, \therefore r^\infty$ is negligible 
$\therefore S_\infty=\frac{a}{(1-r)}$

### Properties of GP

1. The common ratio can be positive or negative but not zero.
2. If a, b, c in GP then

    |$\frac{b}{a}=\frac{c}{b}$|
    |-|

3. The product if the terms of a GP equidistant from the beginning & end is constant and equal to the product of first & last term.
4. If each term of a GP is multiplied or divided or raised to the power by the same non zero number, then the resulting sequence is also a GP. 
5. If $a_1, a_2 ,a_3,...$ and $b_1, b_2, b_3,...$ are two GP with common ratio $r_1$ and $r_2$ respectively then the sequence $a_1b_2, a_2b_2, a_3b_3,..$ are also a GP with common ratio $r_1,r_2$
6. if $a_1, a_2, a_3,...$ are in GP, where $a_i>0$, then $\log{a_1}, \log{a_2}, \log{a_3},...$ are in AP and its converse is also true

### Considering number in AP

|3 Numbers: $\frac{a}{r}, a, ar$|
|-|

|4 Numbers: $\frac{a}{r^2}, \frac{a}{r}. ar, ar^2$|
|-|

|5 Numbers: $\frac{a}{r^2}, \frac{a}{r}, a, ar, ar^2$|
|-|

### Geometric Mean

#### GM between two terms

if $a, b, c$ are in GP, b is the GM between $a$ and $c$

|$b=\sqrt{ac}; a \, \&\, b>0\\b=-\sqrt{ac}; a \, \&\, b<0$|
|-|

#### GM for n terms

GM for any $n$ positive number, $a_1, a_2, a_3, ..., a_n$ is

|$(a_1.a_2.a_3.....a_n)^{\frac{1}{n}}$|
|-|

#### Inserting n GM between two terms

Inserting n GM beween $a$ and $b$. The new GP is

$a, G_1, G_2, G_3, ..., G_n, b$

First Term $= a = T_1$
Second Term $= G_1 = T_2$
...
Last Term $= b = T_{n+2}$

Use $T_{n+2}=\frac{a(1-r^{n+1})}{1-r}$ to find $r$

All inserted means can be found using $a$ and $r$ as

$G_1=ar\\
G_2=ar^2\\
...\\
G_n=ar^n$

## Harmonic Progression (HP)

A sequence is said to be in HP, if the reciprocals of its terms are in AP.

$1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, ...$

### Harmonic Mean

#### HM between two terms

if $a, b, c$ are in HP, b is the HM between $a$ and $c$ 

|$b=\frac{2ac}{a+c}$| 
|-|

#### HM for n terms

|$\frac{n}{\frac{1}{a_1}+\frac{1}{a_2}+\frac{1}{a_3}+...+\frac{1}{a_n}}$|
|-|

Method:

1. Take reciprocal for each term to form an AP
2. Add n terms and divide by n
3. Take reciprocal of the fraction

#### Inserting n GM between two terms

1. Take reciprocal for each term to form an AP
2. Find $d$ 
3. Find $n$ AM between $\frac{1}{a}$ and $\frac{1}{b}$
4. Take reciprocal for each term to from the HP

## Relation between AM, GM, HM

$\because A=\frac{a+b}{2}$, $G=\sqrt{ab}$ and $H=\frac{2ab}{a+b}$

|$\therefore G^2=AH$|
|-|

### Inequality between A, G, H

### For positive Distinct Numbers

If $a, b \in \mathbb{R^+}$

|$AM>GM>HM$|
|-|

Taking, $A-G\\
=\frac{a+b}{2}-\sqrt{ab}\\
=\frac{a+b-2\sqrt{ab}}{2}\\
=\frac{(\sqrt{a}-=\sqrt{b})^2}{2}>0\\
\therefore A-G>0\\
\therefore A>G$

Again, $G-H\\
=\sqrt{ab}-\frac{2ab}{a+b}\\
=\frac{(a+b)\sqrt{ab}-2ab}{a+b}\\
=(\sqrt{ab})(1-\frac{2\sqrt{ab}}{a+b})\\
=\frac{(\sqrt{ab})(\sqrt{a}-\sqrt{b})^2}{a+b}>0\\
\therefore G-H>0\\
\therefore G>H$

### For Negative Distince Numbers

If $a, b \in \mathbb{R^-}$

|$AM<GM<HM$|
|-|

### For Equal Numbers

If $a, b \in \mathbb{R}$ and $a=b$ 

|$AM=GM=HM$|
|-|

## Arithmetic Geometric Progression (AGP)

$a, (a+d), (a+2d), (a+3d), ...\rightarrow$ AP
$b, br, br^2, br^3, ...\rightarrow$ GP

$ab, br(a+d), br^2(a+2d), ...\rightarrow$ AGP

$1(x)+3(x^2)+5(x^3)+7(x^4)+...\rightarrow$ AGP

### Sum of n Terms

$S=1(x)+3(x^2)+5(x^3)+7(x^4)+...\\
xS=1(x^2)+3(x^3)+5(x^4)+7(x^5)+...\\
S-xS=1(x)+2(x^2)+2(x^3)+...\\
(1-x)S=x+2x^2(1+x+x^2+...)$

## Important Summations

|$\sum_{r=1}^n{1}=n$|
|-|

$\sum_{r=1}^n{1}=1+1+1+1+1+...$ upto n terms $=n$

|$\sum_{r=1}^n{r}=\frac{n(n+1)}{2}$|
|-|

$\sum_{r=1}^n{r}=1+2+3+4+...$ upto n terms $=\frac{n(n+1)}{2}$

|$\sum_{r=1}^n{r^2}=\frac{n(n+1)(2n+1)}{6}$|
|-|

$\sum_{r=1}^n{r^2}=1^2+2^2+3^2+4^2+...$ upto $n$ terms= $\frac{n(n+1)(2n+1)}{6}$

|$\sum_{r=1}^n{r^3}=\left(\frac{n(n+1)}{2}\right) ^2$|
|-|

$\sum_{r=1}^n{r^3}=1^3+2^3+3^3+4^3+...$ upto $n$ terms= $\left(\frac{n(n+1)}{2}\right) ^2$

## Difference Method

|$T_n=S_n-S_{n-1}$|
|-|

## Licensing and Links

[All Mathematics Formula by Abhays here](README.md)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>. 
