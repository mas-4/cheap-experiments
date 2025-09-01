- [Spivak Chapter 01 Basic Properties of Numbers Exercises](#spivak-chapter-01-basic-properties-of-numbers-exercises)
  - [1.](#1)
    - [1. (i)](#1-i)
    - [1. (ii)](#1-ii)
    - [1. (iii)](#1-iii)
    - [1. (iv)](#1-iv)
    - [1. (v)](#1-v)
  - [2.](#2)
  - [3.](#3)
    - [3. (i)](#3-i)
    - [3. (ii)](#3-ii)
    - [3. (iii)](#3-iii)
    - [3. (iv)](#3-iv)
    - [3. (v)](#3-v)
    - [3. (vi)](#3-vi)
  - [4.](#4)
    - [4. (i)](#4-i)
    - [4. (ii)](#4-ii)
    - [4. (iii)](#4-iii)
    - [4. (iv)](#4-iv)
    - [4. (v)](#4-v)
    - [4. (vi)](#4-vi)
    - [4. (vi)](#4-vi-1)
    - [4. (viii)](#4-viii)
    - [4. (ix)](#4-ix)
    - [4. (x)](#4-x)
    - [4. (xi)](#4-xi)
    - [4. (xii)](#4-xii)
    - [4. (xiii)](#4-xiii)
    - [4. (xiv)](#4-xiv)
  - [5.](#5)
    - [5. (i)](#5-i)
    - [5. (ii)](#5-ii)
    - [5. (iii)](#5-iii)
    - [5. (iv)](#5-iv)
    - [5. (v)](#5-v)
    - [5. (vi)](#5-vi)
    - [5. (vii)](#5-vii)
    - [5. (viii)](#5-viii)
    - [5. (ix)](#5-ix)
    - [5. (x)](#5-x)
  - [6.](#6)
    - [6. (a)](#6-a)
    - [6. (b)](#6-b)
    - [6. (c)](#6-c)
  - [7.](#7)
  - [8.](#8)
  - [9.](#9)
    - [9. (i)](#9-i)
    - [9. (ii)](#9-ii)
    - [9. (iii)](#9-iii)
    - [9. (iv)](#9-iv)
    - [9. (v)](#9-v)
  - [10.](#10)
    - [10. (i)](#10-i)
    - [10. (ii)](#10-ii)
    - [10. (iii)](#10-iii)
    - [10. (iv)](#10-iv)
  - [11.](#11)
    - [11. (i)](#11-i)
    - [11. (ii)](#11-ii)
    - [11. (iii)](#11-iii)
    - [11. (iv)](#11-iv)
    - [11. (v)](#11-v)
    - [11. (vi)](#11-vi)
    - [11. (vii)](#11-vii)
    - [11. (viii)](#11-viii)
  - [12.](#12)
    - [12. (i)](#12-i)
    - [12. (ii)](#12-ii)


# Spivak Chapter 01 Basic Properties of Numbers Exercises

| Proposition | Name                                   | Law                                                                                                 |
| ----------- | -------------------------------------- | --------------------------------------------------------------------------------------------------- |
| P1          | Associative law for addition           | $a+(b+c)=(a+b)+c$                                                                                   |
| P2          | Existence of an additive identity      | $a+0=0+a=a$                                                                                         |
| P3          | Existence of an additive inverse       | $a+(-a)=(-a)+a=0$                                                                                   |
| P4          | Commutative law for addition           | $a+b=b+a$                                                                                           |
| P5          | Associative law for multiplication     | $a\cdot(b\cdot c)=(a\cdot b)\cdot c$                                                                |
| P6          | Existence of a multiplicative identity | $a\cdot1=1\cdot a; \quad 1 \neq 0$                                                                  |
| P7          | Existence of a multiplicative inverse  | $a\cdot a^{-1}=a^{-1}\cdot a=1,$ for $a \neq 0$                                                     |
| P8          | Commutative law for multiplication     | $a\cdot b=b\cdot a$                                                                                 |
| P9          | Distributive law                       | $a\cdot(b+c)=a \cdot b + a \cdot c$                                                                 |
| P10         | Trichotomy law                         | For every number $a$, one and only one: i. $a=0,$, ii. $a \in \mathbb{P}$, iii. $-a \in \mathbb{P}$ |
| P11         | Closure under addition                 | If $a \in \mathbb{P}$ and $b \in \mathbb{P},$ then $a+b \in \mathbb{P}$                             |
| P12         | Closure under multiplication           | If $a \in \mathbb{P}$ and $b \in \mathbb{P},$ then $a\cdot b \in \mathbb{P}$                        |


***
## 1.

### 1. (i)

> Prove the following:
>
> If $ax=a$ for some number $a \neq 0$, then $x = 1$. 🙄

$$
\begin{align*}
ax &= a \\
a^{-1} \cdot a \cdot x &= a^{-1} \cdot a \\
1x &= 1 \tag{P7} \\
x &= 1 \quad🤌\tag{P6} \\
\end{align*}
$$

### 1. (ii)

> $x^2 - y^2 = (x-y)(x+y).$

$$
\begin{align*}
x^2 - y^2 &= (x-y)(x+y) \\
&= (x-y)x+(x-y)y \tag{P9}\\
&= x(x-y)+y(x-y) \tag{P8}\\
&= x^2-xy+xy-y^2 \tag{P9}\\
&= x^2-y^2 \quad🤌\\
\end{align*}
$$

### 1. (iii) 

> If $x^2=y^2,$ then $x=y$ or $x = -y.$

$$
\begin{align*}
x^2 &= y^2 \\
x^2 - y^2 &= 0 \\
(x-y)(x+y)&= 0 \tag{from ii.}\\
\end{align*}
$$

Therefore,

$$
\begin{align*}
x - y &= 0 \\
x &= y \\
x + y &= 0 \\
x &= -y \quad🤌\\
\end{align*}
$$

### 1. (iv)

> $x^3 - y^3 = (x-y)(x^2 + xy + y^2).$

$$
\begin{align*}
x^3 - y^3 &= (x-y)(x^2 + xy + y^2) \\
&= (x-y)x^2 + (x-y)xy + (x-y)y^2 \tag{P9}\\
&= x^3-x^2y + x^2y-xy^2 + xy^2-y^3 \tag{P9}\\
&= x^3-y^3 \quad🤌\\
\end{align*}
$$

### 1. (v)

> $x^n - y^n = (x-y)(x^{n-1}+x^{n-2}y+\cdots+xy^{n-2}+y^{n-1}).$

$$
\begin{align*}
x^n - y^n &= (x-y)(x^{n-1}+x^{n-2}y+\cdots+xy^{n-2}+y^{n-1}) \\
&= (x-y)x^{n-1}+(x-y)x^{n-2}y+\cdots+(x-y)xy^{n-2}+(x-y)y^{n-1} \tag{P9} \\
&= x^n-x^{n-1}y+x^{n-1}y-x^{n-2}y^2+\cdots+x^2y^{n-2}-xy^{n-1}+xy^{n-1}-y^n \tag{P9} \\
&= x^n-y^n \quad🤌\\
\end{align*}
$$

> 1. (vi) $x^3 + y^3 = (x+y)(x^2-xy+y^2).$

$$
\begin{align*}
(x+y)(x^2-xy+y^2) &= x^2(x+y)-xy(x+y)+y^2(x+y) \tag{P9} \\
&= x^3+x^2y-x^2y-xy^2+xy^2+y^3 \tag{P9} \\
&= x^3+y^3 \quad🤌 \\
\end{align*}
$$

For the trick can just take $x^3+y^3$ to be $x^3-(-y)^3$ and apply (iv)

## 2.

> What is wrong with the following "proof"? Let x = y. Then
> 
> $$
> \begin{align*}
> x^2 &= xy \\
> x^2 - y^2 &= xy - y^2 \\
> (x+y)(x-y) &= y(x-y) \\
> x + y = y \\
> 2y = y \\
> 2 = 1 \\
> \end{align*}
> $$

If $x^2 = xy$, then $x = y$, which means $x-y = 0$ so the fourth step, dividing by $x-y$ is dividing by $0$ and is undefined.

## 3.

> Prove the following.

### 3. (i)

> $\frac{a}{b} = \frac{ac}{bc},$ if $b,c \neq 0.$

$$
\begin{align*}
\frac{a}{b} &= \frac{ac}{bc} \\
&= \frac{a}{b} \cdot \frac{c}{c} \\
&= \frac{a}{b} \cdot 1 \\
&= \frac{a}{b} \quad 🤌 \\
\end{align*}
$$

### 3. (ii)

> $\frac{a}{b} + \frac{c}{d} = \frac{ad + bc}{bd},$ if $b,d \neq 0.$

$$
\begin{align*}
\frac{a}{b} + \frac{c}{d} &= \frac{ad + bc}{bd} \\
&= \frac{ad}{bd} + \frac{bc}{bd} \\
&= \frac{a}{b} \cdot \frac{d}{d} + \frac{b}{b} \cdot \frac{c}{d} \\
&= \frac{a}{b} \cdot 1 + 1 \cdot \frac{c}{d} \\
&= \frac{a}{b} + \frac{c}{d} \quad 🤌 \\
\end{align*}
$$

### 3. (iii)

> $(ab)^{-1} = a^{-1}b^{-1},$ if $a,b \neq 0.$ (To do this you must remember the defining property of $(ab)^{-1}.$)

Since $(ab)^{-1}$ is defined as satisfying $(ab)(ab)^{-1}$ it suffices to show that $a^{-1}b^{-1}$ also satisfies this property.

$$
\begin{align*}
(ab)a^{-1}b^{-1} &= aa^{-1}bb^{-1} \\
&= 1 \cdot 1 \\
&= 1 \quad 🤌
\end{align*}
$$

### 3. (iv)

> $\frac{a}{b} \cdot \frac{c}{d} = \frac{ac}{db},$ if $b,d \neq 0.$

$$
\begin{align*}
\frac{a}{b} \cdot \frac{c}{d} &= ab^{-1} \cdot cd^{-1} \\
&= acb^{-1}d^{-1} \\
&= ac(bd)^{-1} \\
&= \frac{ac}{bd} \quad 🤌 \\
\end{align*}
$$

### 3. (v)

> $\frac{a}{b} / \frac{c}{d} = \frac{ad}{bc},$ if $b,c,d \neq 0.$

$$
\begin{align*}
\frac{a}{b} / \frac{c}{d}  &= ab^{-1} \cdot (\frac{c}{d})^{-1}\\
&= ab^{-1} \cdot (cd^{-1})^{-1}\\
&= ab^{-1} \cdot c^{-1}(d^{-1})^{-1}\\
&= ab^{-1} \cdot c^{-1} \cdot d\\
&= ad \cdot b^{-1}c^{-1} \\
&= ad \cdot (bc)^{-1} \\
&= \frac{ad}{bc} \quad 🤌 \\
\end{align*}
$$

### 3. (vi) 

> If $b,d \neq 0,$ then $\frac{a}{b} = \frac{c}{d}$ if and only if $ad = bc.$ Also determine when $\frac{a}{b} = \frac{b}{a}$.

Since

$$
\begin{align*}
ad &= bc \\
b^{-1}d^{-1} \cdot ad &= bc \cdot b^{-1}d^{-1}\\
b^{-1}a &= cd^{-1}\\
\frac{a}{b} &= \frac{c}{d} \\
b^{-1}a &= cd^{-1}\\
b^{-1}d^{-1} \cdot ad &= bc \cdot b^{-1}d^{-1}\\
ad &= bc \\
\end{align*}
$$

Furthermore,

$$
\begin{align*}
\frac{a}{b} &= \frac{b}{a} \\
b \cdot ab^{-1} &= ba^{-1} ab^{-1} \cdot b\\
a &= b^2a^{-1} \\
a \cdot a &= b^2a^{-1} \cdot a\\
a^2 &= b^2 \\
a &= \pm b  \quad 🤌\\
\end{align*}
$$

## 4.

> Find all numbers $x$ for which

### 4. (i) 

> $4 - x < 3 - 2x.$

$$
\begin{align*}
4 - x &< 3 - 2x \\
4 - x + 2x &< 3 \\
4 + x &< 3 \\
x &< -1
\end{align*}
$$

### 4. (ii) 

> $5-x^2<8.$

$$
\begin{align*}
5-x^2&<8 \\
-x^2&<3 \\
-x^2&<3 \\
x^2&>-3 \\
\end{align*}
$$

Since $x^2>0$ for all real $x,$ this is true for all real x.

### 4. (iii) 

> $5-x^2<-2.$

$$
\begin{align*}
5-x^2&<-2 \\
-x^2&<-7 \\
x^2&>7 \\
\end{align*}
$$

Which means $|x| > \sqrt 7$

### 4. (iv) 

> $(x-1)(x-3)>0$

Since the inequality only holds when the left side is not zero, both terms $(x-1),(x-3)$ need to evaluate to a non zero identity and the pair need to multiply to a positive number.

We know that this can happen when both are negative, which will only be the case when $x < 1$.

We also know that they are both positive only when $x > 3$.

So we have $x \in (-\infty, 1)\cup(3,\infty)$.

### 4. (v) 

> $x^2 - 2x + 2 > 0$

After completing the square we get

$$
\begin{align*}
x^2 - 2x + 2 &> 0 \\
x^2 - 2x + 1 - 1 + 2 &> 0 \\
(x-1)^2 + 1 &> 0
\end{align*}
$$

In this case we can see that $(x-1)^2$ is at least $0$, and with the addition of $1$ we see this inequality holds for all real numbers.

### 4. (vi) 

> $x^2+x+1>2$ 
$$
\begin{align*}
x^2+x+1&>2\\
x^2+x-1&>0\\
x^2+x+\frac{1}{4}-\frac{1}{4}-1&>0\\
(x+\frac{1}{2})^2-\frac{5}{4}&>0\\
(x+\frac{1}{2})^2&>\frac{5}{4}\\
x+\frac{1}{2}&>\pm \frac{\sqrt5}{2}\\
x >\frac{\sqrt5 - 1}{2} &\quad x <\frac{-\sqrt 5 -1}{2}\\
\end{align*}
$$

So!

$$
x \in (-\infty, \frac{-\sqrt 5 - 1}{2}) \cup (\frac{\sqrt5-1}{2}, \infty)
$$

### 4. (vi) 

> $x^2-x+10>16$

$$
\begin{align*}
x^2-x+10 &> 16 \\
x^2-x-6 &> 0 \\
x^2-x+\frac{1}{4}-\frac{1}{4}-6 &> 0 \\
(x-\frac{1}{2})^2 - \frac{25}{4} &> 0 \\
(x-\frac{1}{2})^2 &> \frac{25}{4} \\
x-\frac{1}{2} &> \pm \frac{5}{2} \\
x > \frac{6}{2} &\quad x < -\frac{4}{2} \\
x > 3 &\quad x < -2
\end{align*}
$$

So!

$$
x \in (-\infty, -2) \cup (3,\infty)
$$

### 4. (viii) 

> $x^2+x+1>0$

$$
\begin{align*}
x^2+x+1&>0 \\
x^2+x+\frac{1}{4}-\frac{1}{4}+1&>0 \\
(x+\frac{1}{2})^2+\frac{3}{4}&>0 \\
\end{align*}
$$

Since $(x+\frac{1}{2})^2$ is always positive and is at least $0$, the smallest possible value on the left is $\frac{3}{4}$ so $x \in (-\infty,\infty).$

### 4. (ix) 

> $(x-\pi)(x+5)(x-3)>0.$

In this case, since it's 3 terms, the calculus is significantly more complicated.

We know that x can't equal any of it's roots, so $x\notin (\pi,-5,3)$

It can also only have two negative terms, not one or three.

We must table this!

| Interval      | $x - \pi$ | $x+5$ | $x-3$ | Sign |
| ------------- | --------- | ----- | ----- | ---- |
| $x<-5$        | -         | -     | -     | -    |
| $-5 < x < 3$  | -         | +     | -     | +    |
| $3 < x < \pi$ | -         | +     | +     | -    |
| $x > \pi$     | +         | +     | +     | +    |


Now we can see that $x \in (-5,3) \cup (\pi, \infty)$

### 4. (x) 

> $(x - \sqrt[3]2)(x-\sqrt 2) > 0$

$$
x \in (-\infty, \sqrt[3]2) \cup (\sqrt 2, \infty)
$$

### 4. (xi) 

> $2^x < 8$

$$
x < 3
$$

### 4. (xii) 

> $x+3^x < 4$

$$
x < 1
$$

### 4. (xiii) 

> $\frac{1}{x}+\frac{1}{1-x}>0.$

This simplifies to $\frac{1}{x-x^2} > 0$

$x \in (0,1)$ since past 1 and below 0 the $x^2$ term will dominate.

### 4. (xiv) 

> $\frac{x-1}{x+1} > 0.$

Well, it's undefined at $-1$. $x \in (-\infty,-1)\cup (1,\infty)$

## 5. 

> Prove the following:

### 5. (i) 

> If $a < b$ and $c < d,$ then $a+c < b+d$

Well, there's this trick I know of, adding equations. Why don't we try it with an inequality with identical operators

$$
\begin{align*}
a &< b \\
+ c &< d \\
a + c &< b + d \\
\end{align*}
$$

Whoa! it worked! 🤌

### 5. (ii) 

> If $a < b$, then $-b < -a.$

From $a < b$ we know $b - a \in \mathbb{P}$. So, watch this 👀

$$
\begin{align*}
b - a &\in \mathbb{P}\\
-a+b &\in \mathbb{P}\\
-a-(-b) &\in \mathbb{P}\\
\end{align*}
$$

And there we know $-a-(-b)\in \mathbb{P}$ means $-b < -a.$ 🤌

### 5. (iii) 

> If $a<b$ and $c>d,$ then $a-c<b-d.$

Translating our statements into $b-a \in \mathbb{P}$ and $c-d \in \mathbb{P}$ we then see that adding two positive numbers is still positive so

$$
\begin{align*}
(b-a)+(c-d) &\in \mathbb{P} \\
b-d+c-a &\in \mathbb{P} \\
(b-d)+(-(-c+a) &\in \mathbb{P} \\
(b-d)-(a-c) &\in \mathbb{P} \\
\end{align*}
$$

Since the last statement fits our pattern we know it to say $b-d>a-c.$ 🤌

### 5. (iv) 

> If $a < b$ and $c > 0$, then $ac < bc.$

Since $\mathbb{P}$ is closed under multiplication and both $b-a \in \mathbb{P}$ and $c \in \mathbb{P}$, then $c(b-a) \in \mathbb{P}$ so $bc-ac \in \mathbb{P}$ and $bc > ac$ and $ac < bc.$ 🤌

### 5. (v) 

> If $a<b$ and $c<0,$ then $ac > bc$.

Since $b-a \in \mathbb{P}$ and $0-c\in \mathbb{P}$ we can see multiply again.

$$
\begin{align*}
(0-c)(b - a) &\in \mathbb{P}\\
-c(b - a) &\in \mathbb{P}\\
-cb - (-c)a &\in \mathbb{P}\\
-cb + ca &\in \mathbb{P}\\
ca-cb &\in \mathbb{P}\\
ac-bc &\in \mathbb{P}\\
\end{align*}
$$

And from that we can see $ac>bc.$ 🤌

### 5. (vi) 

> If $a>1,$ then $a^2>a.$

We know that $\mathbb{P}$ is closed under multiplication so

$$
\begin{align*}
(a-1) &\in \mathbb{P} \\
a(a-1) &\in \mathbb{P} \\
a^2-a &\in \mathbb{P} \\
\end{align*}
$$

From this we see $a^2>a.$ 🤌

### 5. (vii) 

> If $0 < a < 1,$ then $a^2<a.$

$$
\begin{align*}
a-0 &\in \mathbb{P} \\
a &\in \mathbb{P}
\end{align*}
$$

From this we know $a \in \mathbb{P}$ and since it is closed under multiplication, it suffices to show $a-a^2 \in \mathbb{P}$

$$
\begin{align*}
1-a &\in \mathbb{P} \\
a(1-a) &\in \mathbb{P} \\
a-a^2 &\in \mathbb{P} 🤌\\
\end{align*}
$$

### 5. (viii) 

> If $0\le a <b$ and $0\le c <d,$ then $ac<bd.$

Let's examine our term $ac<bd.$

$$
bd-ac \\
bd-ad+ad-ac \\
d(b-a)+a(d-c) \\
$$

Examining our terms, we know $b-a \in \mathbb{P}$ and $d>c\ge0$ so the whole term $d(b-a)$ is positive.

We also know $a$ is at least $0$ and $d-c$ is positive, so the term $a(d-c)$ is at least 0.

Therefore the whole term $d(b-a)+a(d-c)$ must be positive because it is at least $d(b-a)$ which is positive. 🤌

### 5. (ix) 

> If $0 \le a <b,$ then $a^2<b^2.$ (Use (viii).)

Take the terms $c=a$ and $d=b$ from the previous proof. We know $ac<bd,$ and applying our equalities we get $aa<bb$ and therefore $a^2<b^2.$ 🤌

### 5. (x) 

> If $a,b \ge 0$ and $a^2 < b^2,$ then $a<b.$ (Use (ix), backwards.)

Assume $a^2 < b^2$ and $a>b$. Since $a,b\ge 0$ it also follows that $0\le b < a$. But then $b^2<a^2$ by (ix) contradicting our assumption. So $a \le b.$

This $a \le b$ decomposes into two cases. Assume $a=b.$ Then $a^2=b^2$ which contradicts our statement $a^2<b^2.$ Therefore $a<b.$ 🤌

## 6. 

### 6. (a) 

> Prove that if $0\le x < y,$ then $x^n<y^n,n=1,2,3....$

For a proof by induction, note that we already have the first case:

**Case 1**

If $0 \le x < y,$ then $x<y$ and $x^1<y^1$ since $x^1=x$ and $y^1=y.$

**Case n+1**

From case (5-viii) take $a=x,b=y,c=x^k,$ and $d=y^k$. We know 

$$
\begin{align*}
ac&<bd \\
xx^k&<yy^k\\
x^{k+1}&<y^{k+1} 🤌\\
\end{align*}
$$

### 6. (b) 

> Prove that if $x<y$ and $n$ is odd, then $x^n<y^n.$

Let's separate into three separate cases, $0\le x<y, x<y\le0,$ and $x<0<y.$

For the first case, from (a), we already know $x^n<y^n$ for all $n.$

Please note (5-ii: if $a>b \implies -b>-a$)

For the second case, from (5-ii) we know from $x<y\le0$ that $-x>-y\ge0$ which means $0 \le -y < -x$ so $-y^n<-x^n$ from (a) and from that (and that n is odd and sign preserving) we know $x^n<y^n$ (by (5-ii)) again.

Finally, because odd $n$ preserve sign, from $x<0\le y$ we know $x^n<0\le y.$ 🤌

### 6. (c) 

> Prove that if $x^n=y^n$ and $n$ is odd, then $x=y.$ 

Assume for the sake of contradiction that $x \neq y$.

By the trichotomy law, either $x-y \in \mathbb{P}$ or $y-x \in \mathbb{P}.$

Then, $x<y$ or $x>y$.

For the first case, note from (b) that $x^n<y^n$ contradicting $x^n=y^n.$

For the second case, reverse $x$ and $y$ and notice the same contradiction. 🤌

> 6. (d) Prove that if $x^n=y^n$ and $n$ is even, then $x=y$ or $x=-y.$

If $x,y\ge 0$ then $x<y,x>y,$ or $x=y$. If $x<y$ then by (a) $x^n<y^n$ contradicting our premise. Likewise from (a) for $x>y.$ Therefore $x=y.$

On the other hand, if $x,y<0,$ well then $-x,-y>0,$ and repeated application of the same logic has $x=y.$

So far we've proven $x=y$ for both negative and positive $x,y$. The last possibility is $x=-y.$ WLOG assume $x<0<y.$ Since $n$ is even, $x^n=(-|x|)^n=|x|^n$ and $y^n=y^n.$

From $x^n=y^n, |x|^n = y^n.$ Since $|x|,y>0$, by our first case $|x|=y.$

Therefore $x=-|x|=-y.$ 🤌

## 7. 

> Prove that if $0<a<b,$ then
> 
> $$
> a < \sqrt{ab} < \frac{a+b}{2} < b.
> $$
>
> Notice that the inequality $\sqrt{ab} \le (a+b)/2$ holds for all $a,b\ge0.$ A generalization of this fact occurs in Problem 2-22.

**Case 1** $a < \sqrt{ab}$

$$
\begin{align*}
a &< b \\
aa &< ab \\
a^2 &< ab \\
\sqrt{a^2} &< \sqrt{ab} \\
a &< \sqrt{ab} \\
\end{align*}
$$

Next, 

$$
\begin{align*}
a+b &< 2b \\
\frac{a+b}{2} &< b.
\end{align*}
$$

Finally,

$$
\begin{align*}
(b-a)^2&>0 \\
b^2-2ab+a^2&>0 \\
b^2+a^2&>2ab \\
b^2+a^2+2ab&>4ab \\
(a+b)^2&>4ab \\
a+b&>2\sqrt{ab} \\
\frac{a+b}{2}&>\sqrt{ab} 🤌 \\
\end{align*}
$$

## 8.

> Although the basic properties of inequalities were stated in terms of the collection $\mathbb{P}$ of all positive numbers, and $<$ was defined in terms of $\mathbb{P},$ this procedure can be reversed. Suppose that P10-P12 are replaced by
> 
> (P'10) For any numbers $a$ and $b$ one, and only one, of the following holds:
> 
> $$
> \begin{align*}
> (i)&\quad a = b \\
> (ii)&\quad a < b \\
> (iii)&\quad b < a \\
> \end{align*}
> $$
> 
> (P'11) For any numbers $a,b,$ and $c,$ if $a<b$ and $b<c,$ then $a<c.$
> 
> (P'12) For any numbers $a,b,$ and $c,$ if $a<b$, then $a+c<b+c.$
> 
> (P'13) For any numberse $a,b,$ and $c,$ if $a<b$ and $0<c,$ then $ac<bc.$
> 
> Show that P10-P12 can be deduced as theorems.

(P10) Trichotomy law: For every number $a$, one and only one: i. $a=0,$, ii. $a \in \mathbb{P}$, iii. $-a \in \mathbb{P}$ 

Take $\mathbb{P}$ to be all numbers satisfying the quality $x>0.$

Suppose $b=0$. Then from (P'10) either $a=b=0,a<b=0$ and so $-a>b=0$ and therefore $-a \in \mathbb{P}$ or $a>b=0$ and so $a \in \mathbb{P}.$

(P11) Closure under addition: If $a \in \mathbb{P}$ and $b \in \mathbb{P},$ then $a+b \in \mathbb{P}$

We know both $a \in \mathbb{P}$ and $b \in \mathbb{P}$ by definition.

$$
\begin{align*}
0 &< b \\
a &< a + b \\
\end{align*}
$$

Since $a > 0$ by supposition, $a+b>0$ so $a+b \in \mathbb{P}$


(P12) Closure under multiplication: If $a \in \mathbb{P}$ and $b \in \mathbb{P},$ then $a\cdot b \in \mathbb{P}$

$$
\begin{align*}
0 &< b \\
a\cdot0 &< a\cdot b \\
0 &< ab \\
\end{align*}
$$

## 9.

> Express each of the following with at least one less pair of absolute value signs.

### 9. (i) 

> $|\sqrt2+\sqrt3-\sqrt5+\sqrt7|.$

$\sqrt{(\sqrt2+\sqrt3-\sqrt5+\sqrt7)^2}$ 🤌

If you want to nitpick, we know that the only negative term above is $\sqrt5$ and since $\sqrt7>\sqrt5\to\sqrt7-\sqrt5>0.$ The other terms are positive, so the whole statement is positive, so we can just simplify to 

$$
\sqrt2+\sqrt3-\sqrt5+\sqrt7
$$

but that's being too square.

### 9. (ii) 

> $|(|a+b|-|a|-|b|)|.$

we observe from Theorem 1 that

$$
\begin{align*}
|a+b|\le|a|+|b| \\
|a+b|-|a|-|b|\le0\\
\end{align*}
$$

Therefore the equation within the outer absolute value bars is always negative or 0 and can rewrite it as $-(|a+b|-|a|-|b|).$ 🤌

### 9. (iii) 

> $|(|a+b|+|c|-|a+b+c|)|.$

Taking $d=a+b$ we can rewrite out equation as $|(|d|+|c|-|d+c|)|.$ We then observe the same fact as before, but in this case we know $|d|+|c|\ge|d+c|$ so can conclude the number is always positive and can rewrite it as $|d|+|c|-|d+c|$ and thence substitute back our original terms $|a+b|+|c|-|a+b+c|.$ 🤌

### 9. (iv) 

> $|x^2-2xy+y^2|.$

The statement reduces to $(x-y)^2$ which is always positive. 🤌

### 9. (v) 

> $|(|\sqrt2+\sqrt3|-|\sqrt5-\sqrt7|)|.$

We know both $\sqrt 2,\sqrt 3 \in \mathbb{P}$ so

$$
|(\sqrt2+\sqrt3-|\sqrt5-\sqrt7|)|
$$

Furthermore

$$
\begin{align*}
\sqrt7&>\sqrt5 \\
0&>\sqrt5-\sqrt7 \\
0&<-(\sqrt5-\sqrt7) \\
0&<-\sqrt5+\sqrt7 \\
\end{align*}
$$

So

$$
|(\sqrt2+\sqrt3-|\sqrt5-\sqrt7|)|\\
|(\sqrt2+\sqrt3-|-(\sqrt7-\sqrt5)|)|\\
|(\sqrt2+\sqrt3+(\sqrt7-\sqrt5))|\\
\sqrt2+\sqrt3+\sqrt7-\sqrt5 \quad 🤌\\
$$

## 10. 

> Express each of the following without absolute value signs, treating various cases separately when necessary.

### 10. (i) 

> $|a+b|-|b|.$

$$
|a+b|-|b|=
\begin{cases}
a,      & a+b\ge0,b\ge0\\
a+2b,   & a+b\ge0,b<0\\
-(a+2b) & a+b<0,  b\ge0\\
-a      & a+b<0,  b<0
\end{cases}
$$

### 10. (ii) 

> $|(|x|-1)|.$

Let $S=|x|-1$

$$
|(|x|-1)|=
\begin{cases}
x-1,    & x\ge1 \\
x+1,    & 0\le x<1\\
-x+1,   & x<0
\end{cases}
$$

### 10. (iii) 

> $|x|-|x^2|.$

$$
|x|-|x^2| =
\begin{cases}
x-x^2,      & x\ge0 \\
-x-x^2,     & x<0 \\
\end{cases}
$$

### 10. (iv) 

> $a-|(a-|a|)|.$

$$
a-|(a-|a|)|=
\begin{cases}
a,      & a \ge 0\\
3a,     & a < 0
\end{cases}
$$

## 11.

> Find all numbers $x$ for which

### 11. (i) 

> $|x-3| = 8.$

$$
x=\{-5\}\cup\{11\}
$$

### 11. (ii) 

> $|x-3|<8.$

$$
-5<x<11
$$

### 11. (iii) 

> $|x+4|<2.$

$$
-6<x<-2
$$

### 11. (iv) 

> $|x-1|+|x-2|>1.$

$$
x<0\text{ or }x>2.
$$

### 11. (v) 

> $|x-1|+|x+1|<2.$

No x.

### 11. (vi) 

> $|x-1|+|x+1|<1.$

No x.

### 11. (vii) 

> $|x-1| \cdot |x+1| = 0.$

$$
x=-1\text{ or }x=1
$$

### 11. (viii)

> $|x-1|\cdot|x+2|=3.$

When $x>1$ or $x<-2$ both sides of the number line behave identically as $(x-1)(x+2)=3$ for which the solutions are $\frac{-1\pm\sqrt{21}}{2}.$ Between that range there are no real solutions.

## 12.

> Prove the following:

### 12. (i) 

> $|xy|=|x|\cdot|y|.$

$$
\begin{align*}
|xy|^2=(xy)^2=x^2\cdot y^2=(|x|\cdot|y|)^2
\end{align*}
$$

Since both $|xy|$ and $|x|,|y|\ge0$ this shows equivalence.

### 12. (ii) 

> $|\frac{1}{x}|=\frac{1}{|x|},$ if $x \neq 0.$ Best to remember what $|x|^{-1}$ is.

$$
\begin{align*}
|\frac{1}{x}|\cdot|x|&=|\frac{1}{x}\cdot x| \tag{by (i)} \\
&=|1| \\
&=1 \\
\end{align*}
$$

Now divide both sides by $|x|.$ 🤌

NB: This proof is a little unsatisfying. It seems to leave some logic on the table.

> 12. (iii) $\frac{|x|}{|y|}=|\frac{x}{y}|,$ if $y\neq0.$

$$
\begin{align*}
\frac{|x|}{|y|} &= |x|\cdot|y^-1| \\
&= |xy^-1| \tag{i} \\
&= |x\cdot\frac{1}{y}| \\
&= |\frac{x}{y}| \quad 🤌\\
\end{align*}
$$

> 12. (iv) $|x-y|\le|x|+|y|.$ (Give a very short proof)

$$
|x-y|=|x+(-y)|\le|x|+|-y|=|x|+|y| \quad  🤌
$$

> 12. (v) $|x|-|y|\le|x-y|.$ (A very short proof is possible, if you write things in the right way.) 

$$
\begin{align*}
|(x-y)+y|&\le|x-y|+|y| \\
|(x-y)+y|-|y|&\le|x-y|+|y|-|y| \\
|x|-|y|&\le|x-y| 🤌\\
\end{align*}
$$

> 12. (vi) $|(|x|-|y|)|\le|x-y|.$ (Why does this follow immediately from (v)?)

Since $|x-y|=|y-x|,$ swapping $x,y$ from (v) we get

$$
\begin{align*}
|y|-|x|&\le|y-x|=|x-y|\\
-(|x|-|y|)&\le|x-y|\\
\end{align*}
$$

Since both $|x|-|y|$ and its negative are less than $|x-y|,$ we know $|(|x|-|y|)|\le|x-y|.$ 🤌

> 12. (vii) $|x+y+z|\le|x|+|y|+|z|.$ Indicate when equality holds and prove your statement.

Supposing $y=y+z$ and applying the triangle inequality we see $|x+(y+z)|\le|x|+|y+z|.$ However, applying the triangle inequality to $|y+z|$ we see again $|y+z|\le|y|+|z|$ and so we can susbstitute the right hand of the inequality again to derive

$$
|x+y+z|\le|x|+|y|+|z| 🤌
$$

Equality holds when all three terms have the same sign.

If all three terms have the same sign then equality holes.

Forward cases:

**Case 1a**:  $x,y,z\ge0.$ Then $|x+y+z|=x+y+z=|x|+|y|+|z|$

**Case 1b**:  $x,y,z\le0.$ Then $|x+y+z|=-(x+y+z)=(-x)+(-y)+(-z)=|x|+|y|+|z|.$

Backward cases, look at the triangle inequality applications:

- If $|y+z|=|y|+|z|,$ then $y,z$ have the same sign.
- If $|x+(y+z)|=|x|+|y+z|$ then $x,y+z$ have the same sign.

Therefore equality holds when if and only if three terms have the same sign. 🤌

> 13. The maximum of two numbers $x$ and $y$ is denoted by $\mathrm{max}(x,y).$ Thus $\mathrm{max}(-1,3)=\mathrm{max}(3,3)=3$ and $\mathrm{max}(-1,-4)=\mathrm{max}(-4,-1)=-1.$ The minimum of $x$ and $y$ is denoted by $\mathrm{min}(x,y).$ Prove that
> 
> $$
> \begin{align}
> \mathrm{max}(x,y)&=\frac{x+y+|y-x|}{2}, \\
> \mathrm{min}(x,y)&=\frac{x+y-|y-x|}{2}. \\
> \end{align}
> $$

For (1), take $y>x.$ Then $|y-x|=y-x$ and

$$
\frac{x+y+|y-x|}{2}=\frac{x+y+y-x}{2}=\frac{2y}{2}=y
$$

Since $|y-x|=|-(y-x)|$ for $x>y$ reverse $x$ and $y$ 🤌.

For (2), take $y>x.$ Then the same property holds and

$$
\frac{x+y-|y-x|}{2}=\frac{x+y-(y-x)}{2}=\frac{x+y-y+x)}{2}=\frac{2x}{2}=x
$$

The same argument holds in the case $x>y. 🤌$

> Derive a formula for $\mathrm{max}(x,y,z)$ and $\mathrm{min}(x,y,z),$ using, for example
>
> $$
> \mathrm{max}(x,y,z)=\mathrm{max}(x,\mathrm{max}(y,z))
> $$

Taking $y = \mathrm{max}(y,z)$ we start with

$$
\mathrm{max}(y,z) = \frac{y+z+|y-z|}{2}
$$

And then substitute

$$
\begin{align*}
\mathrm{max}(x,y,z)=\mathrm{max}(x,\mathrm{max}(y,z))&=\frac{x+y+|y-x|}{2}, \\
&=\frac{x+\frac{y+z+|y-z|}{2}+|\frac{y+z+|y-z|}{2}-x|}{2} \\
&=\frac{1}{2}(x+\frac{y+z+|y-z|}{2}+|\frac{y+z+|y-z|}{2}-x|) \\
&=\frac{1}{2}(\frac{2x}{2}+\frac{y+z+|y-z|}{2}+|\frac{y+z+|y-z|}{2}-\frac{2x}{2}|) \\
&=\frac{1}{2}(\frac{2x+y+z+|y-z|}{2}+\frac{|y+z+|y-z|-2x|}{2}) \\
&=\frac{1}{2}(\frac{2x+y+z+|y-z|+|y+z+|y-z|-2x|}{2}) \\
&=\frac{2x+y+z+|y-z|+|y+z+|y-z|-2x|}{4} \\
\end{align*}
$$

Hideous. 🤮. But 🤌 nonetheless.

> 14. (a) Prove that $|a|=|-a|.$ (The trick is to not become comfused by too many cases. First prove the statement for $a\ge0.$ Why is it then obvious for $a\le0$?)

**Case 1** If $a\ge0,$ then $|a|=a$ and $|-a|=a$ and therefore $|a|=|-a|$ for $a\ge0.$

**Case 2** If $a<0,$ then $|a|=-a$ and $|-a|=-a$ and therefore $|a|=|-a|$ for $a<0.$
 
> 14. (b) Prove that $-b\le a\le b$ if and only if $|a|\le b.$ In particular, it follows that $-|a|\le a \le|a|.$

For $|a|\le b \implies -b \le a \le b,$ we know that $|a|\ge0$ so $b\ge0.$

Supposing $a\ge0,$ then

$$
0 \le a \le b \\
-b \le -a \le 0 \\
-b \le -a \le 0 \le a \le b \\
-b \le a \le b\\
$$

And supposing $a\le0,$ then because $|a|\le b=-a\le b$

$$
0 \le -a \le b \\
-b \le a \le 0 \\
-b \le a \le 0 \le -a \le b \\
-b \le a \le  b\\
$$

That's for the forward case, now reversing, for $-b \le a \le b\implies|a|\le b ,$ assume for contradiction that $|a|>b.$

Now assume $a\ge0.$ Then $a>b,$ contradicting $-b \le a \le b.$

Assume again that $a<0.$ Then $-a>b$ and $a<-b,$ contradicting $-b \le a \le b.$ 🤌

Furthermore, to prove $-|a|\le a \le |a|,$ assume $b=|a|.$ Then $|a|\le b=|a|.$ And $-|a|\le a \le |a|.$

> 14. (c) Use this fact to give a new proof that $|a+b|\le|a|+|b|.$

First, take any $a,b.$ From (b) we can sum these inequalities:

$$
\begin{align*}
-|a| &\le a &\le|a| \\
-|b| &\le b &\le|b| \\
\hline
-(|a|+|b|)&\le a+b &\le|a|+|b|
\end{align*}
$$

Now, taking $a=a+b$ and $b=|a|+|b|$ we can see that $|a+b|=|a|\le b = |a|+|b|.$ 🤌

> 15. Prove that if $x$ and $y$ are not both $0,$ then
> 
> $$
> x^2+xy+y^2>0 \\
> x^4+x^3y+x^2y^2+xy^3+y^4>0
> $$
> 
> Hint: Use Problem 1.

First, from 1(iv) we know $x^3-y^3=(x-y)(x^2+xy+y^2)$ and so

$$
x^2+xy+y^2=\frac{x^3-y^3}{x-y}
$$

From 6(b) we know that $x^n<y^n$ if $x<y$ so the numerator and denominator are always the same sign and thus $x^2+xy+y^2>0.$ If $x=y\ne0,$ the statement reduces to $3x^2$ which is always greater than 0 because $x^2$ is positive.

For, $x^4+x^3y+x^2y^2+xy^3+y^4$ the same proof applies using problem 1(v) since it's simply $\frac{x^5-y^5}{x-y}.$

> 16. (a) Show that
> 
> $$
> \begin{align*}
> (x+y)^2=x^2+y^2&\quad\text{only when }x=0\text{ or }y=0, \\
> (x+y)^3=x^3+y^3&\quad\text{only when }x=0\text{ or }y=0\text{ or }x=-y.
> \end{align*}
> $$

If

$$
x^2+y^2=(x+y)^2=x^2+2xy+y^2
$$

Then $xy=0$ so either $x=0$ or $y=0.$ If

$$
x^3+y^3=(x+y)^3=x^3+3x^2y+3xy^2+y^3
$$

Then $3x^2y+3xy^2=3xy(x+y)=0$ so $x=0$ or $y=0$ or $x=-y.$

> 16. (b) Using the fact that
> 
> $$
> x^2+2xy+y^2=(x+y)^2\ge0,
> $$
> 
> show that $4x^2+6xy+4y^2>0$ unless $x$ and $y$ are both $0.$

We know from $x^2+2xy+y^2=(x+y)^2\ge0$ that 

$$
4x^2+8xy+4y^2\ge0
$$

Assume for contradiction that we know

$$
4x^2+6xy+4y^2\le0
$$

Subtracting these we find $xy\ge0.$ If neither $x$ nor $y$ is $0,$ then we must have $2xy>0.$ But then x and y share the same sign so $ 4x^2+6xy+4y^2>0,$ contradicting our assumption.

Further, if only one of x or y i s0, then $x^2>0$ or $y^2>0,$ so the equation remains positive.

> 16. (c) Use part (b) to find out when $(x+y)^4=x^4+y^4.$

If

$$
x^4+y^4=(x+y)^4=x^4+4x^3y+6x^2y^2+4xy^3+y^4
$$

then

$$
4x^3y+6x^2y^2+4xy^3=xy(4x^2+6xy+4y^2)=0
$$

So either $x=0,y=0,$ or $4x^2+6xy+4y^2=0,$ but we know from (b) $4x^2+6xy+4y^2=0$ only when $x=y=0,$ but then $x^4+y^4=0,$ so $x=0$ or $y=0$ but not both. 🤌

> 16. (d) Find out when $(x+y)^5=x^5+y^5.$ Hint: From the assumption $(x+y)^5=x^5+y^5$ you should be able to derive the equation $x^3+2x^2y+2xy^2+y^3=0,$ if $xy\neq0.$ This implies $(x+y)^3=x^2y+xy^2=xy(x+y).$

First, note that

$$
(x+y)^5=x^5+y^5=x^5+5x^4y+10x^3y^2+10x^2y^3+5xy^4+y^5
$$

So we know

$$
\begin{align*}
5x^4y+10x^3y^2+10x^2y^3+5xy^4&=0\\
5xy(x^3+2x^2y+2xy^2+y^3)&=0
\end{align*}
$$

So by the same argument we've been dealing with, either $xy=0$ or our long ass equation is $0$.

But that thing looks familiar, right? Like

$$
(x+y)^3=x^3+3x^2y+3xy^2+y^3
$$

Oh wow, wild, why don't we subtract them? They're asking for subtraction right? 🏓

$$
x^2y+xy^2=xy(x+y)
$$

Look at that thing! That seems like it tells us some wild shit right? Like the fact that $xy=0$ or $x=-y$, right?

Yeah, so $x=0,y=0,$ or $x=-y.$ 🤌


> You should now be able to make a good guess as to when $(x+y)^n=x^n+y^n;$ The proof is contained in Problem 11-63.

I don't know man, probably $x=0,y=0,$ or $x=-y.$ I'll prove it later.

> 17. (a) Find the smallest possible value of $2x^2-3x+4$. Hint: "Complete the square. ⏹"

$$
\begin{align*}
2x^2-3x+4\\
2(x^2-\frac{3}{2}x+2)\\
2(x^2-\frac{3}{2}x+\frac{9}{16}-\frac{9}{16}+2)\\
2((x-\frac{3}{4})^2-\frac{9}{16}+2)\\
2(x-\frac{3}{4})^2-\frac{9}{8}+4\\
2(x-\frac{3}{4})^2-\frac{9}{8}+\frac{32}{8}\\
2(x-\frac{3}{4})^2+\frac{23}{8}\\
\end{align*}
$$

Since $2(x-\frac{3}{4})^2$ is at least zero, the smallest value is $\frac{23}{8}$ when $x=\frac{3}{4}$

> 17. (b) Find the smallest possible value of $x^2-3x+2y^2+4y+2.$

$$
\begin{align*}
x^2-3x&+2y^2+4y+2 \\
x^2-3x+\frac{9}{4}-\frac{9}{4}&+2(y^2+2y+1) \\
(x-\frac{3}{4})^2&+2(y+1)^2-\frac{9}{4}
\end{align*}
$$

Since the first 2 terms are always positive the smallest possible value is $-\frac{9}{4}.$

> 17. (c) Find the smallest possible value of $x^2+4xy+5y^2-4x-6y+7.$

$$
\begin{align*}
x^2+4xy&+5y^2-4x-6y+7\\
x^2+4xy-4x&+5y^2-6y+7\\
x^2+4(y-1)x&+5y^2-6y+7\\
[x+2(y-1)]^2&+5y^2-6y+7-4(y-1)^2 \\
[x+2(y-1)]^2&+5y^2-6y+7-4(y^2-2y+1) \\
[x+2(y-1)]^2&+5y^2-6y+7-4y^2+8y-4 \\
[x+2(y-1)]^2&+y^2+2y+3 \\
[x+2(y-1)]^2&+y^2+2y+1-1+3 \\
[x+2(y-1)]^2&+(y+1)^2+2
\end{align*}
$$

By the same logic we see this one to be at least 2.

> 18. (a) Suppose that $b^2-4c\ge0.$ Show that the numbers
>
> $$
> \frac{-b+\sqrt{b^2-4c}}{2},\quad\frac{-b-\sqrt{b^2-4c}}{2}
> $$
>
> both satisfy the equation $x^2+bx+c=0.$

$$
\begin{align*}
(x-\frac{-b+\sqrt{b^2-4c}}{2})(x-\frac{-b-\sqrt{b^2-4c}}{2})&=0\\
x^2-\frac{-b+\sqrt{b^2-4c}}{2}x-\frac{-b-\sqrt{b^2-4c}}{2}x+(\frac{-b+\sqrt{b^2-4c}}{2}\cdot\frac{-b-\sqrt{b^2-4c}}{2})&=0\\
x^2- \frac{-b+\sqrt{b^2-4c}-b-\sqrt{b^2-4c}}{2}x+(\frac{(-b+\sqrt{b^2-4c})(-b-\sqrt{b^2-4c})}{4})&=0 \\
x^2- \frac{-2b}{2}x+\frac{b^2+b\sqrt{b^2-4c}-b\sqrt{b^2-4c}-(b^2-4c)}{4}&=0 \\
x^2+bx+\frac{4c}{4}&=0 \\
x^2+bx+c&=0 \\
\end{align*}
$$

> 18. (b) Suppose $b^2-4c<0.$ Show that there are no numbers $x$ satisfying $x^2+bx+c=0$

I mean, I guess I could rederive the formula but why man?

$$
\begin{align*}
x^2+bx+c&=0\\
x^2+bx+\frac{b^2}{4}-\frac{b^2}{4}+c&=0\\
(x+\frac{b}{2})^2-\frac{b^2}{4}+c&=0\\
(x+\frac{b}{2})^2&=\frac{b^2}{4}-c\\
(x+\frac{b}{2})^2&=\frac{b^2-4c}{4}\\
x+\frac{b}{2}&=\pm\sqrt{\frac{b^2-4c}{4}}\\
x+\frac{b}{2}&=\pm\frac{\sqrt{b^2-4c}}{2}\\
x&=-\frac{b}{2}\pm\frac{\sqrt{b^2-4c}}{2}\\
x&=\frac{-b\pm\sqrt{b^2-4c}}{2}\\
\end{align*}
$$

Since this is the form, if $b^2-4c<0,$ then the square root of it is complex and no real number exists to satisfy.

> 18. (c) Use this fact to give another proof that if $x$ and $y$ are not both $0,$ then $x^2+xy+y^2>0.$

$$
\begin{align*}
x&=\frac{-y\pm\sqrt{y^2-4y^2}}{2}\\
&=\frac{-y\pm\sqrt{-3y^2}}{2}\\
\end{align*}
$$

At this point, however, we see that $y^2\ge0$ and so $-3y^2<0$ if $y\ne0.$ Since no $x$ satisfies the equation when $y\ne0,$ for $x^2+xy+y^2=0,$ both $x=y=0.$ Since we're told this is not the case, the equation can never equal zero.

> 18. (d) For which numbers $\alpha$ is it true that $x^2+\alpha xy+y^2>0$ whenever $x$ and $y$ are not both $0$?

Since we're looking for when there are no real solutions (i.e., roots, when the equation equals $0$), we want to find

$$
\begin{align*}
b^2-4c&<0\\
(\alpha y)^2-4y^2&<0\\
\alpha^2 y^2-4y^2&<0\\
(\alpha^2-4)y^2&<0\\
\end{align*}
$$
    
Since we know $y^2\ne0,$ it's always positive so we need to know

$$
\begin{align*}
\alpha^2-4&<0\\
\alpha^2&<4\\
\alpha&<\pm2\\
|\alpha|&<2\\
\end{align*}
$$

Therefore, it is always positive when $|\alpha|<2.$

> 18. (e) Find the smallest possible value of $x^2+bx+c$ and of $ax^2+bx+c,$ for $a>0.$

Well,

$$
\begin{align*}
x^2+bx+c=\left(x+\frac{b}{2}\right)^2+c-\frac{b^2}{4}\ge c-\frac{b^2}{4}
\end{align*}
$$

and since $ax^2+bx+c=c-\frac{b^2}{4}$ when $x=-\frac{b}{2}$ the minimum value is $c-\frac{b^2}{4}.$ And since

$$
\begin{align*}
ax^2+bx+c&=a\left(x^2+\frac{b}{a}x+\frac{c}{a}\right)\\
&=a\left(x^2+\frac{b}{a}x+\frac{c}{a}\right)\\
&=a\left(x^2+\frac{b}{a}x+\frac{b^2}{4a^2}-\frac{b^2}{4a^2}+\frac{c}{a}\right)\\
&=a\left(\left(x+\frac{b}{2a}\right)^2-\frac{b^2}{4a^2}+\frac{c}{a}\right)\\
\end{align*}
$$

We can see that when $x=-\frac{b}{2a}$ the smallest value is

$$
a\left(\frac{c}{a}-\frac{b^2}{4a^2}\right)=c-\frac{b^2}{4a}
$$

> 19. The fact that $a^2\ge0$ for all numbers $a,$ elementary as it may seem, is nevertheless the fundamental idea upon which most important inequalities are ultimately based. The great-granddaddy of all inequalities is the *Schwarz inequality:*
> 
> $$
> x_1y_1+x_2y_2\le\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}
> $$
> 
> (A more general form occurs in Problem 2-21.) The three proofs of the Schwarz inequality outlined below have only one thing in common—their reliance on the fact that $a^2\ge0$ for all $a.$
>
> 19. (a) Prove that if $x_1=\lambda y_1$ and $x_2=\lambda y_2$ for some $\lambda \ge0,$ then equality holds in the Schwarz inequality. Prove the same thing if $y_1=y_2=0$. Now suppose that $y_1$ and $y_2$ are not both $0,$ and that there is no number $\lambda$ such that $x_1=\lambda y_1$ and that $x_2=\lambda y_2.$ Then
>
> $$
> 0 < (\lambda y_1-x_1)^2+(\lambda y_2-x_2)^2=\lambda^2({y_1}^2+{y_2}^2)-2\lambda(x_1y_1+x_2y_2)+({x_1}^2+{x_2}^2).
> $$
>
> Using problem 18, complete the proof of the Schwarz inequality.

If $x_1=\lambda y_1,x_2=\lambda y_2,$

$$
\begin{align*}
x_1y_1+x_2y_2&\le\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}\\
\lambda y_1y_1+\lambda y_2y_2&\le\sqrt{{(\lambda y_1)}^2+{(\lambda y_2)}^2}\sqrt{{y_1}^2+{y_2}^2}\\
\lambda ({y_1}^2+{y_2}^2)&\le\sqrt{\lambda^2({y_1}^2+{y_2}^2)}\sqrt{{y_1}^2+{y_2}^2}\\
\lambda ({y_1}^2+{y_2}^2)&\le\lambda(\sqrt{{y_1}^2+{y_2}^2})^2\\
\lambda ({y_1}^2+{y_2}^2)&=\lambda({y_1}^2+{y_2}^2)\\
\end{align*}
$$

If $y1=y2=0$

$$
\begin{align*}
x_1y_1+x_2y_2&\le\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}\\
x_10+x_20&\le\sqrt{{x_1}^2+{x_2}^2}\sqrt{{0}^2+{0}^2}\\
0&\le\sqrt{{x_1}^2+{x_2}^2}\cdot0\\
0&=0
\end{align*}
$$

Finally, if $x$ is not a multiple of $y$ and $y\ne0,$ then we know

$$
\begin{align*}
0 &< (\lambda y_1-x_1)^2+(\lambda y_2-x_2)^2
\end{align*}
$$

because squared numbers are always positive, and there is no $\lambda$ for which both terms cancel out. So

$$
\begin{align*}
0 &< (\lambda y_1-x_1)^2+(\lambda y_2-x_2)^2\\
0 &< (\lambda^2 {y_1}^2-2\lambda y_1x_1+{x_1}^2)+(\lambda^2 {y_2}^2-2\lambda y_2x_2+{x_2}^2)\\
0 &< ({y_1}^2+{y_2}^2)\lambda^2-2(y_1x_1+y_2x_2)\lambda+({x_1}^2+{x_2}^2) \\
\end{align*}
$$

this is the form Spivak was looking for, from here we know that the equation is always positive, so it has no real roots. This means $b^2-4ac<0$ so from the quadratic form we've found for $a\lambda^2+b\lambda+c$ we know

$$
\begin{align*}
(-2(y_1x_1+y_2x_2))^2-4({y_1}^2+{y_2}^2)({x_1}^2+{x_2}^2)&<0\\
4(y_1x_1+y_2x_2)^2-4({y_1}^2+{y_2}^2)({x_1}^2+{x_2}^2)&<0\\
4(y_1x_1+y_2x_2)^2&<4({y_1}^2+{y_2}^2)({x_1}^2+{x_2}^2)\\
(y_1x_1+y_2x_2)^2&<({y_1}^2+{y_2}^2)({x_1}^2+{x_2}^2)\\
y_1x_1+y_2x_2&<\sqrt{{y_1}^2+{y_2}^2}\sqrt{{x_1}^2+{x_2}^2}\\
\end{align*}
$$

And there we have the Schwarz inequality which holds equality when our two pairs are scaled equally by some $\lambda$ or $y_1=y_2=0$ and inequality otherwise. 🤌

> 19. (b) Prove the Schwarz inequality by using $2xy\le x^2+y^2$ (how is this derived?) with
>
> $$
> x=\frac{x_i}{\sqrt{{x_1}^2+{x_2}^2}},\quad y=\frac{y_i}{\sqrt{{y_1}^2+{y_2}^2}}
> $$
>
> first for $i=1$ and then for $i=2.$

First, observe that 

$$
\begin{align*}
(x-y)^2&\ge0\\
x^2-2xy+y^2&\ge0\\
x^2+y^2&\ge2xy\\
2xy&\le x^2+y^2\\
\end{align*}
$$

From this we can sum inequalities for our terms

$$
\begin{align*}
2\left(\frac{x_1}{\sqrt{{x_1}^2+{x_2}^2}}\cdot\frac{y_1}{\sqrt{{y_1}^2+{y_2}^2}}\right)
&\le
\left(\frac{x_1}{\sqrt{{x_1}^2+{x_2}^2}}\right)^2+\left(\frac{y_1}{\sqrt{{y_1}^2+{y_2}^2}}\right)^2\\
2\left(\frac{x_2}{\sqrt{{x_1}^2+{x_2}^2}}\cdot\frac{y_2}{\sqrt{{y_1}^2+{y_2}^2}}\right)
&\le
\left(\frac{x_2}{\sqrt{{x_1}^2+{x_2}^2}}\right)^2+\left(\frac{y_2}{\sqrt{{y_1}^2+{y_2}^2}}\right)^2\\
\hline
2\left(\frac{x_1}{\sqrt{{x_1}^2+{x_2}^2}}\cdot\frac{y_1}{\sqrt{{y_1}^2+{y_2}^2}}\right)+
2\left(\frac{x_2}{\sqrt{{x_1}^2+{x_2}^2}}\cdot\frac{y_2}{\sqrt{{y_1}^2+{y_2}^2}}\right)
&\le
\left(\frac{x_1}{\sqrt{{x_1}^2+{x_2}^2}}\right)^2+\left(\frac{y_1}{\sqrt{{y_1}^2+{y_2}^2}}\right)^2+
\left(\frac{x_2}{\sqrt{{x_1}^2+{x_2}^2}}\right)^2+\left(\frac{y_2}{\sqrt{{y_1}^2+{y_2}^2}}\right)^2\\
2\left(\frac{x_1y_1}{\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}}+\frac{x_2y_2}{\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}}\right)
&\le
\frac{{x_1}^2}{{x_1}^2+{x_2}^2}+\frac{{y_1}^2}{{y_1}^2+{y_2}^2}+ \frac{{x_2}^2}{{x_1}^2+{x_2}^2}+\frac{{y_2}^2}{{y_1}^2+{y_2}^2}\\
2\frac{x_1y_1+x_2y_2}{\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}}
&\le
\frac{{x_1}^2+{x_2}^2}{{x_1}^2+{x_2}^2}+\frac{{y_1}^2+{y_2}^2}{{y_1}^2+{y_2}^2}\\
2\frac{x_1y_1+x_2y_2}{\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}} &\le 1+1\\
2\frac{x_1y_1+x_2y_2}{\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}} &\le 2\\
\frac{x_1y_1+x_2y_2}{\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}} &\le 1\\
x_1y_1+x_2y_2&\le \sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}
\end{align*}
$$

And there we have our Schwarz inequality. 🤌

> 19. (c) Prove the Schwarz inequality by first proving that
>
> $$
> ({x_1}^2+{x_2}^2)({y_1}^2+{y_2}^2)=(x_1y_1+x_2y_2)^2+(x_1y_2-x_2y_1)^2.
> $$

If we start with the right it will be easier to see where the negative term comes in

$$
\begin{align*}
(x_1y_1+x_2y_2)^2+(x_1y_2-x_2y_1)^2&=(x_1^2y_1^2+2x_1x_2y_1y_2+x_2^2y_2^2) + (x_1^2y_2^2-2x_1x_2y_1y_2+x_2^2y_1^2)\\
&={x_1}^2{y_1}^2+{x_2}^2{y_2}^2 + {x_1}^2{y_2}^2+{x_2}^2{y_1}^2\\
&={x_1}^2{y_1}^2+{x_2}^2{y_1}^2+{x_2}^2{y_2}^2 + {x_1}^2{y_2}^2\\
&={y_1}^2({x_1}^2+{x_2}^2)+{y_2}^2 ({x_1}^2+ {x_2}^2)\\
&=({y_1}^2+{y_2}^2)({x_1}^2+{x_2}^2)\\
\end{align*}
$$

We know $(x_1y_2-x_2y_1)^2\ge0$ so by dropping it from our equality we get an inequality

$$
\begin{align*}
(x_1y_1+x_2y_2)^2&\le({x_1}^2+{x_2}^2)({y_1}^2+{y_2}^2)\\
x_1y_1+x_2y_2&\le\sqrt{{x_1}^2+{x_2}^2}\sqrt{{y_1}^2+{y_2}^2}\\
\end{align*}
$$

And we're back to our inequality. 🤌

> 19. (d) Deduce, from each of these three proofs, that equality holds only when $y_1=y_2=0$ or when there is a number $\lambda\ge0$ such that $x_1=\lambda y_1$ or $x_2=\lambda y_2$

We already did this. Refer to part (a). Both the right and left terms multiply to zero when $y_1=y_2=0$ and if the x's and y's are scaled check part (a).

> 20. Prove that if
>
> $$
> |x-x_0|<\frac{\epsilon}{2} \text{ and } |y-y_0|<\frac{\epsilon}{2},
> $$
>
> then
>
> $$
> |(x+y)-(x_0+y_0)|<\epsilon\\
> |(x-y)-(x_0-y_0)|<\epsilon
> $$

If we add the formulas
$$
\begin{align*}
|x-x_0|+|y-y_0|&<\frac{\epsilon}{2}+\frac{\epsilon}{2}\\
|x-x_0|+|y-y_0|&<\epsilon,
\end{align*}
$$

From $|a+b|\le|a|+|b|$ we know that 


$$
\begin{align*}
|(x+y)-(x_0+y_0)|&\le|x-x_0|+|y-y_0|<\epsilon\\
|(x+y)-(x_0+y_0)|&<\epsilon\\
\end{align*}
$$

Now if we take from the previous equation $y'=-y$ and $y_0'=-y_0$ we get

$$
\begin{align*}
|(x+y')-(x_0+y_0')|&<\epsilon\\
|(x+(-y))-(x_0+(-y_0))|&<\epsilon\\
|(x-y)-(x_0-y_0)|&<\epsilon\\
\end{align*}
$$

> 21. Prove that if
>
> $$
> |x-x_0|<\min\left(\frac{\epsilon}{2(|y_0|+1)},1\right)\quad\text{ and }\quad|y-y_0|<\frac{\epsilon}{2(|x_0|+1)}
> $$
>
> then $|xy-x_0y_0|<\epsilon.$
>
> The notation "min" was defined in Problem 13, but the formula provided by that problem is irrelevant at the moment; the first inequality in the hypothesis just means that
>
> $$
> |x-x_0|<\frac{\epsilon}{2(|y_0|+1)}\quad\text{ and }\quad|x-x_0|<1
> $$
>
> at one point in the argument you will need the first inequality, and at another point you will need the second. One more word of advice: since the hypotheses only provide information about $x-x_0$ and $y-y_0,$ it is almost a foregone conclusion that the proof will depend upon writing $xy-x_0y_0$ in a way that involves $x-x_0$ and $y-y_0.$

We can start by rearranging our goal statement looking for a bound with the triangle inequality and then get a strict upper bound on our supposition.

$$
\begin{align*}
|xy-x_0y_0|=|x(y-y_0)+y_0(x_0-x)|&=|x(y-y_0)+y_0(x-x_0)|\\
|xy-x_0y_0|=|x(y-y_0)+y_0(x-x_0)|&\le|x|\cdot|y-y_0|+|y_0|\cdot|x-x_0|\\
|xy-x_0y_0|&\le|x|\cdot|y-y_0|+|y_0|\cdot|x-x_0|\\
|xy-x_0y_0|&<|x|\cdot\frac{\epsilon}{2(|x_0|+1)}+|y_0|\cdot|x-x_0|\\
|xy-x_0y_0|&<|x|\cdot\frac{\epsilon}{2(|x_0|+1)}+|y_0|\cdot\frac{\epsilon}{2(|y_0|+1)}\\
\end{align*}
$$

Then we can look for a bound on $|x|,$ and make it stricter with $|x-x_0|<1$ from our supposition again.

$$
\begin{align*}
|x|=|x-x_0+x_0|&\le|x-x_0|+|x_0|\\
|x|&\le|x-x_0|+|x_0|\\
|x|&<1+|x_0|=|x_0|+1\\
\end{align*}
$$

So we can tighten our mainline bound and do some rearranging

$$
\begin{align*}
|xy-x_0y_0|&<|x|\cdot\frac{\epsilon}{2(|x_0|+1)}+|y_0|\cdot\frac{\epsilon}{2(|y_0|+1)}\\
|xy-x_0y_0|&<(|x_0|+1)\cdot\frac{\epsilon}{2(|x_0|+1)}+|y_0|\cdot\frac{\epsilon}{2(|y_0|+1)}\\
|xy-x_0y_0|&<\frac{\epsilon}{2}+|y_0|\cdot\frac{\epsilon}{2(|y_0|+1)}\\
|xy-x_0y_0|&<\frac{\epsilon}{2}+|y_0|\cdot\frac{1}{|y_0|+1}\cdot\frac{\epsilon}{2}\\
|xy-x_0y_0|&<\frac{\epsilon}{2}+\frac{|y_0|}{|y_0|+1}\cdot\frac{\epsilon}{2}\\
\end{align*}
$$

Next, because $\frac{b}{b+1}<1,$ we know $a\cdot\frac{b}{b+1}<a,$ so

$$
\begin{align*}
|xy-x_0y_0|&<\frac{\epsilon}{2}+\frac{|y_0|}{|y_0|+1}\cdot\frac{\epsilon}{2}<\frac{\epsilon}{2}+\frac{\epsilon}{2}\\
|xy-x_0y_0|&<\frac{\epsilon}{2}+\frac{\epsilon}{2}\\
|xy-x_0y_0|&<\epsilon \quad 🤌
\end{align*}
$$

> 22. Prove that if $y_0\ne0$ and
>
> $$
> |y-y_0|<\min\left(\frac{|y_0|}{2},\frac{\epsilon|y_0|^2}{2}\right),
> $$
>
> then $y\ne0$ and
>
> $$
> \left|\frac{1}{y}-\frac{1}{y_0}\right|<\epsilon.
> $$

Since

$$
\begin{align*}
|y_0|=|y_0-y+y|&\le|y|+|y_0-y|=|y|+|y-y_0|\\
|y_0|&\le|y|+|y-y_0|\\
|y_0|-|y-y_0|&\le|y|\\
|y|&\ge|y_0|-|y-y_0|
\end{align*}
$$

we have a lower bound on $|y|$ and using our supposition we get

$$
\begin{align*}
|y|&\ge|y_0|-|y-y_0|\\
|y|&>|y_0|-\frac{|y_0|}{2}\\
|y|&>\frac{|y_0|}{2}\\
\end{align*}
$$

Since $y_0\ne0$ we have $\frac{|y_0|}{2}>0$ and transitively $|y|>0$ and so $y\ne0,$ proving one of our goals. Next, if we rewrite our second goal 

$$
\left|\frac{1}{y}-\frac{1}{y_0}\right|=\frac{|y_0-y|}{|y|\cdot|y_0|}=\frac{|y-y_0|}{|y|\cdot|y_0|}=|y-y_0|\cdot\frac{1}{|y|\cdot|y_0|}\\
$$

We can get a strict upper bound on our goal term.

$$
\begin{align*}
\left|\frac{1}{y}-\frac{1}{y_0}\right|=|y-y_0|\cdot\frac{1}{|y|\cdot|y_0|}&<\frac{\epsilon|y_0|^2}{2}\cdot\frac{1}{|y|\cdot|y_0|}\\
\left|\frac{1}{y}-\frac{1}{y_0}\right|&<\frac{\epsilon|y_0|^2}{2}\cdot\frac{1}{|y|\cdot|y_0|}\\
\left|\frac{1}{y}-\frac{1}{y_0}\right|&<\epsilon\cdot\frac{|y_0|}{2}\cdot\frac{1}{|y|}\\
\end{align*}
$$

Now let's look at our right term from the bound we established earlier

$$
\begin{align*}
|y|&>\frac{|y_0|}{2}\\
2|y|&>|y_0|\\
\frac{2|y|}{|y_0|}&>1\\
\frac{2}{|y_0|}&>\frac{1}{|y|}\\
\frac{1}{|y|}&<\frac{2}{|y_0|}&\\
\end{align*}
$$

So we can make another inequality bounding pinch in that larger goal inequality.

$$
\begin{align*}
\left|\frac{1}{y}-\frac{1}{y_0}\right|&<\epsilon\cdot\frac{|y_0|}{2}\cdot\frac{1}{|y|}\\
\left|\frac{1}{y}-\frac{1}{y_0}\right|&<\epsilon\cdot\frac{|y_0|}{2}\cdot\frac{2}{|y_0|}\\
\left|\frac{1}{y}-\frac{1}{y_0}\right|&<\epsilon\\
\end{align*}
$$


And badda bing badda boom. 🤌

> 23. Replace the question marks in the following statement by expressions involving $\epsilon,x_0,$ and $y_0$ so that the conclusion will be true:
> If $y_0\ne0$ and
>
> $$
> |y-y_0|<?\quad\text{ and }\quad|x-x_0|<?
> $$
>
> then $y\ne0$ and
>
> $$
> \left|\frac{x}{y}-\frac{x_0}{y_0}\right|<\epsilon.
> $$
>
> This problem is trivial in the sense that its solution follows from Problems 21 and 22 with almost no work at all (notice that $x/y=x\cdot1/y$ ). The crucial point is not to become confused; decide which of the two problems should be used first, and don't panic if your answer looks unlikely.

We want to use the previous 2 problems to cash out the $|y|$ reciprocals to the preconditions for our multiplication $|x\frac{1}{y}-x_0\frac{1}{y_0}|\le\epsilon$

This means we need

$$
\left|\frac{1}{y}-\frac{1}{y_0}\right|<\frac{\epsilon}{2(|x_0|+1)}.\tag{1}
$$

So if we take

$$
|y-y_0|<\min\left(\frac{|y_0|}{2},\frac{\epsilon|y_0|^2}{2}\right),\tag{2}
$$

and plug (1) in for the $\epsilon$ in (2) we get there.
$$
\begin{align*}
|y-y_0|&<\min\left(\frac{|y_0|}{2},\frac{\epsilon|y_0|^2}{2}\right)\\
|y-y_0|&<\min\left(\frac{|y_0|}{2},\frac{\frac{\epsilon}{2(|x_0|+1)}|y_0|^2}{2}\right)\\
|y-y_0|&<\min\left(\frac{|y_0|}{2},\frac{\epsilon}{2(|x_0|+1)}\cdot\frac{|y_0|^2}{2}\right)\\
|y-y_0|&<\min\left(\frac{|y_0|}{2},\frac{\epsilon|y_0|^2}{4(|x_0|+1)}\right)\\
\end{align*}
$$

Then we can evaluate to our expected condition using the logic from 23.

$$
\begin{align*}
\left|\frac{x}{y}-\frac{x_0}{y_0}\right|&=\left|x\cdot\frac{1}{y}-x_0\cdot\frac{1}{y_0}\right|\\
&=\left|x\left(\frac{1}{y}-\frac{1}{y_0}\right)+\frac{1}{y_0}(x-x_0)\right| \le \left|x\left(\frac{1}{y}-\frac{1}{y_0}\right)\right|+\left|\frac{1}{y_0}(x-x_0)\right| \\
&\le |x|\cdot\left|\frac{1}{y}-\frac{1}{y_0}\right|+\frac{1}{|y_0|}\cdot|x-x_0|
\end{align*}
$$




> 24. Let us agree for definiteness, and $a_1+\cdots+a_n$ will denote
>
> $$
> a_1+(a_2+(a_3+\cdots+(a_{n-2}+(a_{n-1}+a_n)))\cdots).
> $$
>
> Thus $a_1+a_2+a_3$ denotes $a_1+(a_2+a_3),$ and $a_1+a_2+a_3+a_4$ denotes $a_1+(a_2+(a_3+a_4)),$ etc.
>
> 24. (a) Prove that
>
> $$
> (a_1+\cdots+a_k)+a_{k+1}=a_1+\cdots+a_{k+1}.
> $$
>
> Hint: Use induction on $k.$

> 24. (b) Prove that if $n\ge k,$ then
>
> $$
> (a_1+\cdots+a_k)+(a_{k+1}+\cdots+a_n)=a_1+\cdots+a_n.
> $$
>
> Hint: Use part (a) to give a proof by induction on $k.$

> 24. (c) Let $s(a_1,...,a_k)$ be some sum formed from $a_1,...,a_k.$ Show that
>
> $$
> s(a_1,...,a_k)=a_1+\cdots+a_k.
> $$
>
> Hint: There must be two sums $s'(a_1,...,a_l)$ and $s''(a_{l+1},...,a_k)$ such that
>
> $$
> s(a_1,...,a_k)=s'(a_1,...,a_l)+s''(a_{l+1},...,a_k).
> $$

> 25. Suppose we interpret "number" to mean either $0$ or $1,$ and $+$ and $\cdot$ to be the operations defined by the following two tables.
> 
> $$
> \begin{array}{c|cc}
> + & 0 & 1\\\hline
> 0 & 0 & 1\\
> 1 & 1 & 0
> \end{array}
> \quad\quad
> \begin{array}{c|cc}
> \cdot & 0 & 1\\\hline
> 0 & 0 & 0\\
> 1 & 0 & 1
> \end{array}
> $$
> 
> Check that properties P1-P9 all hold, even though $1+1=0.$