---
output: html_document
editor_options: 
  chunk_output_type: console
---
# (PART) 💡 SOLUTIONS {-}

**[✍️ Final Exam](#final)**




# Chapter 8 {- #s8}

## Exercise 8.1* {- #e8.1}

### Question 3 {- #eq8.1.3}

(a) The feasible region has three corners: $(0,5), (2,4), (4,0)$, and the values of $2x + 3y$ are $15,16, 8$. Thus the maximum is $16$, which occurs at $(2,4)$. 

<img src="4-6-solutions_files/figure-html/unnamed-chunk-2-1.png" width="672"  />

(b)
The feasible region has three corners: $(0,3), (2,0), (1,5)$, and the values of $-8x + 4y$ are $12,-16, 12$. Thus the maximum is $12$, which occurs at any point on the line $y=2x+3,0<x<1$.

<img src="4-6-solutions_files/figure-html/unnamed-chunk-3-1.png" width="672"  />

### Question 7 {- #eq8.1.7}

(a)

    (i) The feasible region has three corners: $(4/3,40/3), (6,4),(12,0)$.

    (ii) There corners are $(4/3,40/3),(6,4),(12,0)$, and the values of $x + y$ are $44/3,10, 12$, respectively. The optimal point is $(6,4)$.

    (iii) $$ x \geq 0 $$ is redundant since it is not a bounary line of the feasible region.

(b) 

    (i) There is no solution since $x+y$ increases without bound as the lines $x+y = c$ sweep across the region to the right.

    (ii) The feasible region has three corners: $(4/3,40/3), (6,4),(12,0)$, and the values of  $2x + y$ are $16,16,24$. Thus the minimum is $16$, which occurs at any point on the line   $y=-2x+16, 4/3<x<6$.

(c) To get the minimum at $(12,0)$, the objective function must be less steep than the slope $-2/3$. So $-a/2 \geq-2/3$ and then $a\le 4/3$.

<img src="4-6-solutions_files/figure-html/unnamed-chunk-4-1.png" width="672"  />

# Chapter 6 {- #s6}

## Exercise 6.1* {- #e6.1}

### Question 1 {- #eq6.1.1}

(a)$$ \int x(x^5-2) {\rm d}x = \int (x^6-2x) {\rm d}x\\=\frac{1}{7}x^7-x^2+c $$
(b)$$ \int x^{10}-3\sqrt{x}+e^{-x} {\rm d}x = \frac{1}{11}x^{11}-2x^{\frac{3}{2}}-e^{-x}+c $$
(c)$$ \int x^3-\frac{5}{x^6}+\frac{2}{x}-4e^{-4x} {\rm d}x = \frac{1}{4}x^4+\frac{1}{x^5}+2\lnx+e^{-4x}+c $$

### Question 10 {- #eq6.1.10}

$$ N = \int 10e^{-0.1t} {\rm d}t = -100e^{-0.1t}+c $$
The employee is unable to produce any goods at the beginning of her shift, thus when t = 0, N=0. Then we can get $$ N = 0 \\=-100e^{-0.1t}+c\\=-100+c $$
$$ c = 100$$
$$ N = -100e^{-0.1t}+100 $$
When t=8, $$ N = -100e^{-0.1t}+100\\
               = -100e^{-0.8}+100\\
               \approx 55$$
In the long run, t tends to infinity, 
$$ N = -100e^{-0.1t}+100\\
     = 100$$

### Question 12 {- #eq6.1.12}

$$ TR = \int MR {\rm d}Q\\
      = \int (240-0.6Q^2) {\rm d}Q\\
      = 240Q-0.2Q^3+c_1$$
As TR=PQ,when Q=0, TR=0.
Thus $$ TR = 0 =0+c_1$$
we get $$ c_1=0 $$
$$ TR = 240Q-0.2Q^3 $$
$$ TC = \int MC {\rm d}Q\\
      = \int (150+0.3Q^2) {\rm d}Q\\
      = 150Q+0.1Q^3+c_2$$

As the fixed costs are 50, which means when t=0, TC=50, then we can get 
$$ TC = 50\\
      = 0+c_2$$
$$c_2 = 50 $$
$$ TC = 150Q+0.1Q^3+50$$
$$ \pi = TR-TC\\
       = (240Q-0.2Q^3)-(150Q+0.1Q^3+50)\\
       = -0.3Q^3+90Q-50$$
$$ \frac{\partial \pi}{\partial Q} = -0.9Q^2+90 = 0 $$
As Q>0,we get $$ Q = 10 $$
$$ \frac{\partial^2 \pi}{\partial Q^2} = -0.18Q = -1.8<0 $$
$$ \pi_{max} = -0.3Q^3+90Q-50 = 550  $$
Thus when Q=10, there is the maximum profit which is 550.

### Question 13 {- #eq6.1.13}

(a)$$ \int (ax+b)^n {\rm d}x = \frac{(ax+b)^{n+1}}{(n+1)a}+c $$
(b)$$ \int e^{ax+b} {\rm d}x = \frac{e^{ax+b}}{a}+c $$
(c)$$ \int \frac{1}{ax+b} {\rm d}x = \frac{\ln(ax+b)}{a}+c $$

## Exercise 6.2* {- #e6.2}

### Question 1 {- #eq6.2.1}

(a)$$ \int_{-1}^{2} 5x^2-4x+6 {\rm d}x \\
    = [\frac{5x^3}{3}-2x^2+6x]_{-1}^{2}\\
    = [\frac{5\times2^3}{3}-2\times2^2+6\times2] - [\frac{5\times(-1)^3}{3}-2\times(-1)^2+6\times(-1)]\\
    = 27$$
(b)$$ \int_{2}^{10} \frac{1}{(2x+5)\sqrt{2x+5}} {\rm d}x \\
    = \int_{2}^{10} (2x+5)^{-\frac{3}{2}} {\rm d}x \\
    = [-(2x+5)^{-\frac{1}{2}}]_{2}^{10}\\
    = [-(2\times10+5)^{-\frac{1}{2}}] - [-(2\times2+5)^{-\frac{1}{2}}]\\
    = \frac{2}{15}$$

### Question 4 {- #eq6.2.4}

$$ \begin{cases} P=Q+50\\ P=\frac{4000}{Q+20} \end{cases}$$
$$ Q+50 = \frac{4000}{Q+20} $$
As Q > 0 , we get Q = 30.
$$ P = Q+50=80 $$
$$ CS = \int_{0}^{30} \frac{4000}{(Q+20)} {\rm d}Q - PQ\\
      = [4000\ln(Q+20)]_0^{30}-80\times30 \\
      = 4000\ln50-4000\ln20-2400\\
      = 4000\ln(\frac{5}{2})-2400\\
      \approx 1265.16 $$
$$ PS = PQ - \int_{0}^{30} Q+50 {\rm d}Q \\
      = 80\times30 - [\frac{Q^2}{2}+50Q]_0^{30} \\
      = 2400 - 1950\\
      = 450 $$
      
### Question 6 {- #eq6.2.6}

(a)$$ \int_{2}^{5} 100e^{0.1t} {\rm d}t \\
    = [1000e^{0.1t}]_2^5\\
    = 1000e^{0.5}-1000e^{0.2}\\
    \approx 427.32 $$

(b)$$ \int_{0}^{T} 100e^{0.1t} {\rm d}t \\
    = [1000e^{0.1t}]_0^T\\
    = 1000e^{0.1T}-1000\\
    = 100000 $$
we get $$ T \approx 46.15 $$
As T is a integer, the capital stock exceeds the $100000 level during the 47th year.

### Question 12 {- #eq6.2.12}

$$ \pi =  f(Q) \\
       = TR -TC\\
       = 100(1-e^{-0.1Q}) - (0.1Q^2+2Q+1)\\
       = -100e^{-0.1Q} -0.1Q^2-2Q+99$$
As a = 3 ,b=8,we get:
$$ \frac{1}{b-a}\int_{a}^{b} f(Q) {\rm d}Q \\ 
  =\frac{1}{8-3}\int_{3}^{8} -100e^{-0.1Q} -0.1Q^2-2Q+99 {\rm d}Q \\ 
  =\frac{1}{5}\times[1000e^{-0.1Q} -\frac{0.1}{3}Q^3-Q^2+99Q]_3^8 \\
  =\frac{1}{5}\times[(1000e^{-0.8} -\frac{0.1}{3}\times8^3-8^2+99\times8)-(1000e^{-0.3} -\frac{0.1}{3}\times3^3-3^2+99\times3)]\\
  \approx 26.5$$

# Chapter 5 {- #s5}

## Exercise 5.1* {- #e5.1}

### Question 2 {- #eq5.1.2}

$$ f(w,x,y)=5w^{0.34}x^{0.25}y^{0.41}  $$
$$ f(kw,kx,ky)=5(kw)^{0.34}(kx)^{0.25}(ky)^{0.41}\\
              =5kw^{0.34}x^{0.25}y^{0.41}\\
              =kf(w,x,y)$$

### Question 4 {- #eq5.1.4}

$$ \frac{\partial z}{\partial x} = 2xy^3-10y = 78$$
$$ \frac{\partial z}{\partial y} = 3x^2y^2-10x+2y = 94 $$
$$ dz = \frac{\partial z}{\partial x}dx+\frac{\partial z}{\partial y}dy \\
= 78\times0.2+94\times(-0.1)\\
= 6.2$$
Thus the change in z is 6.2.

### Question 12 {- #eq5.1.12}

(a)$$ f_x = 3x^2y+4y^2\\
      f_y = x^3+8xy$$
$$\frac{dy}{dx}=-\frac{f_x}{f_y} \\
               =-\frac{3x^2y+4y^2}{x^3+8xy}$$
(b)$$ f_x = 4x^{-\frac{2}{3}}y^{\frac{1}{4}}+1\\
      f_y = 3x^{\frac{1}{3}}y^{-\frac{3}{4}}$$
$$\frac{dy}{dx}=-\frac{f_x}{f_y} \\
               =-\frac{4x^{-\frac{2}{3}}y^{\frac{1}{4}}+1}{3x^{\frac{1}{3}}y^{-\frac{3}{4}}}$$              
(c)$$ f_x = y^2e^{xy}\\
      f_y = (1+xy)e^{xy}$$
$$\frac{dy}{dx}=-\frac{f_x}{f_y} \\
               =-\frac{y^2e^{xy}}{(1+xy)e^{xy}}\\
               =-\frac{y^2}{1+xy}$$               
(d)$$ f_x = \frac{2x(x+y)-(x^2+y^2)}{(x+y)^2} = \frac{x^2+2xy-y^2}{(x+y)^2} \\
      f_y = \frac{2y(x+y)-(x^2+y^2)}{(x+y)^2}= \frac{y^2+2xy-x^2}{(x+y)^2} $$
$$\frac{dy}{dx}=-\frac{f_x}{f_y} \\
               =-\frac{\frac{x^2+2xy-y^2}{(x+y)^2}}{\frac{y^2+2xy-x^2}{(x+y)^2}}\\
               =\frac{x^2+2xy-y^2}{x^2-2xy-y^2}$$

## Exercise 5.2* {- #e5.2}

### Question 4 {- #eq5.2.4}

$$ Q(\lambda K,\lambda L) = A(\lambda K)^\alpha (\lambda L)^\beta = A\lambda^{\alpha+\beta}K^\alpha L^\beta = \lambda^{\alpha+\beta}Q  $$
Thus it is a homogeneous of degree$$\alpha + \beta $$

(a)$$ \frac{\partial Q}{\partial K} = \alpha AK^{\alpha -1}L^{\beta} $$
$$ \frac{\partial Q}{\partial L} = \beta AK^{\alpha}L^{\beta-1} $$
$$K \frac{\partial Q}{\partial K} + L \frac{\partial Q}{\partial L} =\alpha AK^{\alpha}L^{\beta} + \beta AK^{\alpha}L^{\beta}= (\alpha + \beta)Q $$
(b)$$ \frac{\partial^2 Q}{\partial K^2} = \alpha(\alpha -1) AK^{\alpha - 2}L^{\beta} $$
$$ \frac{\partial^2 Q}{\partial K \partial L} = \alpha \beta AK^{\alpha - 1}L^{\beta-1} $$
$$ \frac{\partial^2 Q}{\partial L^2} = \beta(\beta-1) AK^{\alpha}L^{\beta-2} $$
$$K^2 \frac{\partial^2 Q}{\partial K^2} + 2KL\frac{\partial^2 Q}{\partial K \partial L}+ L^2 \frac{\partial^2 Q}{\partial L^2} =\alpha(\alpha -1) AK^{\alpha}L^{\beta} + 2\alpha \beta AK^{\alpha}L^{\beta}+\beta(\beta-1) AK^{\alpha}L^{\beta} \\
=(\alpha + \beta)(\alpha + \beta -1)Q $$

### Question 5 {- #eq5.1.5}

(a)$$ \frac{\partial U}{\partial x_1}=0.7Ax_1^{-0.3}x_2^{0.5} > 0  $$
It is greater than 0 as it is the product of four positive numbers.Utility increases when more units of good 1 are consumed.

(b)$$ \frac{\partial^2 U}{\partial x_1 \partial x_2}=0.35Ax_1^{-0.3}x_2^{-0.5}>0 $$
It is greater than 0 as it is the product of four positive numbers.Consuming more of one good increases the marginal utility of the other good.

(c)$$ \frac{\partial^2 U}{\partial x_1^2}=-0.21Ax_1^{-1.3}x_2^{0.5}<0 $$
It is less than 0 as it is the product of three positive numbers and one negative number.Consuming more of good 1 decreases the marginal utility of good 1.There is diminishing marginal utility of good 1.

### Question 6 {- #eq5.1.6}

$$ 700=Q=5L+7K $$
The graph is showed in the following.
<img src="4-6-solutions_files/figure-html/unnamed-chunk-5-1.png" width="672"  />
From the graph, we can get the slope is$$ -\frac{100}{140}=-\frac{5}{7} $$
Thus the $$ MRTS = \frac{5}{7} $$

$$ \frac{\partial Q}{\partial L } = 5 \\
    \frac{\partial Q}{\partial K } = 7 $$
$$ MRTS = \frac{\frac{\partial Q}{\partial L }}{\frac{\partial Q}{\partial K }}= \frac{5}{7}  $$

### Question 9 {- #eq5.1.9}

(a)The alternative good  is complementary as the coefficient of the price of an alternative good is negative.

(b)(i)
$$ E_P = \frac{P}{Q} \times \frac{\partial Q}{\partial P}\\
       = \frac{50}{5000} \times (-b)\\
       = \frac{-b}{100}$$

(ii)$$ E_{CP} = \frac{P_A}{Q} \times \frac{\partial Q}{\partial P_A}\\
       = \frac{30}{5000} \times (-c)\\
       = \frac{-3c}{500}$$
(iii)
$$ E_Y = \frac{Y}{Q} \times \frac{\partial Q}{\partial Y}\\
       = \frac{1000}{5000} \times (d)\\
       = \frac{d}{5}$$
(c)$$  E_{CP} =  \frac{-3c}{500} = -0.012 $$
we get c=2.
$$E_Y = \frac{d}{5} = \frac{2%}{10%} = \frac{1}{5} $$
we get d=1.

As the price elasticity of demand is always less than 0, thus $$ E_{CP} = \frac{-b}{100} = -\frac{1}{4} \times \frac{1}{5}  $$
we get b=5.
$$ Q = a-bP-cP_A+dY $$
$$5000=a-5\times 50 - 2\times 30+1 \times 1000$$
we get a=4310.

### Question 11 {- #eq5.1.11}

(a)$$ \frac{\partial U}{\partial x_1}=6(2x_1+3x_2)^2 $$
$$ \frac{\partial U}{\partial x_2}=9(2x_1+3x_2)^2 $$
$$ MRCS = \frac{\frac{\partial U}{\partial x_1}}{\frac{\partial U}{\partial x_2}} \\
  = \frac{6(2x_1+3x_2)^2}{9(2x_1+3x_2)^2}\\
  = \frac{2}{3} $$
As the MRCS is a constant , the indifference map consists of straight lines.
(b)$$ \frac{\partial U}{\partial x_1}=15x_1^2x_2 $$
$$ \frac{\partial U}{\partial x_2}=5x_1^3 $$
$$ MRCS = \frac{\frac{\partial U}{\partial x_1}}{\frac{\partial U}{\partial x_2}} \\
  = \frac{15x_1^2x_2}{5x_1^3}\\
  = \frac{3x_2}{x_1} $$
As the MRCS decreases when x1 increases, the indifference curve is convex.

(c)$$ \frac{\partial U}{\partial x_1}=x_1^{-0.5} $$
$$ \frac{\partial U}{\partial x_2}=3x_2^{-0.5} $$
$$ MRCS = \frac{\frac{\partial U}{\partial x_1}}{\frac{\partial U}{\partial x_2}} \\
  = \frac{x_1^{-0.5}}{3x_2^{-0.5}}\\
  = \frac{\sqrt{x_2}}{3\sqrt{x_1}} $$
As the MRCS decreases when x1 increases, the indifference curve is convex.


## Exercise 5.4* {- #e5.4}

### Question 2 {- #eq5.4.2}

$$ \pi = TR - TC\\
          = PQ - TC\\
          = 8(2L^{\frac{1}{2}}+3K^{\frac{1}{2}}) - (2L+K)\\
          = 16L^{\frac{1}{2}}+24K^{\frac{1}{2}}-2L-K$$

$$ \frac{\partial \pi}{\partial L} = 8L^{-\frac{1}{2}}-2 = 0 $$
We get L=16.
$$ \frac{\partial^2 \pi}{\partial L^2} = -4L^{-\frac{3}{2}} = \frac{-1}{16} < 0 $$
$$ \frac{\partial \pi}{\partial K} = 12K^{-\frac{1}{2}}-1 $$
We get K=144.
$$ \frac{\partial^2 \pi}{\partial K^2} = -6K^{-\frac{3}{2}} = \frac{-1}{288} < 0 $$
$$ \pi_{max} = 16L^{\frac{1}{2}}+24K^{\frac{1}{2}}-2L-K = 176$$
Thus when L=16 and K=144, there is the maximum profit which is 176.

### Question 4 {- #eq5.4.4}

$$ \pi = TR - TC\\
          = P_1Q_1+P_2Q_2 - TC\\
          = (50-5Q_1)Q_1+(30-4Q_2)Q_2-(10+10(Q_1+Q_2))\\
          = -5Q_1^2+40Q_1-4Q_2^2+20Q_2-10$$
$$ \frac{\partial \pi}{\partial Q_1} = -10Q_1+40 = 0 $$
We get $$ Q_1 = 4 $$.
$$ \frac{\partial^2 \pi}{\partial Q_1^2} = -10 < 0 $$

$$ \frac{\partial \pi}{\partial Q_2} = -8Q_2+20 = 0 $$
We get $$ Q_2 = 2.5 $$.
$$ \frac{\partial^2 \pi}{\partial Q_2^2} = -8 < 0 $$
$$ \pi = -5Q_1^2+40Q_1-4Q_2^2+20Q_2-10 = 95$$
$$P_1=50-5Q_1=30\\
P_2=30-4Q_2=20$$
Thus when $$P_1=30, P_2=20$$, there is a maximum profit which is 95.

### Question 7 {- #eq5.4.7}

As $$c_iQ_i^2$$ is the total cost of producing good i, $$ c_i >0$$ 

$$ \pi(Q_1,Q_2) = TR - TC\\
          = PQ - TC\\
          = (p_1Q_1+p_2Q_2)-(c_1Q_1^2+c_2Q_2^2)\\
          = p_1Q_1+p_2Q_2-c_1Q_1^2-c_2Q_2^2$$

$$ \frac{\partial \pi}{\partial Q_1} = p_1-2c_1Q_1 = 0 $$
We get $$ Q_1 = \frac{p_1}{2c_1} $$
$$ \frac{\partial^2 \pi}{\partial Q_1^2} = -2c_1 < 0 $$
$$ \frac{\partial \pi}{\partial Q_2} = p_2-2c_2Q_2 = 0 $$
We get $$ Q_2 = \frac{p_2}{2c_2} $$
$$ \frac{\partial^2 \pi}{\partial Q_2^2} = -2c_2 < 0 $$

$$ \pi_{max} = p_1Q_1+p_2Q_2-c_1Q_1^2-c_2Q_2^2\\
       = \frac{p_1^2}{2c_1}+\frac{p_2^2}{2c_2}-c_1(\frac{p_1}{2c_1})^2-c_2(\frac{p_2}{2c_2})^2\\
       = \frac{p_1^2}{4c_1}+\frac{p_2^2}{4c_2}$$
Thus when $$Q_1 = \frac{p_1}{2c_1},Q_2 = \frac{p_2}{2c_2}$$, there is a maximum profit which is $$ \pi_{max} = \frac{p_1^2}{4c_1}+\frac{p_2^2}{4c_2}$$


## Exercise 5.5* {- #e5.5}

### Question 3 {- #eq5.5.3}

$$ 2L+K=99$$
$$ K = 99-2L $$
$$ \pi = TR - TC\\
          = PQ - TC\\
          = 8(2L^{\frac{1}{2}}+3K^{\frac{1}{2}}) - (2L+K)\\
          = 16L^{\frac{1}{2}}+24(99-2L)^{\frac{1}{2}}-99$$
$$ \frac{\partial \pi}{\partial L} = 8L^{-\frac{1}{2}}-24(99-2L)^{-\frac{1}{2}} = 0 $$
We get L=9.

$$ \frac{\partial^2 \pi}{\partial L^2} = -4L^{-\frac{3}{2}}-24(99-2L)^{-\frac{3}{2}} =-\frac{44}{243}< 0 $$
$$ K = 99-2L =81 $$
$$ \pi = 16L^{\frac{1}{2}}+24(99-2L)^{\frac{1}{2}}-99=165$$
Thus when L=9 and K=81,there is the maximum profit which is 165.

### Question 5 {- #eq5.5.5}

(a)$$ 2x_1+4x_2=300$$
(b)As$$ 2x_1+4x_2=300$$
$$x_1 = 150-2x_2 $$

$$ U = x_1\sqrt{x_2}\\
     = (150-2x_2)\sqrt{x_2}$$
$$ U'= -2\sqrt{x_2} + (150-2x_2)\frac{1}{2\sqrt{x_2}} \\
     = -2\sqrt{x_2} + \frac{75-x_2}{\sqrt{x_2}} =0$$
     
we get $$ x_2 = 25 $$

$$ U''= -\frac{1}{\sqrt{x_2}} + \frac{-\sqrt{x_2}-(75-x_2)\frac{1}{2\sqrt{x_2}})}{x_2}\\
 = -0.6 <0 $$
