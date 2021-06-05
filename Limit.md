# Limit

## Method of Limits

### Direct Substitution

Put value of x if no indefinite from occurs. 
 $\lim_{x \to 2} \frac{x+2}{x^2+4}=\frac{2+2}{2^2+4}=\frac{1}{2}$ 

Limit is only solved for $\frac{0}{0}$ or $\frac{\infty}{\infty}$ form. Else use direct substation. 

### Factorization Method

If elimination of indefinite form possible using factorization then cancel it out.
$\lim_{x \to 3} \frac{x^2-5x+6}{x-3}$
at $x=3$, $\frac{3^2-5 \times 3+6}{3-3}=\frac{0}{0}$ is undefined. So factorize the numerator and cancel with the denominator.

*Better use L'Hôpital's rule*

### Rationalization Method

Multiply numerator and denominator by rationalizing factor. 
$\lim_{x \to 0} \frac{\sqrt{1+x}-\sqrt{1-x}}{x}$
at $x=0$, $\frac{0}{0}$ is undefined. So rationalize as:
$\lim_{x \to 0} \frac{\sqrt{1+x}-\sqrt{1-x}}{x} \times \frac{\sqrt{1+x}+\sqrt{1-x}}{\sqrt{1+x}+\sqrt{1-x}}$
$=\lim_{x \to 0} \frac{2}{(\sqrt{1+x}+\sqrt{1-x})}$
at $x=0$, $\frac{2}{\sqrt{1+0}+\sqrt{1-0}}=1$

*Better use L'Hôpital's rule*

###  limit when $x \to \infty$

Use $x\to \infty \implies \frac{1}{x}\to 0$

#### Type 1  $\frac{p}{q}$ form

Divide the numerator and denominator by the greatest power of x.
$\lim_{x\to\infty} \frac{5x^2-7x+11}{6x^2+9x-13}$
+Here divide by $x^2$ to get $\lim_{x\to 0} \frac{5-\frac{7}{x}+\frac{11}{x^2}}{6+\frac{9}{x}-\frac{13}{x^22}}=\frac{5}{6}$

##### Trick

$\lim_{x\to\infty} \frac{5x^2-7x+11}{6x^2+9x-13}$ Same power then get coefficient of highest power $\to \frac{5}{6}$
$\lim_{x\to\infty} \frac{5x^2-7x+11}{6x+9}$ numerator > denominator $\to \infin$
$\lim_{x\to\infty} \frac{5x-7}{6x^2+9x-13}$ denominator > numerator $\to 0$

#### Type 2 with rationalization

$\lim_{x\to\infty}(\sqrt{x^2+7x}-x)$
$=\lim_{x\to\infty}\frac{x^2+7x-x^2}{\sqrt{x^2+7x}+x}$ [rationalization]
$=\lim_{x\to\infty}\frac{7x}{\sqrt{x^2+7x}+x}$ 
NOTE: here numerator and denominator has equal greatest power i.e. 1. $\sqrt{x^2}$ is potentially $x$. Divide and proceed as Type 1.

### L'Hôpital's rule

**Required Condition:** $\lim_{x \to a}\frac{f(x)}{g(x)}=\frac{f(a)}{g(a)}=\frac{0}{0}$ or $\frac{\infty}{\infty}$
and according to the rule, differentiate numerator and denominator *separately*
$\lim_{x \to a} \frac{\frac{d}{dx}f(x)}{\frac{d}{dx}g(x)}$

## List of Formulae

### Limit Formulae

| Algebraic                                                    | $\sin$ and $\tan$                                            | $1^\infty$ form                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1. $\lim_{x\to a} \frac{x^n-a^n}{x-a}=na^{n-1}$ *<br/>2. $\lim_{x\to 0}\frac{e^x-1}{x}=1$*<br/>3. $\lim_{x\to0}\frac{a^x-1}{x}=\log_ea$*<br/>4. $\lim_{x\to 0}\frac{log(1+x)}{x}=1$  <br/>5. $\lim_{x\to 0}\frac{log(1+ax)}{x}=a$ | 6. $\lim_{x\to0}\frac{\sin{ax}}{x}=a$<br/>7. $\lim_{x\to0}\frac{\sin{ax}}{\sin{bx}}=\frac{a}{b}$<br/>8. $\lim_{x\to0}\frac{\tan{ax}}{x}=a$<br/>9. $\lim_{x\to0}\frac{\tan{ax}}{\tan{bx}}=\frac{a}{b}$<br />10. $\lim_{x\to0}\frac{\sin^{-1}{x}}{x}=1$<br/>11. $\lim_{x\to0}\frac{\tan^{-1}{x}}{x}=1$ | 1. $\lim_{x\to a}[f(x)]^{g(x)}=\lim_{x\to a}e^{g(x)(f(x)-1)}$<br/>    	where $f(a)\to1$ and $g(a)\to \infty$<br/>    	Trick: $B^P=e^P[B-1]$ <br/>2. $\lim_{x\to 0}(1+x)^\frac{1}{x}=e$<br/>3. $\lim_{x\to \infty}(1+\frac{1}{x})^x=e$<br/>4. $\lim_{x\to 0}(1+ax)^\frac{1}{x}=e^a$<br/>5. $\lim_{x\to \infty}(1+\frac{a}{x})^x=e^a$ |

