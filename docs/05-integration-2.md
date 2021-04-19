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

**Example** Evaluate $\int_0^4x\sqrt{x^2+9}dx, \int_0^1(x+1)e^{x^2+2x}dx, \int_0^{\frac{\pi}{2}}\sin x\cos xdx$

**Example** Find the area of the region that lies between the $x$-axis and the graph of $y=xe^{-x^2}$ for $-1\le x\le 2$.

## Integration of Rational Functions

## Integration by Parts

## More Applications of Definite Integrals
