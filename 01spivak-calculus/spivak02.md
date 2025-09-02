- [Spivak's Calculus Chapter 02 Exercises](#spivaks-calculus-chapter-02-exercises)
  - [1.](#1)
    - [1. (i)](#1-i)
    - [1. (ii)](#1-ii)
  - [2.](#2)
    - [2. (i)](#2-i)
    - [2. (ii)](#2-ii)
  - [3.](#3)
    - [3. (a)](#3-a)
    - [3. (b)](#3-b)
    - [3. (c)](#3-c)
    - [3. (d)](#3-d)
    - [3. (e)](#3-e)
      - [3. (e) (i)](#3-e-i)
      - [3. (e) (ii)](#3-e-ii)
      - [3. (e) (iii)](#3-e-iii)
      - [3. (e) (iv)](#3-e-iv)
  - [4.](#4)
    - [4. (a)](#4-a)
    - [4. (b)](#4-b)
    - [5. (a)](#5-a)
    - [5. (b)](#5-b)
  - [6.](#6)
    - [7. (i)](#7-i)
    - [7. (ii)](#7-ii)
    - [7. (iii)](#7-iii)
    - [7. (iv)](#7-iv)
  - [7.](#7)
  - [8.](#8)
  - [9.](#9)
  - [10.](#10)
  - [11.](#11)
  - [12.](#12)
    - [12. (a)](#12-a)
    - [12. (b)](#12-b)
    - [12. (c)](#12-c)
    - [12. (d)](#12-d)
  - [13.](#13)
    - [13. (a)](#13-a)
    - [13. (b)](#13-b)
  - [14.](#14)
    - [14. (a)](#14-a)
    - [14. (b)](#14-b)
  - [15.](#15)
    - [15. (a)](#15-a)
    - [15. (b)](#15-b)
  - [16.](#16)
    - [16. (a)](#16-a)
    - [16. (b)](#16-b)


# Spivak's Calculus Chapter 02 Exercises

## 1.

> Prove the following formulas by induction.

### 1. (i)

> $1^2+\cdots+n^2=\frac{n(n+1)(2n+1)}{6}.$

**Case 1**

$$
\begin{align*}
1^2&=\frac{1(1+1)(2\cdot1+1)}{6}\\
1&=\frac{1(2)(3)}{6}\\
&=\frac{6}{6}\\
\end{align*}
$$

**Case n**

$$
\begin{align*}
1^2+\cdots+n^2&=\frac{n(n+1)(2n+1)}{6}\\
1^2+\cdots+n^2+(n+1)^2&=\frac{n(n+1)(2n+1)}{6}+(n+1)^2\\
&=\frac{n(n+1)(2n+1)}{6}+\frac{6(n+1)^2}{6}\\
&=\frac{n(n+1)(2n+1)+6(n+1)^2}{6}\\
&=\frac{(n+1)[n(2n+1)+6(n+1)]}{6}\\
&=\frac{(n+1)[2n^2+n+6n+6]}{6}\\
&=\frac{(n+1)[2n^2+7n+6]}{6}\\
&=\frac{(n+1)(n+2)(2n+3)}{6}\\
&=\frac{(n+1)((n+1)+1)(2n+2+1)}{6}\\
&=\frac{(n+1)((n+1)+1)(2(n+1)+1)}{6} \quad🤌\\
\end{align*}
$$

### 1. (ii)

> $1^3+\cdots+n^3=(1+\cdots+n)^2$

**Case 1**

$$
\begin{align*}
1^3=(1)^2\\
\end{align*}
$$

**Case n**

It would be helpful to recognize that

$$
\begin{align*}
1+\cdots+n&=1+\cdots+n\\
2(1+\cdots+n)&=(1+\cdots+n)+(1+\cdots+n)\\
&=(1+n)+\cdots+(n+1)\\
&=\frac{n(n+1)}{2}\\
\end{align*}
$$

So that

$$
\begin{align*}
1^3+\cdots+n^3=(1+\cdots+n)^2&=(\frac{n(n+1)}{2})^2\\
1^3+\cdots+n^3+(n+1)^3&=\frac{n^2(n+1)^2}{4}+(n+1)^3\\
&=\frac{n^2(n+1)^2}{4}+(n+1)^3\\
&=\frac{n^2(n+1)^2+4(n+1)^3}{4}\\
&=\frac{(n+1)^2[n^2+4(n+1)]}{4}\\
&=\frac{(n+1)^2[n^2+4n+4]}{4}\\
&=\frac{(n+1)^2(n+2)^2}{4}\\
&=(\frac{(n+1)[(n+1)+2]}{2})^2 \quad 🤌\\
\end{align*}
$$

## 2.

> Find a formula for
>
> Hint: What do these expressions have to do with $1+2+3+\cdots+2n$ and $1^2+2^2+3^2+\cdots+(2n)^2$

### 2. (i)

> $\sum^{n}_{i=1}(2i-1)=1+3+5+\cdots+(2n-1).$

$$
\begin{align*}
\sum^{n}_{i=1}(2i-1)=1+3+5+\cdots+(2n-1)&=1+3+5+\cdots+(2(n-2)-1)+(2(n-1)-1)+(2n-1)\\
2(1+3+5+\cdots+(2n-1))&=1+3+5+\cdots+(2n-3)+(2n-1)+1+3+5+\cdots+(2n-5)+(2n-3)+(2n-1)\\
2(1+3+5+\cdots+(2n-1))&=((2n-1)+1)+((2n-3)+3)+((2n-5)+5)+\cdots+(5+(2n-5))+(3+(2n-3))+(1+(2n-1))\\
2(1+3+5+\cdots+(2n-1))&=n(2n)\\
2(1+3+5+\cdots+(2n-1))&=2n^2\\
1+3+5+\cdots+(2n-1)&=n^2\\
\end{align*}
$$

$$\begin{align}
\sum_{i=1}^n (2i-1) &= \sum_{i=1}^n 2i - \sum_{i=1}^n 1 \quad \text{(linearity)} \\
&= 2\sum_{i=1}^n i - \sum_{i=1}^n 1 \quad \text{(factor out constant)} \\
&= 2 \cdot \frac{n(n+1)}{2} - n \quad \text{(known formulas)} \\
&= n(n+1) - n \\
&= n^2 \quad 🤌
\end{align}$$

### 2. (ii)

> $\sum^{n}_{i=1}(2i-1)^2=1^2+3^2+5^2+\cdots+(2n-1)^2.$

$$
\begin{align*}
\sum^{n}_{i=1}(2i-1)^2&=1^2+3^2+5^2+\cdots+(2n-1)^2 \\
1^2+3^2+5^2+\cdots+(2n-1)^2&=(1^2+2^2+3^2+\cdots+(2n)^2)-(2^2+4^2+6^2+\cdots+(2n)^2) \\
&=(1^2+2^2+3^2+\cdots+(2n)^2)-(2^2+4^2+6^2+\cdots+(2n)^2) \\
&=\frac{2n(2n+1)(4n+1)}{6}-4(1^2+2^2+3^2+\cdots+n^2) \\
&=\frac{2n(2n+1)(4n+1)}{6}-4(\frac{n(n+1)(2n+1)}{6}) \\
&=\frac{2n(2n+1)(4n+1)-4n(n+1)(2n+1)}{6} \\
&=\frac{2n(2n+1)[(4n+1)-2(n+1)]}{6} \\
&=\frac{2n(2n+1)(4n+1-2n-2)}{6} \\
&=\frac{2n(2n+1)(2n-1)}{6} \\
&=\frac{n(2n+1)(2n-1)}{3}\quad 🤌\\
\end{align*}
$$

## 3.

> If $0\le k\le n,$ the "binomial coefficient" $\binom{n}{k}$ is defined by
>
> $$
> \begin{align*}
> \binom{n}{k} &=\frac{n!}{k!(n-k)!}=\frac{n(n-1)\cdots(n-k+1)}{k!},\quad \text{ if }k\ne0,n \\
> \binom{n}{0}&=\binom{n}{n}=1\quad\text{ a special case of the first formula if we define }0!=1
> \end{align*}
> $$
>
> and for $k<0$ or $k>n$ we just define the binomial coefficient to be $0.$

### 3. (a)

> Prove that 
>
> $$
> \binom{n+1}{k}=\binom{n}{k-1}+\binom{n}{k}.
> $$
>
> (The proof does not require an induction argument.)
>
> This relation gives rise to the following configuration, known as "Pascal's triangle"--a number not on one of the sides is the sum of the two numbers above it; the binomial coefficient $\binom{n}{k}$ is the $(k+1)$st number in the $(n+1)$st row.
>
> $$
> 1\\
> 1\quad1\\
> 1\quad2\quad1\\
> 1\quad3\quad3\quad1\\
> 1\quad4\quad6\quad4\quad1\\
> 1\quad5\quad10\quad10\quad5\quad1\\
> ...
> $$

$$
\begin{align*}
\binom{n}{k-1}+\binom{n}{k}&=\frac{n!}{(k-1)!(n-(k-1))!}+\frac{n!}{k!(n-k)!}\\
&=\frac{kn!}{k!(n-k)!(n-k+1)}+\frac{n!(n-k+1)}{k!(n-k)!(n-k+1)}\\
&=\frac{kn!+n!(n-k+1)}{k!(n-k)!(n-k+1)}\\
&=\frac{n!(k+(n-k+1))}{k!(n-k)!(n-k+1)}\\
&=\frac{n!(n+1)}{k!(n-k+1)!}\\
&=\frac{(n+1)!}{k!((n+1)-k)!}\quad🤌\\
\end{align*}
$$

### 3. (b)

> Notice that all the numbers in Pascal's triangle are natural numbers. Use part (a) to prove by induction that $\binom{n}{k}$ is always a natural number. (Your entire proof by induction will, in a sense, be summed up in a glance by Pascal's triangle.)

Alright, we know for the basecase that $\binom{1}{1}=\binom{1}{0}=1$ is natural. For the inductive step, suppose $\binom{n}{p}$ is natural for all $p\le n.$ From part (a) we know

$$
\binom{n+1}{p}=\binom{n}{p-1}+\binom{n}{p} \quad \text{for }p\le n,
$$

And therefore, the sum of two known natural numbers is also natural. So we have $\binom{n+1}{p}$ is natural for all $p\le n.$ But we also know that $\binom{n}{n}=\binom{n+1}{n+1}=1$ so we also have that as natural. Thus $\binom{n+1}{p}$ is natural for all $p\le n+1.$ 🤌

### 3. (c)

> Give another proof that $\binom{n}{k}$ is a natural number by showing that $\binom{n}{k}$ is the number of sets of exactly $k$ integers chosen from $1,...,n.$

Let $C(n,k)$ be the number of sets of $k$ length chosen from $n$ elements.

By our definition we know that $C(n,0)=C(n,n)=1$ since there is only one empty set and only one way to choose all $n$ elements. Furthermore, since it is impossible to choose sets of length $k<0$ or $k>n$ from $n$ elements, let $C(n,k)=0$ when $k<0$ or $k>n.$

For our base case observe that $C(1,0)=C(1,1)=1$ by our definition.

Now, for our induction case, assume $C(n,k)$ is natural for all $k\le n.$ To count $n+1$ sets observe that all sets of elements chosen from $n+1$ elements either contain the $n+1$ element or they do not.

If they contain $n+1,$ then there are $k-1$ slots left to fill from the elements $1,...,n$ so this set can be denoted $C(n,k-1).$

If they do not contain $n+1,$ then they are equal to $C(n,k).$ So now we know that $C(n+1,k)=C(n,k-1)+C(n,k).$ Since we are counting, we are using natural numbers, and since $C(n,k-1)$ and $C(n,k)$ are natural, we know $C(n+1,k),$ the sum of two natural numbers, to be natural. 🤌

### 3. (d)

> Prove the "binomial theorem": If $a$ and $b$ are any numbers and $n$ is a natural number, then
>
> $$
> \begin{align*}
> (a+b)^n&=a^n+\binom{n}{1}a^{n-1}b+\binom{n}{2}a^{n-2}b^2+\cdots+\binom{n}{n-1}ab^{n-1}+b^n\\
> &= \sum_{j=0}^n\binom{n}{j}a^{n-j}b^j
> \end{align*}
> $$

$$
\begin{align*}
(a+b)^n &= \sum_{j=0}^n\binom{n}{j}a^{n-j}b^j\\
(a+b)^n (a+b) &= (a+b)\sum_{j=0}^n\binom{n}{j}a^{n-j}b^j\\
(a+b)^{n+1} &= a\sum_{j=0}^n\binom{n}{j}a^{n-j}b^j+b\sum_{j=0}^n\binom{n}{j}a^{n-j}b^j\\
&= \sum_{j=0}^n\binom{n}{j}a^{n-j+1}b^j+\sum_{j=0}^n\binom{n}{j}a^{n-j}b^{j+1}\\
&= \sum_{j=0}^n\binom{n}{j}a^{n-j+1}b^j+\sum_{j=0}^n\binom{n}{j}a^{n-j}b^{j+1}\\
&=\binom{n}{0}a^{n-0+1}b^0 + \sum_{j=1}^n\binom{n}{j}a^{n-j+1}b^j+\sum_{j=0}^{n-1}\binom{n}{j}a^{n-j}b^{j+1}+\binom{n}{n}a^{j-j}b^{n+1} \\
&=a^{n+1} + \sum_{j=1}^n\binom{n}{j}a^{n-j+1}b^j+\sum_{j=0}^{n-1}\binom{n}{j}a^{n-j}b^{j+1}+b^{n+1} \\
&=a^{n+1} + \sum_{j=1}^n\binom{n}{j}a^{n-j+1}b^j+\sum_{k=1}^{n}\binom{n}{k-1}a^{n-k+1}b^{k}+b^{n+1}\\
&=a^{n+1} + \sum_{j=1}^n[\binom{n}{j}+\binom{n}{j-1}]a^{n-j+1}b^j+b^{n+1}\\
&=a^{n+1} + \sum_{j=1}^n\binom{n+1}{j}a^{n-j+1}b^j+b^{n+1}\\
&=\sum_{j=0}^{n+1}\binom{n+1}{j}a^{(n+1)-j}b^{j} \quad 🤌\\
\end{align*}
$$

Fuck me that was not straightforward. But I guess I started to understand these summations.

### 3. (e)

> Prove that

#### 3. (e) (i)

> $\sum_{j=0}^n\binom{n}{j}=\binom{n}{0}+\cdots+\binom{n}{n}=2^n$

$$
2^n=(1+1)^n=\sum^n_{j=0}\binom{n}{j}1^{n-j}1^j=\sum^n_{j=0}\binom{n}{j} \quad🤌
$$

#### 3. (e) (ii)

> $\sum^n_{j=0}(-1)^j\binom{n}{j}=\binom{n}{0}-\binom{n}{1}+\cdots\pm\binom{n}{n}=0$


$$
\begin{align*}
\sum^n_{j=0}(-1)^j\binom{n}{j}&=\sum^n_{j=0}\binom{n}{j}(-1)^j\\
&=\sum^n_{j=0}\binom{n}{j}1^{n-j}(-1)^j\\
&=(1+(-1))^n\\
&=0^n=0 \quad 🤌\\
\end{align*}
$$

#### 3. (e) (iii)

> $\sum_{l\text{ odd}}\binom{n}{l}=\binom{n}{1}+\binom{n}{3}+\cdots=2^{n-1}.$

$$
\begin{align*}
(1+1)^n&=\binom{n}{0}+\binom{n}{1}+\binom{n}{2}+\binom{n}{3}+\cdots\\
(1+1)^n-(1-1)^n&=\left(\binom{n}{0}+\binom{n}{1}+\binom{n}{2}+\binom{n}{3}+\cdots\right)-\left(\binom{n}{0}-\binom{n}{1}+\binom{n}{2}-\binom{n}{3}\pm\cdots\right)\\
2^n-0^n&=\left(\binom{n}{0}+\binom{n}{1}+\binom{n}{2}+\binom{n}{3}+\cdots\right)-\binom{n}{0}+\binom{n}{1}-\binom{n}{2}+\binom{n}{3}\pm\cdots\\
2^n-0&=\left(\binom{n}{0}-\binom{n}{0}\right)+\left(\binom{n}{1}+\binom{n}{1}\right)+\left(\binom{n}{2}-\binom{n}{2}\right)+\left(\binom{n}{3}+\binom{n}{3}\right)\\
2^n&=2\binom{n}{1}+2\binom{n}{3}+2\binom{n}{5}+\cdots\\
2^n&=2\left(\binom{n}{1}+\binom{n}{3}+\binom{n}{5}+\cdots\right)\\
2^{n-1}&=\binom{n}{1}+\binom{n}{3}+\binom{n}{5}+\cdots \quad 🤌\\
\end{align*}
$$

#### 3. (e) (iv)

> $\sum_{l\text{ even}}\binom{n}{l}=\binom{n}{0}+\binom{n}{2}+\cdots=2^{n-1}.$

The same proof above follows from $(1+1)^n+(1-1)^n.$

## 4.

### 4. (a)

> Prove that
>
> $$
> \sum^l_{k=0}\binom{n}{k}\binom{m}{l-k}=\binom{n+m}{l}.
> $$
>
> Hint: Apply the binomial theorem to $(1+x)^n(1+x)^m.$

$$
\begin{align*}
(1+x)^n(1+x)^m&=(1+x)^{n+m}\\
\sum_{k=0}^n\binom{n}{k}x^k \sum_{j=0}^m\binom{m}{j}x^j&=\sum_{l=0}^{n+m}\binom{n+m}{l}x^l\\
\sum_{k=0}^n\sum_{j=0}^m\binom{n}{k}\binom{m}{j}x^{k+j}&=\sum_{l=0}^{n+m}\binom{n+m}{l}x^l\\
\end{align*}
$$

Since the coefficients of a polynomial are uniquely determined, we only want the terms where $x^{k+j}=x^l.$  That would be when the coefficients are equal. That is when $j=l-k.$ So

$$
\sum_{k=0}^l\binom{n}{k}\binom{m}{l-k}=\binom{n+m}{l} \quad 🤌
$$

### 4. (b)

> Prove that
>
> $$
> \sum_{k=0}^n\binom{n}{k}^2=\binom{2n}{n}.
> $$

Well, since

$$
\begin{align*}
\binom{n}{n-k}&=\frac{n!}{(n-k)!(n-(n-k))!}\\
&=\frac{n!}{(n-k)!(n-n+k)!}\\
&=\frac{n!}{(n-k)!k!}\\
&=\frac{n!}{k!(n-k)!}=\binom{n}{k}\\
\end{align*}
$$

We can just do this!

$$
\begin{align*}
\sum_{k=0}^n\binom{n}{k}^2&=\sum_{k=0}^n\binom{n}{k}\binom{n}{k}\\
&=\sum_{k=0}^n\binom{n}{k}\binom{n}{n-k}\\
&=\binom{n+n}{n}=\binom{2n}{n} \quad 🤌\\
\end{align*}
$$

### 5. (a)

> Prove by induction on $n$ that
>
> $$
> 1+r+r^2+\cdots+r^n=\frac{1-r^{n+1}}{1-r} \\
> $$
> 
> if $r\ne1$ (if $r=1,$ evaluating the sum certainly presents no problem).

For the $n=1$ case observe that $1+r=\frac{(1+r)(1-r)}{1-r}=\frac{1-r^2}{1-r}.$ But for the $n+1$ case observe

$$
\begin{align*}
1+r+r^2+\cdots+r^n&=\frac{1-r^{n+1}}{1-r}\\
1+r+r^2+\cdots+r^n+r^{n+1}&=\frac{1-r^{n+1}}{1-r}+r^{n+1}\\
&=\frac{1-r^{n+1}+(1-r)r^{n+1}}{1-r}\\
&=\frac{1-r^{n+1}(1-(1-r))}{1-r}\\
&=\frac{1-r^{n+1}r}{1-r}\\
&=\frac{1-r^{(n+1)+1}}{1-r}\\
\end{align*}
$$

### 5. (b)

> Derive this result by setting $S=1+r+\cdots+r^n,$ multiplying this equation by $r,$ and solving the two equations for $S.$

$$
\begin{align*}
S&=1+r+\cdots+r^n\\
rS&=r+\cdots+r^{n+1}\\
S-rS&=1+r+\cdots+r^n-(r+\cdots+r^{n+1})\\
S(1-r)&=1-r^{n+1}\\
S&=\frac{1-r^{n+1}}{1-r}\\
1+r+\cdots+r^n&=\frac{1-r^{n+1}}{1-r}\\
\end{align*}
$$

## 6.

> The formula $1^2+\cdots+n^2$ may be derived as follows. We begin with the formula $(k+1)^3-k^3=3k^2+3k+1$ and add the iterative equations.
> 
> $$
> \begin{align*}
> 2^3-1^3&=3\cdot1^2+3\cdot1+1\\
> 3^3-2^3&=3\cdot2^2+3\cdot2+1\\
> &\vdots\\
> (n+1)^3-n^3&=3\cdot n^2+3\cdot n+1\\
> \hline
> (n+1)^3-1&=3(1^2+\cdots+n^2)+3(1+\cdots+n)+n
> \end{align*}
> $$
> 
> Now we can take our new formula and find what we want.

$$
\begin{align*}
(n+1)^3&=3(1^2+\cdots+n^2)+3(1+\cdots+n)+n+1\\
(n+1)^3&=3\sum^n_{k=1}k^2+3\sum^n_{k=1}k+n+1\\
3\sum^n_{k=1}k^2&=(n+1)^3-3\sum^n_{k=1}k-n-1\\
3\sum^n_{k=1}k^2&=(n+1)^3-3\frac{n(n+1)}{2}-n-1\\
3\sum^n_{k=1}k^2&=\frac{2(n+1)^3-3n(n+1)}{2}-n-1\\
3\sum^n_{k=1}k^2&=\frac{2(n+1)^3-3n(n+1)}{2}-\frac{2(n+1)}{2}\\
3\sum^n_{k=1}k^2&=\frac{2(n+1)^3-3n(n+1)-2(n+1)}{2}\\
\sum^n_{k=1}k^2&=\frac{(n+1)[2(n+1)^2-3n-2]}{6}\\
\sum^n_{k=1}k^2&=\frac{(n+1)[2(n^2+2n+1)-3n-2]}{6}\\
\sum^n_{k=1}k^2&=\frac{(n+1)[2n^2+4n+2-3n-2]}{6}\\
\sum^n_{k=1}k^2&=\frac{(n+1)(2n^2+n)}{6}\\
\sum^n_{k=1}k^2&=\frac{n(n+1)(2n+1)}{6}\\
\end{align*}
$$

> Thus we can find $\sum^n_{k=1}k^2$ if we already know $\sum_{k=1}^n$ (which could have been found in a similar way).
>
> Use this method to find

### 7. (i)

> $1^3+\cdots+n^3$

If we use

$$
\begin{align*}
(n+1)^4&=n^4+4n^3+6n^2+4n+1\\
(n+1)^4-n^4&=4n^3+6n^2+4n+1\\
(k+1)^4-k^4&=4k^3+6k^2+4k+1
\end{align*}
$$

we can sum to derive

$$
\begin{align*}
2^4-1^4&=4\cdot1^3+6\cdot1^2+4\cdot1+1\\
3^4-2^4&=4\cdot2^3+6\cdot2^2+4\cdot2+1\\
&\vdots\\
(n+1)^4-n^4&=4\cdot n^3+6\cdot n^2+4\cdot n+1\\
\hline \\
(n+1)^4-1&=4(1^3+\cdots+n^3)+6(1^2+\cdots+n^2)+4(1+\cdots+n)+n\\
(n+1)^4-1&=4\sum_{k=1}^nk^3+\frac{6n(n+1)(2n+1)}{6}+\frac{4n(n+1)}{2}+n\\
4\sum_{k=1}^nk^3&=(n+1)^4-\frac{6n(n+1)(2n+1)}{6}-\frac{4n(n+1)}{2}-n-1\\
4\sum_{k=1}^nk^3&=(n+1)^4-n(n+1)(2n+1)-2n(n+1)-n-1\\
4\sum_{k=1}^nk^3&=(n+1)^4-n(n+1)(2n+1)-2n(n+1)-(n+1)\\
4\sum_{k=1}^nk^3&=(n+1)[(n+1)^3-n(2n+1)-2n-1]\\
4\sum_{k=1}^nk^3&=(n+1)[(n+1)^3-n(2n+1)-(2n+1)]\\
4\sum_{k=1}^nk^3&=(n+1)[(n+1)^3-(n(2n+1)+(2n+1))]\\
4\sum_{k=1}^nk^3&=(n+1)[(n+1)^3-(2n+1)(n+1)]\\
4\sum_{k=1}^nk^3&=(n+1)^2[(n+1)^2-(2n+1)]\\
4\sum_{k=1}^nk^3&=(n+1)^2[n^2+2n+1-2n-1]\\
4\sum_{k=1}^nk^3&=n^2(n+1)^2\\
\sum_{k=1}^nk^3&=\frac{n^2(n+1)^2}{4}\\
\end{align*}
$$

But it seems that's not what Mr. Spivak was after, so let's try again.

$$
\begin{align*}
(n+1)^4-1&=4(1^3+\cdots+n^3)+6(1^2+\cdots+n^2)+4(1+\cdots+n)+n\\
(n+1)^4-1&=4\sum_{k=1}^nk^3+6\sum_{k=1}^nk^2+4\sum_{k=1}^nk+n\\
4\sum_{k=1}^nk^3&=(n+1)^4-1-6\sum_{k=1}^nk^2-4\sum_{k=1}^nk-n \\
4\sum_{k=1}^nk^3&=(n+1)^4-1-6\frac{n(n+1)(2n+1)}{6}-4\frac{n(n+1)}{2}-n \\
4\sum_{k=1}^nk^3&=(n+1)^4-1-n(n+1)(2n+1)-2n(n+1)-n \\
4\sum_{k=1}^nk^3&=(n^4+4n^3+6n^2+4n+1)-1-n(2n^2+3n+1)-(2n^2+2n)-n \\
\sum_{k=1}^nk^3&=\frac{n^4+4n^3+6n^2+4n+1-1-2n^3-3n^2-n-2n^2-2n-n}{4} \\
\sum_{k=1}^nk^3&=\frac{n^4+2n^3+n^2}{4} \\
\sum_{k=1}^nk^3&=\frac{n^4}{4}+\frac{n^3}{2}+\frac{n^2}{4} \\
\end{align*}
$$

That's the solution he had, I see it now.


### 7. (ii)

> $1^4+\cdots+n^4.$

Using,

$$
\begin{align*}
(n+1)^5&=n^5+5n^4+10n^3+10n^2+5n+1\\
(n+1)^5&-n^5=5n^4+10n^3+10n^2+5n+1\\
(k+1)^5&-k^5=5k^4+10k^3+10k^2+5k+1\\
\end{align*}
$$

we can find

$$
\begin{align*}
2^5-1^5&=5\cdot1^4+10\cdot1^3+10\cdot1^2+5\cdot1+1\\
3^5-2^5&=5\cdot2^4+10\cdot2^3+10\cdot2^2+5\cdot2+1\\
&\vdots\\
(n+1)^5-n&=5\cdot n^4+10\cdot n^3+10\cdot n^2+5\cdot n+1\\
\hline
(n+1)^5-1&=5(1^4+\cdots+n^4)+10(1^3+\cdots+n^3)+10(1^2+\cdots+n^2)+5(1+\cdots+n)+n\\
(n+1)^5-1&=5\sum_{k=1}^nk^4+10\sum_{k=1}^nk^3+10\sum_{k=1}^nk^2+5\sum_{k=1}^nk+n\\
5\sum_{k=1}^nk^4&=(n+1)^5-1-10\sum_{k=1}^nk^3-10\sum_{k=1}^nk^2-5\sum_{k=1}^nk-n\\
5\sum_{k=1}^nk^4&=(n+1)^5-1-10(\frac{n^4}{4}+\frac{n^3}{2}+\frac{n^2}{4})-10\frac{n(n+1)(2n+1)}{6}-5\frac{n(n+1)}{2}-n\\
5\sum_{k=1}^nk^4&=(n^5+5n^4+10n^3+10n^2+5n+1)-1-10(\frac{n^4}{4}+\frac{n^3}{2}+\frac{n^2}{4})-10\frac{n(n+1)(2n+1)}{6}-5\frac{n(n+1)}{2}-n\\
5\sum_{k=1}^nk^4&=n^5+5n^4+10n^3+10n^2+5n-\frac{5n^4}{2}-5n^3-\frac{5n^2}{2}-10\frac{n(n+1)(2n+1)}{6}-5\frac{n(n+1)}{2}-n\\
5\sum_{k=1}^nk^4&=n^5+5n^4+5n^3+10n^2+4n-\frac{5n^4+5n^2}{2}-\frac{5n(n+1)(2n+1)}{3}-\frac{5n^2+5n}{2}\\
5\sum_{k=1}^nk^4&=n^5+5n^4+5n^3+10n^2+4n-\frac{5n^4+10n^2+5n}{2}-\frac{5n(2n^2+3n+1)}{3}\\
5\sum_{k=1}^nk^4&=n^5+5n^4+5n^3+10n^2+4n-\frac{3(5n^4+10n^2+5n)+10n(2n^2+3n+1)}{6}\\
5\sum_{k=1}^nk^4&=n^5+5n^4+5n^3+10n^2+4n-\frac{15n^4+30n^2+15n+20n^3+30n^2+10n}{6}\\
5\sum_{k=1}^nk^4&=n^5+5n^4+5n^3+10n^2+4n-\frac{15n^4+20n^3+60n^2+25n}{6}\\
5\sum_{k=1}^nk^4&=\frac{6(n^5+5n^4+5n^3+10n^2+4n)}{6}-\frac{15n^4+20n^3+60n^2+25n}{6}\\
5\sum_{k=1}^nk^4&=\frac{6n^5+30n^4+30n^3+60n^2+24n-(15n^4+20n^3+60n^2+25n)}{6}\\
5\sum_{k=1}^nk^4&=\frac{6n^5+30n^4+30n^3+60n^2+24n-15n^4-20n^3-60n^2-25n}{6}\\
5\sum_{k=1}^nk^4&=\frac{6n^5+15n^4+10n^3-n}{6}\\
\sum_{k=1}^nk^4&=\frac{6n^5+15n^4+10n^3-n}{30}\\
\sum_{k=1}^nk^4&=\frac{n^5}{5}+\frac{n^4}{2}+\frac{n^3}{3}-\frac{n}{30}\\
\end{align*}
$$

### 7. (iii)

> $\frac{1}{1\cdot2}+\frac{1}{2\cdot3}+\cdots+\frac{1}{n(n+1)}.$

Let's start by decomposing the fraction

$$
\begin{align*}
\frac{1}{k(k+1)}&=\frac{a}{k}+\frac{b}{k+1}\\
\frac{1}{k}&=\frac{a(k+1)}{k}+b\\
1&=a(k+1)+bk\\
1&=ak+a+bk\\
1&=(a+b)k+a\\
\end{align*}
$$

From this we can assume coefficients, $a=1$ and

$$
\begin{align*}
a+b&=0\\
a&=-b\\
1&=-1
\end{align*}
$$

Based on that we can see

$$
\begin{align*}
\frac{1}{1\cdot2}+\frac{1}{2\cdot3}+\cdots+\frac{1}{n(n+1)}&=\sum_{k=1}^n\frac{1}{k(k+1)}\\
&=\sum_{k=1}^n(\frac{1}{k}-\frac{1}{k+1})\\
\end{align*}
$$

With this we can start to write out our terms

$$
\begin{align*}
(\frac{1}{1}-\frac{1}{2})+(\frac{1}{2}-\frac{1}{3})+(\frac{1}{3}-\frac{1}{4})+\cdots+(\frac{1}{n}-\frac{1}{n+1})\\
1-\frac{1}{n+1}\\
\frac{n+1}{n+1}-\frac{1}{n+1}\\
\frac{n+1-1}{n+1}\\
\frac{n}{n+1}\\
\end{align*}
$$

### 7. (iv)

> $\frac{3}{1^2\cdot2^2}+\frac{5}{2^2\cdot3^2}+\cdots+\frac{2n+1}{n^2(n+1)^2}$

$$
\frac{3}{1^2\cdot2^2}+\frac{5}{2^2\cdot3^2}+\cdots+\frac{2n+1}{n^2(n+1)^2}=\sum_{k=1}^n\frac{2k+1}{k^2(k+1)^2}
$$

We need to end up with something like $(k+1)^2-k^2$ to get our telescope. Luckily $(k+1)^2-k^2=(k^2+2k+1)-k^2=2k+1$

So we can see

$$
\begin{align*}
\sum_{k=1}^n\frac{2k+1}{k^2(k+1)^2}&=\sum_{k=1}^n\left(\frac{(k+1)^2}{k^2(k+1)^2}-\frac{k^2}{k^2(k+1)^2}\right)\\
&=\left(\frac{2^2}{1^2\cdot2^2}-\frac{1^2}{1^2\cdot2^2}\right)+\left(\frac{3^2}{2^2\cdot3^2}-\frac{2^2}{2^2\cdot3^2}\right)+\cdots+\left(\frac{(n+1)^2}{n^2(n+1)^2}-\frac{n^2}{n^2(n+1)^2}\right)\\
&=\left(\frac{1}{1^2}-\frac{1}{2^2}\right)+\left(\frac{1}{2^2}-\frac{1}{3^2}\right)+\cdots+\left(\frac{1}{n^2}-\frac{1}{(n+1)^2}\right)\\
&=\frac{1}{1^2}-\frac{1}{(n+1)^2}\\
&=1-\frac{1}{(n+1)^2}\\
&=\frac{(n+1)^2-1}{(n+1)^2}\\
&=\frac{n^2+2n}{(n+1)^2}\\
&=\frac{n(n+2)}{(n+1)^2}\\
\end{align*}
$$

Dang man, getting a sense for this stuff is tough.

## 7.

> Use the method of Problem 6 to show that $\sum_{i=1}^nk^p$ can always be written in the form
>
> $$
> \frac{n^{p+1}}{p+1} + An^p+Bn^{p-1}+Cn^{p-2}+\cdots.
> $$
>
> (The first 10 such expressions are
>
> $$
> \begin{align*}
> &\sum_{k=1}^nk       &=\frac{1}{2}n^2     &+\frac{1}{2}n^1\\
> &\sum_{k=1}^n k^2    &=\frac{1}{3}n^3     &+\frac{1}{2}n^2    &+\frac{1}{6}n\\
> &\sum_{k=1}^n k^3    &=\frac{1}{4}n^4     &+\frac{1}{2}n^3    &+\frac{1}{4}n^2\\
> &\sum_{k=1}^n k^4    &=\frac{1}{5}n^5     &+\frac{1}{2}n^4    &+\frac{1}{3}n^3  &-\frac{1}{30}n^1 \\
> &\sum_{k=1}^n k^5    &=\frac{1}{6}n^6     &+\frac{1}{2}n^5    &+\frac{5}{12}n^4 &-\frac{1}{12}n^2 \\
> &\sum_{k=1}^n k^6    &=\frac{1}{7}n^7     &+\frac{1}{2}n^6    &+\frac{1}{2}n^5  &-\frac{1}{6}n^3  &+\frac{1}{42}n\\
> &\sum_{k=1}^n k^7    &=\frac{1}{8}n^8     &+\frac{1}{2}n^7    &+\frac{7}{12}n^6 &-\frac{7}{24}n^4 &+\frac{1}{12}n^2\\
> &\sum_{k=1}^n k^8    &=\frac{1}{9}n^9     &+\frac{1}{2}n^8    &+\frac{2}{3}n^7  &-\frac{7}{15}n^5 &+\frac{2}{9}n^3     &-\frac{1}{30}n\\
> &\sum_{k=1}^n k^9    &=\frac{1}{10}n^{10} &+\frac{1}{2}n^9    &+\frac{3}{4}n^8  &-\frac{7}{10}n^6 &+\frac{1}{2}n^4     &-\frac{3}{20}n^2\\
> &\sum_{k=1}^n k^{10} &=\frac{1}{11}n^{11} &+\frac{1}{2}n^{10} &+\frac{5}{6}n^9  &-1n^7            &+1n^5               &-\frac{1}{2}n^3  &+\frac{5}{66}n
> \end{align*}
> $$

It's easy to see that the base case holds true, for p=1

$$
\sum_{k=1}^nk^1=\frac{1}{2}n^2+\frac{1}{2}n=\frac{1}{1+1}n^{1+1}+\frac{1}{2}n
$$

Now assume we know that for all $j<p$ we have

$$
S_j(n)=\sum_{k=1}^nk^j=\frac{n^{j+1}}{j+1} + An^j+Bn^{j-1}+Cn^{j-2}+\cdots.
$$

From the binomial theorem,

$$
\begin{align*}
(n+1)^p&=n^p+\binom{p}{1}n^{p-1}+\binom{p}{2}n^{p-2}+\cdots\\
(n+1)^p-n^p&=\binom{p}{1}n^{p-1}+\binom{p}{2}n^{p-2}+\cdots
\end{align*}
$$

Using this and summing from $k=1,...,n$ and then solving for $\sum_{k=1}^nk^p$ we can see

$$
\begin{align*}
(k+1)^{p+1}-k^{p+1}&=\binom{p+1}{1}k^{p}+\binom{p+1}{2}k^{p-1}+\cdots\\
(n+1)^{p+1}-1&=\binom{p+1}{1}\sum_{k=1}^nk^{p}+\binom{p+1}{2}\sum_{k=1}^nk^{p-1}+\cdots\\
(n+1)^{p+1}-1&=\frac{(p+1)!}{1!((p+1)-1)!}\sum_{k=1}^nk^{p}+\binom{p+1}{2}\sum_{k=1}^nk^{p-1}+\cdots\\
(n+1)^{p+1}-1&=\frac{p!(p+1)}{p!}\sum_{k=1}^nk^{p}+\binom{p+1}{2}\sum_{k=1}^nk^{p-1}+\cdots\\
(n+1)^{p+1}-1&=(p+1)\sum_{k=1}^nk^{p}+\binom{p+1}{2}\sum_{k=1}^nk^{p-1}+\cdots\\
(n+1)^{p+1}-1&=(p+1)\sum_{k=1}^nk^{p}+\binom{p+1}{2}\sum_{k=1}^nk^{p-1}+\cdots\\
(p+1)\sum_{k=1}^nk^{p}&=(n+1)^{p+1}-1-\binom{p+1}{2}\sum_{k=1}^nk^{p-1}-\cdots\\
\sum_{k=1}^nk^{p}&=\frac{1}{p+1}\left[(n+1)^{p+1}-1-\binom{p+1}{2}\sum_{k=1}^nk^{p-1}-\cdots\right]\\
\end{align*}
$$

Next, since we are assuming 

$$
S_j(n)=\sum_{k=1}^nk^j=\frac{n^{j+1}}{j+1} + An^j+Bn^{j-1}+Cn^{j-2}+\cdots
$$

for all $j<p$ we can substitute it for all the lesser terms and expand $(n+1)^{p+1}$ by the binomial theorem

$$
\begin{align*}
\sum_{k=1}^nk^{p}&=\frac{1}{p+1}\left[(n+1)^{p+1}-1-\binom{p+1}{2}S_{p-1}-\cdots\right]\\
\sum_{k=1}^nk^{p}&=\frac{1}{p+1}\left[(n+1)^{p+1}-1-\sum_{j=2}^{p-1}\binom{p+1}{j}S_{j}(n)\right]\\
\sum_{k=1}^nk^{p}&=\frac{1}{p+1}\left[n^{p+1}+(p+1)n^p+\binom{p+1}{2}n^{p-1}+\cdots-\sum_{j=2}^{p-1}\binom{p+1}{j}S_{j}(n)\right]\\
\sum_{k=1}^nk^{p}&=\frac{1}{p+1}\left[n^{p+1}+(p+1)n^p+\binom{p+1}{2}n^{p-1}+\cdots-\sum_{j=2}^{p-1}\binom{p+1}{j}S_{j}(n)\right]\\
\sum_{k=1}^nk^{p}&=\frac{1}{p+1}\left[n^{p+1}+\cdots\text{terms from lower powers}\right]\\
\sum_{k=1}^nk^{p}&=\frac{n^{p+1}}{p+1}+\frac{\cdots\text{ terms from lower powers }}{p+1}
\end{align*}
$$

So we see that if it's true for $j<p,$ it's also true for $p$. 🤌

## 8.

> Prove that every natural number is either even or odd.

Well, our base case 1 is obviously odd, so the statement `even(1) or odd(1)==True` works.

Next we must find if `(even(n) or odd(n))=>(even(n+1) or odd(n+1))`

Either $2$ is a factor of $n$ or it is not. 

- If it is, then $n=2m.$ Since $1$ is a natural number, and $2m$ is a natural number, and the sum of natural numbers is a natural number, so $n+1=2m+1$ is a natural number. Since $n$ is even, and $n+1$ is of the form $2m+1,$ it is odd.

- If it is not, then $n=2m+1$ for some m. Since it is a natural number, and $1$ is a natural number, once again their sum, $2m+2$ is also natural. And since $n+1=2m+2=2(m+1),$ $2$ is a factor of $n+1$ and so it is even.

Therefore, if $n$ is odd or even, $n+1$ is odd or even.

## 9.

> Prove that if a set $A$ of natural numbers contains $n_0$ and contains $k+1$ whenever it contains $k,$ then $A$ contains all natural numbers $\ge n_0.$

To symbolize this,

$$
(1: n_0\in A) \land(2: k\in A\to k+1\in A)\to \mathbb{N} \ge n_0\in A
$$

Assume for contradiction the antecedent and deny the consequent. That is, that there exists a number $m>n_0\notin A.$

From $n_0\in A,$ we know $n_0+1\in A.$ And since $n_0+1\in A,(n_0+1)+1=n_0+2\in A.$ The same is true of every $n_k<m.$

This means $m-1\in A.$ We therefore know $(m-1)+1=m\in A.$ This is a contradiction. Therefore our statement is true.

## 10.

> Prove the principle of mathematical induction from the well-ordering principle.

## 11.

> Prove the principle of complete induction from the ordinary principle of induction. Hint: If $A$ contains $1$ and $A$ contains $n+1$ whenever it contains $1,...,n,$ consider the set $B$ of all $k$ such that $1,...,k$ are all in $A.$

## 12.

### 12. (a)

> If $a$ is rational and $b$ is irrational, is $a+b$ necessarily irrational? What if $a$ and $b$ are both irrational?

Yes, $a+b$ is necessarily irrational if only $b$ is irrational because otherwise $b=(a+b)-a$ would be rational, being the sum of two rational numbers.

If both $a,b$ are irrational, then $a+b$ could be rational since $b=r-a$ could be the case.

### 12. (b)

> If $a$ is rational and $b$ is irrational, is $ab$ necessarily irrational? (Careful!)

If $a=0,ab=0$ which would be rational, otherwise $ab$ is irrational since $b=a^{-1}ab$ cannot be rational.

### 12. (c)

> Is there a number $a$ such that $a^2$ is irrational, but $a^4$ is rational?

Yes, $a=\sqrt[4]2$

### 12. (d)

> Are there two irrational numbers whose sum and product are both rational?

Yes, consider $a=-\sqrt2,b=\sqrt2,$ for which $-\sqrt2\sqrt2=-2$ and $-\sqrt2+\sqrt2=0.$

## 13.

### 13. (a)

> Prove that $\sqrt3,\sqrt5,\sqrt6$ are irrational. Hint: To treat $\sqrt3,$ for example, use the fact that every integer is of the form $3n$ or $3n+1$ or $3n+2.$ Why doesn't this proof work for $\sqrt4$?

### 13. (b)

> Prove that $\sqrt[3]2$ and $\sqrt[3]3$ are irrational.

## 14.

> Prove that

### 14. (a)

> $\sqrt2+\sqrt6$ is irrational.

### 14. (b)

> $\sqrt2+\sqrt3$ is irrational.

## 15.

### 15. (a)

> Prove that if $x=p+\sqrt q$ where $p$ and $q$ are rational, and $m$ is a natural number, then $x^m=a+b\sqrt q$ for some rational $a$ and $b.$

### 15. (b)

> Prove also that $(p-\sqrt q)^m=a-b\sqrt q.$

## 16.

### 16. (a)

> Prove that if $m$ and $n$ are natural numbers and $\frac{m^2}{n^2}\le2,$ then $\frac{(m+2n)^2}{(m+n)^2}>2;$ show, moreover, that
> 
> $$
> \frac{(m+2n)^2}{(m+n)^2}-2<2-\frac{m^2}{n^2}.
> $$

### 16. (b)

> Prove the same result with all inequality signs reversed.
