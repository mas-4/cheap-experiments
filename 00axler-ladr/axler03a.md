# Axler LADR 3A Vector Spaces of Linear Maps

## Chapter Assertions

### Verify each example is a linear map

> 3.1 definition: linear map
>
> A *linear map* from $V$ to $W$ is a function $T: V \to W$ with the following properties.
>
> **additivity**
>
> $T(u+v)=Tu+Tv$ for all $u,v\in V.$
>
> **homogeneity**
>
> $T(\lambda v)=\lambda(Tv)$ for all $\lambda\in \mathbb{F}$ and all $v\in V.$
>
> Verify these linear maps.

> ## zero

First, we can see that

$$
0(u+v)=0=0+0=0u+0v\\
\lambda 0v=\lambda0=0=0\lambda=0\lambda v
$$

So 🤌.

> ## identity operator

If $Iv=v,$

$$
I(u+v)=u+v=Iu+Iv\\
\lambda I v =\lambda v =I\lambda v 🤌
$$

> ## differentiation

If $Dp=p'$

$$
\begin{align*}
D(p+q)&=(p+q)'=p'+q'=Dp+Dq \\
\lambda Dp &= \lambda p'= (\lambda p)'=D\lambda p 🤌
\end{align*}
$$

> ## integration

If $Tp=\int_0^1p,$ then

$$
T(p+q)=\int_0^1(p+q)=\int_0^1p+\int_0^1q=Tp+Tq\\
\lambda(Tp)=\lambda\int_0^1p=\int_0^1\lambda p=T\lambda p 🤌
$$

> ## multiplication by $x^2$

Define a linear map $T\in \mathcal{L}(\mathcal{P}(\mathbb{R}))$ by

$$
(Tp)(x)=x^2p(x)
$$

Then

$$
\begin{align*}
T(p+q)(x)&=x^2(p+q)(x)=x^2p+ x^2q=T p+T q \\
\lambda Tp(x)&=\lambda x^2p(x)=x^2\lambda p=T\lambda p(x) 🤌
\end{align*}
$$

> ## backward shift
> Recall that $\mathbb{F}^\infty$ denotes the vector space of all sequences of elements of $\mathbb{F}.$ Define a linear map $T\in\mathcal{L}(\mathbb{F}^\infty)$ by
>
> $$
> T(x_1,x_2,x_3,...)=(x_2,x_3,...).
> $$

Define two lists in $u,v \in \mathbb{F}^\infty.$ Then,

$$
T(u+v)=(u_2,u_3,...)+(v_2,v_3,...)=Tu+Tv\\
\lambda Tu=\lambda(u_2,u_3,...)=T\lambda u 🤌
$$

> ## from $\mathbb{R}^3$ to $\mathbb{R}^2$
> Define a linear map $T\in \mathcal{L}(\mathbb{R}^3,\mathbb{R}^2)$ by
>
> $$
> T(x,y,z)=(2x-y+3z,7x+5y-6z).
> $$

Well now, define $u=(x_u,y_u,z_u),v=(x_v,y_v,z_v)\in \mathbb{R}^3$

$$
\begin{align*}
T(u+v)&=(2(x_u+x_v)-(y_u+y_v)+3(z_u+z_v),7(x_u+x_v)+5(y_u+y_v)-6(z_u+z_v))\\
&=(2x_u-y_u+3z_u,7x_u+5y_u-6z_u)+(2x_v-y_v+3z_v,7x_v+5y_v-6z_v)\\
&=Tu+Tv
\end{align*}
$$

$$
\begin{align*}
\lambda Tu&=\lambda(2x_u-y_u+3z_u,7x_u+5y_u-6z_u)\\
&=(\lambda(2x_u-y_u+3z_u),\lambda(7x_u+5y_u-6z_u))\\
&=T\lambda u 🤌
\end{align*}
$$

> ## from $\mathbb{F}^n$ to $\mathbb{F}^m$
> To generalize the previous example, let $m$ and $n$ be positive integers, let $A_{j,k}\in \mathbb{F}$ for each $j=1,...,m$ and each $k=1,...,n,$ and define a linear map $T\in\mathcal{L}(\mathbb{F}^n,\mathbb{F}^m)$ by
>
> $$
> T(x_1,...,x_n)=(A_{1,1}x_1+\cdots+A_{1,n}x_n,...,A_{m,1}x_1+\cdots+A_{m,n}x_n).
> $$
>
> Actually, every linear map from $\mathbb{F}^n$ to $\mathbb{F}^m$ is of this form.

Extrapolating from the previous proof, we know that two vectors in $\mathbb{F}^n$ can be added in both domains and so retain additivity. The same argument applies to scalar multiplication. 🤌

> ## composition
> Fix a polynomial $q\in\mathcal{P}(\mathbb{R}).$ Define a linear map $T\in \mathcal{L}(\mathcal{P}(\mathbb{R}))$ by
> $$
> (Tp)(x)=p(q(x)).
> $$

