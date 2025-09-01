- [Axler LADR 2B Exercises](#axler-ladr-2b-exercises)
  - [1.](#1)
  - [2.](#2)
    - [2. (a)](#2-a)
    - [2. (b)](#2-b)
    - [2. (c)](#2-c)
    - [2. (d)](#2-d)
    - [2. (e)](#2-e)
    - [2. (f)](#2-f)
    - [2. (g)](#2-g)
  - [3.](#3)
    - [3. (a)](#3-a)
    - [3. (b)](#3-b)
    - [3. (c)](#3-c)
  - [4.](#4)
    - [4. (a)](#4-a)
    - [4. (b)](#4-b)
    - [4. (c)](#4-c)
  - [5.](#5)
  - [6.](#6)
  - [7.](#7)
  - [8.](#8)
  - [9.](#9)
  - [10.](#10)
  - [11.](#11)

# Axler LADR 2B Exercises

## 1. 

> Find all vector spaces that have exactly one basis.

There is only one vector space with exactly one basis, it is the empty set, ${0}$ whose basis is the empty list $()$. 🤌

## 2. 

> Verify all assertions in example 2.27.

### 2. (a) 

> The list $(1,0,...,0),(0,1,0,...,0),...,(0,...,0,1)$ is a basis of $\mathbb{F}^n$, called the _standard basis_ of $\mathbb{F}^n$.

A basis is a linearly independent list that spans the space.

Suppose a vector in $\mathbb{F}^n$, $(a_1,a_2,...,a_n)$. You can represent it as the linear combination

$$
(a_1,a_2,...,a_n) = a_1(1,0,...,0) + a_2(0,1,0,...,0) + \cdots + a_n(0,...,0,1)
$$

Therefore the list spans the space.

Furthermore, to show that this is a unique representation, suppose some set of coefficients $c_1,...,c_n \in \mathbb{F}^n$ exist for which 

$$
(a_1,a_2,...,a_n) = c_1(1,0,...,0) + a_2(0,1,0,...,0) + \cdots + a_n(0,...,0,1)
$$

Subtacting the two representations we get

$$
\begin{align*}
0 &= (a_1-c_1)(1,0,...,0) + (a_2-c_2)(0,1,0,...,0) + \cdots + (a_n-c_n)(0,...,0,1) \\
0 &= ((a_1-c_1),0,...,0) + (0,(a_2-c_2),0,...,0) + \cdots + (0,...,0,(a_n-c_n))
\end{align*}
$$

Thus $a_1-c_1 = a_2-c_2 = \cdots = a_n-c_n = 0$ and $a_1 = c_1 = \cdots = a_n = c_n = 0$. 🤌

### 2. (b) 

> The list $(1,2),(3,5)$ is a basis of $\mathbb{F}^2$. Note that this list has length two, which is the same length of the standard basis of $\mathbb{F}^2$.

Choose any $v \in \mathbb{F}^2$. Then

$$
\begin{align*}
v = a_1(1,2) + a_2(3,5) = (a_1+3a_2, 2a_1+5a_2) 
\end{align*}
$$

Furthermore, since we have

$$
\begin{align*}
v_1 &= a_1 + 3a_2 \tag{1}\\
v_2 &= 2a_1 + 5a_2 \tag{2}\\
v_1+v_2 &= 3a_1 + 8a_2 \tag{3}
\end{align*}
$$

We can solve for $a_1$ with equation(1): $a_1 = v_1 - 3a_2$ and then we have

$$
\begin{align*}
v_2 &= 2(v_1 - 3a_2) + 5a_2 \\
v_2 &= 2v_1 - 6a_2 + 5a_2 \\
v_2 &= 2v_1 - a_2 \\
v_2 - 2v_1 &= -a_2 \\
a_2 &= 2v_1 - v_2
\end{align*}
$$

So now we see unique representations for $a_1,a_2$, namely $a_1=v_1-3a_2$ and $a_2=2v_1-v_2$. 🤌

### 2. (c) 

> The list $(1,2,-4),(7,-5,6)$ is linearly independent in $\mathbb{F}^3$ but is not a basis of $\mathbb{F}^3$ because it does not span $\mathbb{F}^3$.

In this case none of the basis vectors are within the plane described by the two vectors. 

### 2. (d) 

> The list $(1,2),(3,5),(4,13)$ spans $\mathbb{F}^2$ but is not a basis of $\mathbb{F}^2$ because it is not linearly independent.

To prove the statement it suffices to show that any two vectors span the space, showing the third to be superfluous:

$$
\begin{align*}
x_1 &= a + 3b \\
x_2 &= 2a + 5b \\
\end{align*}
$$

$$
\begin{align*}
x_1 &= a + 3b \\
a &= x_1 - 3b \\
\end{align*}
$$

$$
\begin{align*}
x_2 &= 2(x_1 - 3b) + 5b \\
x_2 &= 2x_1 - 6b + 5b \\
x_2 &= 2x_1 - b \\
b &= 2x_1 - x_2\\
\end{align*}
$$

$$
\begin{align*}
a &= x_1 - 3(2x_1-x_2) \\
a &= x_1 - 6x_1+3x_2 \\
a &= -5x_1 + 3x_2 \\
\end{align*}
$$


So we can see that for $(1,2),(3,5)$ $a = 3x_2-5x_1,b=2x_1-x_2$ which means the set spans the space, and the third vector is superfluous and therefore not a basis. 🤌

### 2. (e) 

> The list $(1,1,0),(0,0,1)$ is a basis of $\{(x,x,y) \in \mathbb{F}^3 : x,y \in \mathbb{F} \}$.

It suffices to show any $(x,x,y)$ can be represented by the vector set and that the list is linearly independent.

$$
\begin{align*}
x_1 &= 1a + 0b = a\\
x_2 &= 1a + 0b = a\\
x_3 &= 0a + 1b = b\\
\end{align*}
$$

This shows that **every** vector $(x,x,y)$ in the vector space can be written as a linear combination of $(1,1,0)$ and $(0,0,1)$. Therefore the list **spans** the vector space.

Furthermore, 

$$a(1,1,0) + b(0,0,1) = (0,0,0)$$

This gives:
$$\begin{align*}
a &= 0\\
a &= 0\\
b &= 0
\end{align*}$$

Therefore $a = b = 0$, so the list is **linearly independent**. 🤌

### 2. (f) 

> The list $(1,-1,0),(1,0,-1)$ is a basis of $\{(x,y,z) \in \mathbb{F^3}: x + y + z = 0 \}$.

First, let's find $a,b$ in terms of $x,y,z$ to show every vector in the space can be represented.

$$
\begin{align*}
x_1 &= a + b \\
x_2 &= -a \\
x_3 &= -b \\
\end{align*}
$$

Immediately we see $a = -x_2,b = -x_3$. And finally, adding our system of equations we get:

$$
\begin{align*}
x_1 + x_2 + x_3 &= a + b - a - b \\
&= -x_2 + -x_3 - (-x_2) - -x_3 \\
&= -x_2 + -x_3 + x_2 +x_3 \\
&= 0
\end{align*}
$$

So we see that the vector set spans the space. To show they are linearly independent:

$$
a(1,-1,0) + b(1,0,-1) = (0,0,0)
$$

Gives $a = b = 0$, so the list is linearly independent. 🤌


### 2. (g) 

> The list $1,z,...,z^m$ is a basis of $\mathcal{P}_m(\mathbb{F})$, called the _standard basis_ of $\mathcal{P}_m(\mathcal{F})$.

First to show it spans the space, observe

$$
a_0 + a_1z + \cdots + a_mz^m = a_0(1) + a_1(z) + \cdots + a_m(z^m)
$$

Second, note that for

$$
a_0 + a_1z + \cdots + a_mz^m = 0
$$

clearly, $a_0 = a_1 = \cdots = a_m = 0$ because the coefficients of a polynomial are uniquely determined and on the right side of the equation is the 0 polynomial for which all coefficients are 0. 🤌

## 3.

### 3. (a) 

> Let $U$ be the subspace of $\mathbb{R}^5$ defined by $U = \{(x_1,x_2,x_3,x_4,x_5) \in \mathbb{R}^5 : x_1 = 3x_2 \text{ and } x_3 = 7x_4\}$. Find a basis of $U$.

Since the vector can be re-expressed $(3x_2,x_2,7x_4,x_4,x_5)$, we can express the basis as $(3,1,0,0,0),(0,0,7,1,0),(0,0,0,0,1)$. Proving linear independence is trivial and dispensed with. 🤌

### 3. (b) 

> Extend the basis in (a) to a basis of $\mathbb{R}^5$.

Simply add $(1,0,0,0,0),(0,0,1,0,0)$ to the set for the basis. 🤌

### 3. (c) 

> Find a subspace $W$ of $\mathbb{R}^5$ such that $\mathbb{R}^5 = U \oplus W$.

$$
W = \{(0,x,0,y,0) \in \mathbb{R}^5 \} 🤌
$$

## 4.

### 4. (a) 

> Let $U$ be the subspace of $\mathbb{C}^5$ defined by $U = \{(z_1,z_2,z_3,z_4,z_5) \in \mathbb{C}^5 : 6z_1 = z_2 \text{ and } z_3 + 2z_4 + 3z_5 = 0 \}$. Find a basis of $U$.

We're going to reduce the vector by using the constraints through substitution

$$
\begin{align*}
(z_1,z_2,z_3,z_4,z_5) &= (z_1,6z_1,-2z_4-3z_5, z_4,z_5)
\end{align*}
$$

Therefore the free variables are $z_1,z_4,z_5$ and our basis is $(1,6,0,0,0),(0,0,-2,1,0),(0,0,-3,0,1)$ 🤌

### 4. (b) 

> Extend the basis in (a) to a basis of $\mathbb{C}^5$.

Simply by adding $(0,1,0,0,0),(0,0,1,0,0)$ we form $\mathbb{C}^5$. 🤌

### 4. (c) 

> Find a subspace $W$ of $\mathbb{C}^5$ such that $\mathbb{C}^5 = U \oplus W$.

The subspace $W = (x,0,y,0,0,0)$ 🤌

## 5. 

> Suppose $V$ is finite-dimensional and $U,W$ are subspaces of $V$ such that $V = U + W$. Prove that there exists a basis of $V$ consisting of vectors in $U \cup W$.

Since $V$ is a finite-dimensional vector space and U,W are subspaces of $V$, $U,W$ are also finite-dimensional and therefore also have bases.

Since ever vector in $U$ can be represented by linear combinations of its basis, and the same applies to the basis in $W$, and $V = U + W$, the union of the bases in $u_1,...,u_m,w_1,...,w_m \in U \cup W$ _also_ spans $V$.

Let $\{u_1, \ldots, u_m\}$ be a basis of $U$ and $\{w_1, \ldots, w_n\}$ be a basis of $W$.

Since $V = U + W$, every vector $v \in V$ can be written as:
$$v = u + w$$
where $u \in U$ and $w \in W$.

Since $u \in U$: $u = a_1u_1 + \cdots + a_mu_m$ for some scalars $a_i$

Since $w \in W$: $w = b_1w_1 + \cdots + b_nw_n$ for some scalars $b_j$

Therefore:
$$v = a_1u_1 + \cdots + a_mu_m + b_1w_1 + \cdots + b_nw_n$$

This shows that **every** vector in $V$ is a linear combination of vectors from $\{u_1, \ldots, u_m, w_1, \ldots, w_n\} \subset U \cup W$.

To see that you can form a basis from the union of these two bases, note from 2.30 that every spanning list contains a basis and therefore can be reduced by removing redundant vectors from the list $u_1,...,u_m,w_1,w_m$. 🤌

## 6. 

> Prove or give a counterexample: If $p_0,p_1,p_2,p_3$ is a list in $\mathcal{P}_3(\mathbb{F})$ such that none of the polynomials $p_0,p_1,p_2,p_3$ has degree 2, then $p_0,p_1,p_2,p_3$ is not a basis of $\mathcal{P}_3(\mathbb{F})$.

Consider this basis: $1,x,x^2+x^3,x^3$ 🤌
 
## 7. 

> Suppose $v_1,v_2,v_3,v_4$ is a basis of $V$. Prove that $v_1+v_2,v_2+v_3,v_3+v_4,v_4$ is also a basis of $V$.

Consider

$$
\begin{align*}
v_4 &= v_4 \\
v_3 &= (v_3 + v_4) - v_4 \\
v_2 &= (v_2 + v_3) - v_3 = (v_2 + v_3) - (v_3 + v_4) + v_4 \\
v_1 &= (v_1 + v_2) - v_2 = (v_1 + v_2) - (v_2 + v_3) + (v_3 + v_4) - v_4
\end{align*}
$$

So we see that the original set is equal to a linear combination of the new set. Therefore it spans the original basis, and is linearly independent. 🤌

## 8. 

> Prove or give a counterexample: If $v_1,v_2,v_3,v_4$ is a basis of $V$ and $U$ is a subspace of $V$ such that $v_1,v_2 \in U$ and $v_3 \notin U$ and $v_4 \notin U$, then $v_1,v_2$ is a basis of $U$.

We know that when $v_k$ is removed from a linearly independent list, $v_1,...,v_{k-1}$ is still linearly independent, so $v_1,v_2$ is linearly independent in $U$.

However, to prove $v_1,v_2$ span $U$:

**Suppose** (for contradiction) that there exists some $u \in U$ such that $u \notin \text{span}(v_1, v_2)$.

Since $v_1, v_2, v_3, v_4$ is a basis of $V$, we can write:
$$u = a_1v_1 + a_2v_2 + a_3v_3 + a_4v_4$$

Since $u \notin \text{span}(v_1, v_2)$, at least one of $a_3$ or $a_4$ must be non-zero.

**Case 1**: Suppose $a_3 \neq 0$. Then:
$$v_3 = \frac{1}{a_3}(u - a_1v_1 - a_2v_2 - a_4v_4)$$

But $u, v_1, v_2 \in U$, so the right side involves vectors in $U$ and $v_4$. If we could eliminate $v_4$ from this expression, we'd get $v_3 \in U$, contradicting our assumption.

**Case 2**: Similar reasoning for $a_4 \neq 0$.

Since this leads to contradiction, no such $u$ can exist. Therefore, $U = \text{span}(v_1, v_2)$. 🤌 

## 9. 

> Suppose $v_1,...,v_m$ is a list of vectors in $V$. For $k \in \{1,...,m\}$, let $w_k = v_1 + \cdots + v_k$. Show that $v_1,...,v_m$ is a basis of $V$ if and only if $w_1,...,w_m$ is a basis of $V$.

It would suffice to show that $\mathrm{span}(v_1,...,v_m) = \mathrm{span}(w_1,...,w_m)$.

Observe

$$
\begin{align*}
v_1 &= w_1 \\
v_2 &= w_2 - w_1 \\
v_3 &= w_3 - w_2 \\
v_k &= w_k - w_{k-1} \quad \text{for } k = 2, 3, \ldots, m
\end{align*}
$$

Therefore we see that every $v_k$ is a linear combination of some $w_k$. Since they have equal length and equal span, they are also both linearly independent if and only if the other is. Therefore they are equivalently bases. 🤌

## 10. 

> Suppose $U$ and $W$ are subspaces of $V$ such that $V = U \oplus W$. Suppose also that $u_1,...,u_m$ is a basis of $U$ and $w_1,...,w_n$ is a basis of $W$. Prove that $u_1,...,u_m,w_1,...,w_n$ is a basis of $V$.

We have to show that the concatenation is linearly independent and spans V.

Since $V = U \oplus W$ we know that $u_1,...,u_m,w_1,...,w_n$ spans $V$.

Suppose $a_1u_1 + \cdots + a_mu_m + b_1w_1 + \cdots +b_mw_m = 0$.

Let $u = a_1u_1+\cdots +a_mu_m$ and $w = b_1w_1+\cdots b_mw_m$.

Then, since $u+w = 0$, $u = -w$.

Since $u \in U$ and $-w \in W$ and by the definition of the direct sum $U \cap W = \{0\}$, we must have $u = w = 0$. And since $u_1,...,u_m$ is linearly independent in $U$ and the same is true of $w_1,...,w_m \in W$, we know as well that $a_1=\cdots=a_m=0$ and $b_1=\cdots=b_m=0$.

Therefore the concatenated list is linearly independent. 🤌

## 11. 

> Suppose $V$ is a real vector space. Show that if $v_1,...,v_n$ is a basis of $V$ (as a real vector space), then $v_1,...,v_n$ is also a basis of the complexification $V_{\mathbb{C}}$ (as a complex vector space).

To prove $v_1,...,v_n$ is a basis of $V_{\mathbb{C}}$ we must show that $v_1,...,v_n$ is linearly independent in $V_{\mathbb{C}}$ and also that $\mathrm{span}(v_1,...,v_n)=V_{\mathbb{C}}$.

To show the list is linearly independent in $V_{\mathbb{C}}$, suppose $c_1v_1+\cdots+c_nv_n=0$ where $c_i \in \mathbb{C}$.

Then,

$$
\begin{align*}
c_1v_1+\cdots+c_nv_n&=0 \\
(a_1+b_1i)v_1+\cdots+ (a_n+b_ni)v_n &= 0 \\
(a_1v_1+ib_1v_1)+\cdots+ (a_nv_1+ib_nv_n) &= 0\\
a_1v_1+\cdots+a_nv_n+i(b_1v_1+\cdots+ b_nv_n) &= 0\\
\end{align*}
$$

Now suppose $u = a_1v_1+\cdots+a_nv_n$ and $v=i(b_1v_1+\cdots+b_nv_n)$. Then $u + iw = 0$ in $V_{\mathbb{C}}$. Since we know a complex element equals zero if and only if both its real part and complex part equal zero,

$$
u+iw = 0 \in V_{\mathbb{C}} \iff u = w = 0 \in V
$$

Which means $a_1=\cdots=a_n=b_1=\cdots=b_n=0$ and $v_1,...,v_n$ is linearly independent in $V_{\mathbb{C}}$.

Now to show it spans, let $w$ be any element of $V_{\mathbb{C}}$. Then $w = u + iv$ for some $u,v \in V$. Then

$$
\begin{align*}
u &= a_1v_1+\cdots+a_nv_n \\
v &= b_1v_1+\cdots+b_nv_n
\end{align*}
$$

Now,

$$
\begin{align*}
w &= u + iv \\
&= (a_1v_1+\cdots+a_nv_n) + i(b_1v_1+\cdots+b_nv_n) \\
&= a_1v_1+\cdots+a_nv_n + ib_1v_1+\cdots+ib_nv_n \\
&= a_1v_1+ib_1v_1+\cdots+a_nv_n+ib_nv_n \\
&= (a_1+ib_1)v_1+\cdots+(a_n+ib_n)v_n \\
&= c_1v_1+\cdots+c_nv_n \\
\end{align*}
$$

So we see $v_1,...,v_n$ also spans $V_{\mathbb{C}}$. And therefore it is a basis in the complexification of $V$. 🤌
