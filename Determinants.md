

# Determinants

[TOC]

[All Mathematics Formula by Abhyas here](./README.md)

Please see [README](./README.md#README) if this is the first time you are here.

## Definition

A definite number associated to a square matrix

### Notiation

For matrix $A = \begin{bmatrix}a_{ij}\end{bmatrix}$ determinant is $\Delta=D=det(A) = \begin{vmatrix}a_{ij}\end{vmatrix}$

## Comparing Matrix and determinant

||Matrix|Determinant|
|-|-|-|
|**Arrangement**| Square/Rectangular |Square|
|**Solution**|Cannot be converted into single number| Can be converted into single number|
|**Scalar Multiplication**| All elements are multiplied| Multiply any one row or any one column|

## Expansion 

### 2<sup>nd</sup> order 

$\begin{vmatrix}a & b \\ c & d\end{vmatrix} = (ad - bc)$

### 3<sup>rd</sup> order

$\begin{vmatrix}a_{11} & a_{12} & a_{13}\\
                a_{21} & a_{22} & a_{23}\\
                a_{31} & a_{32} & a_{33}\\\end{vmatrix}$
                
#### Method

1. Chose any row or column(preferably one with most $0$s)
2. For each element in the row/column:
    1. Use checkerboard method to give a sign.
        $\begin{vmatrix}+ & - & + & ...\\
                        - & + & - & ...\\
                        ... & ... & ... & ...\\ 
                        + & - & + & ...\\\end{vmatrix}$
    2. Multiply the element, sign from checkerboard and the 2<sup>nd</sup> order minor of that element. 
3. Add all the terms obtained in step 2.
4. Exapnd 2<sup>nd</sup> order determinants obtained as minors in step 2.
5. Simplify

## Properties of Determinants

1. Value of determinant doesn't changes if transpose of determinant is taken
    $\begin{vmatrix}A\end{vmatrix}=\begin{vmatrix}A^T\end{vmatrix}$
2. If any two columns or rows are **interchanged** ($R_a \leftrightarrow R_b$) then value of determinant changes by minus sign. 
    $\begin{vmatrix}a & b & c\\
                    d & e & f\\
                    g & h & i\\\end{vmatrix} = -\begin{vmatrix}d & e & f\\
                                                               a & b & c\\
                                                               g & h & i\\\end{vmatrix}\quad [$ Using, $R_1 \leftrightarrow R_2]$
4. If any two column or row are **identical**, then value of determinant is $0$
    $\begin{vmatrix}2 & -3 & 4\\
                    4 & -6 & 8\\
                    5 & 6 & 7\end{vmatrix} = 2\begin{vmatrix}2 & -3 & 4\\
               2 & -3 & 4\\
               5 & 6 & 7\end{vmatrix} = 0\quad[\because R_1 = R_2]$
4. If any row or column be **multiplied by $k$** then determinant becomes $k$ times
5. If each element of any row or column is expressed as **sum of two or more elements**, then determinant can be **expressed as sum** of two or more determinants
    $\begin{vmatrix}a + \alpha & b + \beta & c +\gamma\\
                    d          & e         & f\\
                    g          & h         & i\\
                    \end{vmatrix}$ = $\begin{vmatrix}a & b & c \\
                                                     d          & e         & f\\
                                                     g          & h         & i\\
                    \end{vmatrix}$ + $\begin{vmatrix}\alpha & \beta & \gamma\\
                                                      d          & e         & f\\
                                                      g          & h         & i\\
                    \end{vmatrix}$
6. Value of determinant does not changes if any row or column is added or subtracted by multiplying by same constant. eg. Using, $C_a \rightarrow  C_a \pm k C_b$
7. If **all elements** of any row or column are **zero**, then value of determinant is $0$
8. Determinant of Diagonal matrix, upper triangular matrix, lower triangular matrix has value  equal to the **product of principal diagonal elements**. 
9. If A and B are square matrix of same order then, 
    $|AB| = |A||B| = |B||A|$
10. **Factor Theorem:** 
    If in any deterninant $\Delta$ by putting $x=a$, $\Delta = 0$ then $(x - a)$ will be one factor.
    Product of diagonal elements gives the degree of determinants. The determinant gives same number of linear factors.
11. Sum of product of any row or columns to its cofactors gives the **value of determinant.** 
12. While using properties at least one row or column should be unchanged. 

## Licensing and Links

[All Mathematics Formula by Abhays here](./README.md)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.




