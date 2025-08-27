# Axler LADR Exercises 1c

## 1. For each of the following subsets of $F^3$ determine whether it is a subspace of $F^3$

#### (a) ${(x_1,x_2,x_3) \in F^3 : x_1 + 2x_2 + 3x_3 = 0}$

To determine if the set belongs we merely have to show it is closed under addition and scalar multiplication and the
additive identity is in the set.

For the additive identity, test whether the 0 vector holds:

$$
(0,0,0) : 0 + 2(0) + 3(0) = 0
$$

To show closure under addition, we take two arbitrary elements of the set $(u_1, u_2, u_3)$
and $(v_1, v_2, v_3)$ $u1, u2, u3, v1, v2, v3 \in F$ and show that their sum is also in the set.

If $u + v &= (u_1 + v_1, u_2 + v_2, u_3 + v_3),

$$
\begin{align*}
(u_1 + v_1) + 2(u_2 + v_2) + 3(u_3 + v_3) &= u_1 + v_1 + 2u_2 + 2v_2 + 3u_3 + 3v_3 \\
&= (u_1 + 2u_2 + 3u_3) + (v_1 + 2v_2 + 3v_3) \\
&= 0 + 0 \\
&= 0
\end{align*}
$$

To show closure under scalar multiplication, we take an arbitrary element of the set $(u_1, u_2, u_3)$ and a
scalar $c \in F$ and show that their product is also in the set. Assume $(u_1, u_2, u_3) \in F^3$ and $\lambda \in F$.
If $\lambda \cdot (u_1, u_2, u_3) = (\lambda u_1, \lambda u_2, \lambda u_3)$, then

$$
\begin{align*}
\lambda u_1 + 2(\lambda u_2) + 3(\lambda u_3) &= \lambda (u_1 + 2u_2 + 3u_3) \\
&= \lambda \cdot 0 \\
&= 0
\end{align*}
$$

#### (b) ${(x_1,x_2,x_3) \in F^3 : x_1 + 2x_2 + 3x_3 = 4}$

The additive identity is not in the set since $x_1 + 2x_2 + 3x_3 = 0 \neq 4$, therefore we can conclude that this set is
not a subspace of $F^3$.

#### (c) ${(x_1,x_2,x_3) \in F^3 : x_1x_2x_3 = 0}$

$0\cdot0\cdot0 = 0$, so the additive identity is in the set.

Assuming $u+v = (u_1 + v_1, u_2 + v_2, u_3 + v_3)$, we have

$$
\begin{align*}
(u_1 + v_1)(u_2 + v_2)(u_3 + v_3) &= (u_1u_2 + u_1v_2 + v_1u_2 + v_1v_2)(u_3 + v_3) \\
&= u_1u_2u_3 + u_1u_2v_3 + u_1v_2u_3 + u_1v_2v_3 + v_1u_2u_3 + v_1u_2v_3 + v_1v_2u_3 + v_1v_2v_3 \\
&= 0 + u_1u_2v_3 + u_1v_2u_3 + v_1u_2v_3 + v_1v_2u_3 + 0 \\
\end{align*}
$$

We can see that the sum is not necessarily zero, so the set is not closed under addition and therefore not a subspace
of $F^3$.

#### (d) ${(x_1,x_2,x_3) \in F^3 : x_1 = 5x_3}$

First, for $(0,0,0)$< $0 = 5(0)$, so the additive identity is in the set.

Second, for closure under addition, let $(u_1, u_2, u_3)$ and $(v_1, v_2, v_3)$ be in the set. Then $u_1 = 5u_3$
and $v_1 = 5v_3$, and
$u_1 + v_1 = 5u_3 + 5v_3 = 5(u_3 + v_3)$, so the sum is also in the set.

Finally, for $\lambda \in F$, we have $\lambda(u_1, u_2, u_3) = (\lambda u_1, \lambda u_2, \lambda u_3)$,
and $\lambda u_1 = \lambda(5u_3) = 5(\lambda u_3)$, so the scalar multiple is also in the set. Therefore, this set is a
subspace of $F^3$.

## 2. Verify all assertions about subspaces in Example 1.35.

#### (a) If $b \in F$, then $\{(x_1,x_2,x_3,x_4) \in F^4 : x_3 = 5x_4 + b\}$ is a subspace of $F^4$ if and only if $b=0$.

For $(0,0,0,0) : 0 = 5(0) + b$ only in the case that $b = 0$.

