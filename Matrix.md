# Matrix

[TOC]

[All Mathematics Formula by Abhyas here](./README.md)

Please see [README](./README.md#README) if this is the first time you are here.

## Matrix Defition

 Rectangular arrangement of $m \times n$ numbers having $m$ rows and $n$ columns. Matrix is denoted by: $\begin{bmatrix}\end{bmatrix}$ or $\begin{pmatrix}\end{pmatrix}$ or $\begin{Vmatrix}\end{Vmatrix}$

## General Form

 $A=\begin{bmatrix} a_{ij} \end{bmatrix}_{m \times n}$

 $a_{ij}$ is the general element

$m \times n$ is the order of matrix read as m corss n or m by n.<br>

$\therefore A=\begin{bmatrix} a_{11} & a_{12} & a_{13} & a_{14} & a_{15} & \ldots & a_{1n}\\ a_{21} & a_{22} & a_{23} & a_{24} & a_{25} & \ldots & a_{2n}\\ a_{31} & a_{32} & a_{33} & a_{34} & a_{35} & \ldots & a_{3n}\\ \ldots & \ldots & \ldots & \ldots & \ldots & \ldots & \ldots\\ a_{m1} & a_{m2} & a_{m3} & a_{m4} & a_{m5} & \ldots & a_{mn}\\ \end{bmatrix}_{m \times n}$

## Types of Matrices

01. Row Matrix

    Matirx having one row. Order: $1 \times n$

02. Column Matrix

   Matrix having one column. Order: $m \times 1$

03. Square Matrix

    Square shaped. Order: $m \times m$

04. Rectangular Matrix

    Rectangular shaped. Order $m \times n, m \ne n$

05. Diagonals

    a. _Principal Dialognal_

    All those elements $a_{ij}$ where $i = j$

    eg. $A=\begin{bmatrix}PD_{11} & - & -\\ - & PD_{22} & -\\ - & - & PD_{33}\end{bmatrix}_{3 \times 3}$

    b. _Following Diagonal_

    All those Elements $a_{ij}$ where $j = m - i + 1$

    eg. $A=\begin{bmatrix}- &         - &       FD_{13}\\ 

                            - &         FD_{22} & -\\ 
                            - FD_{31} & - &       -\end{bmatrix}_{3 \times 3}$

06. Diagonal Matrix

    Square matrix where except principal diagonal all other elements are $0$.

    $A=\begin{bmatrix}d_1 & 0 & 0\\ 0 & d_2 & 0\\ 0 & 0 & d_3\end{bmatrix}_{3 \times 3}$

    $A=diag(d_1, d_2, d_3)$

    **Property**

    - $A^n=diag(d_1^n, d_2^n, d_3^n)$
    - $A^{-1}=diag(d_1^{-1}, d_2^{-1}, d_3^{-1})$

07. Triangular Matrix

    a. _Upper Triangular Matrix_

    Square matrix where _except_ principal diagonal and elements above it where $i < j$, all other elements are 0.

    eg. $A=\begin{bmatrix}a_{11} & a_{12} & a_{13}\\ 0 & a_{22} & a_{23}\\ 0 & 0 & a_{33}\end{bmatrix}_{3 \times 3}$

    b. _Lower Triangular Matrix_

    Square matrix where _except_ principal diagonal and elements below it where $i > j$, all other elements are 0.

    eg. $A=\begin{bmatrix}a_{11} & 0 & 0\\ a_{21} & a_{22} & 0\\ a_{31} & a_{32} & a_{33}\end{bmatrix}_{3 \times 3}$

08. Scalar Matrix

    Diagonal Matrix where all diagonal elements are equal.

    eg. $A=\begin{bmatrix}k & 0 & 0\\ 0 & k & 0\\ 0 & 0 & k\end{bmatrix}_{3 \times 3}$

09. Identity Matrix

    Scalar matrix where all diagonal elements are $1$. It is denoted by $I_m$ where $m$ is the order.

    eg. $I_3=\begin{bmatrix}1 & 0 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1\end{bmatrix}_{3 \times 3}$.

10. Trace of Matrix

    Sum of diagonal elements of a square matrix

    $Tr(A)=a_{11}+a_{22}+a_{33}+a_{44}+ \ldots + a_{mm}$

    $\therefore Tr(A)=\sum_{i=1}^{n} a_{ij}$

    Properties of Tract of Matrix

    1. $Tr(A)=Tr(A^T)$
    2. $Tr(kA)=kTr(A)$
    3. $Tr(AB)=Tr(BA)$
    4. $Tr(I_n)=n$

11. Singular Matrix

    Square matrix whose determinant is $0$.

    $\begin{vmatrix}A\end{vmatrix}=0$

=

12. Non Singular Matrix

    Determinant of matrix is not equal to $0$

=

    $\begin{vmatrix}A\end{vmatrix}\ne0$

=

13. Sub Matrix

    Matrix obtained by deleting rows or columns or both in given matrix A.Similar as minor in Determinant. 

14. Idempotent Matrix

    Square matrix where $A^2=A$

15. Invoutary Matrix

    Square matrix where $A^2=I$

16. Nilpotent Matrix

    Square matrix of order $m$ where $A^k=0$ where $k$ is minimum +ve integer and $0$ is a null matrix

## Algebra of Matrices

### Equality

Two matrices are said to be equal if their order is same and corresponing elements are equal.

### Addition and Subtracion

Two matrics having same order can be added or subtracted by adding or subtracting corresponing elements.

### Scalar Multiplicaiton

$kA$ if found by multiplying all the element of $A$ by $k$

### Multiplication of two matrices

#### Condition

$A \times B$ is only possible if $columns(A)=rows(B)=p$(say)

Thus multiplication is possible for $A_{mp}$ and $B_{pn}$

Order of product will be $m \times n$

#### Method

Multiplicaiton is done by taking sum of $row(A)\times column(B)$

eg. $A = \begin{bmatrix}
1 & -2 & 3\\
2 & 3 & -1\\
0 & 2 & 4
\end{bmatrix}_{3 \times 3}$ and $B = \begin{bmatrix}

                                        3 & 4  & -2\\
                                        0 & 2 & 3\\  
                                        1 & 3 & 5
                                        \end{bmatrix}_{3 \times 3}$

$\therefore AB = \begin{bmatrix}
(1\times3+-2\times0+3\times1) & \dots & \dots\\
\dots &                         \dots & \dots\\
\dots &                         \dots & \dots
\end{bmatrix}_{3 \times 3}$

$\therefore AB=\begin{bmatrix}
5 & 9 & 7\\
5 & 11 & 0\\
2 & 1 & 26
\end{bmatrix}_{3 \times 3}$

### Properties of Multiplication

1. Generally $AB \ne BA$
2. $(AB)C = A(BC)$ Associative
3. $A(B+C) = AB + AC$ Distributive 
4. $I_m \times A_{m \times n} = A_{m \times n} = A_{m \times n} \times I_n$
5. If A is a square matrix then $A^{n+1} = A^n \times A$
6. $(A \pm B)^2 = (A \pm B) \times (A \pm B)$

    $=A^2 \pm AB \pm BA + B^2$

7. $(A+B)(A-B)= A^2 - AB + BA - B^2$
8. If $AB = 0$ does not imply that $A=0$ and/or $B=0$

## Transpose of Matrix $A^T$ or $A^{'}$

Change rows into columns  or columns into rows.

eg. $A=\begin{bmatrix}1 & 2 & 3 & 4\\

                      a & b & c & d \\
                      \end{bmatrix}$

$\therefore A^T=\begin{bmatrix}1 & 2\\

                              2 & b\\
                              3 & c\\
                              4 & d\\
                              \end{bmatrix}$

### Properties of Transpose

1. $(A^T)^T=A$
2. $(A \pm B)^T=A^T \pm B^T$
3. $(ABC)^T = C^TB^TA^T$[Remember, product is not commutative. ] Reversal Law
4. $Tr(A) = Tr(A^T)$
5. If $A^T=A \implies A$ is symetric matrix

    eg. $A=\begin{bmatrix}a & b\\
                          b & c\\
                          \end{bmatrix}$
    and $A^T=\begin{bmatrix}a & b\\
                            b & c\\
                            \end{bmatrix}$
    $\because A=A^T \therefore A$ is a **symetrix matrix**

6. If $A^T=-A \implies A$ is skew-symetric matrix

    eg. $A=\begin{bmatrix}0 & -a& b\\
                          a & 0 & c\\
                          -b& -c& 0\\
                          \end{bmatrix}$
    and $A^T=\begin{bmatrix}0 & a & -b\\
                           -a & 0 & -c\\
                            b & c & 0\\
                          \end{bmatrix}$$
    $\because -A=A^T \therefore A$ is a **skew-symetrix matrix**

7. $(kA)^T=kA^T$
8. For square matrix $A$, if $AA^T=A^TA=I$ then A is Orthogonal Matrix

## Matrix to sum of symetric and skew-symetric matrix

For given matrix $A$ do

$A=\frac{1}{2}(A+A^T) + \frac{1}{2}(A-A^T)$

## Cofactors of elemnets of Matrix

Minor of element multiplied by $(-1)^{i+j}$ 

eg. $A=\begin{bmatrix}1& 4 & 5\\

                      3 & 2 & 6\\
                      0 & 1 & 0\\\end{bmatrix}$

Cofactor of middle elelment 2 would be, 

$C_{22}=(-1)^{2+2}\begin{vmatrix}1 & 5 \\ 0 & 0\\\end{vmatrix}$

$\therefore C_{22}=\begin{vmatrix}1 & 5 \\ 0 & 0\\\end{vmatrix}$

NOTE: minor is part of determinant. Find notes for minor.

## Adjoint of a Matrix $adjA$

$A$ is a square matrix

$C_{ij}$ are the cofactors of $a_{ij}$

$\therefore\, adjA=\begin{bmatrix}C_{ij}\end{bmatrix}^T$

## Licensing and Links

[All Mathematics Formula by Abhays here](./README.md)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
