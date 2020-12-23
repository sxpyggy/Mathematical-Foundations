# Differentiation

**[✍️ Final Exam](#final)**

## Summary of the textbook

#### Derivative of a function {-}

- **Derivative** The gradient of the tangent to a curve at a point.

- **Derived function** The rule, $f'$, which gives the gradient of a function $f$ at a general point.

- **Differentiation** The process or operation of determining the first derivative of a function.

- **Tangent** A line that just touches a curve at a point.

- **Chord** A straight line joining two points on a curve.

- **Notations**

$$f'(x),\frac{dy}{dx}=\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta x}$$

#### Rules of differentiation {-}

- **Rule 1 The constant rule** Differentiate the function and multiply by the constant. $h(x)=cf(x)$ then $h'(x)=cf'(x)$.

- **Rule 2 The sum rule** Differentiate each function separately and add. $h(x)=f(x)+g(x)$ then $h'(x)=f'(x)+g'(x)$.

- **Rule 3 The difference rule** $h(x)=f(x)-g(x)$ then $h'(x)=f'(x)-g'(x)$.

- **Second-order derivative** The gradient of the first-order derivative denoted by $f''(x)$ or $\frac{d^2y}{dx^2}$.

- **Concave** Graph bends downwards when $f''(x)<0$.

- **Convex** Graph bends upwards when $f''(x)>0$.

#### Marginal functions in economics {-}

- **Marginal revenue** The extra revenue gained by selling 1 more unit of a good. $MR = \frac{d TR}{dQ}$.

- **Average revenue** Total revenue per unit of output. Average revenue curve and demand curve are synonymous.

- **Marginal cost** The cost of producing 1 more unit of output. $MC=\frac{dTC}{dQ}$.

- **Marginal product of labor** The extra output produced by 1 more unit of labor. $MP_L=\frac{dQ}{dL}$.

- **Marginal propensity to consume** The fraction of a rise in national income which goes into consumption. $MPC=\frac{dC}{dY}$.

- **Marginal propensity to save** The fraction of a rise in national income which goes into savings. $MPS=\frac{dS}{dY}$.

- **Monopolist** The only firm in the industry.

- **Perfect competition** A situation in which there are no barries to entry in an industry where there are many firms selling an identical product at the market price.

- **Law of diminishing marginal productivity (Law of diminishing returns)** Once the size of the workforce exceeds a particular value, the increase in output due to 1-unit increase in labor will decline. $\frac{d^2Q}{dL^2}<0$ for sufficiently large $L$.

#### Further rules of differentiation {-}

- **The chain rule** Differentiate the outer function and multiply by the derivative of the inner function. A composite function is given by $h(x)=f(g(x))$, then the derivative of it is $h'(x)=f'(g(x))g'(x)$. 

- **The product rule** Multiply each function by the derivative of the other and add. The derivative of $h(x)=f(x)g(x)$ is given by $h'(x)=f'(x)h(x)+f(x)h'(x)$.

- **The quotient rule** Bottom times derivative of top, minus top times derivative of bottom, all over bottom squared. The derivative of $h(x)=\frac{f(x)}{g(x)}$ is given by $h'(x)=\frac{f'(x)g(x)-f(x)g'(x)}{g(x)^2}$.

#### Elasticity {-}

- **Price elasticity of demand** A measure of the relative change in demand due to a relative change in price. 

- **Price elasticity of supply** A measure of the relative change in supply due to a relative change in price.

- **Arc elasticity** Elasticity measured by a chord on a curve.

- **Point elasticity** Elasticity measured by a tangent on a curve, defined as $E=\frac{p}{Q}\times\frac{dQ}{dP}$.

- **Elastic (inelastic/unit elastic) demand** When the relative change in demand is more (less/same) than the corresponding relative change in price, i.e., $E>1 (E<1/E=1)$.

- **Derivative of an inverse function** Given $y=f(x)$ and its inverse function $x=f^{-1}(y)=h(y)$. The derivative of the inverse function $f^{-1}(y)$ is the reciprocal of the derivative of the original function. $\frac{dx}{dy}=h'(y)=\frac{1}{dy/dx}=\frac{1}{f'(x)}$.

#### Optimisation of economic functions {-}

- **Optimization** The determination of the optimal points of a function.

- **Stationary points (critical points, turning points, extrema)** Points on a graph at which the tangent is horizontal. At such a point, the first-order derivative is zero.

- **Local maximum** A point on a curve which has the highest function value in comparison with other values in its neighbourhood. At such a point, the first-order derivative is zero and the second-order derivative is negative.

- **Local minimum** A point on a curve which has the lowest function value in comparison with other values in its neighbourhood. At such a point, the first-order derivative is zero and the second-order derivative is positive.