For $u,v \in \mathbb{F^4} : u_3 + v_3 = 5u_4 + 5v_4 + 2b = 5(u_4 + v_4) + 2b$.

But since $(u+v)_3 = 5(u+v)_4 + b$ and $u_4+v_4 = (u+v)_4$, $5(u_4+v_4) + 2b = 5(u_4 + v_4) + b$ and

$$
\begin{align*}
5(u_4+v_4) + 2b &= 5(u_4 + v_4) + b \\
2b &= b
\end{align*}
$$

So the set is closed under addition iff $b = 0$.

#### (b) The set of continuous real-valued functions on the interval [0,1] is a subspace of $R^{[0,1]}$.

- $f(x) = 0$ is continuous, so the zero function is in the set.
- $f(x) + g(x)$ is continuous if $f$ and $g$ are continuous, so the set is closed under addition.
- $c f(x)$ is continuous if $f$ is continuous and $c$ is a scalar, so the set is closed under scalar multiplication.

#### (c) The set of differentiable real-valued functions on R is a subspace of $\mathbb{R}^{\mathbb{R}}$.

- The derivative of $f(x) = 0$ is 0 everywhere, so zero function is in the set.
- Because $(f+g)(x)$ is differentiable if $f$ and $g$ are differentiable, the set is closed under addition.
- Because $cf(x)$ is differentiable if $f$ is differentiable and $c$ is a scalar, the set is closed under scalar
  multiplication.

#### (d) The set of differentiable real-valued functions $f$ on the interval $(0,3)$ such that $f'(2) = b$ is a subspace of $R^{(0,3)}$ if and only if $b = 0$.

To verify this, we need to check the conditions for a subspace:

- The zero function $f(x) = 0$ has $f'(2) = 0$, so it is in the set if $b = 0$.
- Because $f'(x) + g'(x) = (f + g)'(x)$, $f'(x) = b$ and $g'(x) = b$ implies $(f + g)'(x) = 2b$, so the set is closed
  under addition if $b = 0$.
- Because $c f'(x) = c b$ for any scalar $c$, the set is closed under scalar multiplication if $b = 0$.

But if $b \neq 0$,

- the zero function is not in the set, because $f'(2) = 0 \neq b$,
- and the set is not closed under addition because $(f + g)'(2) = b + b = 2b \neq b$,
- or scalar multiplication because $c f'(2) = c b \neq b$ for $c \neq 1$ and $c \neq 0$.

Therefore, the set is a subspace of $R^{(0,3)}$ if and only if $b = 0$.

#### (e) The set of all sequences of complex numbers with limit 0 is a subspace of $C^\infty$

- First, (0 + 0i, 0 + 0i, 0 + 0i, ...) is in the set because the limit of the zero sequence is 0.
- Second, because $\lim_{n \to \infty} (a_n + b_n) = \lim_{n \to \infty} a_n + \lim_{n \to \infty} b_n = 0 + 0 = 0$, the
  set is closed under addition.
- Third, because $\lim_{n \to \infty} (c a_n) = c \lim_{n \to \infty} a_n = c \cdot 0 = 0$ for any scalar $c$, the set
  is closed under scalar multiplication.

## 3. Show that the set of differentiable real-valued functions $f$ on the interval $(-4,4)$ such that $f'(-1) = 3f(2)$ is a subspace of $R^{(-4,4)}$.

First, the derivative of $f(x) = 0$ is $f'(x) = 0$ so for the zero function

$$
\begin{align*}
f'(-1) &= 3f(2) \\
0 &= 3(0) ✅
\end{align*}
$$

Next, since $f'(x) + g'(x) = (f+g)'(x)$,

$$
\begin{align*}
3f(2) + 3g(2) &= f'(-1) + g'(-1) \\
&= (f+g)'(-1) ✅
\end{align*}
$$

Finally, since assuming $\lambda \in R$

$$
(\lambda f)'(-1)  = \lambda \cdot f'(-1) = \lambda \cdot 3f(2) = 3(\lambda f)(2)  ✅
$$

## 4. Suppose $b \in \mathbb{R}$. Show that the set of continuous real-valued functions $f$ on the interval $[0,1]$ such that $\int_{0}^{1}f = b$ is a subspace of $\mathbb{R}^{[0,1]}$ if and only if $b = 0$.

First, for the zero function $f(x) = 0 : \int_{0}^{1}f = 0$ so the additive identity is in the set. But if $b\neq0$ then $\int_{0}^{1}f\neq b$ so the additive identity is in the set iff $b=0$.

