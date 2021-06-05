# Indefinite Integrals























## Fundamental Integration Formulas
### Algebra

$\int x^{n}dx=\frac{x^{n+1}}{n+1}+c$

$\int \frac{1}{x^n}=\frac{1}{-(n-1)x^{n-1}}$

$\int \sqrt{x}dx=\frac{2}{3}x^{\frac{3}{2}}+c$

$\int\frac{dx}{\sqrt{x}}=2\sqrt{x}+c$

$\int a^xdx=\frac{a^x}{\log a}+c$

$\int e^xdx=e^x+c$

$\int \frac{1}{x}dx=\log x+c$

$\int|x|dx=\frac{x|x|}{2}$

$\int |x|^ndx=\frac{x|x|^n}{n+1}$

### Trigonometric

$\int \sin x\,dx={-\cos x}+c$

$\int \cos x\,dx=\sin x+c$

$\int \sec^2x\,dx=\tan x+c$

$\int \text{cosec}^2x\,dx=-\cot x+c$

$\int \sec x \tan x\,dx=\sec x+c$

$\int \text{cosec } x \cot x\,dx=-\text{cosec }x+c$

### Inverse Trigonometric

$\int \frac{dx}{\sqrt{1-x^2}}=\left\{\begin{array}{ll}
	\sin^{-1}x+c\\
	-\cos^{-1}x+c
\end{array}\right.$

$\int \frac{dx}{1+x^2}=\left\{\begin{array}{ll}
	\tan^{-1}x+c\\
	-\cot^{-1}x+c
\end{array}\right.$

$\int \frac{dx}{x \sqrt{x^2-1}}=\left\{\begin{array}{ll}
	\sec^{-1}x+c\\
	-\text{cosec }^{-1}x+c
\end{array}\right.$

### Trigonometric Integration

|Integration of | Use technique|
|-|-|
|$\cos$, $\sin$, $\sec^2$ ,$\text{cosec }^2$, $(\sec x \tan x)$ and $(\text{cosec } x \cot x)$| Use Fundamental Integrals|
|$\sin^n x$ or $\cos^nx$| Use [Odd and even power tehcnique](#sinToThePowerN) shown later|
|$1+\sin x$ in the denominator| Rationalize. Get $1-sin^2 x$ form. Put $cos^2x$|
|$1+\cos x$ in the denominator| Use half angle formulae or Rationalize.|
|$\tan^mx\sec^{2n}x$|Separate $\sec^2x$ and put $\tan x=t$|
|$\cot^mx\text{cosec }^{2n}x$|Separate $\text{cosec }^2x$ and put $\cot x = t$|
|$\tan^{2m+1}x\sec^{2n+1}x$|Separate $\sec x \tan x$ and put $\sec x=t$|
|$\tan^n x$ or $\cot^n x$| try to get either $\sec^2x$ or $\sec x\tan x$|
|$\sin^m x \cos^n x\,dx$| Even odd technique |
|$\sin^m x \cos^n x\,dx$,  $m+n\rightarrow$ negative even integer| Change integrand to $\tan x$ and $sec^2x$ by dividing by $cos^kx$ where $k=-(m+n)$ |
|Denominator has $(a^2-x^2)^n$ or $(a-x)^n$| Put $x=a\sin\theta$ or Put $x=a\sin^2x$ |
|Denominator has $(a^2+x^2)^n$ or $(a+x)^n$| Put $x=a\tan\theta$ or Put $x=a\tan^2\theta$ |
|Denominator has $(x^2-a^2)^n$ or $(a-x)^n$| Put $x=a\sec\theta$ or Put $x=a\sec^2\theta$ |

## 14 Standard Formulae

These are used pretty often but not that much

1. $\int \log{x}\,dx=\left\{\begin{array}{ll}x\log x -x\\ x\log \frac{x}{e}\end{array}\right.$
2. $\int \tan x \,dx=\left\{\begin{array}{ll}\log|\sec x|\\-\log|\cos x|\end{array}\right.$
3. $\int \cot x\, dx =\left\{\begin{array}{ll} \log|\sin x|\\-\log|\text{cosec } x|\end{array}\right.$
4. $\int \sec x\,dx=\left\{\begin{array}{ll}\log|\sec x+\tan x|\\\log |\tan(\frac{\pi}{4}+\frac{x}{2})|\end{array}\right.$
5. $\int\text{cosec } x\,dx=\left\{\begin{array}{ll}\log|\text{cosec } x - \cot x| \\\log|\tan \frac{x}{2}|\\-\log|\text{cosec } x+\cot x|\end{array}\right.$

### 9 Standard Results: 

Without Square root

1. $\int \frac{dx}{a^2+x^2}=\frac{1}{a}\tan^{-1}\frac{x}{a}$

2. $\int \frac{dx}{a^2-x^2}=\frac{1}{2a}\log \begin{vmatrix}\frac{a+x}{a-x}\end{vmatrix}$

3. $\int \frac{dx}{x^2-a^2}=\frac{1}{2a}\log \begin{vmatrix}\frac{x-a}{a+x}\end{vmatrix}$

Square root in denominator

1. $\int \frac{dx}{\sqrt{a^2+x^2}}=\log \begin{vmatrix}x+\sqrt{a^2+x^2}\end{vmatrix}$

2. $\int \frac{dx}{\sqrt{a^2-x^2}}=\sin^{-1}\frac{x}{a}$

3. $\int \frac{dx}{\sqrt{x^2-a^2}}=\log \begin{vmatrix}x+\sqrt{x^2-a^2}\end{vmatrix}$

Square root in numerator

1. $\int \sqrt{a^2+x^2}\,dx=\frac{1}{2}[x \sqrt{a^2+x^2}+a^2\log(x+\sqrt{a^2+x^2})]$

2. $\int \sqrt{a^2-x^2}\,dx=\frac{1}{2}[x \sqrt{a^2-x^2}+a^2 \sin^{-1}\frac{x}{a}]$

3. $\int \sqrt{x^2-a^2}\,dx=\frac{1}{2}[x \sqrt{x^2-a^2}-a^2\log(x+\sqrt{x^2-a^2})]$|

## Operations on Integrals

$\int c f(x)\,dx = c\int f(x)\,dx$

$\int[f(x)\pm g(x)]dx=\int f(x)\,dx \pm \int g(x)\,dx$

Integration not possible on improper fraction. Change to proper fraction first.

## Substitution Method

1. $\int f(x)f'(x)\,dx=\frac{\{f(x)\}^2}{2}+c$
2. $\int [f(x)]^n f'(x)\,dx=\frac{\{f(x)\}^{n+1}}{n+1}+c$
3. $\int{\frac{f'(x)}{f(x)}\,dx}=\log{f(x)}+c$
4. $\int \frac{f'(x)}{[f(x)]^n}\,dx=\frac{1}{-(n+1)\{f(x)\}^{n+1}}+c$

### Method

1. Put $f(x)=t$
2. Differentiate to get $f'(x)\,dx=dt$
3. Put $t$ and $f'(x)\,dx$ in the given integral
4. Solve the integral with $t$
5. put back $f(x)$ in place of $t$

### <a name="sinToThePowerN"></a>Odd and even powers of $\sin$ and $\cos$

**Odd Powers:** Make even power and use substitutions.
**Even Powers:** Use $\sin^2x=\frac{1-\cos2x}{2}$ OR $\cos^2x=\frac{1+\cos2x}{2}$ until fundamental integral is reached.

### Type A: Polynomial Type Integrals

#### Perfect Square forms

1. Type 1: $\int{\frac{dx}{ax^2+bx+c}}$
2. Type 2: $\int{\frac{dx}{\sqrt{ax^2+bx+c}}}$
3. Type 3: $\int{\sqrt{ax^2+bx+c}}\,dx$

##### Method

1. Make perfect square
2. Use 9 Standard results

#### Polynomial on numerator

1. $\int{\frac{px+q}{ax^2+bx+c}}\,dx=A\log \begin{vmatrix}D\end{vmatrix}+B\int \frac{dx}{D}$
2. $\int{\frac{px+q}{\sqrt{ax^2+bx+c}}}\,dx=2A\sqrt{D}+B\int \frac{dx}{\sqrt{D}}$
3. $\int{(px+q)\sqrt{ax^2+bx+c}}\,dx=\frac{2A}{3}D^\frac{3}{2}+B\int \sqrt{D}\,dx$

##### Method

Put $px+q=A\{\frac{d}{dx}(ax^2+bx+c)\}+B$ 

#### Type B: Half Angle

1. Type 1:$\int \frac{dx}{a+b\sin x}$

2. Type 2: $\int \frac{dx}{a+b \cos x}$

3. Type 3: $\int \frac{dx}{a \sin x + b \cos x}$

###### Method 

1. Let $\tan \frac{x}{2} = t$
2. $\therefore dx=\frac{2dt}{1+t^2}$
3. Put $\sin x = \frac{2 \tan \frac{x}{2}}{1+\tan^2 \frac{x}{2}}=\frac{2t}{1+t^2}$
4. Put $\cos x = \frac{1- \tan^2 \frac{x}{2}}{1+\tan^2 \frac{x}{2}}=\frac{1-t^2}{1+t^2}$

#### Type C: linear sin cos 

Type 1: $\int \frac{dx}{a \sin x + b \cos x}$

1. Divide numerator and denominator by $\sqrt{a^2+b^2}$
2. Get $\int \sec x dx=\log \begin{vmatrix}\tan(\frac{x}{2}+\frac{\pi}{4})\end{vmatrix}$
3. Get $\int \text{cosec } dx = \log \begin{vmatrix}\tan \frac{x}{2}\end{vmatrix}$

Type 2: $\int \frac{p\sin x +q \cos x}{a\sin x +b \cos x}dx =Ax+B\log \begin{vmatrix}D\end{vmatrix}+c$

1. Put $p\sin x +q \cos x =A(D)+B(\frac{d}{dx}D)$

### Integral Formula (Product Formula)

$\int uv\,dx=u\int{v\,dx}-\int[\frac{d}{dx}u\int v\,dx]dx$
$\int 12dx=1\int2dx-\int[\frac{d}{dx}1\int2dx]dx$

|I|L|A|T|E|
|-|-|-|-|-|
|Inverse Trigonometric|Logarithmic|Algebraic|Trigonometric|Exponential|
|$\sin^{-1}x$, $\cos^{-1}x$|$\log$|$x^3$, $2x$, $3x$|$\sin x$, $\cos x$|$e^x$|

## Partial Fraction in Integrals

Only used in proper fraction otherwise first divide and make improper fraction. Type 1 is 70% important. Type 2 is 25%. Type 3 is 4% and Type 4 is 1%.

You might not need to find all A, B, C... to solve these questions. Stop wherever the options match. Start with final answer and slowly fill either A/B/C... depending upon which is easier to find/which leads to option selection faster.

### Rules for Proper Fraction

1. $\int \frac{px+q}{(a+x)(b+x)}=A\log(a+x)+B\log(b+x)+c$

   Put $\frac{px+q}{(a+x)(b+x)}=\frac{A}{(a+x)}+\frac{B}{(b+x)}$

2. $\int \frac{px+q}{(a+x)(b+x)^3}=A\log \begin{vmatrix}a+x\end{vmatrix}+B\log \begin{vmatrix}b+x\end{vmatrix}-\frac{C}{2}\frac{1}{(b+x)}-\frac{D}{3}\frac{1}{(b+x)^2}+c$

   Put $ \frac{px+q}{(a+x)(b+x)^3}=\frac{A}{(a+x)}+\frac{B}{(b+x)}+\frac{C}{(b+x)^2}+\frac{D}{(b+x)^3}$

3. $\int \frac{px+q}{(a+x)(b+x^2)}dx=A\log \begin{vmatrix}a+x\end{vmatrix}+\frac{B}{2}\log \begin{vmatrix}b+x^2\end{vmatrix}+\frac{C}{\sqrt{b}}\tan^{-1}\frac{x}{2}+c$

   Put $\frac{px+q}{(a+x)(b+x^2)}= \frac{A}{a+x}+\frac{Bx+C}{b+x^2}$

4. $\int \frac{px+q}{(a+x)(b+x^2)^2}dx$

   Put $\frac{px+q}{(a+x)(b+x^2)^2}=\frac{A}{a+x}+\frac{Bx+c}{b+x^2}+\frac{Dx+E}{(b+x^2)^2}$

## Special Type

### Form $(x^2+1)/(x^4+1)$

1. Type 1: $\frac{x^2+1}{x^4+kx^2+1}$
2. Type 2: $\frac{x^2-1}{x^4+kx^2+1}$
3. Type 3: $\frac{x^2+a}{x^4+kx^2+a^2}$
4. Type 4: $\frac{x^2-a}{x^4+kx^2+a^2}$

#### Formulae

1. $\int \frac{x^2+1}{x^4+1}dx=\frac{1}{\sqrt2}\tan^{-1}\left(\frac{x^2-1}{\sqrt2x}\right)$
2. $\int \frac{x^2-1}{x^4+1}dx=\frac{1}{2\sqrt2}\log\left|\frac{x^2-\sqrt2x+1}{x^2+\sqrt2x+1}\right|$
3. $\int \frac{x^2+a}{x^4+a^2}dx=\frac{1}{\sqrt{2a}}\tan^{-1}\left(\frac{x^2-a}{\sqrt{2a}x}\right)$
4. $\int \frac{x^2-a}{x^4+a^2}dx=\frac{1}{2\sqrt{2a}}\log\left|\frac{x^2-\sqrt{2a}x+1}{x^2+\sqrt{2a}x+1}\right|$

#### Method 

1. Divide numerator and denominator by $x^2$
2. break denominator as $\left\{\begin{array}{ll}x^2+\frac{1}{x^2}=(x+\frac{1}{x})^2-2& \text{if numerator has plus}\\x^2+\frac{1}{x^2}=(x-\frac{1}{x})^2-2& \text{if numerator has minus}\end{array}\right.$
3. e.g. Numerator: $1+\frac{1}{x^2}$ denominator: $(1-\frac{1}{x})^2+a$
   Put $t=1-\frac{1}{x}$

## Observations

- $\int\cos2x\log \sin x dx$ 
  $\log$ and trig ek saath wale questions mei integration by parts karna hota hai
- $\int x^2\sin x dx$ 
  trig aur algebra saath aae to integration by parts karna hota hai
- $\int xe^x dx$ 
  exp .aur algebra ek saath wale questions mei integration by parts karna hota hai
- $\int \frac{dx}{x(1+x)}$
  ismei bracket  mei se x common lo. bahar $1/x^2 $banega andar $1/x$ phir $1/x$ ko t maan lo
- $\int \frac{1}{\log x} - \frac{1}{(\log x)^2}\,dx$
  Bohot sare log wale questions mei put $\log x= t$ and $e^t = x$ then you might get $\int e^x(f(x) +f'(x))dx=e^xf(x)$
- Always put under root quantity as $t^2$ and not just $t$
- Agar options mei sab kuch $\sin$ aur $\cos$ k form mei ho to option reject karo in integral with $\cos$  cannot be positive and $\sin$ cannot be negative.
