# Ordinary differentiation

Note that *an italic title* indicates an application section which is less important than a theoretical one.

## Notes {-}

**Formula for slope** Suppose a curve $C$ is given by $y=f(x)$, where $f$ is a function; and a point $P(x_0;f(x_0))$ is on $C$. For any point $Q$ on $C$ with $Q\neq P$, its $x$-coordinate can be written as $x_0+h$ where $h\neq 0$ (if $h>0$, $Q$ is on the right of $P$; if $h<0$, Q is on the left of $P$). Thus, $Q$ can be written as $(x_0+h,f(x_0+h))$. The slope $m_{PQ}$ of the *secant line* $PQ$ is
$$m_{PQ}=\frac{f(x_0+h)-f(x_0)}{(x_0+h)-x_0}=\frac{f(x_0+h)-f(x_0)}{h}$$
Note that as $Q$ approaches $P$, the number $h$ approaches $0$. From these, we see that the slope of $C$ at $P$ (denoted by $m_p$) is 

\begin{equation}
m_p=\underset{h\rightarrow\infty}{\lim}\frac{f(x_0+h)-f(x_0)}{h} (\#eq:mp)
\end{equation}
provided that the limit exists.

<img src="./plots/2/slope.png" width="30%" style="display: block; margin: auto;" />

**Example** Find the slope of the curve $y=x^2$ at the point $P(3,9)$.

**Definition** Let $x_0$ be a real number and let $f$ be a function defined on an open interval containing $x_0$. Suppose the limit in \@ref(eq:mp) exists. Then we say that $f$ is **differentiable** at $x_0$.

**Example** Let $f(x)=|x|$. The domain of $f$ is $\mathbb{R}$. The function $f$ is continuous at $0$. However it is not differentiable at $0$.

**Definition** Let $f$ be a function that is differentiable at some points belonging in its domain. Then the **derivative** of $f$, denoted by $f'$, is the function (from a subset of $\text{dom}(f)$ into $\mathbb{R}$) given by
$$f'(x)=\underset{h\rightarrow\infty}{\lim}\frac{f(x+h)-f(x)}{h}$$
where the domain of $f'$ is $\{x\in\text{dom}(f):\underset{h\rightarrow\infty}{\lim}\frac{f(x+h)-f(x)}{h}~~ \text{exits} \}$

**Example** Find the derivative of $f(x)=|x|$.

**Example** Find the derivative of $f(x)=x^2$.

**Example** Find the derivative of $f(x)=x^3$.

**Notation**

- To denote the derivative of a function $f$, we have the following notations.

  $$f',f'(x),y',\frac{dy}{dx},\frac{d}{dx}y,\frac{d}{dx}f(x)$$

- To denote the derivative of $f$ at $x_0$, we have the following notations.

  $$f'(x_0),y'(x_0),\left.\frac{dy}{dx}\right|_{x=x_0}$$
  
**Caution** $\frac{dy}{dx}$ is not a fraction, but a function in $x$.  

**Rate of change** The slope of a curve $y=f(x)$ at a point $P(x_0,f(x_0))$  is the rate of change of $y$ with respect to $x$ at $P$. That is, $f'(x_0)$ is the rate of change of $y$ w.r.t. $x$ when $x=x_0$.

**Prove the following rules of differentiation**

- **Power Rule for Differentiation (positive integer version)** Let $n$ be a positive integer. Then the power function $x^n$ is differentiate on $\mathbb{R}$ and we have $\frac{d}{dx}x^n=nx^{n-1}$

- **Product Rule** Let $f$ and $g$ be functions with the same domain. Suppose that $f$ and $g$ are differentiable. Then the function $fg$ is also differentiable. Moreover, we have $\frac{d}{dx}(fg)(x)=g(x)\cdot\frac{d}{dx}f(x)+f(x)\cdot\frac{d}{dx}g(x)$

## Derivative of a function

**Derivative** The gradient of the tangent to a curve at a point.

**Derived function** The rule, $f'$, which gives the gradient of a function $f$ at a general point.

**Differentiation** The process or operation of determining the first derivative of a function.

**Tangent** A line that just touches a curve at a point.

**Chord, Secant** A straight line joining two points on a curve.

**Notations**

$$f'(x),\frac{dy}{dx}=\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta x}$$

## Rules of differentiation

**The constant rule** Differentiate the function and multiply by the constant. $h(x)=cf(x)$ then $h'(x)=cf'(x)$.

**The sum rule** Differentiate each function separately and add. $h(x)=f(x)+g(x)$ then $h'(x)=f'(x)+g'(x)$.

**The difference rule** $h(x)=f(x)-g(x)$ then $h'(x)=f'(x)-g'(x)$.

**Second-order derivative** The gradient of the first-order derivative denoted by $f''(x)$ or $\frac{d^2y}{dx^2}$.

**Concave** Graph bends downwards when $f''(x)<0$.

**Convex** Graph bends upwards when $f''(x)>0$.

## *Marginal functions in economics*

**Monopolist** The only firm in the industry.

**Perfect competition** A situation in which there are no barries to entry in an industry where there are many firms selling an identical product at the market price.

### *Profit* {-}

**Marginal revenue** The extra revenue gained by selling 1 more unit of a good. $MR = \frac{d TR}{dQ}$.

**Average revenue** Total revenue per unit of output. Average revenue curve and demand curve are synonymous.

**Marginal cost** The cost of producing 1 more unit of output. $MC=\frac{dTC}{dQ}$.

### *Production* {-}

**Marginal product of labor** The extra output produced by 1 more unit of labor. $MP_L=\frac{dQ}{dL}$.

**Law of diminishing marginal productivity (Law of diminishing returns)** Once the size of the workforce exceeds a particular value, the increase in output due to 1-unit increase in labor will decline. $\frac{d^2Q}{dL^2}<0$ for sufficiently large $L$.

### *National income* {-}

**Marginal propensity to consume** The fraction of a rise in national income which goes into consumption. $MPC=\frac{dC}{dY}$.

**Marginal propensity to save** The fraction of a rise in national income which goes into savings. $MPS=\frac{dS}{dY}$.

## Further rules of differentiation

**The chain rule** Differentiate the outer function and multiply by the derivative of the inner function. A composite function is given by $h(x)=f(g(x))$, then the derivative of it is $h'(x)=f'(g(x))g'(x)$. 

**The product rule** Multiply each function by the derivative of the other and add. The derivative of $h(x)=f(x)g(x)$ is given by $h'(x)=f'(x)h(x)+f(x)h'(x)$.

**The quotient rule** Bottom times derivative of top, minus top times derivative of bottom, all over bottom squared. The derivative of $h(x)=\frac{f(x)}{g(x)}$ is given by $h'(x)=\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^2}$.

## *Elasticity*

**Price elasticity of demand** A measure of the relative change in demand due to a relative change in price. 

**Price elasticity of supply** A measure of the relative change in supply due to a relative change in price.

**Arc elasticity** Elasticity measured by a chord on a curve.

**Point elasticity** Elasticity measured by a tangent on a curve, defined as $E=\frac{p}{Q}\times\frac{dQ}{dP}$.

**Elastic (inelastic/unit elastic) demand** When the relative change in demand is more (less/same) than the corresponding relative change in price, i.e., $E>1 (E<1/E=1)$.

**Derivative of an inverse function** Given $y=f(x)$ and its inverse function $x=f^{-1}(y)=h(y)$. The derivative of the inverse function $f^{-1}(y)$ is the reciprocal of the derivative of the original function. $\frac{dx}{dy}=h'(y)=\frac{1}{dy/dx}=\frac{1}{f'(x)}$.

