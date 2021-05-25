# Vectors and Geometry of Space

## Three-Dimensinal Coordinate Systems 

**Definition** The three coordinate axes determine the three coordinate planes. These three coordinate planes divide space into eight parts, called octants. 
The first octant is determined by the positive axes.
<img src="./plots/6/3d.png" width="30%" style="display: block; margin: auto;" />

**Coordinates** We represent the point $P$ by the ordered triple $(a,b,c)$. We call $a, b, c$ the coordinates of $P$.

**Projection** The point $P(a,b,c)$ determines a rectangular box. If we drop a perpendicular from $P$ to each coordinate plane. We get three projections of $P$ as $Q(a,b,0), R(0,b,c), S(a,0,c)$.
<img src="./plots/6/projection.png" width="30%"  style="display: block; margin: auto;" />

**Three dimensional rectangular coordinate system** The Cartesian product $\mathbb{R}\times\mathbb{R}\times\mathbb{R}=\{(x,y,z)|x,y,z\in\mathbb{R}\}$ is the set of all ordered triples of real numbers and is denoted by $R^3$.

**Surface** In three-dimensional analytica geometry, an equation in $x,y,z$ represents a surface in $R^3$.
<img src="./plots/6/plane.png" width="70%"  style="display: block; margin: auto;" />

<img src="./plots/6/curve.png" width="70%"  style="display: block; margin: auto;" />

**Distance** The distance $|P_1P_2|$ between the points $P_1(x_1,y_1,z_1)$ and $P_2(x_2,y_2,z_2)$ is 
$$|P_1P_2|=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}$$

**Equation of a sphere** An equation of a sphere with center $C(h,k,l)$ and radius $r$ is 
$$(x-h)^2+(y-k)^2+(z-l)^2=r^2.$$


<img src="./plots/6/sphere.png" width="30%"  style="display: block; margin: auto;" />

## Vectors

**Definition** A quantity (such as displacement or velocity or force) with both magnitude and direction. 

**Example** For instance, suppose a particle moves along a line segment from point $A$ to point $B$. The corresponding displacement vector $\mathbf{v}$ has initial point $A$ (the tail) and terminal point $B$ (the tip), and we indicate this by writing $\mathbf{v}=\overset{\longrightarrow}{AB}$. Notice that if a vector $\mathbf{u}$ has the same length and the same direction even though it is in a different position. We say $\mathbf{u}$ and $\mathbf{v}$ are equivalent and we write $\mathbf{u}=\mathbf{v}$.
<img src="./plots/6/vector.png" width="30%"  style="display: block; margin: auto;" />

**Vector addition** If $\mathbf{u}$ and $\mathbf{v}$ are vectors positioned so the initial point of $\mathbf{v}$ is at the terminal point of $\mathbf{u}$, then the sum $\mathbf{u}+\mathbf{v}$  is the vector from the initial point of $\mathbf{u}$  to the terminal point of $\mathbf{v}$.
<img src="./plots/6/addition.png" width="70%"  style="display: block; margin: auto;" />

**Scalar multiplication** If $c$ is a scalar and $\mathbf{v}$ is a vector, then the scalar multiple $c\mathbf{v}$ is the vector whose length is $|c|$ times the length of $\mathbf{v}$ and whose direction is the same as $\mathbf{v}$ if $c>0$ and is opposite to $\mathbf{v}$ if $c<0$.
<img src="./plots/6/scalar.png" width="70%"  style="display: block; margin: auto;" />

**Components** 
If we place the initial point of a vector $\boldsymbol{a}$ at the origin of a rectangle coordinate system, then the terminal point has coordinates $(a_1,a_2)$. These coordinates are called the components of $\boldsymbol{a}$. We write $$\boldsymbol{a}=\langle a_1, a_2 \rangle.$$

**Representation** Given the points $A(x_1,y_1,z_1)$ and $B(x_2,y_2,z_2)$, the vector $\boldsymbol{a}$ with **representation** $\overset{\longrightarrow}{AB}$ is $\boldsymbol{a}=\langle x_2-x_1,y_2-y_1, z_2-z_1 \rangle,$

