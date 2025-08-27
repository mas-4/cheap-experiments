# 2.16.b (example): linearly independent lists

Suppose $m$ is a nonnegative integer. To see that the list $1,z,...,z_m$ is linearly independent in $\mathcal{P}(\mathbb{F})$, suppose $a_0,a_1,...,a_m \in \mathbb{F}$ and
$$
a_0 + a_1z + \cdots + a_mz^m = 0,
$$
where we think of both sides as elements of $\mathcal{P}(\mathbb{F})$. Then
$$
a_0 + a_1z + \cdots + a_mz^m = 0,
$$
for all $z \in \mathbb{F}$. As discussed earlier (and as follows from 4.8), this implies that $a_0 = a_1 = \cdots = a_m = 0. Thus $1,z,...,z^m is a lienarly independent list in $\mathcal{P}(\mathbb{F})$.

# 2.19 linear dependence lemma

Suppose v_1,...,v_m is a linearly dependent list in V. Then there exists k \in \{1,2,...,m\} such that


v_k \in \mathrm{span}(v_1,...,v_{k-1})


Furthermore, if k satisfies the condition above and the k^{\text{th}} term is removed from v_1,...,v_m, then the span of the remaining list equals \mathrm{span}(v_1,...,v_m).

**Proof.** Because the list v_1,...,v_m is linearly dependent, there exist numbers a_1,...,a_m \in \mathbb{F}, not all 0, such that


a_1v_1 + \cdots + a_mv_m = 0


Let k be the largest element of \{1,...,m\} such that a_k \neq 0. Then


v_k = -\frac{a_1}{a_k}v_1 - \cdots - \frac{a_{k-1}}{a_k}v_{k-1}


which proves that v_k \in \mathrm{span}(v_1,...,v_m), as desired.

Now suppose k is any element of \{1,...,m\} such that v_k \in \mathrm{span}(v_1,...,v_{k-1}). Let b_1,...,b_{k-1} \in \mathbb{F} be such that


v_k = b_1v_1 + \cdots + b_{k-1}v_{k-1} \tag{2.20}


Suppose u \in \mathrm{span}(v_1,...,v_m). Then there exist c_1,...,c_m \in \mathbb{F} such that


u = c_1v_1 + \cdots + c_mv_m


In the equation above, we can replace v_k with the right side of 2.20, which shows that u is in the span of hte list obtained by removing the k^{\text{th}} term of the list v_1,...,v_m does not change the span of the list.