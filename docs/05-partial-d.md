# Partial Differentiation

Note that *an italic title* indicates an application section which is less important than a theoretical one.

## Functions of several variables

**Dependent variable** A variable whose value is determined by that taken by the independent variable; in $z=f(x,y)$ the dependent variable is $z$.

**Independent variable** Variables whose values determine that of the dependent variable; in $z=f(x,y)$ the independent variable are $x,y$.

**Partial derivative** The derivative of a function of two or more variables with respect to one of these variables, the others being regarded as constant.

$$f_x=\frac{\partial z}{\partial x}, f_y=\frac{\partial z}{\partial y}$$

**Second-order partial derivative** The partial derivative of a first-order partial derivative. For example, $f_{xy}$ is the second-order partial derivative when $f$ is differentiated with respect to $y$ and then with respect to $x$.

$$f_{xy}=\frac{\partial\frac{\partial z}{x}}{\partial y}$$

**Differentials** Limiting values of incremental changes. In the limit the approximation $\Delta z \approx \partial z/\partial x\times\Delta x$ becomes $d z =\partial z/\partial x\times dx$ where $dz,dx$ are the differentials.

**Small increments formula** $\Delta z\approx \frac{\partial z}{\partial x}\Delta x + \frac{\partial z}{\partial y} \Delta y$

**Implicit differentiation** The process of obtaining $dy/dx$ where the function is not given explicitly as an expression for $y$ in terms of $x$.

## *Partial elasticity and marginal functions*

### *Elasticity* {-}

**Own price elasticity of demand** The responsiveness of demand for one good due to change in the price of itself.

**Cross-price elasticity of demand** The responsiveness of demand for one good due to change in the price of the alternative good.

**Income elasticity of demand** The responsiveness of demand for one good due to a change in income.

**Substitutable good** A pair of goods that are alternatives to each other. As the price of one good goes up, the demand for the other rises.

**Complementary good** A pair of goods consumed together. As the price of either goes up, the demand for both goods goes down.

**Inferior good** A good whose demand decreases as income increases.

**Normal good** A good whose demand increases as income increases.

**Superior good** A normal good for which the percentage rise in consumption exceeds the percentage increases in income.

### *Utility* {-}

**Utility** The satisfaction gained from the consumption of a good.

**Marginal utility** The extra satisfaction gained by consuming 1 extra unit of a good. $\partial U/\partial x_i$.

**Law of diminishing marginal utility** The law which states that the increase in utility due to the consumption of an additional good will eventually decline. $\partial^2 U/\partial x_i^2<0$ for sufficiently large $x_i$.

**Indifference curve** A curve indicating all combinations of two goods which give the same level of utility.

**Indifference map** A diagram showing the graphs of a set of indifference curves. The further the curve is from the origin, the greater the level of utility.

**Marginal rate of commodity substitution** The amount by which one input $x_2$ needs to increase to maintain a constant value of utility when the other input $x_1$ decreases by 1 unit. $MRCS=\frac{\partial U/\partial x_1}{\partial U /\partial x_2}$

### *Production* {-}

**Marginal product of capital** The additional output produced by one unit increase in capital. $MP_k=\frac{\partial Q}{\partial K}$

**Marginal product of labour** The additional ouput produced by one unit increase in labour. $MP_L=\frac{\partial Q}{\partial L}$

**Isoquants** A curve indicating all combinations of two factors which give the same level of output.

**Marginal rate of technical substitution** The amount by which capital needs to rise to maintain a constant level of output when labour decreases by 1 unit. $MRTS=\frac{MP_L}{MP_K}$

**Homogeneous function** A function with the property that when all of the inputs are multiplied by a constant, $\lambda$, the output is multiplied by $\lambda^n$ where $n$ is the degree of homogeneity.

**Euler's theorem** If each inputs is paid the value of its marginal product, the total cost of these inputs is equal to total output, provided there are constant returns to scale.

## *Comparative statics*

*This section is not examinable.*

## Unconstrained optimization

**Routine**

1. Solve the simultaneous equations to find the stationary points

$$
\begin{cases}
f_x(x,y)=0\\
f_y(x,y)=0
\end{cases}
$$

2. Classify the stationary points

   - Minimum point if  $f_{xx}>0,f_{yy}>0, f_{xx}f_{yy}-f_{xy}^2>0$

   - Maximum point if $f_{xx}<0,f_{yy}<0, f_{xx}f_{yy}-f_{xy}^2>0$

   - Saddle point if $f_{xx}f_{yy}-f_{xy}^2<0$

**Saddle point**: A stationary point which is neither a maximum or minimum and at which the surface looks like the middle of a horse’s saddle.

**Maximum point** (of a function of two variables): A point on a surface which has the highest function value in comparison with other values in its neighborhood; at such a point the surface looks like the top of a mountain.

**Minimum point** (of a function of two variables): A point on a surface which has the lowest function value in comparison with other values in its neighborhood; at such a point the surface looks like the bottom of a valley or bowl.

## Constrained optimization

**Objective function**: A function that one seeks to optimize (usually) subject to constraints.

**Method of substitution**: The method of solving constrained optimization problems whereby the constraint is used to eliminate one of the variables in the objective function.

### *Constrained optimization of economic functions* {-}

**Isocost curve**: A line showing all combinations of two factors which can be bought for a fixed cost.

When the **production is maximized**, we have the ratio of marginal product to price is the same for all inputs.
$\frac{MP_L}{P_L}=\frac{MP_K}{P_K}$

When the **utility is maximized**, we have the ratio of marginal utility to price is the same for all goods consumed.
$\frac{U_1}{P_1}=\frac{U_2}{P_2}$

## Lagrange multipliers

**Lagrangian** The function $f(x, y) + \lambda[M − \phi(x, y)]$, where $f(x, y)$ is the objective function and $\phi(x, y) = M$ is the constraint. The stationary point of this function is the solution of the associated constrained optimization problem.

**Lagrange multiplier**: The number $\lambda$ which is used in the Lagrangian function. In economics this gives the approximate change in the optimal value of the objective function when the value of the constraint is increased by $1$ unit.


  
  