- **Stationary point of inflection** A stationary point that is neither a maximum nor a minimum. At such a point, the first-order derivative is zero and the second-order derivative is zero.

- **Average product of labour (labour productivity)** Output per worker. $AQ_L=Q/L$.

- If a firm maximizes profit, then $MR=MC$.

- If a firm maximizes average product of labour, then $AP_L=MP_L$.

- **Economic order quantity** The quantity of a product that should be ordered so as to minimize the total cost that includes ordering costs and holding costs.

#### The derivative of the exponential and natural logarithm functions {-}

- **The derivative of the exponential function** If $f(x)=e^x$ then $f'(x)=e^x$. If $f(x)=c^x$ then $f'(x)=c^x\ln c$.

- **The derivative of the logarithm function** If $f(x)=\ln x$ then $f'(x)=\frac{1}{x}$. If $f(x)=\log_c x$ then $f'(x)=\frac{1}{x\ln c}$.

#### A summary of applications of differentiation {-}

- Marginal revenue (compared with average revenue)
  
- Marginal cost (compared with average cost)
  
- Marginal product of labour (compared with average product of labour)
  
- Marginal propensity to consume
  
- Marginal propensity to save
  
- Price elasticity of demand (relationship with marginal revenue)
  
- Price elasticity of supply
  
- Maximize the profit (MR=MC, E=-1)
  
  - with price discrimination
    
  - without price discrimination
  
- Maximize the average product of labour (AP=MP)
  
- Maximize the tax revenue under the market equilibrium conditions.
  
- Minimize the total cost in inventory control

## Additional notes

**Formula for slope** Suppose a curve $C$ is given by $y=f(x)$, where $f$ is a function; and a point $P(x_0;f(x_0))$ is on $C$. For any point $Q$ on $C$ with $Q\neq P$, its $x$-coordinate can be written as $x_0+h$ where $h\neq 0$ (if $h>0$, $Q$ is on the right of $P$; if $h<0$, Q is on the left of $P$). Thus, $Q$ can be written as $(x_0+h;f(x_0+h))$. The slope $m_{PQ}$ of the *secant line* $PQ$ is
$$m_{PQ}=\frac{f(x_0+h)-f(x_0)}{(x_0+h)-x_0}=\frac{f(x_0+h)-f(x_0)}{h}$$
Note that as $Q$ approaches $P$, the number $h$ approaches $0$. From these, we see that the slope of $C$ at $P$ (denoted by $m_p$) is 