$$ x_1 =150-2x_2 = 100 $$
$$ U = (150-2x_2)\sqrt{x_2} = 500$$
Thus when $$ x_1=100,x_2=25 $$, there is a maximum value that is 500.

(c)

<img src="4-6-solutions_files/figure-html/unnamed-chunk-6-1.png" width="672"  />

As you can see, the maximum point of the constrained problem occurs at a point where the budgetary constraint is a tangent to an indifference curve.

### Question 7 {- #eq5.5.7}

(a)$$U(x_1,x_2) = \sqrt{x_1}+x_2 \\
                = \sqrt{x_1}+b-ax_1$$
$$ U' = \frac{1}{2\sqrt{x_1}}-a = 0$$
we get $$ x_1 = \frac{1}{4a^2} $$
As a is positive constant,
$$ U'' = -\frac{1}{4}x_1^{-\frac{3}{2}} < 0$$
$$ U(x_1,x_2)_{max} = \sqrt{x_1}+b-ax_1\\
                    = \frac{1}{2a}+b-\frac{1}{4a}\\
                    = \frac{4ab+1}{4a}$$
Thus when $$ x_1 = \frac{1}{4a^2} $$, there is the maximum value of U  that is $$U^* = \frac{4ab+1}{4a}$$                    
(b)$$ \frac{\partial U^*}{\partial a} = -\frac{1}{4a^2} < 0 $$ 
Thus an increase in a causes a decrease in optiomal utility. 
$$ \frac{\partial U^*}{\partial b} = 1 >0 $$                      
Thus one unit increase in b causes one unit increase in optiomal utility.                     
                    

