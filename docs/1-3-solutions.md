
# (PART) 💡 SOLUTIONS {-}



# Chapter 1 {- #ch1}

## Exercise 1.1 {- #q1.1}

### Q1 {- #q1.1.1}
(Fernando Li)

(a) $$ A \cap B = \lbrace 2,3,5,7 \rbrace $$
(b) $$ A \cap C = \lbrace 2,4,6,8,10 \rbrace $$
(c) $$ B \cap C = \lbrace 2 \rbrace $$
(d) $$ A \cup B = \lbrace 1,2,3,4,5,6,7,8,9,10,11,13,17,19 \rbrace $$
(e) $$ A \cup C = \lbrace 1,2,3,4,5,6,7,8,9,10,12,14,16,18 \rbrace $$
(f) $$ B \cup C = \lbrace 2,3,4,5,6,7,8,10,11,12,13,14,16,17,18,19 \rbrace $$
(g) $$ A \cup B \cup C = \lbrace 1,2,3,4,5,6,7,8,9,10,11,12,13,14,16,17,18,19 \rbrace $$
(h) $$ A \cap B \cap C = \lbrace 2 \rbrace $$
(i) $$ (A \cup B) \cap C = \lbrace 2,4,6,8,10 \rbrace $$
(j) $$ (A \cap B) \cup C = \lbrace 2,3,4,5,6,7,8,10,12,14,16,18 \rbrace $$
(k) $$ A \cap B' = \lbrace 1,4,6,8,9,10 \rbrace $$
(l) $$ 'A \cap B' = \lbrace 12,14,15,16,18 \rbrace $$

### Q2 {- #q1.1.2}
(David Rosa)

(a)false, a counterexample is as follows
$$ A = \lbrace 1,2,3,4 \rbrace \\
   B = \lbrace 3,4,5,6 \rbrace \\
   U = \lbrace 1,2,3,4,5,6,7,8 \rbrace \\$$
Then $$ A - B = \lbrace 1,2 \rbrace \\
        A' = \lbrace 5,6,7,8 \rbrace \\
        A' \cap B = \lbrace 5,6 \rbrace \\$$
Thus $$ A - B = A' \cap B $$ is false.

(b)false, a counterexample is as follows
$$ A = \lbrace 1,2 \rbrace \\
   B = \lbrace 2,3 \rbrace \\
   C = \lbrace 3,4 \rbrace \\
   U = \lbrace 1,2,3,4,5 \rbrace \\$$
Then $$ A \cup B = \lbrace 1,2,3 \rbrace \\
        (A \cup B) \cap C = \lbrace 3 \rbrace \\
        B \cap C = \lbrace 3 \rbrace \\
        A \cup ( B \cap C) = \lbrace 1,2,3 \rbrace \\ $$
Thus $$ (A \cup B) \cap C = A \cup ( B \cap C) $$ is false.

(c)true
As $$ B' \cap B = \emptyset $$
$$ (A' \cup B') \cap B = (A' \cap B) \cup (B' \cap B) \\
= (A' \cap B) \cup \emptyset \\
= A' \cap B \\
= \lbrace x \in U : x \in B \ and \ x \in A' \rbrace\\
= \lbrace x \in U : x \in B \ and \ x \notin A \rbrace\\
= B -A $$

## Exercise 1.2 {- #q1.2}

### Q1 {- #q1.2.1} 

(a) $$ \lbrace x:\pm \sqrt2 \rbrace $$
(b) $$ \lbrace x: \sqrt2 \rbrace $$
(c)Q means rational numbers, so $$\lbrace x \in Q: x^2 = 2 \rbrace =  \emptyset $$

### Q2 {- #q1.2.2} 
(Jiin Kim)

(a)$$ A \cap B = [3,5]  $$
(b)$$ A \cup B = [1,9)  $$
(c)$$ A - C = (1,5)  $$
(d)$$ B \cap C = \lbrace 5 \rbrace  $$
(e)$$ C - B = \lbrace 1 \rbrace  $$
(f)$$ B - C = [3,5) \cup (5,9) $$
(g)$$ B - (B - C) = \lbrace 5 \rbrace $$
(h)$$ A \cup D = [1,\infty)  $$
(i)$$ C \cap D = \lbrace 5 \rbrace  $$

## Exercise 1.3 {- #q1.3}

### Q1 {- #q1.3.1}
(Maria Kahlert)

### Q2 {- #q1.3.2}

(a)$$ 2x^3+7x^2-15x = x(2x^2+7x-15) \\
                    = x(x+5)(2x-3)$$
(b)$$ 2x^3+3x^2-2x-3 = (2x^3-2x)+(3x^2-3) \\
                     = 2x(x^2-1) + 3(x^2-1) \\
                     = (2x+3)(x^2-1) \\
                     = (2x+3)(x+1)(x-1)$$
(c)$$ x^3-x^2-x-2 = (x^3-1)-(x^2+x+1) \\
                  = (x-1)(x^2+x+1)-(x^2+x1) \\
                  = (x-1-1)(x^2+x+1) \\
                  = (x-2)(x^2+x+1)$$
(d)$$ x^4-3x^3-13x^2+15x = x(x^3-3x^2-13x+15) \\
                         = x[(x^3-x)+(-3x^2-12x+15)] \\
                         = x[x(x^2-1)-3(x^2+4x-5)] \\
                         = x[x(x+1)(x-1)-3(x-1)(x+5)] \\
                         = x(x-1)[x(x+1)-3(x+5)] \\
                         = x(x-1)(x^2-2x-15)\\
                         = x(x-1)(x+3)(x-5)$$
(e)$$ x^4-3x^3+x^2+3x-2 = (x^4+x^2-2)+(-3x^3+3x) \\
= (x^2+2)(x^2-1)-3x(x^2-1) \\
= (x^2+2-3x)(x^2-1) \\
= [(x-2)(x-1)][(x+1)(x-1)] \\
= (x-2)(x+1)(x-1)^2$$

(f)$$  x^4-x^3+x^2-3x+2 = (x^4-x^3)+(x^2-3x+2) \\
= x^3(x-1)+(x-1)(x-2) \\
= (x-1)(x^3+x-2) \\
= (x-1)[(x^3-1)+(x-1)] \\
= (x-1)[(x-1)(x^2+x+1)+(x-1)] \\
= (x-1)^2(x^2+x+2)$$

### Q3 {- #q1.3.3}
(Ashley a-d; Byoungchurl Lee e-h)