Second, for $\int_{0}^{1}f = b$ and $\int_{0}^{1}g = b$, since $\int_{0}^{1}f + \int_{0}^{1}g = \int_{0}^{1}(f+g)$,

$$
b = \int_{0}^{1}(f+g) = \int_{0}^{1}f + \int_{0}^{1}g = b + b = 2b
$$

So that addition is closed under addition if and only if $b = 0$

Finally, for $\int_{0}^{1}f = b$ and $\lambda \in \mathbb{R}$, since $\lambda \cdot \int_{0}^{1}f = \int_{0}^{1}\lambda f$,

$$
b = \int_{0}^{1}\lambda f = \lambda \int_{0}^{1}f = \lambda \cdot b
$$

But $\lambda b = b$ for all $\lambda \in \mathbb{R}$ if and only if $b = 0$, so once again, the set is closed under scalar multiplication if and only if $b = 0$.

## 5. Is $\mathbb{R}^2$ a subspace of the complex vector space $\mathbb{C}^2$?

No, because while the additive identity is present and it is also closed under addition, it is not closed under scalar multiplication because the scalars come from $\mathbb{C}$ not $\mathbb{R}$.

## 6.
#### (a) Is $\{(a,b,c) \in \mathbb{R}^3 : a^3 = b^3\}$ a subspace of $\mathbb{R}^3$?

First, $0^3 = 0^3$ so the additive identity is in the set.

Second, it is useful to note that 

$$
(-1)^n =
\begin{cases}
1 & \text{if } n \text{ is even} \\
-1 & \text{if } n \text{ is odd}
\end{cases}
$$

As a result, since $f(x) = x^3$ is strictly increasing, it must be that $a = b$. So our set is really $\{(a,a,b) \in \mathbb{R}^3\}$. So, $(a,a,b) + (c,c,d) = (a+c,a+c,b+d)$ and we know that $a+c = a+c$ so the sum is in the set and the space is closed under addition.

Likewise, for $\lambda \in \mathbb{R}$, $\lambda(a, a, c) = (\lambda a, \lambda a, \lambda c)$ with the result that $\lambda a = \lambda a$ and the scalar multiplication is still in our set.

So it is a subspace.

#### (b) Is $\{(a,b,c) \in \mathbb{C}^3 : a^3 = b^3 \}$ a subspace of $\mathbb{C}^3$?

To prove this is not a subspace we can identify a counter example that is not closed under addition. We will use $u = (1,1,0)$ and $v = (1, \omega, 0)$ where $\omega = -\frac{1}{2} + \frac{\sqrt 3}{2}i$, one of the cube roots of unity. Since $\omega^3 = 1^3$ the condition holds for both $u$ and $v$.

$$
(1,1,0) + (1,\omega,0) = (2, 1+\omega, 0)
$$

And yet, $8 = 2^3 \neq (1+\omega)^3$ since

$$
\begin{align*}
(1 + \omega)^3 &= (1 + \omega)(1 + \omega)(1 + \omega) \\
&= (1 + 2\omega + \omega^2)(1 + \omega) \\
&= (1 + 3\omega + 3\omega^2 +  \omega^3) \\
&= 2 + 3\omega + 3\omega^2 \\
&= 2 + 3(\omega + \omega^2) \\
\end{align*}
$$

But since, for $\omega^3 = 1$, $\omega^3 - 1 = (\omega - 1)(\omega^2+\omega+1) = 0$ and for one of these roots $\omega^2 + \omega = -1$

$$
\begin{align*}
&= 2 + 3(-1) \\
&= 2 - 3 \\
&= -1
\end{align*}
$$

Then, clearly, $(1 + \omega)^3 \neq 2^3 = 8$.

## 7. Prove or give a counterexample: If $U$ is a nonempty subset of $\mathbb{R}^2$ such that $U$ is closed under addition and under taking additive inverses (meaning $-u \in \mathbb{U}$ whenever $u \in \mathbb{U}$), then $U$ is a subspace of $\mathbb{R}^2$.

There are 3 conditions of subspaces. The prompt gives us closed under addition, so that's one.

The second is the existence of the additive identity, and this is clear from it being closed under addition and additive inverses, so that $-u + u = 0$.

The third is closed under scalar multiplication, and this is not clear. A good counterexample is $\{(a,b) \in \mathbb{R}^2 : a,b \in \mathbb{Z}\}$. It is closed under addition and has the additive identity, but since scalars come from the parent space, it is not closed under scalar multiplication. So it is not actually a subspace of $\mathbb{R}^2$.