## Exercise 5.6* {- #e5.6}

### Question 1 {- #eq5.6.1}

(a)$$ g(x,y,\lambda)=x+2y+\lambda(M-x-y^2) $$
$$ \frac{\partial g(x,y,\lambda)}{\partial x} = 1-\lambda=0$$
we get $$\lambda = 1 $$
$$ \frac{\partial g(x,y,\lambda)}{\partial y} = 2-2\lambda y=0$$
we get $$y = 1 $$
$$ \frac{\partial g(x,y,\lambda)}{\partial \lambda} = M-x-y^2=0$$
we get $$x=M-1 $$
Then$$ z= x+2y \\= M-1+2 \\= M+1 $$

(b)$$ \frac{\partial z}{\partial M} = 1$$
If M increases by 1 unit, z increases by 1 unit, which is the value of $$ \lambda $$

### Question 4 {- #eq5.6.4}

As 1 bicycle has 1 frame and 2 wheels, we get
$$ y =2x $$
$$ \pi = 5x^2-10xy+3y^2+240x\\
       = 5x^2-10x(2x)+3(2x)^2+240x\\
       = -3x^2+240x$$
$$ \frac{\partial \pi}{\partial x} = -6x+240 =0 $$
$$ x=40 $$
$$ \frac{\partial^2 \pi}{\partial x^2} = -6<0 $$
Thus we can get the maximum profit when x = 40.
$$ y=2x=80 $$
$$ \pi_{max} = -3x^2+240x = 4800 $$

