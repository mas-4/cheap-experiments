- [Axler LADR 2a](#axler-ladr-2a)
  - [p. 30](#p-30)
    - [Commutativity](#commutativity)
    - [Associativity](#associativity)
    - [Additive Identity](#additive-identity)
    - [Additive Inverse](#additive-inverse)
    - [Multiplicative Identity](#multiplicative-identity)
    - [Distributive Properties](#distributive-properties)
  - [p. 33](#p-33)
  - [p. 33](#p-33-1)
- [Exercises](#exercises)
  - [1.](#1)
  - [2.](#2)
  - [3.](#3)
  - [4.](#4)
    - [4. (a)](#4-a)
    - [4. (b)](#4-b)
  - [5.](#5)
  - [6.](#6)
  - [7.](#7)
    - [7. (a)](#7-a)
    - [7. (b)](#7-b)
- [8.](#8)
  - [9.](#9)
  - [10.](#10)
  - [11.](#11)
  - [12.](#12)
  - [13.](#13)
  - [14.](#14)
  - [15.](#15)
  - [16.](#16)
  - [17.](#17)
  - [18.](#18)
  - [19.](#19)
  - [20.](#20)

# Axler LADR 2a

## p. 30

> Verify $\mathcal{P}(\mathbb{F})$ is a vector space over $\mathbb{F}$.

Assume

$$
\begin{align*}
p_1(x) &= a_0 + a_1x + a_2x^2 + \cdots + a_mx^m \\
p_2(x) &= b_0 + b_1x + b_2x^2 + \cdots + b_mx^m \\
p_3(x) &= c_0 + c_1x + c_2x^2 + \cdots + c_mx^m
\end{align*}
$$

### Commutativity

$$
\begin{align*}
p_1(x)+p_2(x)&=(a_0+a_1x+a_2x^2+\cdots+a_mx^m)+(b_0+b_1x+b_2x^2+\cdots+b_mx^m) \\
&=(a_0+b_0)+(a_1+b_1)x+(a_2+b_2)x^2+\cdots+(a_m+b_m)x^m \\
&=(b_0+a_0)+(b_1+a_1)x+(b_2+a_2)x^2+\cdots+(b_m+a_m)x^m \\
p_2(x)+p_1(x)&=(b_0+b_1x+b_2x^2+\cdots+b_mx^m)+(a_0+a_1x+a_2x^2+\cdots+a_mx^m)\\
\end{align*}
$$

### Associativity

For addition,

$$
\begin{align*}
(p_1(x)+p_2(x))+p_3(x)&=((a_0+a_1x+a_2x^2+\cdots+a_mx^m)+(b_0+b_1x+b_2x^2+\cdots+b_mx^m))+(c_0+c_1x+c_2x^2+\cdots+c_mx^m)\\
&=((a_0+b_0)+(a_1+b_1)x+(a_2+b_2)x^2+\cdots+(a_m+b_m)x^m)+(c_0+c_1x+c_2x^2+\cdots+c_mx^m)\\
&=(a_0+b_0+c_0)+(a_1+b_1+c_1)x+(a_2+b_2+c_2)x^2+\cdots+(a_m+b_m+c_m)x^m) \\
p_1(x)+(p_2(x)+p_3(x))&=(a_0+a_1x+a_2x^2+\cdots+a_mx^m)+((b_0+b_1x+b_2x^2+\cdots+b_mx^m)+(c_0+c_1x+c_2x^2+\cdots+c_mx^m))\\
&=(a_0+a_1x+a_2x^2+\cdots+a_mx^m)+((b_0+c_0)+(b_1+c_1)x+(b_2+c_2)x^2+\cdots+(b_m+c_m)x^m) \\
&=(a_0+b_0+c_0)+(a_1+b_1+c_1)x+(a_2+b_2+c_2)x^2+\cdots+(a_m+b_m+c_m)x^m) \\
\end{align*}
$$

For scalar multiplication,

$$
\begin{align*}
(\lambda \mu) p(x) &= (\lambda \mu) (a_0    + a_1x + a_2x^2         + \cdots + a_mx^m) \\
&= (\lambda \mu) a_0 + (\lambda \mu)a_1x    + (\lambda \mu)a_2x^2   + \cdots + (\lambda \mu)a_mx^m) \\
&= (\lambda \mu a_0) + (\lambda \mu a_1)x   + (\lambda \mu a_2)x^2  + \cdots + (\lambda \mu a_m)x^m) \\
&= \lambda (\mu a_0) + \lambda (\mu a_1)x   + \lambda (\mu a_2)x^2  + \cdots + \lambda (\mu a_m)x^m) \\
&= \lambda (\mu a_0 + \mu a_1x              + \mu a_2x^2            + \cdots + \mu a_mx^m) \\
\lambda (\mu p(x)) &= \lambda (\mu (a_0     + a_1x + a_2x^2         + \cdots + a_mx^m)) \\
\end{align*}
$$

### Additive Identity

Let $0(x) = 0 + 0x + 0x^2 + \cdots + 0x^m$, then

$$
\begin{align*}
0(x) + p(x) &= (0 + 0x + 0x^2 + \cdots + 0x^m) + (a_0 + a_1x + a_2x^2 + \cdots + a_mx^m) \\
&= (0+a_0) + (0+a_1)x + (0+a_2)x^2 + \cdots + (0+a_m)x^m \\
&= a_0 + a_1x + a_2x^2 + \cdots + a_mx^m \\
\end{align*}
$$

### Additive Inverse

For any polynomial $p(x) = a_0 + a_1x + a_2x^2 + \cdots + a_mx^m \in \mathcal{P}(\mathbb{F})$, 

define $-p(x) = (-a_0) + (-a_1)x + (-a_2)x^2 + \cdots + (-a_m)x^m$.

Then:

$$
\begin{align*}
p(x) + (-p(x)) &= (a_0 + a_1x + a_2x^2 + \cdots + a_mx^m) + ((-a_0) + (-a_1)x + (-a_2)x^2 + \cdots + (-a_m)x^m) \\
&= (a_0 + (-a_0)) + (a_1 + (-a_1))x + (a_2 + (-a_2))x^2 + \cdots + (a_m + (-a_m))x^m \\
&= 0 + 0x + 0x^2 + \cdots + 0x^m \\
&= 0(x)
\end{align*}
$$

Since each coefficient $a_i$ has additive inverse $-a_i$ in the field $\mathbb{F}$, we have $a_i + (-a_i) = 0$ for all $i$.

### Multiplicative Identity

$$
\begin{align*}
1p(x) &= 1(a_0 + a_1x + a_2x^2 + \cdots + a_mx^m) \\
&= (1 \cdot a_0) + (1 \cdot a_1)x + (1 \cdot a_2)x^2 + \cdots + (1\cdot a_m)x^m \\
&= a_0 + a_1x + a_2x^2 + \cdots + a_mx^m \\
\end{align*}
$$

### Distributive Properties

$$
\begin{align*}
\lambda (p_1(x) + p_2(x)) &= \lambda (a_0 + a_1x + a_2x^2 + \cdots + a_mx^m + b_0 + b_1x + b_2x^2 + \cdots + b_mx^m) \\
&= \lambda ((a_0+b_0)+(a_1+b_1)x+(a_2+b_2)x^2+\cdots+(a_m+b_m)x^m) \\
&= \lambda (a_0+b_0)+\lambda(a_1+b_1)x+\lambda(a_2+b_2)x^2+\cdots+\lambda(a_m+b_m)x^m) \\
&= (\lambda a_0+ \lambda b_0)+(\lambda a_1+\lambda b_1)x+(\lambda a_2+\lambda b_2)x^2+\cdots+(\lambda a_m+\lambda b_m)x^m) \\
&= \lambda a_0 + \lambda a_1x + \lambda a_2x^2 + \cdots + \lambda a_mx^m + \lambda b_0 + \lambda b_1x + \lambda b_2x^2 + \cdots + \lambda b_mx^m \\
\lambda p_1(x) + \lambda p_2(x) &= \lambda (a_0 + a_1x + a_2x^2 + \cdots + a_mx^m) + \lambda (b_0 + b_1x + b_2x^2 + \cdots + b_mx^m) \\
\end{align*}
$$

and

$$
\begin{align*}
(\lambda + \mu)p(x) &= (\lambda + \mu) (a_0 + a_1x + a_2x^2 + \cdots + a_mx^m) \\
&= (\lambda + \mu) a_0 + (\lambda + \mu)a_1x + (\lambda + \mu)a_2x^2 + \cdots + (\lambda + \mu)a_mx^m \\
&= \lambda a_0 + \mu a_0 + a_1\lambda x + a_1\mu x + \lambda a_2x^2 + \mu a_2x^2 + \cdots + \lambda a_mx^m+ \mu a_mx^m \\
&= (\lambda a_0 + \lambda a_1 x + \lambda a_2x^2 + \cdots + \lambda a_mx^m) + (\mu a_0 + a_1\mu x + \mu a_2x^2 + \cdots + \mu a_mx^m) \\
\lambda p(x) + \mu p(x) &= \lambda (a_0 + a_1x + a_2x^2 + \cdots + a_mx^m) + \mu (a_0 + a_1x + a_2x^2 + \cdots + a_mx^m)
\end{align*}
$$

## p. 33 

> Verify that if some vectors are removed from a linearly independent list, the remaining list is also linearly independent.

We know that for a linearly independent list $v_1,...,v_m \in V$ $a_1v_1 + \cdots + a_mv_m$ if and only if $a_1 = \cdots = a_m = 0$. If this is the case, then it is also the case for $v_1,...,v_{m-1}$ that $a_1v_1 + \cdots + a_{m-1}v_{m-1} = 0$  if and only if $a_1 = \cdots = a_{m-1} = 0$.

## p. 33 

> Verify that the list $(2,3,1),(1,-1,2),(7,3,c)$ is linearly dependent in $\mathbb{F}^3$ if and only if $c=8$.

We will examine the system of equations by adding them

$$
\begin{align*}
2a_1 + a_2 + 7a_3 &= 0 \tag{1}\\
3a_1 - a_2 + 3a_3 &= 0 \tag{2}\\
a_1 + 2a_2 + ca_3 &= 0 \tag{3}\\
\hline
6a_1 + 2a_2 + (10+c)a_3 &= 0 \tag{4}
\end{align*}
$$

Solving for $a_2$ in equation 1 yields $a_2 = -2a_1 -7a_3$ which we will substitute in (2)

$$
\begin{align*}
3a_1 - a_2 + 3a_3 &= 0 \tag{2}\\
3a_1 - (-2a_1-7a_3) + 3a_3 &= 0 \\
3a_1 + 2a_1 + 7a_3 + 3a_3 &= 0 \\
5a_1 + 10a_3 &= 0 \\
5a_1 &= -10a_3 \\
a_1 &= -\frac{10a_3}{5} \\
a_1 &= -2a_3 \tag{5}
\end{align*}
$$

Substituting into (1) we get

$$
\begin{align*}
2a_1 + a_2 + 7a_3 &= 0 \tag{1}\\
2(-2a_3) + a_2 + 7a_3 &= 0 \\
-4a_3 + a_2 + 7a_3 &= 0 \\
3a_3 + a_2 &= 0 \\
a_2 &= -3a_3 \tag{6}
\end{align*}
$$

And substituting (5) and (6) in (4)

$$
\begin{align*}
6a_1 + 2a_2 + (10+c)a_3 &= 0 \tag{4} \\
6(-2a_3) + 2(-3a_3) + (10+c)a_3 &= 0 \\
-12a_3 - 6a_3 + (10+c)a_3 &= 0  \\
-18a_3 + (10+c)a_3 &= 0  \\
-18a_3 + 10a_3 + ca_3 &= 0  \\
-18a_3 + 10a_3 + ca_3 &= 0 \\
-8a_3 + ca_3 &= 0  \\
ca_3 &= 8a_3 \\
c &= 8 \\
\end{align*}
$$

So for the list to be linearly dependent, that is, where the trivial solution $a_1 \neq a_2 \neq a_3 \neq 0$, $c = 8$.


# Exercises

## 1. 

> Find a list of four distinct vectors in $F^3$ whose span equals $\{(x,y,z) \in \mathbb{F}^3 : x + y + z = 0 \}$.

$(0,0,0),(1,-1,0),(-1,1,0),(0,1,-1)$

## 2. 

> Prove or give a counterexample: If $v_1,v_2,v_3,v_4$ spans $V$, then the list $v_1-v_2,v_2-v_3,v_3-v_4,v_4$ also spans $V$.

Let's consider rewriting the original set in terms of the others.

$$
\begin{align*}
v_4 &= v_4 \\
v_3 &= (v_3 - v_4) + v_4 \\
v_2 &= (v_2 - v_3) + v_3 = (v_2 - v_3) + (v_3 - v_4) + v_4 \\
v_1 &= (v_1 - v_2) + v_2 = (v_1 - v_2) + (v_2 - v_3) + (v_3 - v_4) + v_4 \\
\end{align*}
$$

So now, taking

$$
\begin{align*}
u_1 &= v_1 - v_2 \\
u_2 &= v_2 - v_3 \\
u_3 &= v_3 - v_4 \\
u_4 &= v_4
\end{align*}
$$

We can see that

$$
\begin{align*}
v_1 &= 1u_1 + 1u_2 + 1u_3 + 1u_4 \\
v_2 &= 0u_1 + 1u_2 + 1u_3 + 1u_4 \\
v_3 &= 0u_1 + 0u_2 + 1u_3 + 1u_4 \\
v_4 &= 0u_1 + 0u_2 + 0u_3 + 1u_4
\end{align*}
$$

So, since the original list is a linear combination of the second, they are the same span.

## 3. 

> Suppose $v_1,...,v_m$ is a list of vectors in $V$. For $k \in \{1,...,m\}$, let $w_k = v_1 + \cdots + v_k$. Show that $\mathrm{span}(v_1,...,v_m) = \mathrm{span}(w_1,...,w_m)$.

Well, if $w_k = v_1 + \cdots v_k$, then $w_m = v_1 + \cdots v_m$. Now, if every $w_k$ is a linear combination of the preceding $v_1+\cdots+v_k$ on up to $w_m = v_1 + \cdots v_m$, then every $w_k$ is in the $\mathrm{span}(v_1,...,v_m)$.

On the other hand, every $v_k$ can be found as a linear combination from $\mathrm{span}(w_1,...,w_m)$ by setting each $a_{k-1}$ in the linear combination of $a_1w_1 + \cdots a_kw_k$ to 0 except for $a_k = 1$ and $a_{k-1} = -1$ so that $v_k = w_k - w_{k-1}$.

## 4. 

### 4. (a) 

> Show that a list of length one in a vector space is linearly independent if and only if the vector in that list is not 0.

If the vector in the list is $\{0\}$, for $a \cdot v = 0$ any $a$ will do, so the list is not linearly independent.

On the other hand, for any other vector $v \neq 0 \in V$, the only way for $a \cdot v = 0$ is for $a = 0$.

### 4. (b)

> Show that a list of length two in a vector space is linearly independent if and only if neither of the two vectors is a scalar multiple of the other.

If $v_1,v_2 \in V$ are scalar multiples of each other, so that there exists some $b$ for which $bv_1 = v_2$, then for $a_1 = -1, a_2 = 1$ we can find $-1bv_1 + 1v_2 = 0$ showing that there exists some $a_1 \neq a_2 \neq 0$ for which $a_1v_1 + a_2v_2 = 0$, showing it not to be linearly independent.

On the other hand, if neither is a scalar multiple of the other, and are linearly dependent, then there must be some $a_1 \neq 0$ or $a_2 \neq 0$ for which $a_1v_1 + a_2v_2 = 0$. However, if $a_1 \neq 0$, $0v_1 + a_2v_2 = 0$ shows that $a_2$ must be 0, and the same is true for $a_1$ if $a_2 = 0$. And if $a_1 \neq 0$ and $a_2 \neq 0$, then

$$
\begin{align*}
a_1v_1 + a_2v_2 &= 0
a_1v_1 &= -a_2v_2
v_1 &= -\frac{a_2}{a_1}v_2
\end{align*}
$$

So we see that $v_1$ is in fact a scalar multiple of $v_2$, namely $-\frac{a_2}{a_1}$ thus proving, that if neither is a scalar multiple of the other, they are linearly independent.

## 5. 

> Find a number $t$ such that $(3,1,4),(2,-3,5),(5,9,t)$ is not linearly independent in $\mathbb{R}^3$.

We're going to do substitution here

$$
\begin{align*}
3a_1 + 2a_2 + 5a_3 &= 0 \tag{1}\\
1a_1 - 3a_2 + 9a_3 &= 0 \tag{2}\\
4a_1 + 5a_2 + ta_3 &= 0 \tag{3}\\
\end{align*}
$$

Next solve for $a_1$ in (2)

$$
\begin{align*}
a_1 = 3a_2 - 9a_3 \tag{5}
\end{align*}
$$

Plug (5) in (1)

$$
\begin{align*}
3(3a_2 - 9a_3) + 2a_2 + 5a_3 &= 0 \\
9a_2 - 27a_3 + 2a_2 + 5a_3 &= 0 \\
11a_2 - 22a_3 &= 0 \\
11a_2 &= 22a_3 \\
a_2 &= 2a_3 \tag{6}\\
\end{align*}
$$

Plug (5) and (6) in (3)

$$
\begin{align*}
4(3a_2-9a_3)+5a_2+ta_3 &= 0 \\
4(3(2a_3)-9a_3)+5(2a_3)+ta_3 &= 0 \\
4(6a_3-9a_3)+10a_3+ta_3 &= 0 \\
4(-3a_3)+10a_3+ta_3 &= 0 \\
-12a_3+10a_3+ta_3 &= 0 \\
-2a_3+ta_3 &= 0 \\
(t-2)a_3 &= 0 \\
t-2 &= 0 \\
t &= 2
\end{align*}
$$

So in conclusion, when $t=2$, the set is not linearly independent.

## 6. 

> Show that the list (2,3,1),(1,-1,2),(7,3,c) is linearly dependent in $\mathbb{F}^3$ if and only if c = 8

Please refer to the answer to the same question from p.33 above.

## 7.

### 7. (a) 

> Show that if we think of $\mathbb{C}$ as a vector space over $\mathbb{R}$, then the list $1+i,1-i$ is linearly independent.

We can represent $\mathbb{C}$ as a vector space in $\mathbb{R}^2$ so that $i+1,1-i$ are vectors $(1,1),(1,-1)$. As such, trying to solve for 0:

$$
\begin{align*}
1a_1 + 1a_2 &= 0 \\
1a_1 - 1a_2 &= 0
\end{align*}
$$

There is clearly no set $(a_1,a_2)$ for which both equations hold true besides $a_1=a_2=0$, so $1+i,1-i$ is linearly independent in $\mathbb{R}^2$.

### 7. (b)

>  Show that if we think of $\mathbb{C}$ as a vector space over $\mathbb{C}$, then the list $1+i,1-i$ is linearly dependent.

In $\mathbb{C}$ we have the vectors $(1+i),(1-i)$ so that

$$
(1+i)a_1 + (1-i)a_2 = 0
$$

If we solve for a_1 and a_2:

$$
\begin{align*}
(x_1+iy_1)(1+i) + (x_2+iy_2)(1-i) &= 0 \\
(x_1+ix_1+iy_1-y_1) + (x_2-ix_2+iy_2+y_2) &= 0 \\
x_1 - y_1 + x_2 + y_2 + ix_1 + iy_1 - ix_2 + iy_2 &= 0 \\
(x_1 - y_1) + (x_2 + y_2) + i(x_1 + y_1 - x_2 + y_2) &= 0 \\
(x_1 - y_1) + (x_2 + y_2) + i((x_1 + y_1) + (y_2 - x_2) &= 0 \\
\end{align*}
$$

We now have two systems of equations

$$
\begin{align*}
(x_1 - y_1) + (x_2 + y_2) &= 0 \tag{1} \\
(x_1 + y_1) + (y_2 - x_2) &= 0 \tag{2} \\
\end{align*}
$$

Setting $a_1=1=1+0i$ and solving in (1)

$$
\begin{align*}
1 + (x_2 + y_2) &= 0 \\
(x_2 + y_2) &= -1 \\
y_2 &= -1 -x_2\\
\end{align*}
$$

And plugging that into (2)

$$
\begin{align*}
1 + (-1 - x_2 - x_2) &= 0 \\
1 - 1 - x_2- x_2 &= 0 \\
-2x_2 &= 0
x_2 &= 0 
\end{align*}
$$

And plugging that back in for $x_2$ we have $y_2 = -1 - 0 = -1$, so $a_2=0-1i$. Now substituting back into our original equation

$$
\begin{align*}
1(1+i) - i(1-i) &= 0 \\
1+i - (i+1) &= 0 \\
1 + i - i - 1 &= 0 \\
\end{align*}
$$

# 8. 

> Suppose $v_1,v_2,v_3,v_4$ is linearly independent in $V$. Prove that the list $v_1-v_2,v_2-v_3,v_3-v_4,v_4$ is also linearly independent.

Suppose some $a_1,a_2,a_3,a_4$ exist which do not equal 0 such that a linear combination is possible.

$$
\begin{align*}
a_1(v_1-v_2)+a_2(v_2-v_3)+a_3(v_3-v_4)+a_4v_4 &= 0 \\
a_1v_1-a_1v_2+a_2v_2-a_2v_3+a_3v_3-a_3v_4+a_4v_4 &= 0 \\
a_1v_1+(a_2-a_1)v_2+(a_3-a_2)v_3+(a_4-a_3)v_4&= 0 \\
\end{align*}
$$

Since $v_1,v_2,v_3,v_4$ are already linearly independent, their coefficients must be zero for this linear combination to equal 0.

## 9. 

> Prove or give a counterexample: If $v_1,v_2,...,v_m$ is a linearly independent list of vectors in $V$, then $5v_1-4v_2,v_2,v_3,...,v_m$ is linearly independent.

For $5v_1-4v_2,v_2,v_3,...,v_m$ to be linearly independent it suffices to show that the new vectors can be rearranged in the form of the old vectors.

$$
\begin{align*}
a_1(5v_1-4v_2)+a_2v_2+a_3v_3+\cdots+v_m &= 0 \\
5a_1v_1-4a_1v_2+a_2v_2+a_3v_3+\cdots+v_m &= 0 \\
5a_1v_1+a_2v_2-4a_1v_2+a_3v_3+\cdots+v_m &= 0 \\
(5a_1)v_1+(a_2-4a_1)v_2+a_3v_3+\cdots+v_m &= 0 \\
\end{align*}
$$

But now we see the same form as

$$
a_1v_1+a_2v_2+a_3v_3+\cdots+v_m = 0
$$

where we know the coefficients must be 0. So in the new linear combination we know $5a_1 = a_2-4a_1 = a_3 = \cdots = a_m = 0$. And therefore the new system is linearly independent.

## 10. 

> Prove or give a counterexample: if $v_1,v_2,...,v_m$ is a linearly independent list of vectors in $V$ and $\lambda \in \mathbb{F}$ with $\lambda \neq 0$, then $\lambda v_1,\lambda v_2,...,\lambda v_m$ is linearly independent.

We can see a similar pattern from the previous proof.

$$
\begin{align*}
a_1 \lambda v_1 + a_2 \lambda v_2 + \cdots + a_m \lambda v_m &= 0\\
(a_1 \lambda) v_1 + (a_2 \lambda) v_2 + \cdots + (a_m \lambda) v_m &= 0\\
\end{align*}
$$

Having arranged the linear combination to match the linear combination of the original set, we can see that any set of $a_1,a_2,...,a_m$ must simply be scaled from the original set, which would necessitate $a_1 = a_2 = \cdots = a_m = 0$ and so the new set must be linearly independent.

## 11. 

> Prove or give a counterexample: If $v_1,...,v_m$ and $w_1,...,w_m$ are linearly independent lists of vectors in $V$, then the list $v_1+w_1,...,v_m+w_m$ is linearly independent.

An obvious counter example is $(1,0),(0,1)$ for $v_1,v_2$ and $(0,1),(1,0)$ for $w_1,w_2$ with $a_1=1,a_2=-1$ so that

$$
\begin{align*}
1((1,0)+(0,1))+(-1)((0,1)(1,0)) &= 0 \\
1(1,1)+(-1)(1,1) &= 0 \\
(1,1)-(1,1) &= 0 \\
\end{align*}
$$

## 12. 

> Suppose $v_1,...,v_m$ is linearly independent in $V$ and $w \in V$. Prove that if $v_1+w,...,v_m+w$ is linearly dependent, then $w \in \mathrm{span}(v_1,...,v_m)$.

We can take

$$
\begin{align*}
a_1(v_1+w)+a_2(v_2+w)+\cdots+a_m(v_m+w) &= 0\\
a_1v_1+a_1w+a_2v_2+a_2w+\cdots+a_mv_m+a_mw &= 0 \\
a_1v_1+a_2v_2+\cdots+a_mv_m+a_1w+a_2w+\cdots+a_mw &= 0\\
a_1v_1+a_2v_2+\cdots+a_mv_m+(a_1+a_2+\cdots+a_m)w &= 0\\
\end{align*}
$$


There are two possibilities, either the series $a_1+a_2+\cdots+a_m = 0$ or $a_1+a_2+\cdots+a_m \neq 0$. If it does not equal zero, we can see

$$
\begin{align*}
a_1v_1+a_2v_2+\cdots+a_mv_m&=-(a_1+a_2+\cdots+a_m)w \\
\frac{-a_1}{a_1+\cdots+a_m}v_1+\frac{-a_2}{a_1+\cdots+a_m}v_2+\cdots+\frac{-a_m}{a_1+\cdots+a_m}v_m&=w\\
\end{align*}
$$

Which shows that $w$ is equal to a linear combination of the original set, and thus $w \in \mathrm{span}(v_1,...,v_m)$. On the other hand, if the series sums to 0, then


$$
\begin{align*}
a_1v_1+a_2v_2+\cdots+a_mv_m&=-(a_1+a_2+\cdots+a_m)w\\
a_1v_1+a_2v_2+\cdots+a_mv_m&=0\\
\end{align*}
$$

But in that case we see our original set, which is linearly independent, and thus $a_1=a_2=\cdots=a_m=0$, thus contradicting our claim that the new set is linearly dependent.

## 13. 

> Suppose $v_1,..,v_m$ is linearly independent in $V$ and $w \in V$. Show that $v_1,...,v_m,w$ is linearly independent $\iff w \notin \mathrm{span}(v_1,...,v_m)$.

If $w \in \mathrm{span}(v_1,...,v_m)$, then

$$
\begin{align*}
a_1v_1+a_2v_2+\cdots+a_mv_m&=w \\
a_1v_1+a_2v_2+\cdots+a_mv_m + (-1)w &= 0 \\
\end{align*}
$$

But, by the definition of linear independence, for the linear combination to of all the vectors in the span to equal 0, $a_1 = \cdots = a_m = a_w = 0$, but $-1 \neq 0$, thus if $w \in \mathrm{span}(v_1,...,v_m)$, then $v_1,...,v_m,w$ is not linearly independent.

On the other hand, if $w \notin \mathrm{span}(v_1,...,v_m)$, then by the definition of linear independence, adding it to the span it will remain linearly independent.

## 14. 

> Suppose $v_1,...,v_m$ is a list of vectors in $V$. For $k \in \{1,...,m\}$, let $w_k = v_1 + \cdots + v_k$. Show that the list $v_1,...,v_m$ is linearly independent if and only if the list $w_1,...,w_m$ is linearly independent.

Suppose $v_1,...,v_m$ is linearly independent and $w_1,...,w_m$ is linearly dependent. Now consider any linear combination of $w_1,...,w_m$ summing to 0 where $a_1,...,a_m$ are not all 0.

$$
\begin{align*}
a_1w_1 + a_2w_2 + \cdots a_mw_m &= 0 \\
a_1v_1 + a_2(v_1+v_2) + \cdots a_m(v_1+v_2+\cdots+v_m) &= 0 \\
a_1v_1 + a_2v_1+a_2v_2 + \cdots a_mv_1+a_mv_2+\cdots+a_mv_m &= 0 \\
(a_1+a_2+\cdots+a_m)v_1 + (a_2+\cdots+a_m)v_2 + \cdots a_mv_m &= 0 \\
\end{align*}
$$

But now we see our original linear independent set, where the coefficients must be equal to 0. Working backwards, we can see that $a_m = 0$. Further, if $a_m = 0$ and $a_m + a_{m-1}=0$, then $a_{m-1}=0$. Thus $a_1 = \cdots = a_m = 0$, contradicting our claim that $a_1 \neq \cdots \neq a_m \neq 0$, so $w_1,...,w_m$ must be linearly independent.

On the other hand, suppose $v_1,...,v_m$ is linearly dependent and $w_1,...,w_m$ is linearly independent. Now consider each $v_k$

$$
\begin{align*}
w_1 &= v_1 \\
w_2 - w_1 &= v_2 \\
w_3 - w_2 &= v_3 \\
\end{align*}
$$

So that, for our linearly dependent list

$$
\begin{align*}
a_1v_1 + a_2v_2 + \cdots +a_mv_m &= 0 \\
a_1w_1 + a_2(w_2-w_1) + \cdots + a_m(w_m-w_{m-1}) &= 0 \\
a_1w_1 + a_2w_2-a_2w_1 + \cdots + a_mw_m-a_mw_{m-1} &= 0 \\
(a_1-a_2)w_1 + (a_2-a_3)w_2 + \cdots + (a_{m-1}-a_m)w_{m-1} + a_mw_m &= 0 \\
\end{align*}
$$

And, since we know the linear combination of every coefficient for $w_1,...,w_m$ to be zero to sum to zero, we know $a_m=0$, and thus from $a_{m-1}-a_m=0$ we know $a_{m-1}=0$, backward to $a_1=0$. Thus contradicting the claim that $v_1,...,v_m$ is linearly independent.

## 15. 

> Explain why there does not exist a list of six polynomials that is linearly independent in $\mathcal{P}_4(F)$.

We know from lemma 2.22 that the length of every linearly independent list in a finite dimensional vector space is less than or equal to the length of every spanning list of vectors in that space.

I can find a list of five polynomials that span $\mathcal{P}_4(F)$, namely: $1, x, x^2, x^3, x^4$.

Now we know that at least one list of five polynomials exists which span $\mathcal{P}_4(F)$. Therefore, no list of six polynomials can be linearly independent in the same space.


## 16. 

> Explain why no list of four polynomials spans $\mathcal{P}_4(F)$.

I can find a list of five linearly independent polynomials in $\mathcal{P}_4(F)$: $1, x, x^2, x^3, x^4$. Now, from lemma 2.22 we know that no list of less than 5 polynomials can span $\mathcal{P}_4(F)$.

## 17. 

> Prove that $V$ is infinite-dimensional if and only if there is a sequence $v_1,v_2,...$ of vectors in $V$ such that $v_1,...,v_m$ is linearly independent for every positive integer $m$.

To prove the forward direction, suppose $V$ is infite-dimensional. It is therefore not finite-dimensional, and no list exists which spans $V$. Consider $v_1,...,v_k$ which does not span $V$. Since there is no spanning list, we can find a $v_{k+1} \notin \mathrm{span}(v_1,...,v_k)$ which can be added to $v_1,...,v_k$, preservinv linear independence. Therefore there is a sequence of vectors $v_1,...,v_m$ that is linearly independent for every positive integer $m$.

To prove the reverse, consider that in $V$ there is a sequence $v_1,v_2,...$ of vectors in $V$ such that $v_1,...,v_m$ is linearly independent for every positive integer $m$, but that $V$ is not infinite dimensional. In that case, $V$ is finite-dimensional and a spanning list in $V$ exists for $V$, $w_1,...,w_n$. But then $m \leq n$, so there does not exist an $m$ for every positive integer.

## 18. 

> Prove that $\mathbb{F}^\infty$ is infinite-dimensional.

Consider any list of vectors of $\mathbb{F}^\infty$. Let $m$ denote the rightmost position of nonzero numbers in any vector in this list. Thus the span of the list does not contain a vector with a nonzero number in the $m+1$ position. Therefore, there is no spanning list of $\mathbb{F}^\infty$ and it is infinite-dimensional.

## 19. 

> Prove that the real vector space of all continuous real-valued functions on the interval $[0,1]$ is infinite-dimensional.

Consider any finite list of functions $f_1,f_2,\ldots,f_k$ where $f_i$ is a polynomial and the maximum degree of all these polynomials is $m$. We know these polynomials to be defined for the range $[0,1]$. Then $g(x) = x^{m+1}$ is not in the span of the list, and therefore there is no spanning list of continuous real-valued functions on the interval $[0,1]$ and the space is infinite.

## 20. 

> Suppose $p_0,p_1,\ldots,p_m$ are polynomials in $\mathcal{P}_m(\mathbb{F})$ such that $p_k(2) = 0$ for each $k \in \{0,\ldots,m\}$. Prove that $p_0,p_1,\ldots,p_m$ is not linearly independent in $\mathcal{P}_m(\mathbb{F})$

By the factor theorem we know that

$$
\begin{align*}
p_k &= (x-2) \cdot q_k(x)
\end{align*}
$$

Where $q_k(x)$ is a polynomial with degree at most $m-1$, meaning $q(x) \in \mathcal{P}_{m-1}(\mathbb{F})$.

Now, 

We also know that $\mathcal{P}_{m-1}(\mathbb{F})$ is spanned by the list $1,z,z^2,\ldots,z^{m-1}$, which has length m.

Since, by 2.22 we know that an independent list is less than the length of a spanning list, and since $m+1 \geq m$, we know that $q_0,q_1,\ldots,q_m$ is linearly dependent. Therefore there exist $a_0,a_1,\ldots,a_m$, not all zero, such that

$$
\begin{align*}
a_0q_0+a_1q_1+\cdots+a_mq_m = 0
\end{align*}
$$

But then

$$
\begin{align*}
a_0p_0 + a_1p_1+\cdots+a_mp_m &= 0 \\
(x-2)(a_0q_0+a_1q_1+\cdots+a_mq_m) &= 0 \\
(x-2)\cdot 0 &= 0
\end{align*}
$$

Now we have found a set of scalars, $a_0,...,a_m$, not all zero, such that a linear combination of $p_0,\ldots,p_m$ equals 0.