## Optimization

**Optimization** The determination of the optimal points of a function.

**Stationary points (critical points, turning points, extrema)** Points on a graph at which the tangent is horizontal. At such a point, the first-order derivative is zero.

**Local maximum** A point on a curve which has the highest function value in comparison with other values in its neighbourhood. At such a point, the first-order derivative is zero and the second-order derivative is negative.

**Local minimum** A point on a curve which has the lowest function value in comparison with other values in its neighbourhood. At such a point, the first-order derivative is zero and the second-order derivative is positive.

**Stationary point of inflection** A stationary point that is neither a maximum nor a minimum. At such a point, the first-order derivative is zero and the second-order derivative is zero.

## *Optimization of economic functions*

**Average product of labour (labour productivity)** Output per worker. $AQ_L=Q/L$.

**Maximizing profit** If a firm maximizes profit, then $MR=MC$.

**Maximizing average product per labour** If a firm maximizes average product of labour, then $AP_L=MP_L$.

**Economic order quantity** The quantity of a product that should be ordered so as to minimize the total cost that includes ordering costs and holding costs.

## The derivative of the exponential and natural logarithm functions

**The derivative of the exponential function** If $f(x)=e^x$ then $f'(x)=e^x$. If $f(x)=c^x$ then $f'(x)=c^x\ln c$.

**The derivative of the logarithm function** If $f(x)=\ln x$ then $f'(x)=\frac{1}{x}$. If $f(x)=\log_c x$ then $f'(x)=\frac{1}{x\ln c}$.

## *A summary of applications of differentiation* {-}

### *Profit* {-}

Marginal revenue (compared with average revenue)
  
Marginal cost (compared with average cost)

Maximize the profit (MR=MC, E=-1)
  
- with price discrimination
    
- without price discrimination
  
Maximize the tax revenue under the market equilibrium conditions.
  
Minimize the total cost in inventory control

### *Production* {-}
  
Marginal product of labour (compared with average product of labour)

Maximize the average product of labour (AP=MP)

### *National income* {-}
  
Marginal propensity to consume
  
Marginal propensity to save


### *Elasticity* {-}
  
Price elasticity of demand (relationship with marginal revenue)
  
Price elasticity of supply