### Question 7 {- #eq5.6.7}

As the agency has $10000 to spend in total, we can get $$ x+y = 10000 $$
$$ \pi=0.15M+\lambda(10000-x-y)\\
      =0.15(\frac{100000x}{50+x}+\frac{40000y}{30+y})+\lambda(10000-x-y)\\
      =\frac{15000x}{50+x}+\frac{6000y}{30+y}+\lambda(10000-x-y) $$
$$ \frac{\partial \pi}{\partial x} = \frac{15000(50+x)-15000x}{(50+x)^2}-\lambda\\
= \frac{15000\times50}{(50+x)^2}-\lambda\\
= 0 $$
$$ \frac{\partial \pi}{\partial y} = \frac{6000(30+y)-6000y}{(30+y)^2}-\lambda\\
= \frac{6000\times30}{(30+y)^2}-\lambda\\
= 0 $$
$$ \frac{\partial \pi}{\partial \lambda} = 10000-x-y = 0 $$
Then we get $$ x  \approx 6715.56\\
               y  \approx 3284.44$$
Thus when x=6715.56 and y=3284.44,we can get the maximum of the agency's net income.

### Question 9 {- #eq5.6.9}

$$ f(x,y) = 400x+800y $$
$$ g(x,y,\lambda)=400x+800y+\lambda(67-x^2-y^2+4x+6y) $$
$$ \frac{\partial g(x,y,\lambda)}{\partial x} = 400-2\lambda x+4\lambda=0$$
$$ \frac{\partial g(x,y,\lambda)}{\partial y} = 800-2\lambda y +6\lambda=0$$
$$ \frac{\partial g(x,y,\lambda)}{\partial \lambda} =67-x^2-y^2+4x+6y=0$$
As x>0, y>0, then we can get $$ x = 6\\
                   y = 11\\
                   \lambda = 50$$