We already know polynomials distribute scalars and additivity. This works and the proof is trivial. 🤌

***

> 3.5 definition: addition and scalar multiplication on $\mathcal{L}(V,W)$
>
> Suppose $S,T\in \mathcal{L}(V,W)$ and $\lambda \in \mathbb{F}.$ The *sum* $S+T$ and the *product* $\lambda T$ are the linear maps from $V$ to $W$ defined by
>
> $$
> (S+T)(v)=Sv+Tv\quad\text{ and }\quad(\lambda T)(v)=\lambda(Tv)
> $$
> for all $v\in V.$
>
> You should verify $S+T$ and $\lambda T$ as defined are indeed linear maps.

Well, I think we have the drill down, we know that linear maps retain additivity and homogeneity. So let's see if linear maps themselves have homogeneity and additivity.

$$
\begin{align*}
(S+T)(u+v)&=S(u+v)+T(u+v)\\
&=Su+Sv+Tu+Tv\\
&=Su+Tu+Sv+Tv\\
&=(S+T)u+(S+T)v\\
\end{align*}
$$

Hey, look at that we have additivity. Now let's try some fancy pants homogeneity.

$$
\begin{align*}
(\lambda T)(v)&=\lambda(Tv)\\
&=T(\lambda v)
\end{align*}
$$

In this case, we see homogeneity from our definition 3.5 in the first step, and then homogeneity on a linear map from definition 3.1. 🤌

Kinda tricky to think about this, but if we remember that $\mathcal{L}(V,W)$ is the set of all linear maps from $V\to W$ then we just established that combinations of linear maps are also linear maps. That's what this was all about.


## Exercises

> 1. Suppose $b,c\in\mathbb{R}.$ Define $T:\mathbb{R}^3\to\mathbb{R}^2$ by
> $$
> T(x,y,z)=(2x-4y+3z+b,6x+cxyz).
> $$
>
> Show that $T$ is linear if and only if $b=c=0.$

First, let's examine how additivity plays out for $u=(x_1,y_1,z_1),v=(x_2,y_2,z_2).$