\* Better use L'Hôpital's rule 

### Expansion Formula

| Formula                                                      | Formula                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| $e^x=1+\frac{x}{1!}+\frac{x^2}{2!}+\frac{x^3}{3!}+\dots$     | $\sin{x}=x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\dots$ |
| $a^x=1+\frac{x\log_ea}{1!}+\frac{x^2(\log_ea)^2}{2!}+\frac{x^3(\log_ea)^3}{3!}+\dots$ | $\cos{x}=1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\dots$ |
| $\log{(1+x)}=x-\frac{x^2}{2}+\frac{x^3}{3}-\frac{x^4}{4}+\dots$ | $\tan{x}=x+\frac{1}{3}x^3+\frac{2}{15}x^5+\dots$             |
| $\log{(1-x)}=-x-\frac{x^2}{2}-\frac{x^3}{3}-\frac{x^4}{4}-\dots$ | $(1+x)^n=1+nx+\frac{n(n-1)}{2!}x^2+\dots$                    |
| $(1+x)^{\frac{1}{x}}=e(1-\frac{x}{2}+\frac{11}{24}x^2+\dots)$ | $(1-x)^n=1-nx+\frac{n(n-1)}{2!}x^2-\dots$                    |

## Things to remember

### Limits 

| Algebraic                                                    | Trigonometric                                                |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| $\lim_{x\to 0}\frac{1}{x}$ Does not exists<br/>$\lim_{x\to 0}\frac{1}{x^2}=\infty$<br />$\lim_{x\to a}\frac{|x-a|}{x-a}$ Does not exists | $\lim_{x\to \frac{\pi}{2}}\tan{x}$ Does not exists<br />$\lim_{x\to0}\sin{\frac{1}{x}}=\sin{\infty}=[-1,1]\to$ anything from -1 to 1 i.e. Limit Does not exist<br/>$\lim_{x\to0}x\sin{\frac{1}{x}}=0\times [-1,1]=0$ |

#### LHL and RHL

LHL = $f(a-h)\to$ put h = 0
RHL = $f(a+h)$

Use this method in Greatest Integer functions, mod functions, and specially defined functions.  

### Concepts

#### Common indeterminate forms 

| d                                               |                                     |                                                              |                                      |
| ----------------------------------------------- | ----------------------------------- | ------------------------------------------------------------ | ------------------------------------ |
| $\frac{1}{0}=\infty$  is not indeterminate form | $\frac{0}{0}\to$ Indeterminate form | $1^\infty=1^\frac{1}{0}=\sqrt[0]{1}\to$ indeterminate. $\therefore 1^\infty\ne1$ | $\infty^0\ne1\to$ indeterminate form |

## Limit tricks

### $\lim_{x\to 0}$

When we have $\lim_{x\to0}$ these simple forms can be written:

| Algebraic                                                    | $\sin$                                                       | $\tan$                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| $\lim_{x\to0}(1+x)^n=\lim_{x\to0} 1+nx$ <br/>$\lim_{x\to0}(1+x)^n=\lim_{x\to0} 1+nx$ | $\lim_{x\to0} \sin x = \lim_{x\to0} x$<br/>$\lim_{x\to0} \sin ax = \lim_{x\to0} ax$<br/>$\lim_{x\to0} \sin^n x = \lim_{x\to0} x^n$<br/>$\lim_{x\to0} \sin^n ax = \lim_{x\to0} a^nx^n$<br />$\lim_{x\to0}\sin^{-1}x=x$ | $\lim_{x\to0} \tan x = \lim_{x\to0} x$<br/>$\lim_{x\to0} \tan ax = \lim_{x\to0} ax$<br/>$\lim_{x\to0} \tan^n x = \lim_{x\to0} x^n$<br/>$\lim_{x\to0} \tan^n ax = \lim_{x\to0} a^nx^n$<br />$\lim_{x\to0}\tan^{-1}x=x$ |

### Suggestions

- Har line mei $\lim_{x\to a}$ mat likha karo. Save time. 
- Jab bhi Limit DNE ka option ho tab LHL and RHL laga k dekh lena.
- If denominator has power $\ge$ 2 then don't prefer L'Hôpital's rule Rule