Thus the firm should buy 6 units of capital in project A and 11 units in project B in order to maximise total return. 

### Question 11 {- #eq5.6.11}

$$ g(x,y,\lambda)=ax+by+\lambda(1-x^2-y^2) $$
$$ \frac{\partial g(x,y,\lambda)}{\partial x} = a-2\lambda x=0$$
$$ \frac{\partial g(x,y,\lambda)}{\partial y} = b-2\lambda y=0$$
$$ \frac{\partial g(x,y,\lambda)}{\partial \lambda} =1-x^2-y^2=0$$
As x>0, y>0, then we can get $$ x = \frac{a}{\sqrt{a^2+b^2}} \\
                   y = \frac{b}{\sqrt{a^2+b^2}}\\
                   \lambda = \frac{\sqrt{a^2+b^2}}{2}$$
$$ z_{max} = ax+by\\
           = \frac{a^2}{\sqrt{a^2+b^2}}+\frac{b^2}{\sqrt{a^2+b^2}}\\
           = \sqrt{a^2+b^2}$$                  


# Chapter 4 {- #s4}

## Exercise 4.1* {- #e4.1}

### Question 3 {- #e4.1.3}

(i)(a) $$ y_A = 2 $$
$$ y_B = \sqrt{4.1} \approx 2.025 $$
(b)$$ y_A = 8 $$
$$ y_B = 4.1\sqrt{4.1} \approx 8.302 $$
(c)$$ y_A = \frac{1}{2} $$
$$ y_B = \frac{1}{\sqrt{4.1}} \approx 0.494 $$
(ii)(a)$$ \frac{\Delta y}{\Delta x} = \frac{\sqrt{4.1}-2}{4.1-4} \approx 0.248 $$
(b)$$ \frac{\Delta y}{\Delta x} = \frac{4.1\sqrt{4.1}-8}{4.1-4} \approx 3.019 $$
(c)$$ \frac{\Delta y}{\Delta x} = \frac{\frac{1}{\sqrt{4.1}}-\frac{1}{2}}{4.1-4} \approx -0.061 $$
(iii)(a) $$\frac{dy}{dx} = \frac{1}{2}x^{-\frac{1}{2}} = \frac{1}{4} $$
(b) $$ y = x \sqrt{x} = x^{\frac{3}{2}}$$
$$\frac{dy}{dx} = \frac{3}{2}x^{\frac{1}{2}} = 3 $$
(c) $$ y = \frac{1}{\sqrt{x}} = x^{-\frac{1}{2}}$$
$$\frac{dy}{dx} = -\frac{1}{2}x^{-\frac{3}{2}} = -\frac{1}{16} $$

The answers to part(ii) is close to part (iii).


## Exercise 4.2* {- #e4.2}

### Question 1 {- #e4.2.1}

$$ y' = \frac{3}{2}x^{-\frac{1}{2}} + \frac{81}{x^2} $$
When x = 9 , $$ y' = \frac{3}{2} $$

### Question 4 {- #e4.2.4}

(a)$$ f'(x) = 10x^4 -12x^3+4x-17 $$
$$ f'(-1) = 1 > 0 $$
Thus the tranger slopes upstill at x=-1.

(b) $$ f''(x) = 40x^3-36x^2+4 $$
$$ f''(-1) = -72 < 0 $$
Thus the graph is concave at x=-1.

### Question 6 {- #e4.2.6}

$$ y' = 12x^2 -10x+1 $$
When x = 0 ,$$ y = -3 ; y' = 1 > 0 $$
Thus $$ y = x-3 $$

## Exercise 4.3* {- #e4.3}

### Question 1 {- #e4.3.1}

(a) $$ TR  = PQ\\
           = (100-4\sqrt{Q}-3Q)Q\\
           = 100Q-4Q^{1.5}-3Q^2 $$
(b) $$ MR = 100-6 \sqrt{Q} -6Q $$
When Q = 9 , $$ MR = 28 $$

(c) $$ \Delta{TR} = MR \times \Delta{Q} \\
                  = 28\times 0.25\\
                  = 7$$
When Q = 9, TR=549 ; 
When Q = 9.25, $$ TR \approx 555.78 $$
Thus $$\Delta{TR}= 555.78-549 = 6.78 $$
Thus the exact change in TR is 6.78.

### Question 4 {- #e4.3.4}

$$ \frac{dQ}{dL} = 12L-0.6L^2 $$
$$ \frac{d^2Q}{dL^2} = 12-1.2L $$
When $$ \frac{d^2Q}{dL^2} < 0 $$
$$ L > 10 $$

### Question 7 {- #e4.3.7}
$$ MC=20 $$
Thus when Q increasrs by 1 unit, TC increases by 20 units.

As the MR is 18 at Q=219 ,when Q increases by 1 unit, TR increases by 18 units.

18-20 =-2 < 0

Thus the profit decreases.

### Question 9 {- #e4.3.9}

$$ AC = \frac{TC}{Q}\\
      = aQ+b+\frac{c}{Q} $$
$$ \frac{dAC}{dQ} = a - \frac{c}{Q^2}$$
$$ MC = \frac{dTC}{dQ}\\
      = 2aQ+b $$
$$ \frac{MC-AC}{Q} = \frac{(2aQ+b) - (aQ+b+\frac{c}{Q}) }{Q} = a - \frac{c}{Q^2} $$
Thus $$ \frac{dAC}{dQ} = \frac{MC-AC}{Q} $$


## Exercise 4.4* {- #e4.4}

### Question 4 {- #eq4.4.4}

(a)$$ y'=(x-3)^4 + x\times4(x-3)^3\\
        =(5x-3)(x-3)^3$$
(b)$$ y'=\sqrt{2x-3} + x \times \frac{1}{2} \frac{1}{\sqrt{2x-3}}\times2\\
        =\frac{3(x-1)}{\sqrt{2x-3}}$$
(c)$$ y'=\frac{3x^2(3x+5)^2-x^3\times2(3x+5)\times3}{(3x+5)^4}\\
        =\frac{3x^2(x+5)}{(3x+5)^3}$$
(d)$$ y'=\frac{(x^2+1)-x\times2x}{(x^2+1)^2} \\
        =\frac{1-x^2}{(x^2+1)^2}$$
(e)$$ y'=\frac{a(cx+d)-c(ax+b)}{(cx+d)^2} \\
        =\frac{ad-cb}{(cx+d)^2}$$

