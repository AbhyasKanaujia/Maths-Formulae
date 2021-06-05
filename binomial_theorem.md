# Binomial Theorem

## Factorial of $n$

$n!=n(n-1)\dots3\times2\times1$

## Combination Formula

1. $^nC_r=\frac{n!}{(n-r)!r!}$ where $0\le r\le n$
2. $^nC_r=^nC_{n-r}$
3. ||||
   |-|-|-|
   |$n^C_0=1$|$^nC_1=n$|$^nC_n=1$|

## Binomaial Expansion

### $(x\pm a)^n$
$(x+a)^n=\,^nC_0x^na^0+\,^nC_1x^{n-1}a^1+\dots+a^n$
$\therefore (x+a)^n=\sum^n_{r=0}\,^nC_r a ^{n-r}a^r$

- $0\le r \le n \therefore$  Number of terms = $n+1$
- Sum of indices of $x$ and $a=n$

$(x-a)^n=^nC_0x^na^0-^nC_1x^{n-1}a^1+\dots+(-1)^n\,a^n$
$\therefore (x+a)^n=\sum^n_{r=0}(-1)^r\,^nC_r a ^{n-r}a^r$

### $(1+x)^n$

$(1+x)^n=1+nx+\,^nC_2x^2+\dots+x^n$
$(x+1)^n=x^n+\,^{n}C_{1}x^{n-1}+\,^{n}C_{2}x^{n-2}+\dots+\,^{n}C_{n}=(1+x)^n$

- Coefficient of $(r+1)$<sup>th</sup> term $=\,^{n}C_{r}$
- General term $T_{r+1}=\,^{n}C_{r}x^r$

### Sum and Difference of $(x+a)^n$ and $(x-a)^n$

$(x+a)^n=x^n+\,^{n}C_{1}x^{n-1}a^1+\dots+a^n\rightarrow$ eq(1)
$(x-a)^n=x^n-\,^{n}C_{1}x^{n-1}a^1+\dots+(-1)^na^n\rightarrow$ eq(2)

Add eq(1) + eq(2) $=2[\,^{n}C_{0}x^n+\,^{n}C_{2}x^{n-2}a^2+\dots]$
Sub eq(1) - eq(2) $=2[\,^{n}C_{1}x^{n-1}a+\,^{n}C_{3}x^{n-3}a^3+\dots]$

#### Number of terms

|n👉<br>Operation 👇|Odd|Even|
|-|-|-|
|**Add**|$\frac{n+1}{2}$|$\frac{n}{2}+1$|
|**Sub**|$\frac{n+1}{2}$|$\frac{n}{2}$|

## General Term

### $(x+a)^n$

$T_{r+1}=\,^{n}C_{r}x^{n-r}a^r$

### $(x-a)^n$

$T_{r+1}=(-1)^r \,^{n}C_{r}x^{n-r}a^r$

### $r$<sup>th</sup> Term from end in $(x+a)^n$

$T_{(n+1-r+1)}=T_{(n-r+2)}$

where $n+1=$ total number of terms
$n+1-r=r$ from end
$n+1-r+1=T_{r+1}$ from