**Position vector** The vector $\boldsymbol{a}=\overset{\longrightarrow}{OP}=\langle a_1, a_2, a_3 \rangle$ is the position vector of the point $P( a_1, a_2, a_3)$

**Example** Find the vector represented by the directed line segment with initial point $A(2,-3,4)$ and terminal point $B(-2,1,1)$.

**Magnitude** The length of the vector $\boldsymbol{a}=\langle a_1,a_2,a_3 \rangle$ is the length of any of its representations and is denoted by the symbol $|\boldsymbol{a}|$ or $||\boldsymbol{a}||$:
$$|\boldsymbol{a}|=\sqrt{a_1^2+a_2^2+a_3^2}$$

**Operations on algebraic vectors** If $\boldsymbol{a}=\langle a_1,a_2 \rangle$ and $\boldsymbol{b}=\langle b_1,b_2 \rangle$, then 
$$\boldsymbol{a}+\boldsymbol{b}=\langle a_1+b_1, a_2+b_2 \rangle$$
$$\boldsymbol{a}-\boldsymbol{b}=\langle a_1-b_1, a_2-b_2 \rangle$$
$$c\boldsymbol{a}=\langle ca_1, ca_2 \rangle$$

<img src="./plots/6/component.png" width="40%"  style="display: block; margin: auto;" />

**Example** If $\boldsymbol{a}=\langle 4,0,3\rangle$ and $\boldsymbol{b}=\langle -2,1,5\rangle$, find $|\boldsymbol{a}|$ and the vectors $\boldsymbol{a}+\boldsymbol{b},2\boldsymbol{a}+5\boldsymbol{b}$.  

**Properties of Vectors** Consider the set of all $n$-dimensional vectors $V_n$, we have the following properties for any $\boldsymbol{a},\boldsymbol{b},\boldsymbol{c}\in V_n$ and $c,d\in\mathbb{R}$:

1. $\boldsymbol{a} + \boldsymbol{b}= \boldsymbol{b} + \boldsymbol{a}$

2. $\boldsymbol{a} + (\boldsymbol{b} +  \boldsymbol{c} )= (\boldsymbol{a} +\boldsymbol{b}) + \boldsymbol{c}$

3. $\boldsymbol{a} + \boldsymbol{0} = \boldsymbol{a} $

4. $\boldsymbol{a} - \boldsymbol{a} = \boldsymbol{0} $

5. $c(\boldsymbol{a} + \boldsymbol{b}) = c\boldsymbol{a} + c\boldsymbol{b}$

6. $(c+d)\boldsymbol{a}=c\boldsymbol{a}+d\boldsymbol{a}$

7. $(cd)\boldsymbol{a}=c(d\boldsymbol{a})$

8. $1\boldsymbol{a}=\boldsymbol{a}$


**Standard basis vectors** $$\boldsymbol{i}=\langle 1, 0, 0\rangle, \boldsymbol{j}=\langle 0,1,0\rangle, \boldsymbol{k}=\langle 0, 0, 1\rangle$$

**Example** If $\boldsymbol{a}=\langle a_1,a_2,a_3\rangle$, then we have $\boldsymbol{a}=a_1\boldsymbol{i}+a_2\boldsymbol{j}+a_3\boldsymbol{k}$.

**Example** If $\boldsymbol{a}=\boldsymbol{i}+2\boldsymbol{j}-3\boldsymbol{k}$ and $\boldsymbol{b}=4\boldsymbol{i}+7\boldsymbol{k}$, express the vector $2\boldsymbol{a}+3\boldsymbol{b}$ in terms of the three standard basis vectors.

**Unit vector** In general, if $\boldsymbol{a}\neq\boldsymbol{0}$, then the unit vector that has the same direction as $\boldsymbol{a}$ is $$\boldsymbol{u}=\frac{\boldsymbol{a}}{|\boldsymbol{a}|}$$

**Example** Find the unit vector in the direction of the vector $2\boldsymbol{i}-\boldsymbol{j}-2\boldsymbol{k}$.


## Dot Product

## Cross Product

## Equations of Lines and Planes

## Directional Derivatives and  Gradient Vector

## More on Lagrange Multipliers