## 8. Give an example of a nonempty subset of $U$ of $\mathbb{R}^2$ such that $U$ is closed under scalar multiplication, but $U$ is not a subspace of $R^2$.

${(x_1,x_2) \in R^2 : x_1x_2 = 0}$, adapted from problem 1c above, is closed under scalar multiplication but is not closed under addition

## 9. A function $f: \mathbb{R} \to \mathbb{R}$ is called _periodic_ if there exists a positive number $p$ such that $f(x) = f(x+p)$ for all $x \in \mathbb{R}$. Is the set of periodic functions from $\mathbb{R}$ to $\mathbb{R}$ a subspace of $\mathbb{R}^\mathbb{R}$? Explain.

The periodic set is not a subspace of $\mathbb{R}^\mathbb{R}$ because it is not closed under addition. 

For example, let $f(x) = \sin(x)$ and $g(x) = \sin(\sqrt 2 x)$, both of which are periodic functions with periods $2\pi$ and $\frac{2}{\sqrt 2} \pi$ respectively.

Their sum, $f(x) + g(x) = \sin(x) + \sin(\sqrt 2 x)$, is not periodic because it does not have a single period that satisfies the periodic condition for all $x$.

$sin(x)$ has period $p = 2\pi k$ and $sin(\sqrt 2 x)$ has period $p = \sqrt{2} \pi m$ 

Setting these equal

$$
\begin{align*}
2\pi k &= \sqrt 2 \pi m \\
2k &= \sqrt 2 m \\
m &= \frac{2k}{\sqrt 2} = k\sqrt 2
\end{align*}
$$

But since both k and m are integers, $k\sqrt 2$ is not an integer unless $k = 0$, which is not a positive number. Therefore, there is no common period for the sum of these two functions, and thus the set of periodic functions is not closed under addition.

## 10. Suppose $V_1$ and $V_2$ are subspaces of a vector space $V$. Prove that the intersection $V_1 \cap V_2$ is a subspace of $V$.

First, since the additive identity is in both $V_1,V_2$, the additive identity is also in $V_1 \cap V_2$.

Second, since $u,v\in V_1$ and $u,v \in V_2$ because $u,v \in V_1 \cap V_2$, we have that $(u+v) \in V_1$ and $(u+v) \in V_2$, so it is closed under addition.

Third, since for $\lambda \in F, v \in V_1, \lambda v \in V_1$ and $\lambda \in F, v \in V_2, \lambda v \in V_2$, because $v \in V_1 \cap V_2$, therefore $V_1 \cap V_2$ is also closed under scalar multiplication.

## 11. Prove that the intersection of every collection of subspaces of $V$ is a subspace of $V$.

Since every possible subspace of $V$ has the additive identity, the intersection of any collection of subspaces would likewise have the additive identity.

Likewise, since $u,v \in V_i$ for the collection, $u+v \in V_i$ for the collection.

Finally, since each $V_i$ is closed under scalar multiplication, for any $\lambda \in \mathbb{F}$ and $u \in \bigcap V_i$, we have $\lambda u \in V_i$ for each $V_i$ in the collection, so $\lambda u \in \bigcap V_i$.

## 12. Prove that the union of the two subspaces of $V$ is a subspace of $V$ if and only if one of the subspaces is contained in the other.

To prove that the union is a subspace, we need only acknowledge that for $V_1 \subseteq V_2, v_i \in V_1 \subseteq V_2$, so that $V_1 \cup V_2$ is effectively equivalent to $V_2$. Since $V_2$ is a subspace of $V$, $V_1 \cup V_2$ is also a subspace of $V$. The reverse argument is identical.

To prove that it is the only subspace, let's assume $V_1 \not\subseteq V_2$ and $V_2 \not\subseteq V_1$. While the union does have the additive identity, in this case it is not closed under addition. Since there exists a $u \in V_1$ with $u \notin V_2$ and $v \in V_2$ with $v \notin V_1$. 

Consequently, if the union is closed under addition, $u + v$ must exist in $V_1$ or $V_2$ by the definition of a union. If $u + v \in V_1$, we also have $v = (u + v) - u \in V_1$ but this leaves $v$ stranded in $V_1$. The same argument applies to $(u + v) \in V_2$. Consequently, the sum is in neither subspace and therefore the union is not closed under addition and not a subspace.