(f)$$ y'=am(ax+b)^{m-1}(cx+d)^n+cn(ax+b)^m(cx+d)^{n-1} \\
        =[(m+n)acx+adm+bcn](ax+b)^{m-1}(cx+d)^{n-1}$$
(g)$$ y'=(x+2)^2(x+3)^3+x\times2(x+2)(x+3)^3+x(x+2)^2\times3(x+3)^2\\
        =(6x^2+17x+6)(x+2)(x+3)^2$$

### Question 7 {- #eq4.4.7}

$$ MC = \frac{dC}{dY}\\
      = \frac{4Y(9+Y)-(650+2Y^2)}{(9+Y)^2}\\
      = \frac{2Y^2+36Y-650}{(9+Y)^2}\\
      = 2 - \frac{812}{(9+Y)^2}$$
When Y=21, $$ MC \approx 1.098 $$
$$ MR + MS = 1 $$
Thus $$ MS = 1-1.098 \approx -0.098 $$
The comment you can refer to the answers on the textbook.

### Question 8 {- #eq4.4.8}

$$ MC = \frac{dTC}{dQ}\\
      = \frac{(4Q+10)(Q+3)-(2Q^2+10Q)}{(Q+3)^2}\\
      = \frac{2Q^2+12Q+30}{(Q+3)^2}\\
      = \frac{2(Q+3)^2+12}{(Q+3)^2}\\
      = 2+\frac{12}{(Q+3)^2}$$
$$ MC'= \frac{dMC}{dQ}\\
      = -\frac{24}{(Q+3)^3} < 0$$
As MC' is always less than 0, so MC decreases and converges to 2 as Q increases.

## Exercise 4.5* {- #e4.5}

### Question 2 {- #eq4.5.2}

When P =105 ,Q = 7(As Q>0)
$$ \frac{dP}{dQ} = 4Q $$
$$  E = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = \frac{1}{\frac{dP}{dQ}} \times \frac{P}{Q}\\
      = \frac{1}{4Q} \times \frac{P}{Q}\\
      = \frac{P}{4Q^2}$$
Thus $$ \frac{\Delta P }{4Q^2} = \frac{0.07\times105}{4\times7^2} = 0.0375 $$
Thus the percentage increase in supply is 3.75%  when the price rises by 7%.

### Question 4 {- #eq4.5.4}

$$ \frac{dP}{dQ} = -\frac{nA}{Q^{n+1}} $$
$$  E = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = \frac{1}{\frac{dP}{dQ}} \times \frac{P}{Q}\\
      = \frac{1}{-\frac{nA}{Q^{n+1}}} \times \frac{\frac{A}{Q^n}}{Q}\\
      = -\frac{1}{n} $$

### Question 8 {- #eq4.5.8}

(a)As for Q = f(P):
$$ \frac{dQ}{dP} = f'(P) $$
$$  E = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = f'(P) \frac{P}{f(P)} $$
(i)$$ \frac{dQ}{dP} = n[f(P)]^{n-1}f'(P) $$
$$  E_1 = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = n[f(P)]^{n-1}f'(P) \frac{P}{[f(P)]^n}\\
      = nf'(P) \frac{P}{f(P)}\\
      = nE $$
(ii)$$ \frac{dQ}{dP} = \lambda f'(P) $$
$$  E_2 = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = \lambda f'(P) \frac{P}{[\lambda f(P)] }\\
      = f'(P) \frac{P}{f(P)}\\
      = E $$
(iii)$$ \frac{dQ}{dP} = f'(P) $$
$$  E_3 = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = f'(P) \frac{P}{[\lambda + f(P)] }\\
      = \frac{f(P) E}{\lambda + f(P)}$$


(b)As for Q = P:
$$ \frac{dQ}{dP} = 1 $$
$$  E = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = 1 \times \frac{P}{P}\\
      = 1$$
(i)$$E_1 = nE = 3 $$
(ii)$$ Q = f_1(P) = P \\
          f_2(P) = P^{\frac{3}{2}} = f_1(P)^{\frac{3}{2}}\\
          Q_2 = \lambda f_2(P) = 10 P^{\frac{3}{2}} $$
Then $$E_2 = nE = \frac{3}{2} $$
If you don't know why that is 3/2, you can refer to the following.
$$ Q = 10 P^{\frac{3}{2}} $$
$$ \frac{dQ}{dP} = 15P^{\frac{1}{2}} $$
$$  E_2 = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = 15P^{\frac{1}{2}} \frac{P}{10 P^{\frac{3}{2}}}\\
      = \frac{3}{2} $$
(iii)
$$ Q = 5 P^{\frac{1}{2}} - 2 $$
$$ \frac{dQ}{dP} = \frac{5}{2\sqrt{P}} $$
$$  E_2 = \frac{dQ}{dP} \times \frac{P}{Q}\\
      = \frac{5}{2\sqrt{P}} \frac{P}{5 P^{\frac{1}{2}} - 2}\\
      = \frac{5P}{10P-4\sqrt{P}} $$
      
## Exercise 4.6* {- #e4.6}

### Question 2 {- #eq4.6.2}

(a)$$ f'(x)=3x^2 $$
When f'(x)=0,we get x=0, so it has a stationary point at x=0.
$$ f''(x)=6x $$
Thus $$ f''(0)=0 $$
When x=0,f(0)=0.
You can find (0,0) is an inflection as the graph shows(the graph is omitted).

(b)$$ f'(x)=4x^3 $$
When f'(x)=0,we get x=0, so it has a stationary point at x=0.
$$ f''(x)=12x^2 $$
Thus $$ f''(0)=0 $$
When x=0,f(0)=0.
You can find (0,0) is a local min as the graph shows(the graph is omitted).

(c)$$ f'(x)=-6x^5 $$
When f'(x)=0,we get x=0, so it has a stationary point at x=0.
$$ f''(x)=-30x^4 $$
Thus $$ f''(0)=0 $$
When x=0,f(0)=0.
You can find (0,0) is a local max as the graph shows(the graph is omitted).

### Question 5 {- #eq4.6.5}

$$ TR = PQ \\
      = \sqrt{1000-4Q}Q $$
$$ MR = \frac{d(TR)}{dQ}\\
      = \sqrt{1000-4Q} -\frac{2Q}{\sqrt{1000-4Q}}\\
      = \frac{1000-6Q}{\sqrt{1000-4Q}} $$
When MR = 0, we get Q = 500/3
$$ (MR)' =  \frac{-6\sqrt{1000-4Q}-(1000-6Q)\frac{-2}{\sqrt{1000-4Q}}}{1000-4Q}\\
         = \frac{12Q-4000}{(1000-4Q)^{1.5}}$$
When Q = 500/3 , (MR)' < 0.Thus Q = 500/3 maximises total revenue.


### Question 6 {- #eq4.6.6}

(a)$$ \pi = TR - TC\\
          = PQ - TC\\
          = (200-4Q)Q - (Q^2+50Q+10)\\
          = -5Q^2+150Q-10$$
