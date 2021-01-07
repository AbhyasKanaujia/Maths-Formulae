# Binomial Theorem

[TOC]

[All Mathematics Formula by Abhyas here](README.md)

Please see [README](README.md#README) if this is the first time you are here.

## Prerequisite

Learn [Factorials](/@abhyas/permutation_combination#Factorial) from permutation and combination chapter.

Learn $^nC_r$ formula and its properties for [combination](/@abhyas/permutation_combination#Factorial)
$^nC_r=\frac{n!}{(n-r)!\times r!}r$

## Basic

 1. $(x+y)^n\, =\, ^nC_0x^ny^0+^nC_1x^{n-1}y^1+^nC_2x^{n-2}y^2+^nC_3x^{n-3}y^3+\ldots+^nC_nx^{0}y^n$
 2. $(x+y)^n=\sum^n_{r=0}\, ^nC_rx^{n-r}y^r$
 3. Sum of power in each term is n
 4. $^nC_0$, $^nC_1$, $^nC_0$, etc are called _Binomial Coefficients_
 5. Binomial coefficient of terms _equidistintial from beginning and end_ are the same.
 6. $n!$

    - $= n(n-1)(n-2)(n-3) \ldots 3 \times 2 \times 1$
    - $=n\times{(n-1)!}$ - $n\in \mathbb{Z}$ i.e. only whole numbers
    - $-n!=undefined =\infty$
    - thus $\frac{1}{-n!}=0$

 7. $^nC_r = \frac{n!}{r!\times(n-r)!} = c(n, r)$ where, $0 \le r \le n$
 8. Properties of Binomial Coefficients:
 

    - $\,^nC_r \in \mathbb{Z} \quad \forall \quad x,n \in\mathbb{Z^+}$
    - $^nC_r = \,^nC_{n-r}$ Point number 3
    - $^nC_r + \,^nC_{r-1}= \,^{n+1}C_r = \,^{n + 1}C_{badaWalaR}$  

      eg. $^7C_5 + ^7C_{4}=^{8}C_5$

    - $^nC_0 = ^nC_n = 1$
    - $\frac{^nC_r}{^nC_{r-1}} = \frac{n-r+1}{r} = \frac{n - chotaR}{badaR}$
    - $^nC_r = \frac{n}{r} \,^{n-1}C_{r-1}= \frac{n(n-1)}{r(r-1)} \,^{n-2}C_{r-2}=\ldots$

 8. If $^nC_x= \, ^nC_y$ then $x=y$
 

## General Term

 
 _General Term of $(x+y)^n$_ $=T_{r+1}= \, ^nC_rx^{n-r}y^r$
 

## Middle Term and Highest Binomial Coefficient

 
 Since number of terms in exansion is n+1. Thus, middle term has different cases for even and odd index.
 
 1. **Even $n$ in $(x+y)^n$**

    Middle Term will be $T_{\frac{n}{2} + 1}$

 1. **Odd $n$ in $(x+y)^n$**

    Middle Term will be $T_{\frac{n+1}{2}}$ and $T_{\frac{n+1}{2}+1}$

 
 **Highest Binomial Coefficient**
 Middle Terms have the highest binomial coefficient
 

## Number of terms in expansion

 
 For $(x+y+z+ ...upto\, r\, terms)^n$
 
 Number of terms in expansion = $^{n+(r-1)}C_{r-1}$
 
 Examples, 
 
 In $(x+y)^n$, r = 2
 $\therefore$ Number of terms = $^{n+1}C_1 = (n + 1)$ terms
 
 In $(x+y+z)^n$, r = 3
 
 $\therefore$ Number of terms = $^{n+2}C_2$ terms
 

## Numerically Greatest Term

 
 Numerically Greatest between -8 and 5 is -8
 
 Algebrically Greatest between -8 and 5 is 5
 

### Method

 
 In $(x+y)^n$
 
 Find $\mid \frac{T_{r+1}}{T_r} \mid$
 
 $\therefore \quad\mid \frac{T_{r+1}}{T_r} \mid = \mid \frac{^nC_rx^{x-r}y^r}{^nC_{r-1}x^{n-r+1}y^{r-1}} \mid$
 
 $\therefore \quad\mid \frac{T_{r+1}}{T_r} \mid = \mid \frac{n-r+1}{r} \frac{y}{x} \mid$
 
 $\therefore \quad\mid \frac{T_{r+1}}{T_r} \mid = \frac{n-r+1}{r} \mid \frac{y}{x} \mid$ $[\, \because$ it is always positive$]$
 
 Put, $\mid \frac{T_{r+1}}{T_r} \mid \, \ge 1$
 
 Find $r \le k$ (say)
 
 **Case I:** If $k \in \mathbb{I}$, then NGT is $T_k$ and $T_{k+1}$
 
 **Case II:** If $k \notin \mathbb{I}$, then NGT is $T_{[k]+1}$
 

## Licensing and Links

[All Mathematics Formula by Abhays here](README.md)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
