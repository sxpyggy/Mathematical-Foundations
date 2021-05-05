# More Integration

## More Formulas

1. $\int x^rdx=\frac{x^{r+1}}{r+1}+C$

2. $\int \sin x dx=-\cos x +C$

3. $\int \cos x dx=\sin x +C$

4. $\int \sec^2 x dx =\tan x+C$

5. $\int \frac{1}{1+x^2}dx=\tan^{-1}x+C$

6. $\int e^xdx=e^x +C$

7. $\int \frac{1}{x}dx=\ln|x| +C$

## Subsitution Method

Let $y$ be a composition function of $F$ with $g$:
$$y=F(g(x)).$$
Suppose that the function $g$ is differentiable on an open interval $I$ and that the function $F$ is differentiable on an open interval containing the image of $I$ under $g$. By the chain rule, the composition function $F\circ g$ is differentiable on $I$:
$$\frac{d}{dx}F(g(x))=\frac{dy}{dx}=\frac{dy}{d g(x)}\frac{d g(x)}{dx}=F'(g(x))g'(x),$$

Since the integration is the reverse process of differentiation, we have 
$$\int F'(g(x))\cdot g'(x)dx=\int f(g(x))\cdot g'(x)dx=F(g(x))+C,$$
where $F'=f$.

**Change of variable method** Putting $u=g(x)$ and using $du=g'(x)dx$, we get
$$\int f(g(x))g'(x)dx=\int f(u)du=F(u)+C.$$

**Remarks** The notations $du$ and $dx$ are called differentials. They are related by the fact that if $\Delta x$ is small, then $\frac{\Delta u}{\Delta x}$ is approximately equal to $g'(x)$, that is 
$$\Delta u=g'(x)\Delta x.$$
In the limiting situation, we have $du=g'(x)dx$.

**Example** Find $\int(x^2+1)^2 2x dx, \int\frac{\ln x}{x}dx, \int x^2e^{x^3}dx, \int\sin(2x-3)dx$

**Substitution method for definite integrals**
$$\int_a^bf(g(x))g'(x)dx=\int_{g(a)}^{g(b)}f(u)du$$
where $g$ is a continuous function on $[a,b]$ and $f$ is a function defined and continuous on an open interval $I$ containing the image of $[a,b]$ under $g$.

**Example** Evaluate $\int_0^4x\sqrt{x^2+9}dx, \int_0^1(x+1)e^{x^2+2x}dx, \int_0^{\frac{\pi}{2}}\sin x\cos xdx$

**Example** Find the area of the region that lies between the $x$-axis and the graph of $y=xe^{-x^2}$ for $-1\le x\le 2$.

## Integration of Rational Functions

$$\int \frac{A}{ax+b}dx\\=A\int\frac{1}{ax+b}dx\\=A\cdot\frac{1}{a}\cdot\ln|ax+b|+C$$
We consider three cases when integrate 
$$\frac{Ax+B}{ax^2+bx+c}$$

**Case 1** $b^2-4ac>0$

The denominator can be factorized as $a(x-x_1)(x-x_2)$. Moreover, there exists contants $\alpha, \beta$ such that 
$$\frac{Ax+B}{ax^2+bx+c}=\frac{\alpha}{x-x_1}+\frac{\beta}{x-x_2}$$
The above process is called **partial-fraction decomposition** of the rational function.

**Example** Find $\int\frac{x+1}{x^2-2x-3}dx$.

**Case 2** $b^2-4ac=0$.

The denominator can be factorized as $a(x-x_1)^2$. Moreover, there exists contants $\alpha, \beta$ such that 
$$\frac{Ax+B}{ax^2+bx+c}=\frac{\alpha}{x-x_1}+\frac{\beta}{(x-x_1)^2}.$$

**Example** Find $\int\frac{2x+3}{x^2-2x+1}dx$

**Case 3** $b^2-4ac<0$

The denominator can be written as $a((x+s)^2+t^2)$

**Subcase 3a** $A=0$
$$\int\frac{Ax+B}{ax^2+bx+c}dx=\frac{B}{at}\tan^{-1}\frac{x+s}{t} +C$$

**Subcase 3b** $Ax+B=k(2ax+b)$
$$\int\frac{Ax+B}{ax^2+bx+c}dx=\int\frac{k(2ax+b)}{ax^2+bx+c}$$
which can be integrated using substitution $u=ax^2+bx+c$.

**Case 3 in general** We rewrite the numerator as a sum of two terms: the first one is a multiple of the derivative of the denominator and the second one is a constant.

**Example** Find $\int\frac{2x+3}{x^2+4x+13}dx$

## Integration by Parts

The technique in integration that corresponds to the product rule in differentiation is called **integration by parts**.



## More Applications of Definite Integrals