\begin{equation}
m_p=\underset{h\rightarrow\infty}{\lim}\frac{f(x_0+h)-f(x_0)}{h} (\#eq:mp)
\end{equation}
provided that the limit exists.

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

- **Power Rule for Differentiation (positive integer version)** Let $n$ be a positive integer. Then the power function $x^n$ is differentiate on $\mathbb{R}$ and we have $$\frac{d}{dx}x^n=nx^{n-1}$$

- **Product Rule** Let $f$ and $g$ be functions with the same domain. Suppose that $f$ and $g$ are differentiable. Then the function $fg$ is also differentiable. Moreover, we have $$\frac{d}{dx}(fg)(x)=g(x)\cdot\frac{d}{dx}f(x)+f(x)\cdot\frac{d}{dx}g(x)$$

# Partial Differentiation

## Summary of the textbook

#### Functions of several variables {-}

- **Dependent variable** A variable whose value is determined by that taken by the independent variable; in $z=f(x,y)$ the dependent variable is $z$.

- **Independent variable** Variables whose values determine that of the dependent variable; in $z=f(x,y)$ the independent variable are $x,y$.

- **Partial derivative** The derivative of a function of two or more variables with respect to one of these variables, the others being regarded as constant.

$$f_x=\frac{\partial z}{\partial x}, f_y=\frac{\partial z}{\partial y}$$

- **Second-order partial derivative** The partial derivative of a first-order partial derivative. For example, $f_{xy}$ is the second-order partial derivative when $f$ is differentiated with respect to $y$ and then with respect to $x$.

$$f_{xy}=\frac{\partial\frac{\partial z}{x}}{\partial y}$$

- **Differentials** Limiting values of incremental changes. In the limit the approximation $\Delta z \approx \partial z/\partial x\times\Delta x$ becomes $d z =\partial z/\partial x\times dx$ where $dz,dx$ are the differentials.

- **Small increments formula** $$\Delta z\approx \frac{\partial z}{\partial x}\Delta x + \frac{\partial z}{\partial y} \Delta y$$

- **Implicit differentiation** The process of obtaining $dy/dx$ where the function is not given explicitly as an expression for $y$ in terms of $x$.

#### Partial elasticity and marginal functions {-}

##### Elasticity {-}

- **Own price elasticity of demand** The responsiveness of demand for one good due to change in the price of itself.

- **Cross-price elasticity of demand** The responsiveness of demand for one good due to change in the price of the alternative good.

- **Income elasticity of demand** The responsiveness of demand for one good due to a change in income.

- **Substitutable good** A pair of goods that are alternatives to each other. As the price of one good goes up, the demand for the other rises.

- **Complementary good** A pair of goods consumed together. As the price of either goes up, the demand for both goods goes down.

- **Inferior good** A good whose demand decreases as income increases.

- **Normal good** A good whose demand increases as income increases.

- **Superior good** A normal good for which the percentage rise in consumption exceeds the percentage increases in income.

##### Utility {-}

- **Utility** The satisfaction gained from the consumption of a good.

- **Marginal utility** The extra satisfaction gained by consuming 1 extra unit of a good. $\partial U/\partial x_i$.

- **Law of diminishing marginal utility** The law which states that the increase in utility due to the consumption of an additional good will eventually decline. $\partial^2 U/\partial x_i^2<0$ for sufficiently large $x_i$.

- **Indifference curve** A curve indicating all combinations of two goods which give the same level of utility.

- **Indifference map** A diagram showing the graphs of a set of indifference curves. The further the curve is from the origin, the greater the level of utility.

- **Marginal rate of commodity substitution** The amount by which one input $x_2$ needs to increase to maintain a constant value of utility when the other input $x_1$ decreases by 1 unit. $$MRCS=\frac{\partial U/\partial x_1}{\partial U /\partial x_2}$$.

##### Production {-}

- **Marginal product of capital** The additional output produced by one unit increase in capital. $$MP_k=\frac{\partial Q}{\partial K}$$

- **Marginal product of labour** The additional ouput produced by one unit increase in labour. $$MP_L=\frac{\partial Q}{\partial L}$$

- **Isoquants** A curve indicating all combinations of two factors which give the same level of output.

- **Marginal rate of technical substitution** The amount by which capital needs to rise to maintain a constant level of output when labour decreases by 1 unit. $$MRTS=\frac{MP_L}{MP_K}$$

- **Homogeneous function** A function with the property that when all of the inputs are multiplied by a constant, $\lambda$, the output is multiplied by $\lambda^n$ where $n$ is the degree of homogeneity.


- **Euler's theorem** If each inputs is paid the value of its marginal product, the total cost of these inputs is equal to total output, provided there are constant returns to scale.

#### Unconstrained optimization  {-}

- **Maximum point** (of a function of two variables): A point on a surface which has the highest function value in comparison with other values in its neighborhood; at such a point the surface looks like the top of a mountain.

- **Minimum point** (of a function of two variables): A point on a surface which has the lowest function value in comparison with other values in its neighborhood; at such a point the surface looks like the bottom of a valley or bowl.

- **Saddle point**: A stationary point which is neither a maximum or minimum and at which the surface looks like the middle of a horse’s saddle.

- **Routine**

1. Solve the simultaneous equations to find the stationary points

$$
\begin{cases}
f_x(x,y)=0\\
f_y(x,y)=0
\end{cases}
$$

2. Classify the stationary points

- Minimum point

$$f_{xx}>0,f_{yy}>0, f_{xx}f_{yy}-f_{xy}^2>0$$

- Maximum point

$$f_{xx}<0,f_{yy}<0, f_{xx}f_{yy}-f_{xy}^2>0$$

- Saddle point

$$f_{xx}f_{yy}-f_{xy}^2<0$$

#### Constrained optimization {-}

- **Objective function**: A function that one seeks to optimize (usually) subject to constraints.

- **Method of substitution**: The method of solving constrained optimization problems whereby the constraint is used to eliminate one of the variables in the objective function.

##### Production {-}

- **Isocost curve**: A line showing all combinations of two factors which can be bought for a fixed cost.

- When the production is maximized, we have the ratio of marginal product to price is the same for all inputs.
$$\frac{MP_L}{P_L}=\frac{MP_K}{P_K}$$

##### Utility {-}

- When the utility is maximized, we have the ratio of marginal utility to price is the same for all goods consumed.
$$\frac{U_1}{P_1}=\frac{U_2}{P_2}$$

#### Lagrange multipliers {-}

- **Lagrangian** The function $f(x, y) + \lambda[M − \phi(x, y)]$, where $f(x, y)$ is the objective function and $\phi(x, y) = M$ is the constraint. The stationary point of this function is the solution of the associated constrained optimization problem.

- **Lagrange multiplier**: The number $\lambda$ which is used in the Lagrangian function. In economics this gives the approximate change in the optimal value of the objective function when the value of the constraint is increased by $1$ unit.


  
  