$$
\begin{align*}
T(u+v)&=T(x_1+x_2,y_1+y_2,z_1+z_2)\\
&=(2(x_1+x_2)-4(y_1+y_2)+3(z_1+z_2)+b,6(x_1+x_2)+c(x_1+x_2)(y_1+y_2)(z_1+z_2)\\
T(u)+T(v)&=T(x_1,y_1,z_1)+T(x_2,y_2,z_2)\\
&=(2x_1-4y_1+3z_1+b,6x_1+cx_1y_1z_1)+(2x_2-4y_2+3z_2+b,6x_2+cx_2y_2z_2)\\
&=(2x_1-4y_1+3z_1+b+2x_2-4y_2+3z_2+b,6x_1+cx_1y_1z_1+6x_2+cx_2y_2z_2)\\
&=(2(x_1+x_2)-4(y_1+y_2)+3(z_1+z_2)+2b,6(x_1+x_2)+c(x_1y_1z_1+x_2y_2z_2))\\
\end{align*}
$$

You can see that the only difference between the two equations are the $b$ and $c$ terms. Therefore they are not linear if $b,c\ne0.$ On the other hand, if they are $0$ additivity is preserved. Now we have to show homogeneity when $b,c=0.$ Our map when that is the case is simplified:

$$
T(x,y,z)=(2x-4y+3z,6x)
$$

$$
\begin{align*}
\lambda T(v)&=\lambda T(x,y,z)\\
&=\lambda(2x-4y+3z,6x)\\
&=(2\lambda x-4\lambda y+3\lambda z,6\lambda x)\\
T(\lambda v)&=T(\lambda x,\lambda y,\lambda z)\\
&=(2\lambda x-4\lambda y+3\lambda z,6\lambda x) 🤌\\
\end{align*}
$$

> 2. Suppose $b,c\in \mathbb{R}.$ Define $T:\mathcal{P}(\mathbb{R})\to \mathbb{R}^2$ by 
>
> $$
> Tp=(3p(4)+5p'(6)+bp(1)p(2),\int^2_{-1}x^3p(x)dx+c\sin p(0)).
> $$
>
> Show that $T$ is linear if and only if $b=c=0.$

#TODO I still don't have a good sense for integration all my calculus skills have evaporated.

> 3. Suppose that $T\in \mathcal{L}(\mathbb{F}^n,\mathbb{F}^m).$ Show that there exist scalars $A_{j,k}\in \mathbb{F}$ for $j=1,...,m$ and $k=1,...,n$ such that
>
> $$
> T(x_1,...,x_n)=(A_{1,1}x_1+\cdots+A_{1,n}x_n,...,A_{m,1}x_1+\cdots+A_{m,n}x_n)
> $$
>
> for every $(x_1,...,x_n)\in \mathbb{F}^n.$

Every vector in $\mathbb{F}^n$ can be represented as a linear combination on the standard basis $e_1,...,e_n$ where each $e_k$ is a vector of zeroes with a $1$ in the $k$th position.

$$
T(x_1,...,x_n)=T(x_1e_1+\cdots+x_ne_n)
$$

Applying additivity and homogeneity we can see

$$
T(x_1e_1+\cdots+x_ne_n)=Tx_1e_1+\cdots+Tx_ne_n=x_1Te_1+\cdots+x_nTe_n $$

Since $T:\mathbb{F}^n\to\mathbb{F}^m$ each $e_k$ can be represented

$$
T(e_k)=(A_{1,k},...,A_{m,k})
$$

So 
$$
\begin{align*}
T(x_1,\ldots,x_n)&=x_1Te_1+\cdots+x_nTe_n\\
&=x_1(A_{1,1},\ldots,A_{m,1})+\cdots+x_n(A_{1,n},\ldots,A_{m,n})\\
&=(A_{1,1}x_1,\ldots,A_{m,1}x_1)+\cdots+(A_{1,n}x_n,\ldots,A_{m,n}x_n)\\
&=(A_{1,1}x_1+\cdots+A_{1,n}x_n,\ldots,A_{m,1}x_1+\cdots+A_{m,n}x_n) \quad 🤌
\end{align*}
$$

> 4. Suppose $T \in \mathcal{L}(V,W)$ and $v_1,...,v_m$ is a list of vectors in $V$ such that $Tv_1,...,Tv_m$ is a linearly independent list in $W.$ Prove that $v_1,...,v_m$ is linearly independent.

> 5. Prove that $\mathcal{L}(V,W)$ is a vector space, as was asserted in 3.6.

In the following proofs assume for all $u,v\in V,$ all $w\in W$ and all $S,T\in \mathcal{L}(V,W).$ Take this to be your warning not to bother me about trivial bureaucratic statements of universality.

### commutativity

Take any two $S,T\in\mathcal{L}(V,W).$

$$
(S+T)(v)=(S+T)v=Sv+Tv=Tv+Sv=(T+S)v=(T+S)(v)
$$

### associativity

Take any three $R,S,T\in\mathcal{L}(V,W).$

$$
R(v)+(S+T)(v)=Rv+(S+T)v=Rv+Sv+Tv=(R+S)v+Tv=(R+S)(v)+T(v)
$$

### distributivity

$$
\lambda (S+T)(v)=\lambda(Sv+Tv)=\lambda Sv+\lambda Tv=\lambda S(v)+\lambda T(v)
$$

### additive inverse

$$
-T(v)+T(v)=-Tv+Tv=0
$$

### additive identity

Consider the map $0v=0$ and the identity map $Iv=v,$ then

$$
0(v)+T(v)=0+Tv=Tv
$$

### multiplicative identity

$$
1\cdot T(v)=1\cdot Tv=Tv
$$

That's all required by Axler's definition, six properties. From that the other properties can be derived. 🤌

> 6. Prove that multiplication of linear maps has the associative, identity, and distributive properties asserted in 3.8.

> 7. Show that every linear map from a one-dimensional vector space to itself is multiplication by some scalar. More precisely, prove that if $\dim V=1$ and $T\in \mathcal{L}(V),$ then there exists $\lambda \in \mathbb{F}$ such that $Tv=\lambda v$ for all $v\in V.$

> 8. Give an example of a function $\phi:\mathbb{R}^2\to\mathbb{R}$ such that
>
> $$
> \phi(av)=a\phi(v)
> $$
>
> for all $a\in \mathbb{R}$ and $v\in \mathbb{R}^2$ but $\phi$ is not linear.
>
> > *This exercise and the next exercise show that neither homogeneity nor additivity alone is enough to imply that a function is a linear map.*

> 9. Give an example of a function $\phi: \mathbb{C}\to\mathbb{C}$ such that
>
> $$
> \phi(w+z)=\phi(w)+\phi(z)
> $$
>
> for all $w,z\in\mathbb{C}$ but $\phi$ is not linear. (Here $\mathbb{C}$ is thought of as a complex vector space.)
> > *There also exists a function \phi:\mathbb{R}\to\mathbb{R}$ such that $\phi$ satisfies the additivity condition but $\phi$ is not linear. However, the existence of such a function involves considerably more advanced tools.*

> 10. Prove or give a counterexample: If $q\in \mathcal{P}(\mathbb{R})$ and $T:\mathcal{P}(\mathbb{R})\to\mathcal{P}(\mathbb{R})$ is defined by $Tp=q\circ p,$ then $T$ is a linear map.
> > *The function $T$ defined here differs from the function $T$ defined nit eh last bullet point of 3.3 by the order of the functions in the compositions.*

> 11. Suppose $V$ is finite-dimensional and $T\in\mathcal{L}(V).$ Prove that $T$ is a scalar multiple of the identity if and only if $ST=TS$ for every $S\in\mathcal{L}(V).$