When$$ \pi' = -10Q+150 = 0  $$
we get $$ Q = 15 $$
As $$ \pi'' = -10 < 0$$
Thus Q = 15 is needed to maximise the firm's profit.

(b)$$ TC = Q^2+50Q+10+tQ $$
$$ \pi = TR - TC\\
          = PQ - TC\\
          = (200-4Q)Q - (Q^2+50Q+10+tQ)\\
          = -5Q^2+(150-t)Q-10$$
When$$ \pi' = -10Q+150-t = 0  $$
we get $$ Q = 15-0.1t $$
As $$ \pi'' = -10 < 0$$
Thus Q = 15-0.1t is needed to maximise the firm's profit.

When Q = 15, 
$$ P_a = 200-4Q \\
     = 200-4\times15\\
     = 140 $$
When Q = 15-0.1t, 
$$ P_b = 200-4Q \\
     = 200-4(15-0.1t)\\
     = 140+\frac{2}{5}t $$
As $$ P_b-P_a = \frac{2}{5}t $$
Thus the price of the good increases by two-fifths of the tax, irrespective of the value of t.

### Question 7 {- #eq4.6.7}

$$ f'(x)=3x^2+2ax+b $$
As (2,5) is a stationary point, f'(2)=0.
$$ \begin{cases} f(2)=5=8+4a+2b+c\\ f(1)=3=1+a+b+c\\ f'(2)=0=12+4a+b \end{cases}   $$
$$ \begin{cases} a=-7\\ b=16\\ c=-7 \end{cases}   $$

### Question 8 {- #eq4.6.8}

(a) The graph is omitted.

(b) As for function 1:
$$ MR = 0.6Q^2 $$
MR is always more than 0 when Q belong to [0,5].Thus TR is increasing when Q rises.Thus, when Q=5, there is a maximum TR which is 25.

As for function 2:
$$ MR = -8Q+55 $$
When MR = 0, we get Q=55/8.
As $$ (MR)' = -8<0 $$
Thus when Q=55/8, there is a maximum TR which is 625/16.

As 25 is less than 625/16, thus when Q = 55/8, there is a maximum TR which is 625/16.

(c)
$$ \begin{cases} MR = 0.6Q^2,0 \leq Q \leq 5 \\ MR = -8Q+55,5 \leq Q \leq 10 \end{cases}   $$
As for function 1:
$$ (MR)' = 1.2Q $$
(MR)' is always more than 0 when Q belong to [0,5].Thus TR is increasing when Q rises.Thus, when Q=5, there is a maximum TR.

As for function 2:
$$ (MR)' = -8 $$
(MR)' is always less than 0 when Q belong to [5,10].Thus TR is decreasing when Q rises.Thus, when Q=5, there is a maximum TR.

In total, when Q=5, there is a maximum TR.




## Exercise 4.7* {- #e4.7}

### Question 1 {- #eq4.7.1}

(a) $$ TR = PQ\\
          = (aQ+b)Q\\
          = aQ^2+bQ$$
$$ TC = dQ+c $$
(b) $$ MR = \frac{d(TR)}{dQ}\\
         = 2aQ+b$$
$$ MC = \frac{d(TC)}{dQ}\\
         = d$$
(c) When $MR =MC$, the profit is maximised.
$$ MR = 2aQ+b = MC = d $$
$$ Q = \frac{d-b}{2a} $$

### Question 2 {- #eq4.7.2}

(a) At the point of maximum total revenue, there is MR = 0. 
Thus $$ MR = 0 = P(1+\frac{1}{E}) $$
Then $$ E = -1 $$
(b)
$$ 2P+3Q=60 $$
$$ P = -1.5Q+30 $$

$$ TR = PQ\\
      = (-1.5Q+30)Q\\
      = -1.5Q^2+30Q $$
$$ MR = -3Q+30 = 0$$
We get $$ Q = 10 $$
As $$ (MR)' = -3 < 0 $$
Thus when $Q = 10$, the total revenue is maximised.
When $Q=10, P= 15$.

At the point $(10,15)$ which maximises the total revenue, we get:
$$ \frac{dQ}{dP} = \frac{1}{\frac{dP}{dQ}} = \frac{1}{-1.5} $$
$$ E = \frac{P}{Q}\times \frac{dQ}{dP} \\
     = \frac{15}{10}\times\frac{1}{-1.5}\\
     = -1$$

### Question 3 {- #eq4.7.3}

(a)
$$ MC = 10$$
$$ TR_1 = P_1Q_1 \\
        = (50-5Q_1)Q_1\\
        = -5Q_1^2+50Q_1$$
$$ MR_1 = -10Q_1 +50 $$
$$ MR_1 = MC = -10Q_1 +50 = 10$$
$$ Q_1 = 4 $$
$$ P_1 = 50-5Q_1 = 30 $$
$$ TR_2 = P_2Q_2 \\
        = (30-4Q_2)Q_2\\
        = -4Q_2^2+30Q_2$$
$$ MR_2 = -8Q_2 +30 $$
$$ MR_2 = MC = -8Q_2 +30 = 10$$
$$ Q_2 = 2.5 $$
$$ P_2 = 30-4Q_2 = 20 $$
When the firm's doestic price is 30 and foreign price is 20, the profit is maximised.

(b) $$ P_1 = 50-5Q_1;\\P_2 = 30-4Q_2 $$
$$ Q_1 = -0.2P_1 + 10;\\Q_2 = -0.25P_2 + 7.5 $$
$$ Q = Q_1+Q_2 \\
     = -0.2P + 10 -0.25P + 7.5\\
     = -0.45P+17.5$$
$$ P = -\frac{20}{9}Q + \frac{350}{9}$$
$$ TR = PQ \\
      = (-\frac{20}{9}Q + \frac{350}{9})Q\\
      = -\frac{20}{9}Q^2 + \frac{350}{9}Q$$
$$ MR = -\frac{40}{9}Q + \frac{350}{9} $$
$$ MR = MC = -\frac{40}{9}Q + \frac{350}{9} = 10$$
$$ Q = 6.5 $$
$$ P = -\frac{20}{9}Q + \frac{350}{9} = \frac{220}{9}$$
When the firm's price is $220/9$, the profit is maximised.

$$ \pi_a = TR - TC \\
         = P_1Q_1+P_2Q_2 - (10+10(Q_1+Q_2))\\
         = 30\times4 + 20\times2.5-10-10(4+2.5)\\
         = 95 $$
$$ \pi_b = TR - TC \\
         = PQ - (10+10Q)\\
         = \frac{220}{9}\times6.5 - 10-10\times6.5\\
         = \frac{755}{9}\\
         \approx 83.89$$
         
### Question 5 {- #eq4.7.5}

