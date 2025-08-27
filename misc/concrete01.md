# Knuth et al Concrete Mathematics Chapter 1

## Warmups

> 1. All horses are the same color; we can prove this by induction on the number of horses in a given set. Here's how: "If there's just one horse then it's the same color as itself, so the basis is trivial. For the induction step, assume that there are $n$ horses numbered $1$ to $n.$ By the induction step, assume that there are $n$ horses numbered $1$ to $n$. By the induction hypothesis, horses $1$ through $n-1$ are the same color, and similarly horses $2$ through $n$ are the same color. But the middle horses, $2$ through $n-1$, can't change color when they're in different groups; these are horses, not chameleons. So horses $1$ and $n$ must be the same color as well, by transitivity. Thus all $n$ horses are the same color; QED." What, if anything is wrong with this reasoning?

The induction step in this case depends on not just the previous instance but all the intervening instances, thus it breaks down at $2$ since there's no $2$ through $n-1$ for the second case.

> 2. Find the shortest sequence of moves that transfers a tower of n disks from the left peg A to the right peg B, if direct moves between A and B are disallowed. (Each move must be to or from the middle peg. As usual, a larger disk must never appear above a smaller one.)

The solution is

$$
n=3^n-1
$$

To prove it, observe the pattern a:b:c where the pegs are in ascending order.

**Case 1**

$$
\begin{align*}
M_0&=1:\_:\_\\
M_1&=\_:\_:1\\
M_2&=\_:1:\_\\
\end{align*}
$$

$$
3^1-1=2 \quad 🤌
$$

**Case n**

Assume $T_{k+1}=3T_k-1$

$$
\begin{align*}
T_n=3^n-1\\
\end{align*}
$$

