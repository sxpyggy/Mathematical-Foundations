# Limits

Both concepts of differentiation and integration are based on the idea of limit.

## Introduction

**Problem 1** Suppose an object moves along the $x$-axis and its displacement $s$ in meters  at time $t$ in seconds is given by $$s(t)=t^2,~~~t\geq 0.$$
Find its velocity at time $t=2$.

*Solution* Velocity (or speed) is defined by 
$$\text{velocity}=\frac{\text{distance traveled}}{\text{time elapsed}}$$

| $n$ | Time interval | Velocity|
|:--:|:------------: |:-------:|
|$1$|$[2,2.5]$|$4.5$ m/s|
|$2$|$[2,2.25]$|$4.25$ m/s|
|...|...|...|
|$n$|$[2,2+\frac{1}{2^n}]$|$4+\frac{1}{2^n}$ m/s|

**Problem 2** Find the area of the region that lies under the curve $y=x^2$ and above the $x$-axis for $x$ between $0$ and $1$.

*Solution*
<div class="figure" style="text-align: center">
<img src="./plots/3/area.png" alt="Area under the curve" width="40%" />
<p class="caption">(\#fig:unnamed-chunk-1)Area under the curve</p>
</div>
\begin{equation}
\begin{aligned}
S_n&=\frac{1}{n}\cdot 0+\frac{1}{n}\cdot\left(\frac{1}{n}\right)^2+\frac{1}{n}\cdot\left(\frac{2}{n}\right)^2+\ldots+\frac{1}{n}\cdot\left(\frac{n-1}{n}\right)^2 \\
&=\frac{1}{3}-\frac{1}{2n}+\frac{1}{6n^2}
\end{aligned}
\end{equation}

## Limits of Sequences

**Definition**

- A sequence is a function whose domain is $\mathbb{Z}_+$.

- A sequence of real numbers is a sequence whose codomain is $
\mathbb{R}$.

**Illustration** Let $f:~ \mathbb{Z}_+\rightarrow \mathbb{R}$ be a sequence. For each positive integer $n$, the value $f(n)$ is called the $n$-th term of the sequence and is usually denoted by a small letter together with $n$ in the subscript, for example $a_n$. The sequence is also denoted by $(a_n)_{n=1}^\infty$.

**Definition** A sequency $(a_n)_{n=1}^\infty$ is said to be convergent if there exists a real number $L$ such that $a_n$ is arbitrarily close to $L$ if $n$ is sufficiently large. For simplicity, we will say $a_n$ is close to $L$ if $n$ is large.

**Remark** In the definition of convergent, it is clear that if $L$ exists, then it is unique. We say $L$ is the limit of $(a_n)_{n=1}^\infty$ and write $\underset{n\rightarrow\infty}{\lim}a_n=L$.

**Rules for limits of sequences**

1. $\underset{n\rightarrow\infty}{\lim}k=k$

2. $\underset{n\rightarrow\infty}{\lim}\frac{1}{n^p}=0$, where $p$ is a positive constant.

3. $\underset{n\rightarrow\infty}{\lim}\frac{1}{b^n}=0$, where $b$ is a positive constant greater than $1$.

4. $\underset{n\rightarrow\infty}{\lim}(a_n+b_n)=\underset{n\rightarrow\infty}{\lim}a_n+\underset{n\rightarrow\infty}{\lim}b_n$.

5. $\underset{n\rightarrow\infty}{\lim}a_nb_n=\underset{n\rightarrow\infty}{\lim}a_n\cdot\underset{n\rightarrow\infty}{\lim}b_n$.

6. $\underset{n\rightarrow\infty}{\lim}\frac{a_n}{b_n}=\frac{\underset{n\rightarrow\infty}{\lim}a_n}{\underset{n\rightarrow\infty}{\lim}b_n}$.

**Example** Find $\underset{n\rightarrow\infty}{\lim}\left(4+\frac{1}{2^n}\right)$, if it exists.

**Example** Find $\underset{n\rightarrow\infty}{\lim}\frac{2n^3-3n^2+n}{6n^3}$, if it exists.


**Example** Find $\underset{n\rightarrow\infty}{\lim}(1+2n)$, if it exists.

**Example** Find $\underset{n\rightarrow\infty}{\lim}\frac{n+1}{2n+1}$, if it exists.

## Limits of Functions at Infinity

**Definition** Let $f$ be a function such that $f(x)$ is defined for sufficiently large $x$. Suppose $L$ is a real number satisfying the following condition: $f(x)$ is arbitrarily close to $L$ if $x$ is sufficiently large. Then we say that $L$ is the limit of $f$ at infinity and write $\underset{n\rightarrow\infty}{\lim}f(x)=L$.

**Remark** 

- The condition $f(x)$ is defined for sufficiently large $x$ means that there is a real number $r$ such that $f(x)$ is defined for all $x>r$.

- $L$ is called the limit because it is unique if it exists.

- For simplicity we will say $f(x)$ is close to $L$ if $x$ is large.

**Rules for limits of functions at infinity**


1. $\underset{x\rightarrow\infty}{\lim}k=k$

2. $\underset{x\rightarrow\infty}{\lim}\frac{1}{x^p}=0$, where $p$ is a positive constant.

3. $\underset{x\rightarrow\infty}{\lim}\frac{1}{b^x}=0$, where $b$ is a positive constant greater than $1$.

4. $\underset{x\rightarrow\infty}{\lim}(f(x)\pm g(x))=\underset{x\rightarrow\infty}{\lim}f(x)\pm \underset{x\rightarrow\infty}{\lim}g(x)$.

5. $\underset{x\rightarrow\infty}{\lim}(f(x)\cdot g(x))=\underset{x\rightarrow\infty}{\lim}f(x)\cdot\underset{x\rightarrow\infty}{\lim}g(x)$.

6. $\underset{x\rightarrow\infty}{\lim}\frac{f(x)}{g(x)}=\frac{\underset{x\rightarrow\infty}{\lim}f(x)}{\underset{x\rightarrow\infty}{\lim}g(x)}$.

**Example** Find the following limits if they exist.

1. $\underset{x\rightarrow\infty}{\lim}\left(1-\frac{2}{x^3}\right)$

2. $\underset{x\rightarrow\infty}{\lim}\left(2^{-x}+3\right)$

3. $\underset{x\rightarrow\infty}{\lim}\frac{x^2+1}{3x^3-4x+5}$

4. $\underset{x\rightarrow\infty}{\lim}\frac{x^3+1}{3x^3-4x+5}$

**Leading terms rule** Let $f(x)=a_nx^n+\cdots+a_1x+a_0$ and $g(x)=b_mx^m+\cdots+b_1x+b_0$, where $a_n\neq 0$ and $b_m\neq 0$. Then we have 
$$\underset{x\rightarrow\infty}{\lim}\frac{f(x)}{g(x)}=\underset{x\rightarrow\infty}{\lim}\frac{a_nx^n}{b_mx^m}.$$

**Remark** 

- If $n=m$, the limit is $\frac{a_n}{b_n}$.

- If $n<m$, the limit is $0$.

- If $n>m$, the limit does not exist.

- The Leading terms rule can't be applied to limits of rational functions at a point: $\underset{x\rightarrow a}{\lim}\frac{f(x)}{g(x)}$, where $a\in\mathbb{R}$.

**Sandwich Theorem** Let $f,g$ and $h$ be functions such that $f(x)$, $g(x)$ and $h(x)$ are defined for sufficiently large $x$. Suppose that $f(x)\le g(x)\le h(x)$ if $x$ is sufficiently large and that both $\underset{x\rightarrow a}{\lim}f(x)$ and $\underset{x\rightarrow a}{\lim}h(x)$ exist and are equal (with common limit denoted by $L$). Then we have $\underset{x\rightarrow a}{\lim}g(x)=L$.

**Example** Find $\underset{x\rightarrow a}{\lim}\frac{\sin x}{x}$, if it exists.

**Infinite limits** Let $f$ be a function such that $f(x)$ is defined for sufficiently large $x$. Suppose that $f(x)$ is arbitrarily large if $x$ is sufficiently large. Then we write $\underset{x\rightarrow \infty}{\lim}f(x)=\infty$. Because $\infty$ is not a real number, $\underset{x\rightarrow \infty}{\lim}f(x)=\infty$ does not mean the limit exists. In fact, it indicates that the limit does not exist and explains why it does not exist.

**Example** $\underset{x\rightarrow \infty}{\lim}(1+x^2)=\infty$.  $\underset{x\rightarrow \infty}{\lim}(1-x^2)=-\infty$

**Limits at negative infinity** Similar to limits at infinity, we may consider limits at negative infinity provided that $f(x)$ is defined for $x$ sufficiently large negative.

**Example** $\underset{x\rightarrow -\infty}{\lim}\frac{1}{x}=0$. $\underset{x\rightarrow -\infty}{\lim}x^3=-\infty$. $\underset{x\rightarrow -\infty}{\lim}(1-x^3)=\infty$


## One-sided Limits

## Two-sided Limits

## Continunous Functions