## 13. Prove that the union of three subspaces of $V$ is a subspace of $V$ if and only if one of the two subspaces contains the other two.

Like the previous proof, since two of the subspaces are contained in the third, the union is equivalent to the third, and since the third is a subspace, the union is therefore a subspace.

For the other side of the proof, since we none of the three subspaces contain the other two, we can take an element

$$
\begin{align*}
v_1  \in V_1 \text{ with } v_1 \notin V_2 \cup V_3 \\
v_2  \in V_2 \text{ with } v_2 \notin V_1 \cup V_3 \\
v_3  \in V_3 \text{ with } v_3 \notin V_1 \cup V_2
\end{align*}
$$

As a result, we can see to take $(v_1 + v_2 + v_3) \in V_1 \cup V_2 \cup V_3$ similar logic from the previous proof applies. Namely, the sum must be in $V_1 \cup V_2, V_2 \cup V_3,$ or $V_1 \cup V_3$.

$$
\begin{align*}
v_1 + v_2 &= (v_1 + v_2 + v_3) - v_3 \in V_2 \cup V_3
v_1 &= (v_1 + v_2) - v_2 \in V_2 \cup V_3
\end{align*}
$$

But this contradicts our statement that $v_1 \notin V_2 \cup V_3$.

The same argument applies to $v_1$ and $v_2$. Therefore, the union is not closed under addition, and is not a subspace of $V$.

## 14. Suppose $U = \{(x,-x,2x) \in \mathbb{F}^3 : x \in \mathbb{F} \}$ and $W = \{(x,x,2x) \in \mathbb{F}^3 : x \in \mathbb{F} \}$. Describe $U + W$ using symbols, also give a description of $U + W$ that uses no symbols.

Take $(a,-a,2a) + (b,b,2b) = (a+b, b-a, 2a+2b)$. Setting $x=a+b$ and $y=b-a$, then $U + W = \{(x,y,2x)\in \mathbb{F}^3 : x,y \in \mathbb{F} \}$

This describes a plane in $\mathbb{F}^3$ whose z coordinate is twice the x coordinate.

## 15. Suppose $U$ is a subspace of $V$. What is $U + U$?

Well, since $U$ is closed under addition, every element $u_1 + u_2$ is already in $U$.

## 16. Is the operation of addition on the subspaces of $V$ commutative? In other words, if $U$ and $W$ are subspaces of $V$, is $U + W = W + U$.

Every element of $U + W$ has the form $u + w$ for some $u ∈ U, w ∈ W$.

Since vector addition is commutative:
$u + w = w + u$

Therefore every element of $U + W$ is also in $W + U$, and vice versa.

Thus $U + W = W + U$.

## 17. Is the operation of addition on the subspaces of $V$ associative? In other words, if $V_1, V_2, V_3$ are subspaces of $V$, is $(V_1 + V_2) + V_3 = V_1 + (V_2 + V_3)$?

Every element $v_1 \in V_1, v_2 \in V_2, v_3 \in V_3$ can be arranged $(v_1 + v_2) + v_3$, and since vector addition is associative it can be rearranged $v_1 + (v_2 + v_3)$, so subspace addition is also associative.

## 18. Does the operation of addition on the subspaces of $V$ have an additive identity? Which subspaces have additive inverses?

There is an additive identity, the $\{0\}$ set.

However, there is no additive inverse. Because a subspace is a collection of elements and addition on those subspaces is defined as the set of all possible additions between the elements in the added subspaces, there is no subspace containing any set of elements that can cancel out every element in another subspace.

## 19. Prove or give a counterexample: If $V_1, V_2, U$ are subspaces of $V$ such that $V_1 + U = V_2 + U$, then $V_1 = V_2$. 

Consider $U = \{(x,0) \in \mathbb{F}^2\}, V_1 = \{(0,y) \in \mathbb{F}^2\}, V_2 = \{(y,y) \in \mathbb{F}^2\}$.

## 20. Suppose $U = \{(x,x,y,y) \in \mathbb{F}^4 : x,y \in \mathbb{F}\}$. Find a subspace $W$ of $\mathbb{F}^4$ such that $\mathbb{F}^4 = U \oplus W$.

