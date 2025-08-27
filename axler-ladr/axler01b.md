# Axler LADR Exercises 1b

## 1.  Prove that $-(-v) = v$ for every $v \in V$.

$$
\begin{align*}
-(-v) &= -1(-1v) \\
&= (-1\cdot-1)v \\
&= 1v \\
&= v \\
\end{align*}
$$

## 2. Suppose $a \in \mathbb{F}, v \in V$, and $av = 0$. Prove that $a = 0$ or $v = 0$.
Assume the opposite, that $av=0$ and $a \neq 0, v \neq 0$.

If $a \neq 0$, then we can multiply both sides by $a^{-1}$, the multiplicative inverse of $a$.
$$
\begin{align*}
a^{-1}av &= a^{-1}0 \\
v &= 0
\end{align*}
$$
Therefore, if $av=0$ and $a \neq 0$, $v$ must equal $0$. Thus it is not the case that $av = 0, a \neq 0, v \neq 0$.

## 3. Suppose $v,w \in V$. Explain why there exists a unique $x \in V$ such that $v + 3x = w$.

$$
\begin{align*}
v + 3x &= w \\
3x &= w - v \\
x &= \frac{1}{3}(w - v)
\end{align*}
$$

## 4. The empty set is not a vector space. The empty set fails to satisfy only one of the requirements listed in the definitions of a vector space (1.20). Which one?

There's no additive identity. It explicitly states there exists an element $0 \in V$ satisfying the conditions. Since no elements exist, it does not.

## 5. Show that in the definition of a vector space (1.20), the additive inverse can be replaced with the condition that $0v = 0$ for all $v \in V$.

It would suffice to show that the new condition implies the previous condition, and vice versa.

$$
\begin{align*}
0v = (1 - 1)v = 1v + -1v = v + (-v) = 0
\end{align*}
$$

Thus we see that the additive inverse and the condition $0v = 0$ are identical.

## 6. Paraphrase: "Is $\mathbb{R} \cup \{ \infty, -\infty \}$ with $t \in R$ accomodating the listed properties a vector space over $\mathbb{R}$?"

Addition is not associative.

$$
\begin{align*}
(1 + \infty) - \infty = \infty - \infty = 0 \neq 1 = 1 + 0 = 1 + (\infty - \infty)
\end{align*}
$$

## 7. Suppose $S$ is a nonempty set. Let $V^S$ denote the set of functions from $S$ to $V$. Define a natural addition and scalar multiplication on $V^S$, and show that $V^S$ is a vector space with these definitions.

We define natural addition as on $F^S$

An addition on a set S is the function

$$
\begin{align*}
f + g : S &\to V \\
x &\mapsto f(x) + g(x)
\end{align*}
$$

A scalar multiplication $\lambda \in F$ and $f \in V$ is defined

$$
\begin{align*}
\lambda f : S &\to V \\
x & \mapsto \lambda f(x)
\end{align*}
$$

$\textbf{Commutativity.}$ Observe that, for $f,g \in V^S$ and $x \in S$

$$
\begin{align*}
(f+g)(x) = f(x) + g(x) = g(x) + f(x) = (g+f)(x)
\end{align*}
$$

where the second equality is commutativity applied in V.

$\textbf{Associativity.}$ Observe that, for $f,g,h \in V^S$ and $x \in S$

$$
\begin{align*}
(f(x) + g(x)) + h(x) = (f + g)(x) + h(x) = (f + g + h)(x) = f(x) + (g + h)(x) = f(x) + (g(x) + h(x))
\end{align*}
$$

For the rest of the properties, note that the central operation occurs in V and therefore $V^S$ is a vector space.

## 8. Prove that with the definitions of addition and scalar multiplication, $V_C$ is a complex vector space.

$\textbf{Commutativity.}$ Observe that, for $u_1,v_1,u_2,v_2 \in V$

$$
\begin{align*}
(u_1 + iv_1) + (u_2 + iv_2) &= (u_1+u_2) + i(v_1+v_2) \tag{addition in $V_C$} \\
&= (u_2+u_1) + i(v_2+v_1) \tag{commutativity in $V$} \\
&= (u_2 + iv_2) + (u_1+iv_1) \tag{addition in $V_C$}
\end{align*}
$$

$\textbf{Associativity.}$ Observe that, for $u_1,v_1,u_2,v_2,u_3,v_3 \in V$

$$
\begin{align*}
((u_1 + iv_1) + (u_2 + iv_2)) + (u_3 + iv_3) &= ((u_1+u_2) + i(v_1+v_2)) + (u_3 + iv_3) \tag{addition in $V_C$} \\
&= (u_1+u_2+u_3) + i(v_1+v_2+v_3) \tag{addition in $V_C$} \\
&= (u_1+iv_1) + ((u_2+u_3) + i(v_2+v_3)) \tag{addition in $V_C$} \\
&= (u_1+iv_1) + ((u_2+iv_2) + (u_3+iv_3)) \tag{addition in $V_C$} \\
\end{align*}
$$

$\textbf{Additive Identity.}$ Observe that, $u,v \in V$

$$
\begin{align*}
u + iv &= (u + iv) + (0 + i0) \\
&= (u+0) + i(v+0) \tag{addition in $V_C$} \\
&= (u) + i(v) \tag{addition in $V$} \\
&= u + iv
\end{align*}
$$

$\textbf{Additive Inverse.}$ Observe that, $u,v \in V$

$$
\begin{align*}
(u+iv)+(-1+i0)(u+iv) &=(u+iv)+((-1u - 0v)+i(-1v+0u) \tag{scalar multiplication in $V_C$} \\
&=(u+iv)+(-u-iv) \tag{scalar multiplication in $V$} \\
&=(u-u)+i(v-v) \tag{addition in $V_C$} \\
&=0 + i0 \tag{addition in $V$} \\
\end{align*}
$$

$\textbf{Multiplicative Identity.}$ Observe that, $u,v \in V$

$$
\begin{align*}
u+iv &= (1+i0)(u+iv) \\
&= (1u - 0v) + i(1v+0u) \tag{scalar multiplication in $V_C$} \\
&= (u) + i(v) \tag{addition in $V$} \\
&= u + iv \tag{addition in $V_C$} \\
\end{align*}
$$

$\textbf{Distributive properties}$

Observe that, $u_1,v_1,u_2,v_2 \in V$ and $a,b \in R$

$$
\begin{align*}
(a+ib)((u_1+iv_1)+(u_2+iv_2)) &= (a+ib)((u_1+u_2)+i(v_1+v_2)) \tag{addition in $V_C$} \\
&= (a(u_1+u_2)-b(v_1+v_2)) + i(a(v_1+v_2)+b(u_1+u_2)) \tag{scalar multiplication in $V_C$} \\
&= ((au_1+au_2)+(-bv_1-bv_2)) + i((av_1+av_2)+(bu_1+bu_2)) \tag{distribution in $V$} \\
(a+ib)(u_1+iv_1)+(a+ib)(u_2+iv_2) &= ((au_1-bv_1) + i(av_1+bu_1)) + ((au_2-bv_2) + i(av_2+bu_2)) \tag{scalar multiplication in $V_C$} \\
&= ((au_1-bv_1)+(au_2-bv_2)) + i((av_1+bu_1)+(av_2+bu_2)) \tag{scalar multiplication in $V_C$} \\
&= ((au_1+ au_2)+(-bv_1-bv_2)) + i((av_1+av_2)+(bu_1+bu_2)) \tag{association in $V$} \\
\end{align*}
$$

A similar proof suffices for $(a+b)v = av+bv$.

That is all the properties.