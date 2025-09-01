- [Axler LADR 2C Exercises](#axler-ladr-2c-exercises)
  - [1.](#1)
  - [2.](#2)
  - [3.](#3)
    - [3. (a)](#3-a)
    - [3. (b)](#3-b)
    - [3. (c)](#3-c)
  - [4.](#4)
    - [4. (a)](#4-a)
    - [4. (b)](#4-b)
    - [4. (c)](#4-c)
  - [5.](#5)
    - [5. (a)](#5-a)
    - [5. (b)](#5-b)
    - [5. (c)](#5-c)
  - [6.](#6)
    - [6. (a)](#6-a)
    - [6. (b)](#6-b)
    - [6. (c)](#6-c)
  - [7.](#7)
    - [7. (a)](#7-a)
    - [7. (b)](#7-b)
    - [7. (c)](#7-c)
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

# Axler LADR 2C Exercises

## 1.

> Show that the subspaces of $\mathbb{R}^2$ are precisely $\{0\}$, all lines in $\mathbb{R}^2$ containing the origin, and $\mathbb{R}^2$.

Any subspace $U \subseteq \mathbb{R}^2$ has $\dim U \leq \dim \mathbb{R}^2 = 2$ (by 2.37).

So $\dim U \in \{0, 1, 2\}$.

$\dim U = 0$. Then $U = \{0\}$. This is a subspace by definition.

$\dim U = 1$. Then $U$ has a basis consisting of one non-zero vector $v$.  So $U = \text{span}(v) = \{tv : t \in \mathbb{R}\}$.  Geometrically, this is the line through the origin in the direction of $v$. Any line through the origin is $\text{span}(v)$ for some non-zero $v$, which is a subspace.

$\dim U = 2$. Since $\dim U = \dim \mathbb{R}^2$ and $U \subseteq \mathbb{R}^2$, by 2.39 we have $U = \mathbb{R}^2$. $\mathbb{R}^2$ is a subspace of itself.  🤌

## 2.

> Show that the subspaces of $\mathbb{R}^3$ are precisely $\{0\}$, all lines in $\mathbb{R}^3$ containing the origin, all planes in $\mathbb{R}^3$ containing the origin, and $\mathbb{R}^3$ 

Any subspace $U \subseteq \mathbb{R}^3$ has $\dim U \leq \dim \mathbb{R}^3 = 3$ (by 2.37).

So $\dim U \in \{0, 1, 2, 3\}$.

$\dim U = 0$. Then $U = \{0\}$. This is a subspace by definition.

$\dim U = 1$. Then $U$ has a basis consisting of one non-zero vector $v$.  So $U = \text{span}(v) = \{tv : t \in \mathbb{R}\}$.  Geometrically, this is the line through the origin in the direction of $v$. Any line through the origin is $\text{span}(v)$ for some non-zero $v$, which is a subspace

$\dim U = 2$. Then $U$ has a basis consisting of two non-zero vectors $v,u$.  So $U = \text{span}(v,u) = \{tv + su : t,s \in \mathbb{R}\}$.  Geometrically, this is the plane through the origin containing $u,v$. Any plane through the origin is $\text{span}(v,u)$ for some non-zeros $v,u$, which is a subspace.

$\dim U = 3$. Since $\dim U = \dim \mathbb{R}^3$ and $U \subseteq \mathbb{R}^3$, by 2.39 we have $U = \mathbb{R}^3$. $\mathbb{R}^3$ is a subspace of itself.  🤌

## 3.

### 3. (a)

> Let $U = \{p \in \mathcal{P}_4(\mathbb{F}) : p(6) = 0\}$. Find a basis of $U$.

Since $1$ is not in $U$, and $\dim U = 4$, and $(x-6)$ is a root in every polynomial in the space, a basis would be $x-6,(x-6)^2,(x-6)^3,(x-6)^4$.

### 3. (b)

> Extend the basis in (a) to a basis of $\mathcal{P}_4(\mathcal{F})$.

Add $1$ to the previous basis, so 

$$
\{1,x-6,(x-6)^2,(x-6)^3,(x-6)^4\}
$$

### 3. (c)

> Find a subspace $W$ of $\mathcal{P}_4(\mathcal{F})$ such that $\mathcal{P}_4(\mathcal{F}) = U \oplus W$.

$$
W = \mathrm{span}(1)
$$

## 4.

### 4. (a)

> Let $U = \{p \in \mathcal{P}_4(\mathbb{R}) : p''(6) = 0\}$. Find a basis of $U$.

Our basis is $\{1, x, (x-6)^3, (x-6)^4\}$.

### 4. (b)

> Extend the basis in (a) to a basis of $\mathcal{P}_4(\mathcal{F})$.

Just add $x^2$

$$
\{1,x,x^2,(x-6)^3,(x-6)^4\}
$$

### 4. (c)

> Find a subspace of $W$ of $\mathcal{P}_4(\mathbb{R})$ such that $\mathcal{P}_4(\mathbb{R}) = U \oplus W$.

$$
W = \mathrm{span}(x^2)
$$

## 5.

### 5. (a)

> Let $U = \{p \in \mathcal{P}_4(\mathbb{F}) : p(2) = p(5)\}$. Find a basis of $U$.

Since $p(x) = c + (x-2)(x-5)q(x)$, we must find a basis that contains the two roots. Our dimensionality is 4 instead of 5, which means a 4 length basis. We can start with the rooted forms

$$
\{1,(x-2)(x-5),x(x-2)(x-5),x^2(x-2)(x-5)\}  \\
\{1,x^2-7x+10,x^3-7x^2+10x,x^4-7x^3+10x^2\}
$$

### 5. (b)

> Extend the basis in (a) to a basis of $\mathcal{P}_4(\mathcal{F})$.

Include one extra dimension, $x$, to find the full basis, as below:
$$
\{1,x,x^2-7x+10,x^3-7x^2+10x,x^4-7x^3+10x^2\}
$$

### 5. (c)

> Find a subspace of $W$ of $\mathcal{P}_4(\mathcal{F})$ such that $\mathcal{P}_4(\mathcal{F}) = U \oplus W$.

$$
W = \mathrm{span}(x) \\
$$

## 6.

### 6. (a)

> Let $U = \{p \in \mathcal{P}_4(\mathbb{F}) : p(2) = p(5) = p(6) \}$. Find a basis of $U$.

Dimensionality is reduced by 2 from 5 to 3. So the basis would be

$$
\{1,(x-2)(x-5)(x-6),x(x-2)(x-5)(x-6)\} \\
\{1,x^3-13x^2+52x-60,x^4-13x^3+52x^2-60x\} \\
$$

### 6. (b)

> Extend the basis in (a) to a basis of $\mathcal{P}_4(\mathcal{F})$.

Add two more dimensions, $x,x^2$:

$$
\{1,x,x^2,x^3-13x^2+52x-60,x^4-13x^3+52x^2-60x\} \\
$$

### 6. (c)

> Find a subspace of $W$ of $\mathcal{P}_4(\mathcal{F})$ such that $\mathcal{P}_4(\mathcal{F}) = U \oplus W$.

$$
W = \mathrm{span}(x,x^2) \\
$$

#TODO I will do this problem after I get through some of Spivak

## 7.

### 7. (a)

> Let $U = \{p \in \mathcal{P}_4(\mathbb{R}) : \int_{-1}^1 p = 0\}$. Find a basis of $U$.

### 7. (b)

> Extend the basis in (a) to a basis of $\mathcal{P}_4(\mathcal{R})$.

### 7. (c)

> Find a subspace of $W$ of $\mathcal{P}_4(\mathcal{R})$ such that $\mathcal{P}_4(\mathcal{R}) = U \oplus W$.

## 8.

> Suppose $v_1,...,v_m$ is linearly independent in $V$ and $w \in V$. Prove that $\dim \mathrm{span}(v_1+w,...,v_m+w) \ge m - 1$.

Consider the difference vectors $m - 1$ in our span:

$$
\begin{align*}
u_1 - u_2 &= (v_1 + w) - (v_2 + w) = v_1 - v_2 \\
u_1 - u_3 &= v_1 - v_3 \\
\vdots \\
u_1 - u_m &= v_1 - v_m
\end{align*}
$$

We know that these are linearly independent because

$$
\begin{align*}
0 &= a_2(v_1-v_2)+\cdots+a_m(v_1-v_m) \\
0 &= a_2v_1-a_2v_2)+\cdots+a_mv_1-a_mv_m) \\
0 &= a_2v_1+\cdots+a_mv_1-a_2v_2-\cdots-a_mv_m \\
0 &= (a_2+\cdots+a_m)v_1-a_2v_2-\cdots-a_mv_m \\
\end{align*}
$$

Now we have a linear combination of our original set $v_1,...,v_m$ which we know to be linearly independent. This proves that our difference vectors are also linearly independent in our set. Therefore, because the  span $\mathrm{span}(v_1+w,...,v_m+w)$ contains a linearly independent set of vectors of length $m-1$, we know that the dimension of the span is at least $m-1$. 🤌

## 9.

> Suppose $m$ is a positive integer and $p_0,p_1,...,p_m \in \mathcal{P}(\mathbb{F})$ are such that each $p_k$ has degree $k$. Prove that $p_0,p_1,...,p_m$ is a basis of $\mathcal{P}_m(\mathbb{F})$.

We know from 4.8 (asserted by Axler) that the coefficients of a polynomial are uniquely determined by the polynomial. So that 

$$
p_k \ne a_0p_0 + a_1p_1 + \cdots + a_{k-1}p_{k-1}
$$

for any $a_0,...,a_{k-1}$, so we know the list $p_0,p_1,...,p_m$ is linearly independent.

We also know that $p_0,p_1,...,p_m$ is length $m+1$, and $\dim \mathcal{P}_m(\mathbb{F}) = m + 1$.

Since we know any linearly independent list of length $\dim \mathcal{P}_m(\mathbb{F})$ is a basis of $\mathcal{P}_m(\mathbb{F})$, we know that the list is a basis of $\mathcal{P}_m(\mathbb{F})$. 🤌

## 10.

> Suppose $m$ is a positive integer. For $0 \le k \le m$, let

$$
p_k(x) = x^k(1-x)^{m-k}.
$$ 

Show that $p_0,...,p_m$ is a basis of $\mathcal{P}_m(\mathbb{F})$.

Since the expansion of $(1-x)^{m-k}$ will always have the smallest term as a constant, $1$, the smallest term for each polynomial $p_k$ will be $x^k$, since $x^k \cdot x^j = x^{j+k}$ with degree $j + k > k$.

Therefore, no set of polynomials $p_{k+1},...,p_m$ have an $x^k$ term, and therefore there is no linear combination of them for which

$$
p_k = a_{k+1}p_{k+1} + \cdots + a_mp_m 🤌
$$

## 11.

> Suppose $U$ and $W$ are both four-dimensional subspaces of $\mathbb{C}^6$. Prove that there exist two vectors in $U \cap W$ such that neither of these vectors is a scalar multiple of the other.

We know that $U + W \subseteq C^6$ and therefore the $\dim (U + W) \le 6$. We therefore can identify

$$
\begin{align*}
\dim U + \dim W - \dim (U \cap W) = \dim (U + W) &\le 6 \\
4 + 4 - \dim (U \cap W) &\le 6 \\
8 - \dim (U \cap W) &\le 6 \\
\dim (U \cap W) &\ge 2 \\
\end{align*}
$$

We therefore know that there is a linearly independent list of at least 2 in $U \cap W$. 🤌

## 12.

> Suppose that $U$ and $W$ are subspaces of $\mathbb{R}^8$ such that $\dim U = 3, \dim W = 5$, and $U + W = \mathbb{R}^8$. Prove that $\mathbb{R}^8 = U \oplus W$.

Since

$$
\begin{align*}
\dim U + \dim W + \dim (U \cap W) &= \dim (U + W) = \dim \mathbb{R}^8 \\
3 + 5 + \dim (U \cap W) &=  8 \\
\dim (U \cap W) &=  0, \\
\end{align*}
$$

we know that $U \cap W = \{0\}$. Therefore, $\mathbb{R}^8 = U \oplus W$. 🤌

## 13.

> Suppose $U$ and $W$ are both five-dimensional subspaces of $\mathbb{R}^9$. Prove that $U \cap W \ne \{0\}$.

Since $U$ and $W$ are subspaces of $\mathbb{R}^9$, $\dim (U + W) <= 9$.

$$
\begin{align*}
\dim U + \dim W - \dim (U \cap W) = \dim (U + W) &\le \dim \mathbb{R}^9 \\
5 + 5  - \dim (U \cap W) &\le \dim \mathbb{R}^9 \\
10 - \dim (U \cap W) &\le 9 \\
\dim (U \cap W) &\ge 1\\
\end{align*}
$$

Therefore we know the dimension of the intersection of the spaces is greater than $0$ and it must contain more than $\{0\}$. 🤌

## 14.

> Suppose $V$ is a ten-dimensional vector space and $V_1,V_2,V_3$ are subspaces of $V$ with $\dim V_1 + \dim V_2 + \dim V_3 \gt 2 \dim V$. Prove that $V_1 \cap V_2 \cap V_3 \ne \{0\}$.

We can identify $V_1 \cap V_2 \cap V_3$ iteratively by using the dimension formula.

$$
\begin{align*}
\dim V_1 + \dim V_2 - \dim (V_1 \cap V_2) = \dim (V_1 + V_2) \le 10 = \dim V \\
\dim V_1 + \dim V_2 - \dim (V_1 \cap V_2) \le 10 \\
\dim (V_1 \cap V_2) \ge \dim V_1 + \dim V_2 - 10 \tag{1}
\end{align*}
$$

$$
\begin{align*}
\dim (V_1 \cap V_2) + \dim V_3 - \dim (V_1 \cap V_2 \cap V_3) &\le 10 \\
\dim V_3 - \dim (V_1 \cap V_2 \cap V_3) &\le 10 - \dim(V_1 \cap V_2) \\
- \dim (V_1 \cap V_2 \cap V_3) &\le 10 - \dim(V_1 \cap V_2) - \dim V_3 \\
\dim (V_1 \cap V_2 \cap V_3) &\ge -10 + \dim(V_1 \cap V_2) + \dim V_3 \\
\dim (V_1 \cap V_2 \cap V_3) &\ge \dim(V_1 \cap V_2) + \dim V_3 - 10 \tag{2} \\
\end{align*}
$$

Substituting our bound from $(1)$ we get

$$
\begin{align*}
\dim (V_1 \cap V_2 \cap V_3)& \ge \dim V_1 + \dim V_2 + \dim V_3 - 20 \\
\end{align*}
$$

Finally, we already know that $\dim V_1 + \dim V_2 + \dim V_3 > 2\dim V = 20$, that $\dim (V_1 \cap V_2 \cap V_3) > 0$, and so the intersection can not contain just the origin. 🤌

## 15.

> Suppose $V$ is finite-dimensional and $V_1,V_2,V_3$ are subspaces of $V$ with $\dim V_1 + \dim V_2 + \dim V_3 \gt 2 \dim V$. Prove that $V_1 \cap V_2 \cap V_3 \ne \{0\}$.

We can identify $V_1 \cap V_2 \cap V_3$ iteratively by using the dimension formula.

$$
\begin{align*}
\dim V_1 + \dim V_2 - \dim (V_1 \cap V_2) = \dim (V_1 + V_2) \le \dim V \\
\dim V_1 + \dim V_2 - \dim (V_1 \cap V_2) \le \dim V \\
\dim (V_1 \cap V_2) \ge \dim V_1 + \dim V_2 - \dim V \tag{1}
\end{align*}
$$

$$
\begin{align*}
\dim (V_1 \cap V_2) + \dim V_3 - \dim (V_1 \cap V_2 \cap V_3) &\le \dim V \\
\dim V_3 - \dim (V_1 \cap V_2 \cap V_3) &\le \dim V - \dim(V_1 \cap V_2) \\
- \dim (V_1 \cap V_2 \cap V_3) &\le \dim V - \dim(V_1 \cap V_2) - \dim V_3 \\
\dim (V_1 \cap V_2 \cap V_3) &\ge -\dim V + \dim(V_1 \cap V_2) + \dim V_3 \\
\dim (V_1 \cap V_2 \cap V_3) &\ge \dim(V_1 \cap V_2) + \dim V_3 - \dim V \tag{2} \\
\end{align*}
$$

Substituting our bound from $(1)$ we get

$$
\begin{align*}
\dim (V_1 \cap V_2 \cap V_3) &\ge \dim V_1 + \dim V_2 + \dim V_3 - \dim V - \dim V \\
\dim (V_1 \cap V_2 \cap V_3) &\ge \dim V_1 + \dim V_2 + \dim V_3 - 2\dim V \\
\end{align*}
$$


Finally, we already know that $\dim V_1 + \dim V_2 + \dim V_3 > 2\dim V$. Which means

$$
\begin{align*}
\dim (V_1 \cap V_2 \cap V_3) &> 2 \dim V - 2 \dim V \\
\dim (V_1 \cap V_2 \cap V_3) &> 0 \\
\end{align*}
$$

Thus we know the intersection of the 3 subspaces has dimensionality greater than 0, and therefore does not equal the trivial subspace. 🤌

## 16.

> Suppose $V$ is finite-dimensional and $U$ is a subspace of $V$ with $U \ne V$. Let $n = \dim V$ and $m = \dim U$. Prove that there exist $n - m$ subspaces of $V$, each of dimension $n - 1$, whose intersection equals $U$.

Since $U \subseteq V$ we have a basis of $U$, $\{u_1,...,u_m\}$ which can be extended to a basis of $V$ by appending $\{u_1,...,u_m,v_1,...,v_{n-m}\}$.

Now, let $W_i = \mathrm{span}(u_1,...,u_m,v_1,...,v_{i-1},v_{i+1},...,v_{n-m})$ such that it is constructed by removing the $i$-th element from that basis. We know that there are $n-m$ $W$ subspaces, and we know that it has one less dimension than the $V$. And we know that $W_1\cap ... \cap W_{n-m} = \mathrm{span}(u_1,...,u_m) = U$. 🤌

## 17.

> Suppose $V_1,...,V_m$ are finite-dimensional subspaces of $V$. Prove that $V_1+\cdots+V_m$ is finite-dimensional and $\dim(V_1+\cdots+V_m) \le \dim V_1 + \cdots + \dim V_m$.

Consider just two subspaces: $V_1$ and $W = V_2 + \cdots + V_m$.

From the dimension formula we have

$$
\begin{align*}
\dim V_1 + \dim W - \dim (V_1 \cap W) &= \dim (V_1 + W) \\
\dim V_1 + \dim W &= \dim (V_1 + W) + \dim (V_1 \cap W)  \\
\end{align*}
$$

Since $\dim(V_1 \cap W) \ge 0$, we know that

$$
\dim V_1 + \dim W \ge \dim (V_1 + W) \\
$$

And furthermore, that we can now decompose W

$$
\dim V_1 + \dim (V_2 + \cdots + V_m) \ge \dim (V_1 + \cdots + V_m) \\
$$

But since $V_2+\cdots+V_m$ is a subspace of $m-1$ subspaces, we can likewise decompose in an inductive argument where

$$
\dim V_2 + \dim (V_3 + \cdots + V_m) \ge \dim (V_2 + \cdots + V_m) \\
$$

and then

$$
\dim V_{m-2} + \dim (V_{m-1} + \cdots + V_m) \ge \dim (V_{m-2} + \cdots + V_m) \\
$$


And from there it's turtles all the way down! So we can further decompose $\dim (V_2 + \cdots + V_m)$ to

$$
\begin{align*}
\dim V_1 + \dim V_2 + \cdots + \dim V_m &\ge \dim (V_1 + \cdots + V_m) \\
\dim V_1 + \cdots + \dim V_m &\ge \dim (V_1 + \cdots + V_m)
\end{align*}
$$

Furthermore, since each $V_i$ is finite-dimensional, any finite union of their spanning sets gives a finite spanning set for $V_1 + \cdots + V_m$, so the sum is finite-dimensional. 🤌

## 18.

> Suppose $V$ is finite-dimensional, with $\dim V = n \ge 1$. Prove that there exist one-dimensional subspaces $V_1,...,V_n$ of $V$ such that $V = V_1 \oplus \cdots \oplus V_n$.

Since $V$ is finite-dimensional, there exists a basis $\{v_1,...,v_n\}$. Since $\dim \mathrm{span}(v_i) = 1$ (the basis of $v_i$ is $\{v_i\}$), and there are exactly $n$ $v_i$'s, there are exactly $n$ one dimensional subspaces of $V$ where $V_i = \mathrm{span}(v_i)$ who, since they form a basis, are also linearly independent. And we can therefore conclude $V = v_1 \oplus \cdots \oplus v_n$.

## 19.

> Explain why you might guess, motivated by analogy with the formula for the number of elements in the union of three sets, that if $V_1,V_2,V_3$ are subspaces of a finite-dimensional vector space, then

$$
\dim(V_1+V_2+V_3) = \dim V_1 + \dim V_2 + \dim V_3 - \dim(V_1 \cap V_2) - \dim(V_1 \cap V_3) - \dim(V_2 \cap V_3) + \dim(V_1\cap V_2\cap V_3).
$$

Then either prove the formula above or give a counterexample.

Well, I mean, it looks like a recursive application of the formula for the dimensions of a combination of 2 subspaces. So let's try doing that.

Let's take $W = V_1+V_2$. Then

$$
\dim W + \dim V_3 - \dim (W \cap V_3) = \dim (W + V_3) \tag{1}
$$

and 

$$
\dim V_1 + \dim V_2 - \dim (V_1 \cap V_2) = \dim (V_1 + V_2) \tag{2}
$$

If we substitute $(2)$ into $(1)$ we get

$$
\begin{align*}
\dim (V_1 + V_2 + V_3) &= \dim (V_1+V_2) + \dim V_3 - \dim ((V_1+V_2) \cap V_3) \\
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 - \dim (V_1 \cap V_2) + \dim V_3 - \dim ((V_1+V_2) \cap V_3) \\
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_1 \cap V_2) - \dim ((V_1+V_2) \cap V_3) \\
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_1 \cap V_2) - \dim ((V_1 \cap V_3) + (V_2 \cap V_3)) \tag{3} \\
\end{align*}
$$

And, furthermore, treating $U = (V_1 \cap V_3), T = (V_2 \cap V_3)$

$$
\begin{align*}
\dim (U + T) &= \dim U + \dim T - \dim (U \cap T) \\
\dim ((V_1 \cap V_3) + (V_2 \cap V_3)) &= \dim (V_1 \cap V_3) + \dim (V_2 \cap V_3) - \dim ((V_1 \cap V_3) \cap (V_2 \cap V_3)) \\
\dim ((V_1 \cap V_3) + (V_2 \cap V_3)) &= \dim (V_1 \cap V_3) + \dim (V_2 \cap V_3) - \dim (V_1 \cap V_2 \cap V_3) \tag{4} \\
\end{align*}
$$

We can then substitute $(4)$ back into $(3)$

$$
\begin{align*}
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_1 \cap V_2) - \dim ((V_1 \cap V_3) + (V_2 \cap V_3)) \tag{3} \\
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_1 \cap V_2) - (\dim (V_1 \cap V_3) + \dim (V_2 \cap V_3) - \dim (V_1 \cap V_2 \cap V_3)) \\
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_1 \cap V_2) - \dim (V_1 \cap V_3) - \dim (V_2 \cap V_3) + \dim (V_1 \cap V_2 \cap V_3) 🤌\\
\end{align*}
$$

## 20.

> Prove that if $V_1,V_2,$ and $V_3$ are subspaces of a finite-dimensional vector space, then

$$
\dim(V_1+V_2+V_3) = \dim V_1 + \dim V_2 + \dim V_3 - \frac{\dim(V_1 \cap V_2) + \dim(V_1 \cap V_3) + \dim(V_2 \cap V_3)}{3} - \frac{\dim((V_1+V_2)\cap V_3) + \dim((V_1+V_3)\cap V_2) + \dim((V_2+V_3) \cap V_1)}{3} \tag{0}
$$

Well, let's start with equation $(3)$ from problem 19 and dedistribute the intersection by one step.

$$
\begin{align*}
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_1 \cap V_2) - \dim ((V_1 \cap V_3) + (V_2 \cap V_3)) \\
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_1 \cap V_2) - \dim ((V_1+V_2) \cap V_3) \tag{1} \\
\end{align*}
$$

This results from applying the dimension formula to $V_1,V_2$ and then applying the results to $V_1+V_2,V_3$. Let's try a different grouping and we can also find

$$
\begin{align*}
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_2 \cap V_3) - \dim ((V_2+V_3) \cap V_1) \tag{2} \\
\dim (V_1 + V_2 + V_3) &= \dim V_1 + \dim V_2 + \dim V_3 - \dim (V_1 \cap V_3) - \dim ((V_1+V_3) \cap V_2) \tag{3} \\
\end{align*}
$$

Now we can simply add the three equations resulting in

$$
\begin{align*}
3 \dim (V_1 + V_2 + V_3) = 3 \dim V_1 + 3 \dim V_2 + 3 \dim V_3 - \dim (V_1 \cap V_2) - \dim ((V_1+V_2) \cap V_3) - \dim (V_2 \cap V_3) - \dim ((V_2+V_3) \cap V_1) - \dim (V_1 \cap V_3) - \dim ((V_1+V_3) \cap V_2) \\
\dim (V_1 + V_2 + V_3) = \dim V_1 + \dim V_2 + \dim V_3 - \frac{\dim (V_1 \cap V_2) + \dim (V_2 \cap V_3) + \dim (V_1 \cap V_3)}{3} - \frac{\dim ((V_1+V_2) \cap V_3) + \dim ((V_2+V_3) \cap V_1) + \dim ((V_1+V_3) \cap V_2)}{3} 🤌 \tag{0}\\
\end{align*}
$$