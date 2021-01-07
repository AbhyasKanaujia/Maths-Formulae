

---
disqus: abhyas29
---
# Inequality

[All Mathematics Formula by Abhyas here](./README.md)

Please see [README](./README.md#README) if this is the first time you are here.


## Definition
Algebraic statements involving variables and sign of inequality is called inequaltion or inequality.

(The solution of an inequality is in the form of an interval. This notes will not cover intervals.)

## Importance

- Sequence and Series
    AM $\ge$ GM $\ge$ HM
    To Find Max and Min Values
- Function
    Domain and range
- Application of Derivative
- Definite Integration


## Rules

For $a>b$ such that $a,b\in \mathbb{R}$

1. $a \pm c > b \pm c$
    Add/subtract same number does not change the sign of inequality.
2. Multiplying with the same number might change the sign as follows
    1. $a\times p \ge a \times p$ for $p \gt 0$, $p$ is +ve. 
        Multiplying with +ve number does not change the sign of inequality 
    2. $a\times p \le a \times p$ for $p \lt 0$, $p$ is -ve. 
        Multiplying with -ve number changes the sign of inequality
3. Division works same as multiplication. 
    Dividing by +ve number -> no change. 
    Dividing by -ve number -> direction of sign change.
4. Squaring both sides is not allowed. 
5. Cross multiplication is not allowed.
6. Denominator cannot be $0$.
7. If $ab \gt 0$ then either
    1. $a \gt 0$ and $b \gt 0$
    2. $a \lt 0$ and $b \lt 0$
    If product of two real numbers is +ve then both have same sign i.e. either both are +ve or both are -ve
7. If $\frac{a}{b} \gt 0$ then either
    Same as multiplication
    If quotient upon division of two real numbers is +ve then both have same sign.
8. If $ab \ge 0$ then
    1. $a \ge 0$ and $b \ge 0$
    2. $a \le 0$ and $b \le 0$
9. If $\frac{a}{b} \ge 0$ then either
    1. $a \ge 0$ and $b \gt 0$
    2. $a \le 0$ and $b \lt 0$
    Denominator cannot be equal to $0$
10. If $ab \lt 0$ then either
    1. $a \gt 0$ and $b \lt 0$
    2. $a \lt 0$ and $b \gt 0$
    If product of two real numbers is -ve then both have opposite signs
11. If $\frac{a}{b} \lt 0$ then 
    Same as multiplication
    If quotient of two real numbers is -ve then both have same opposite signs.
12. If $a \le 0$ then
    Similar to $\ge$. $a$ and $b$ have opposite signs
13. If $\frac{a}{b} \le 0$ then
    Similar to $\ge$. $a$ and $b$ have opposite signs. Denominator cannot be $0$


## Linear Inequality

Inequality involving linear expression on one side and a constant on the other side. eg. $ax+by \ge c$

## Non-linear Inequality (Wavy Curve Method)

Inequality involving expression of 2^nd^ or higher order on one side and a constant on the other side. eg. $(ax+by)(cx) \ge c$

This is solved using *Wavy curve method*

## Solution of polynomial inequation 

1. Convert the ineuqaltion in this form:
    $\frac{(x-a)(x-b)^2(x-c)}{(x-d)(x-e)} \lt 0$
    "$\lt$" could be any sign of inequality. This is here for example only. RHS should be 0.
    The order should be such that  $a\lt b\lt c\lt d\lt e$
2. Put each factor equal to $0$ to get all critical points: 
    $x-a=0 \quad \therefore x = a$
    $x-b=0 \quad \therefore x = b$
    ...
3. Draw the number line and mark all the numbers
    ```
     a   b   c   d   e
    ___|___|___|___|___|___
    ```
4. Write a plus sign after the rightmost value
    ```
     a   b   c   d   e
    ___|___|___|___|___|_+_
    ```
5. Alternate the plus and minus sign using this rule
    1. If the order of factor containing the constant is even then don't change sign
    2. change sign otherwise. 
    Thus there will be no sign change at $b$ since $(x-b)$ has even power 2 while all other will have a change in sign.
    ```
     a   b   c   d   e
    _+_|_-_|_-_|_+_|_-_|_+_
    ```
6. For "$\ge$" choose all intervals having $+$ in the number line else choose -
    If it also requires equality, eg $\le$ or $\ge$ then use closed interval else use open interval
    
## Modulus Inequality

$\frac{|x-a|+|x-b|}{|x-c|}\ge d$

$x \ne c$

1. Put each expression equal to 0 and find all the critical points. 
    $x=a,b,c$
2. |I||II||III||IV|
    |:-:|:-:|:-:|:-:|:-:|:-:|:-:|
    ||a||b||c||
    |$x<a$||$a \le x \lt b$||$b \le x \lt c$|| $x \gt c$ |
3. Test each case as:
    1. (-exp1 -exp2)/-exp3 $\ge d$ 
    2. (exp1 -exp2)/-exp3 $\ge d$ 
    3. (exp1 -exp2)/exp3 $\ge d$ 
    4. (exp1 +exp2)/exp3 $\ge d$ 
4. Solutions are case n intersection solution of case n
5. Final solution is the union of all the solutions in all the cases. 

### Properties of Modulus

$a,b \in R^+$ and $a < b$

1. $|x|\lt a$ 
    If both sides are positive then, square both sides
    $x^2 < a^2\\
    x^2-a^2 < 0\\
    (x+a)(x-a) < 0$
    ```
    _+_|_-_|_+_
       -a  a
    ```
    $x \in (-a, a)\\
    -a < x < a$
2. $|x|\le a$ 
    $x \in [-a, a]\\
    -a \le x \le a$
3. $|x-b|\lt a$ 
    $-a < (x-b)< a\\
    -a+b < x < a+b$ Adding b 
    $x \in (-a+b, a+b)$
4. $|x-b|\le a$ 
    $x \in [-a+b, a+b]$
5. $|x|\gt a$ 
    $x^2 > a^2\\
    x^2-a^2>0\\
    (x+a)(x-a)>0$
    ```
    _+_|_-_|_+_
       -a  a
    ```
    $x\in (-\infty, -a)\cup(a, \infty)$
    $x < -a$ or $x>a$
6. $|x|\ge a$ 
    $x\in (-\infty, a]\cup[a, \infty)$ 
    $x\le-a$ or $x \ge a$
7. $|x-b|\ge a$ 
    $x-b \le -a$ or $x-b \ge a$
    $x \le -a+b$ or $x \ge a+b$
8. $a < |x| < b$
    1. $|x|=x$ when $x \ge 0$ and
    2. $|x|=-x$ when $x \lt 0$
    From, 
        1. $a < x < b$
            $x \in (a,b)$
        2. $a<-x<b\\
            -a > x > -b\\
            x \in (-b, -a)$
            
    $\therefore x \in (-b, -a) \cup (a, b)$
9.  $a\le |x| \le b$
    $x \in [-b, -a]\cup[a, b]$
10. $a < |x-c| < b$
    $x-c \in (-b,-a)\cup(a,b)\\
    x \in (-b+c,-a+c)\cup(a+c,b+c)$
11. $a\le|x-c|\le b$
    $x\in [-b+c, -a+c]\cup[a+c,b+c]$
            
    

## Licensing and Links

[All Mathematics Formula by Abhays here](./README.md)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.