(a) $$ \frac{dC}{dQ} = -\frac{DR}{Q^2}+\frac{H}{2} $$
$$ \frac{d^2C}{dQ^2} = \frac{2DR}{Q^3} $$
As $Q > 0 $, when $$ \frac{dC}{dQ} = 0 $$
we get $$ Q = \sqrt{\frac{2DR}{H}} $$
As the second-order derivative is always more than 0, thus $$ Q = \sqrt{\frac{2DR}{H}} $$ is a minimum point.

(b) When $$ Q = \sqrt{\frac{2DR}{H}} $$
We get $$ C = \frac{DR}{Q}+\frac{HQ}{2} \\
            = \sqrt{2DRH} $$

### Question 6 {- #eq4.7.6}

Using the following formula:
$$ EOQ = Q = \sqrt{\frac{2DR}{H}} \\
   C = \sqrt{2DRH} $$
(a) As $D = 2000, R = 40 ,H = 100$, we get 
$$ EOQ = Q = \sqrt{\frac{2DR}{H}}= 40\\
   C = \sqrt{2DRH}=4000 $$
(b) As $D = 2000, R = 40 ,H = 64$, we get 
$$ EOQ = Q = \sqrt{\frac{2DR}{H}}= 50\\
   C = \sqrt{2DRH}=3200 $$
(c) As $D = 2000, R = 160 ,H = 100$, we get 
$$ EOQ = Q = \sqrt{\frac{2DR}{H}}= 80\\
   C = \sqrt{2DRH}=8000 $$
   
(d) Reducing (increasing) the order costs by a factor of the square of $k$ reduces (imcreases) the minimum total cost by a factor of $k$. The same applies to charges in the holding costs.         
         

### Question 9 {- #eq4.7.9}
When there is a tax, $t$ , we get:
$$ P-t = aQ_S+b $$$
$$ P = aQ_S+b+t $$
$$ \begin{cases} P=aQ+b+t\\ P =-cQ+d \end{cases}   $$
$$ P=aQ+b+t=-cQ+d  $$
$$ Q = \frac{d-b-t}{a+c} $$
$$ T = tQ \\
     = t\times\frac{d-b-t}{a+c}\\
     = -\frac{1}{a+c}t^2+\frac{d-b}{a+c}t$$
$$ T' = \frac{dT}{dt}\\
      = -\frac{2}{a+c}t+\frac{d-b}{a+c} = 0$$
we get $$ t = \frac{d-b}{2} $$
As $$ T'' = -\frac{2}{a+c} < 0$$
Thus T is maximised by taking $t = (d-b)/2$.


## Exercise 4.8* {- #e4.8} 

### Question 2 {- #eq4.8.2}

(a)$$ y = \ln(\frac{x}{x+1}) = \lnx - \ln(x+1) $$
$$ y' = \frac{1}{x} - \frac{1}{x+1}  = \frac{1}{x(x+1)}$$
(b)$$ y = \ln(x\sqrt{3x-1}) = \lnx + \frac{1}{2}\ln(3x-1) $$
$$ y' = \frac{1}{x} + \frac{3}{2(3x-1)} = \frac{9x-2}{2x(3x-1)}$$
(c)$$ y = \ln(\sqrt{\frac{x+1}{x-1}}) = \frac{1}{2}\ln(x+1) - \frac{1}{2}\ln(x-1) $$
$$ y' = \frac{1}{2(x+1)} - \frac{1}{2(x-1)} = \frac{1}{1-x^2}$$

### Question 5 {- #eq4.8.5}

(a)$$ y'=e^{ax} + axe^{ax}\\
        =(1+ax)e^{ax} = 0$$
$$ x = \frac{-1}{a} $$
$$ y''=(2a+a^2x)e^{ax} $$
When $$ x = \frac{-1}{a} $$
$$ y = -\frac{1}{ae} $$
$$ y'' < 0 $$
Thus the stationary point is $$ (-\frac{1}{a},-\frac{1}{ae}) $$ and it is a maximum at this point.
(b)$$ y'=\frac{2ax+b}{ax^2+bx} = 0$$
$$ x = -\frac{b}{2a} $$
$$y'' = \frac{2a(ax^2+bx)-(2ax+b)^2}{(ax^2+bx)^2}$$
When $$ x = -\frac{b}{2a} $$
$$ y = \ln(-\frac{b^2}{4a}) $$
$$ y''<0 $$
Thus the stationary point is $$ (-\frac{b}{2a},\ln(-\frac{b^2}{4a})) $$ and it is a maximum at this point.

### Question 8 {- #eq4.8.8}

$$ \frac{dP}{dQ} = -\frac{150}{2Q+1} $$
$$ E = \frac{dQ}{dP}\times\frac{P}{Q}\\
     = \frac{1}{\frac{dP}{dQ}}\times\frac{P}{Q}\\
     = \frac{1}{-\frac{150}{2Q+1}}\times\frac{500-75\ln(2Q+1)}{Q}\\
     = \frac{(3\ln(2Q+1)-20)(2Q+1)}{6Q}$$

### Question 12 {- #eq4.8.12}

(a)$$ \frac{dy}{dt} = \frac{abke^{-at}}{(1+be^{-at})^2} $$
As $k,a,b$ are positive constants, the first-order derivative is more than 0, thus the gradient is positive.

(b)$$ \frac{d^2y}{dt^2} = \frac{-a^2bke^{-at}(1+be^{-at})^2+2a^2b^2ke^{-2at}(1+be^{-at})}{(1+be^{-at})^4} \\
= \frac{a^2bke^{-at}(be^{-at}-1)}{(1+be^{-at})^3}$$
When $$ \frac{d^2y}{dt^2} > 0 $$
we get $$ t < \frac{\ln b}{a} $$
When $$ \frac{d^2y}{dt^2} < 0 $$
we get $$ t > \frac{\ln b}{a} $$
Thus the graph is convex when $t<(\lnb)/a$ and concave when 
$t>(\ln b)/a$.

(c) When $t=0$, we get$$ y = \frac{k}{1+b} $$,thus the curve crosses the $y$ axis at $(0,k/((1+b))$.When t goes to infinity, y goes to k.

(d)
I just give you two examples which $k=1$ and $k=8$,you can refer to the exact graph in the textbook.The shape of the graphs is same. 
<img src="4-6-solutions_files/figure-html/unnamed-chunk-7-1.png" width="672"  />

### Question 13 {- #eq4.8.13}

(a)$$ PV = V\times e^{-0.1t}\\
         = 2e^{\sqrt{t}}\times e^{-0.1t}\\
         = 2e^{\sqrt{t}-0.1t}$$
(b)$$ (PV)' = (\frac{1}{\sqrt{t}}-0.2)e^{\sqrt{t}-0.1t} = 0 $$
$$ T = 25 $$
$$ (PV)'' = (-\frac{1}{2t^{\frac{3}{2}}}+(\frac{1}{\sqrt{t}}-0.2)(\frac{1}{2\sqrt{t}}-0.1))e^{\sqrt{t}-0.1t} $$
When $T=25$, $(PV)'' < 0$,thus $T = 25$ is chosen to maximise PV.


