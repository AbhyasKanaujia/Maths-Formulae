# Permutation and Combination

[TOC]

[All Mathematics Formula by Abhyas here](./README.md)

Please see [README](./README.md#README) if this is the first time you are here.

## Fundamental Principle of Counting

### Addition Principle

When things are chosen such that 1 way or 2 ways or 3 ways etc
then add 1+2+3+...

### Multiplication Principle

When things are chosen such that 1 ways and 2 ways and 3 ways etc
then multiply 1\*2\*3\*...

## Concept: Filling the vacant spaces

**Eg 1.** How many 4 digit numbers can be formed using the digits 1, 2, 3, 4, 5 (without repetition)?

Use addition Principle

| 5 choices |4 choices|3 choices|2 choices|
|-|-|-|-|
|All number can be used|1 number have been used|2 numbers have been used|3 numbers have been used|only 2 unused numbers|

Use multiplication principle

5\*4\*3\*2 ways
120 ways

**Eg 2.** How many 4 digit numbers can be formed using the digits 1, 2, 3, 4, 5 (repetition allowed)?

Since repetition is allowed all positions can be filled with all 5 digits

| 5 choices |5 choices|5 choices|5 choices|
|-|-|-|-|

5\*5\*5\*5 ways
625 ways

**Eg 3.** How many 4 digit numbers can be formed using the digits 0, 1, 2, 3, 4 (without repetition)?

Similar to Eg 1
| 4 choices | 4 choices| 3 choices| 2 choices |
| -| -| -| --|
| Since 0 cannot be here | Here 0 can be used | 3 digits remaining | 2 digits remaining | 

**Eg 4.** How many 4 digit numbers can be formed using the digits 0, 1, 2, 3, 4 (without repetition)?

Similar to Eg 2
| 4 choices | 5 choices| 5 choices| 5 choices |
| -| -| -| --|
| Since 0 cannot be here | 0 and all other digits can be used|all digits can be used |all digits| 

**Eg 5.** How many 4 digit numbers divisible by 4 can be formed using the digits 0, 1, 2, 3, 4 (without repetition)

Case 1: Last 2 digits are 04
|3 choices | 2 choices|0|4|
|-|-|-|-|
|||fixed|fixed|

3\*2\*1\*1 ways
6 ways

Case 2: Last 2 digits are 12
|2 choices|2 choices|1|2|
|-|-|-|-|
|0 cannot be used|2 remaining digits|fixed|fixed|

3\*2\*1\*1 ways
6 ways

Case 3: Last 2 digits are 20
|3 choices| 2 choices|2|0|
|-|-|-|-|
|||fixed|fixed|

3\*2\*1\*1 ways
  6 ways

Case 4: Last 2 digits are 24
|2 choices |2 choices|2|4|
|-|-|-|-|
|0 cannot be used||fixed|fixed|

2\*2\*1\*1 ways
4 ways

Case 5: Last 2 digits are 40
|3 choices|2 choices|4|0|
|-|-|-|-|
|||fixed|fixed|

3\*2\*1\*1 ways
6 ways

Case 6: Last 2 digits are 40
|3 choices|2 choices|4|0|
|-|-|-|-|
|||fixed|fixed|

3\*2\*1\*1 ways
6ways

Total ways = 6+4+6+4+4+6 = 30 ways

## Factorial

Factorial of natural number $n$ is product of first $n$ natural numbers

$5!=5\times4\times3\times2\times1$
$n!=n\times(n-1)\times(n-2)\times...\times3\times2\times1$

$\therefore n!=n\times(n-1)!$

Note: factorial of -ve and fractional number is not possible

### Common Factorials

* $0!=1$
* $1!=1$
* $2!=2$
* $3!=6$
* $4!=24$
* $5!=120$
* $6!=720$
* $7!=5040$

## Permutation: Arrangement

Number of ways of arranging $r$ objects out of $n$ available distinct objects.

### Arranging n objects at r places

Arrange 5 objects in 3 places

|5 choices|4 choices|3 choices|
|-|-|-|

$\therefore 5\times4\times3$ ways 
$=\frac{5\times4\times3\times2\times1}{2\times1}$ ways
$=\frac{5!}{2!}$ ways
$=\frac{5!}{(5-3)!}$ ways

$\therefore$ Arranging $n$ objects in $r$ places

|n choices|(n-1) choices| ...|(n-r+1) choices|
|-|-|-|-|

$\therefore n\times(n-1)\times(n-2)\times\times...\times(n-r+1)$ ways
$=\frac{n!}{(n-r)!}$

|$^nP_r=\frac{n!}{(n-r)!}$|
|-|

**Eg 1.** In a train 3 seats are vacant then in how many ways can 5 passengers sit

Arrange 5 passengers in 3 seats

$\therefore ^5P_3=\frac{5!}{(5-3)!}$

### Arranging n objects at n places

$^nP_n=\frac{n!}{(n-n)!}=\frac{n!}{0!}=\frac{n!}{1}\\=n!$

**Eg 1.** How many different words can be formed using all the letters of the word DELHI(words may be meaningless)

$^5P_5=5!=120$

**Eg 2.** How many numbers of five digits can be formed from the numbers 2, 0, 5, 3, 7 when repetition of digits is not allowed

all arrangement - all those arrangements starting with 0
$^5P_5-^4P_4=120-24=96$

**Eg 3.** Words are created by rearranging the letters of the word TABLE and arranged alphabetically. Then what is the position of the word TABLE.

Alphabetically arranging all the letter: A, B, E, L, T

These come before TABLE:

1. A _ _ _ _ : 4! words starting with A
2. B _ _ _ _ : 4! words starting with B
3. E _ _ _ _ : 4!
4. L _ _ _ _ : 4!
5. T A B E _ : 1!

After this table appears
words before TABLE: $4!+4!+4!+4!+1=4\times4!+1=4\times24+1=96+1=97$ words
$\because$ $97$ words appear before TABLE
$\therefore$ position of TABLE is $98$

### Arranging alike objects

Number of ways of arranging $p+q+r$ objects out of which $p$ are alike of one kind and $q$ are alike of second kind and $r$ are distinct

**Eg 1.** How many 3 digit number can be fomed using the digits 1, 2 and 2

$\frac{3!}{2!}=3$ ways

## Combination: Selection 

Number of ways of selecting $r$ objects out of $n$ available distinct objects

$\frac{^nP_r}{r!}=\frac{n!}{(n-r)!\times r!}=^nC_r$

Also, $^nP_r=^nC_r\times r!$

**Eg 1** In how many ways 2 boys can be selected out of a group of 4 boys?

Let the boys be $A, B, C, D$

Groups are: $AB, AC, AD, BA, BC, BD, CA, CB, CD$

$\therefore$ 6 ways

$\frac{^4P_2}{2!}$ ways
$=\frac{4!}{2!\times2!}=6$ ways

### Common values for various nCr

* $^nC_0=1$ 

    Don't select any thing from n. 1 way of doing this: don't choose anything.

* $^nC_1=n$ 

    Choose 1 thing from n things. n ways of doing this: 1^st^ thing, 2^nd^ thing,..., n^th^ thing

* $^nC_n=1$ 

    Choose n things out of n thing. 1 way of doing this: Choose all of them.

* $^nC_r=^nC_{c-r}$

    $\because\, ^nC_r=\frac{n!}{(n-r)!r!}$ and
    $^nC_{n-r}=\frac{n!}{(n-n+r)!(n-r)!}=\frac{n!}{r!(n-r)!}$ 

## Geometry based questions

## Licensing and Links

[All Mathematics Formula by Abhays here](./README.md)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