$\{(0,x,0,y) \in \mathbb{F}^4 : x,y \in \mathbb{F}^4$

## 21. Suppose $U = \{(x,y,x+y,x-y,2x) \in \mathbb{F}^5 : x,y \in F\}$. Find a subspace in $\mathbb{F}^5$ such that $\mathbb{F}^5 : x,y \in \mathbb{F}\}$.

$\{(0,0,x,y,z) \in \mathbb{F}^5 : x,y,z \in \mathbb{F}$

## 22. Suppose $U = \{(x,y,x+y,x-y,2x) \in \mathbb{F}^5 : x,y \in \mathbb{F}\}. Find three subspaces $W_1,W_2,W_3 of $\mathbb{F}^5$, none of which equals $\{0\}$, such that $\mathbb{F}^5 = U \oplus W_1 \oplus W_2 \oplus W_3$.

$$
\begin{align*}
W_1 &= \{(0,0,x,0,0) \in \mathbb{F}^5 : x \in \mathbb{F}\} \\
W_2 &= \{(0,0,0,x,0) \in \mathbb{F}^5 : x \in \mathbb{F}\} \\
W_3 &= \{(0,0,0,0,x) \in \mathbb{F}^5 : x \in \mathbb{F}\}
\end{align*}
$$

## 23. Prove or give a counterexample: If $V-1,V_2,U$ are subspaces of $V$ such that $V = V_1 \oplus U$ and $V = V_2 \oplus U$ then $V_1 = V_2$. 

**Counterexample:** The statement is false.

Let $V = \mathbb{F}^2$ and define:
- $U = \{(0, y) : y \in \mathbb{F}\}$ (the set of all points on the $y$-axis)
- $V_1 = \{(x, 0) : x \in \mathbb{F}\}$ (the set of all points on the $x$-axis)
- $V_2 = \{(x, x) : x \in \mathbb{F}\}$ (the set of all points on the line $y = x$)


For $V = V_2 \oplus U$:
- $V_2 \cap U = \{(0, 0)\}$ (only the origin is in both)
- Every $(x, y) \in \mathbb{F}^2$ can be written as $(x, y) = (x, x) + (0, y - x)$ where $(x, x) \in V_2$ and $(0, y - x) \in U$
- Therefore $V_2 \oplus U = \mathbb{F}^2$

However, $V_1 \neq V_2$ since $(1, 0) \in V_1$ but $(1, 0) \notin V_2$.

Therefore, we have $V = V_1 \oplus U$ and $V = V_2 \oplus U$, but $V_1 \neq V_2$, disproving the statement.

## 24. A function $f: \mathbb{R} \to \mathbb{R}$ is called _even_ if $f(-x) = f(x)$ for all $x \in \mathbb{R}$. A function $f: \mathbb{R} \to \mathbb{R}$ is called _odd_ if $f(-x) = -f(x)$ for all $x \in \mathbb{R}$. Let $V_e$ denote the set of real-valued even functions on $ \mathbb{R}$ and let $V_o$ denote the set of real-valued odd functions on $ \mathbb{R}$. Show that $ \mathbb{R}^\mathbb{R} = V_e \oplus V_o$.

Consider that every function can be written as a sum of two functions, an odd and even part, such that $f(x) = g(x) + h(x)$. From the definitions of odd and even we also have $f(-x) = g(x) + (-h(x)) = g(x) - h(x)$. We solve for $g(x),h(x)$ from our two equations


$$
\begin{align*}
f(x) &= g(x) + h(x) \\
f(-x) &= g(x) - h(x)
\end{align*}
$$

Adding the two equations:

$$
\begin{align*}
f(x) + f(-x) &= 2g(x) \\
g(x) = \frac{f(x) + f(-x)}{2}
\end{align*}
$$

Subtracting the two equations

$$
\begin{align*}
f(x) - f(-x) &= 2h(x) \\
h(x) = \frac{f(x) - f(-x)}{2}
\end{align*}
$$

Now, adding $g(x) + h(x)$

$$
\begin{align*}
f(x) &= g(x) + h(x) \\
f(x) &= \frac{f(x) + f(-x)}{2} + \frac{f(x) - f(-x)}{2} \\
f(x) &= \frac{(f(x) + f(-x)) + (f(x) - f(-x))}{2} \\
f(x) &= \frac{f(x) + f(x)}{2} \\
f(x) &= \frac{2f(x)}{2} = f(x)
\end{align*}
$$

To prove they are a direct sum, we set them equal and solve for x:

$$
\begin{align*}
g(-x) &= h(-x)
g(x) &= -h(x)
g(x) &= -1 \cdot h(x)
\end{align*}
$$

Since only the zero function is equal to itself when $-1$ is applied to it through scalar multiplication, the only time g(x) and h(x) are equal is the zero function.