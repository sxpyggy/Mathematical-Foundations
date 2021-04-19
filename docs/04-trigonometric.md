# Trigonometric Functions

## Angles

**Definition** An angle is formed by rotating a ray about its endpoint. It is uniquely determined by the direction and magnitude of rotation.

- The initial position of the ray is called the *initial side*.

- The endpoint of the ray is called the *vertex*.

- The final position is called the *terminal side*.

- The direction of rotation may be counterclockwise or clockwise which will be considered to be positive or negative, respectively.

- Magnitudes of rotation are traditionally measured in degrees or in radians.

**Terminology** A circle with radius 1 is called a unit circle. The circle with radius 1 and center at the origin is called the unit circle.

**Definition** The angle determined by an arc of length 1 along the circumference of a unit circle is said to be of measure one radian.

- $360^\circ=2\pi$

- $d^\circ=d\times\frac{\pi}{180}$ radians

- $90^\circ=\frac{\pi}{2}, 60^\circ=\frac{\pi}{3}$

**Remark** It is more convenient to consider angles in radians and the unit radian is usually omitted.

## Trigonometric Functions

**Notation** Consider an angle $\theta$ in standard position. Let $P$ be the point of intersection of the terminal side and the unit circle. We define sine and cosine functions from $\mathbb{R}$ to $\mathbb{R}$:

- $\sin\theta=y-$coordinate of $P$

- $\cos\theta=x-$coordinate of $P$

**More trigonometric functions** The tangent, cotangent, secant and cosecant functions are defined as follows:

- $\tan x=\frac{\sin x}{\cos x}$

- $\cot x=\frac{\cos x}{\sin x}$

- $\sec x= \frac{1}{\cos x}$

- $\csc x=\frac{1}{\sin x}$

where the domains are 

- $\text{dom}(\tan)=\text{dom}(\sec)=\mathbb{R}\backslash\{\pm\frac{\pi}{2},\pm\frac{3\pi}{2},\ldots\}$

- $\text{dom}(\cot)=\text{dom}(\csc)=\mathbb{R}\backslash\{\pm\pi,\pm2\pi,\ldots\}$

**Properties**

1. The sine and cosine functions are periodic with period $2\pi$

2. The tangent function is periodic with period $\pi$.

3. The sine and tangent functions are odd functions and the cosine function is an even function.

4. The graphs of the sine and tangent functions are symmetric about the origin and the graph of the cosine function is symmetric about the $y$-axis.

5. The graph of the cosine function can be otained from that of the since function by moving it $\frac{\pi}{2}$ units to the left.

**CAST Rule**

**Sine, Cosine and Tangent of some special angles**

**Important identities** 

- $\sin^2 x + \cos^2 x=1$

- $1+\tan^2x=\sec^2x$

- $\sin(x+\frac{\pi}{2})=\cos x$

- $\cos(\pi-x)=-\cos x $

**Compound angle formulas**

- $\sin(A+B)=\sin A\cos B + \cos A\sin B$

- $\cos(A+B)=\cos A\cos B-\sin A\sin B$

**Continuity of sine and cosine** Both of them are continuous on $\mathbb{R}$.

**Important limits**

- $\underset{x\rightarrow0}{\lim}\frac{\sin x}{x}=1$

- $\underset{h\rightarrow0}{\lim}\frac{\cos h-1}{h}=0$

## Differentiation of Trigonometric Functions

**Derivative of sine** The sine function is differentiable on $\mathbb{R}$ and its derivative is the cosine function:
$$\frac{d}{dx}\sin x=\cos x$$

**Derivative of cosine** The cosine function is differentiable on $\mathbb{R}$ and its derivative is the negative of the sine function:
$$\frac{d}{dx}\cos x=-\sin x$$

**Derivative of tangent** The tangent function is differentiable on its domain and its derivative is the square of the secant function, that is,
$$\frac{d}{dx}\tan x=\sec^2 x,~~~x\neq\pm\frac{\pi}{2},\pm\frac{3\pi}{2},\ldots.$$


