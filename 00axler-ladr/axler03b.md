- [Axler LADR 3A Vector Spaces of Linear Maps](#axler-ladr-3a-vector-spaces-of-linear-maps)
  - [1.](#1)
  - [2.](#2)
  - [3.](#3)
    - [3. (a)](#3-a)



# Axler LADR 3A Vector Spaces of Linear Maps

## 1. 

> Give an example of a linear map $T$ with $\dim \operatorname{null} T=3$

Define $T: \mathbb{F}^3\to\mathbb{F}^3$ by 

$$
T(z_1,z_2,z_3)=(0,0,0)
$$

## 2.

> Suppose $S,T\in\mathcal{L}(V)$ are such that $\operatorname{range} S\subseteq \operatorname{null}T.$ Prove that $(ST)^2=0.$

$$
(ST)^2=(ST)(ST)=ST(ST)=S(T(S(T)))=STST
$$

Since every element $Sv\in \operatorname{null}T,$ we take $(TS)(v)$ to be equivalent to $0(v)$ so that

$$
STST=S0T=0
$$

## 3.

> Suppose $v_1,...,v_m$ is a list of vectors in $V.$ Define $T\in \mathcal{L}(\mathbb{F}^m,V)$ by
>
> $$
> T(z_1,...,z_m)=z_1v_1+\cdots+z_mv_m.
> $$

### 3. (a)

> What property of $T$ corresponds to $v_1,...,v_m$ spanning $V$.
