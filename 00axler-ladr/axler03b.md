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

Clearly not in $\{T\in\mathcal{L}(\mathbb{R}^5,\mathbb{R}^4) : \dim \operatorname{null} T > 2\}.$ Therefore it is not closed under addition. 🤌

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

