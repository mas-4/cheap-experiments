- [Axler LADR 3b Vector Spaces of Linear Maps](#axler-ladr-3b-vector-spaces-of-linear-maps)
  - [1.](#1)
  - [2.](#2)
  - [3.](#3)
    - [3. (a)](#3-a)
    - [3. (b)](#3-b)
  - [4.](#4)
  - [5.](#5)
  - [6.](#6)
  - [7.](#7)
  - [8.](#8)
  - [9.](#9)
  - [10.](#10)
  - [11.](#11)



# Axler LADR 3b Vector Spaces of Linear Maps

## 1. 

> Give an example of a linear map $T$ with $\dim \operatorname{null} T=3$ and $\dim\operatorname{range}2.$

Define $T: \mathbb{F}^5\to\mathbb{F}^3$ by 

$$
T(z_1,z_2,z_3,z_4,z_5)=(0,z_4,z_5)
$$

## 2.

> Suppose $S,T\in\mathcal{L}(V)$ are such that $\operatorname{range} S\subseteq \operatorname{null}T.$ Prove that $(ST)^2=0.$

$$
(ST)^2=(ST)(ST)=ST(ST)=S(T(S(T)))=STST
$$

Since every element $Sv\in \operatorname{null}T,$ we take $(TS)(v)$ to be equivalent to $0(v)$ so that

$$
STST=S0T=0 \quad 🤌
$$

## 3.

> Suppose $v_1,...,v_m$ is a list of vectors in $V.$ Define $T\in \mathcal{L}(\mathbb{F}^m,V)$ by
>
> $$
> T(z_1,...,z_m)=z_1v_1+\cdots+z_mv_m.
> $$

### 3. (a)

> What property of $T$ corresponds to $v_1,...,v_m$ spanning $V$.

If $v_1,...,v_m$ spans $V$ then $\dim \operatorname{range} T=\dim V$ and $V$ is surjective.

### 3. (b)

> What property of $T$ corresponds to $v_1,...,v_m$ being linearly independent?

If $v_1,..,v_m$ is linearly independent in $V$ then for $z_1v_1+\cdots+z_mv_m=0$ we know $z_1=\cdots=z_m=0$ and then $\operatorname{null}T=\{0\}$ so $T$ is injective.

## 4.

> Show that $\{T\in\mathcal{L}(\mathbb{R}^5,\mathbb{R}^4) : \dim \operatorname{null} T > 2\}$ is not a subspace of $\mathcal{L}(\mathbb{R}^5,\mathbb{R}^4).$

Define $T_1(x_1,x_2,x_3,x_4,x_5)=(x_1,x_2,0,0)$ and $T_2(x_1,x_2,x_3,x_4,x_5)=(0,0,x_3,x_4).$ Both clearly in $\{T\in\mathcal{L}(\mathbb{R}^5,\mathbb{R}^4) : \dim \operatorname{null} T > 2\}.$

But observe

$$
(T_1+T_2)(x_1,x_2,x_3,x_4,x_5)=(x_1,x_2,x_3,x_4)
$$

which is clearly not in $\{T\in\mathcal{L}(\mathbb{R}^5,\mathbb{R}^4) : \dim \operatorname{null} T > 2\}.$ Therefore it is not closed under addition. 🤌

## 5.

> Give an example of $T\in\mathcal{L}(\mathbb{R}^4)$ such that $\operatorname{range} T = \operatorname{null} T$

Define

$$
T(x_1,x_2,x_3,x_4)=(x_3,x_4,0,0)
$$

## 6.

> Prove that there does not exist $T\in\mathcal{L}(\mathbb{R}^5)$ such that $\operatorname{range}T=\operatorname{null}T$

The fundamental theorem of linear maps states

$$
\dim V = \dim \operatorname{null} T + \dim \operatorname{range} T
$$

Filling in our known for $\dim V=5$

$$
5 = \dim \operatorname{null} T + \dim \operatorname{range} T
$$

For $\operatorname{range} T=\operatorname{null}T$ we must have $\dim \operatorname{range} T=\dim\operatorname{null}T$ so that 

$$
5 = 2x
$$

But $5$ is not even so it does not equal $2x.$ 🤌

## 7.

> Suppose $V$ and $W$ are finite-dimensional with $2\le\dim V\le\dim W.$ Show that $\{T\in\mathcal{L}(V,W):T \text{ is not injective}\}$ is not a subspace of $\mathcal{L}(V,W)$

<<<<<<< HEAD
Let's consider 

$$
\begin{align*}
S(x,y)&=(x,0)\\
T(x,y)&=(0,y)
\end{align*}
$$

Both clearly not injective. However,

$$
(S+T)(x,y)=S(x,y)+T(x,y)=(x,0)+(0,y)=(x,y)
$$

So clearly the sum of the maps is injective, and it is not closed under addition, and is not a subspace.. 🤌

## 8.

> Suppose $V$ and $W$ are finite-dimensional with $\dim V \ge \dim W \ge 2.$ Show that $\{T\in\mathcal{L}(V,W) : T \text{ is not surjective}\}$ is not a subspace of $\mathcal{L}(V,W).$

Consider the same maps from (7). Neither map is surjective, yet their sum clearly is, and is therefore outside the supposed subspace. It is therefore not closed under addition and not a subspace. 🤌

## 9.

> Suppose $T\in \mathcal{L}(V,W)$ is injective and $v_1,...,v_n$ is linearly independent in $V.$ Prove that $Tv_1,...,Tv_n$ is linearly independent in $W.$

If $Tv_1,...,Tv_n$ is linearly dependent in $W,$ then for some $a_1,...,a_n$ not all $0.$

$$
\begin{align*}
a_1Tv_1+\cdots+a_nTv_n&=0_W\\
Ta_1v_1+\cdots+Ta_nv_n&=0_W\\
T(a_1v_1+\cdots+a_nv_n)&=0_W\\
\end{align*}
$$
Since $T$ is injective, $\operatorname{null}T=\{0\}$ so

$$
a_1v_1+\cdots+a_nv_n=0_V
$$

Since $v_1,...,v_n$ is linearly independent in $V$ we know that $a_1=\cdots=a_n=0$ contradicting the previous statement that they are not all equal to 0. 🤌

## 10.

> Suppose $v_1,...,v_n$ spans $V$ and $T\in \mathcal{L}(V,W).$ Show that $Tv_1,...,Tv_n$ spans $\operatorname{range}T.$

Assume that $Tv_1,...,Tv_n$ does not span $\operatorname{range}T.$ Then there is some vector $w\in\operatorname{range}T$ and $w\notin\mathrm{span}(Tv_1,...,Tv_n).$ 

Since $w\in\operatorname{range}T,$ there exists some $u\in V$ for which $Tu=w.$ Since $v_1,...,v_n$ spans $V,$ there is some set of scalars $a_1,...,a_n$ for which

$$
u=a_1v_1+\cdots+a_nv_n
$$

but this being the case, we now see

$$
\begin{align*}
u&=a_1v_1+\cdots+a_nv_n\\
Tu&=T(a_1v_1+\cdots+a_nv_n)\\
w&=a_1Tv_1+\cdots+a_nTv_n\\
\end{align*}
$$

So clearly $w$ can be represented as a linear combination of $Tv_1,...,Tv_n$ and is therefore in $\mathrm{span}(Tv_1,...,Tv_n),$ contradicting our earlier assumption. 🤌

## 11.

> Suppose that $V$ is finite-dimensional and that $T\in \mathcal{L}(V,W).$ Prove that there exists a subspace $U$ of $V$ such that
>
> $$
> U\cap \operatorname{null}T=\{0\}\quad\text{ and }\quad\operatorname{range}T=\{Tu:u\in U\}
> $$
