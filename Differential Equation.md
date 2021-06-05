# Differential Equation

[TOC]

## Order and Degree of a Differential Equation

### Order

The order of the **height order** derivative in the differential equation.

### Degree

The degree of the **highest derivative** when differential coefficient are rational and free from fractions.

## Formation and Solution of Differential Equations

### Formation

1. Differentiate as many times as there are arbitrary constants.
2. If there are some left after step 1, then replace everything with x and y and dy/dx

### Solution

#### Type 1: Differential Equation of 1<sup>st</sup> Order | Variable Separable

$ \color{red}\frac{dy}{dx}=f(x)f(y)$

$\int\frac{dy}{f(y)}=\int f(x)dx+c$

#### Type 2: Equation Reducible to Variable Separable

$ \color{red}\frac{dy}{dx}=f(ax+by+c)$

$\text{Put, }ax+by+c=t\\
\text{or, }a+b\frac{dy}{dx}=\frac{dt}{dx}\\
\text{or, }\frac{dy}{dx}=\left(\frac{dt}{dx}-a\right)\frac{1}{b}\\
\therefore\left(\frac{dt}{dx}-a\right)\frac{1}{b}=f(t)\\
\text{or, }\frac{dt}{dx}=a+bf(t)\\
\text{use Type 1.c.}$

#### Type 3: Homogenous Differential Equations

$\color{red}\frac{dy}{dx}=\frac{f(x,y)}{g(x,y)}\\
\color{red}\text{where }f\text{ and }g\text{ are homogenous function of same degree}$

$\text{Put } y = vx\\
\frac{dy}{dx}=v+x\frac{dv}{dx}\\
\text{Put, } y = v, x=1\\
\text{lastly, Put back }v=\frac{y}{x}$

#### Type 4: Linear Differential Equation

$\color{red}\frac{dy}{dx}+Py=Q\\
\color{red}\text{where }P\text{ and } Q \text{ either constants or function of } x \text{ only}$

$I.F.=e^{\int Pdx}=e^{Px}\\
\therefore y(I.F.)=\int Q(I.F.)dx + c$

#### Type 5: Equation reducible to linear form(optional) | Bernoulli Differential Equation

##### Type a: $y^n$

$\color{red}\frac{dy}{dx}+Py=Qy^n$

$\text{or, }\frac{1}{y^n}\frac{dy}{dx}+\frac{P}{y^{n-1}}\text{ [Divide both sides by }y^n]\\$

$\text{Put, }\frac{1}{y^{n-1}}=t\\
\therefore \frac{1-n}{y^n}\frac{dy}{dx}=\frac{dt}{dx}\\
\text{or, } \frac{1}{y^n}\frac{dy}{dx}=\left(\frac{1}{1-n}\right)\frac{dt}{dx}$

$\therefore \frac{1}{1-n}\frac{dt}{dx}+Pt=Q\\
\text{Proceed as Linear Equation}$

##### Type b: $f(y)$

$\color{red}\frac{dy}{dx}+Py=Qf(y)$

$\text{Divide both sides by } f(y) \text{ and proceed as type a} $

#### Type 6: Equation Reducible to Homogenous form

$\color{red}\frac{dy}{dx}=\frac{a_1x+b_1y+c_1}{a_2+b_2y+c_2}$

Differentiate options.