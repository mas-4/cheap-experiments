# Axler LADR Exercises 1a

## 1. Show that $\alpha + \beta = \beta + \alpha$ for all $\alpha, \beta \in \mathbb{C}$

$$
\begin{align*}
\alpha + \beta &= (a + bi) + (c + di) \\
&= (a + c) + (b + d)i \\
\beta + \alpha &= (c + di) + (a + bi) \\
&= (a + c) + (b + d)i
\end{align*}
$$

## 2. Show that $(\alpha + \beta) + \lambda = \alpha + (\beta + \lambda)$ for all $\alpha, \beta, \lambda \in \mathbb{C}$

$$
\begin{align*}
(\alpha + \beta) + \lambda &= (a + bi + c + di) + e + fi \\
&= (a + c + e) + (b + d + f)i \\
\alpha + (\beta + \lambda) &= a + bi + (c + di + e + fi) \\
&= (a + c + e) + (b + d + f)i
\end{align*}
$$

## 3. Show that $(\alpha \beta)\lambda = \alpha (\beta \lambda)$ for all $\alpha, \beta, \lambda \in \mathbb{C}$

$$
\begin{align*}
(\alpha \beta)\lambda &= ((a + bi)(c + di))(e + fi) \\
&= (ac - bd + adi + bci)(e + fi) \\
&= (ace - adf - bcf - bde) + (acf + ade + bce - bdf)i \\
\alpha(\beta\lambda) &= (a+bi)((c+di)(e+fi)) \\
&= (a + bi)(ce - df + cfi + dei) \\
&= (ace - adf - bcf - bde) + (acf + ade + bce - bdf)i \\
\end{align*}
$$

## 4. Show that $\lambda(\alpha + \beta) = \lambda\alpha + \lambda\beta$ for all $\alpha, \beta, \lambda \in \mathbb{C}$

$$
\begin{align*}
\lambda(\alpha + \beta) &= (e + fi)((a + bi) + (c + di)) \\
&=(e + fi)(a + c + bi + di)\\
&=(ea + ec - bf - df) + (af + cf + eb + ed)i \\
\lambda\alpha + \lambda\beta &= (e+fi)(a+bi) + (e + fi)(c + di) \\
&= ea-bf+ebi+afi + ec-df+cfi+edi \\
&= (ea + ec - bf - df) + (af + cf + eb + ed)i
\end{align*}
$$

## 5. Show that for every $\alpha \in \mathbb{C}$ there exists a unique $\beta \in \mathbb{C}$ such that $\alpha + \beta = 0$.

Assume 

$$
\begin{align*}
\beta = -a-bi
\end{align*}
$$

then

$$
\begin{align*}
\alpha + \beta &= (a+bi) +(-a-bi)  \\
&=a-a+bi-bi \\
&=0
\end{align*}
$$

Assume $\alpha + \beta_1 = 0$ and $\alpha + \beta_2=0$. Then

$$
\begin{align*}
\alpha + \beta_1 &= 0 \\
\alpha &= -\beta_1 \\
\alpha + \beta_2 &= 0 \\
-\beta_1 + \beta_2 &= 0 \\
\beta_2 &= \beta_1
\end{align*}
$$

## 6. Show that for every $\alpha \in \mathbb{C}$ with $\alpha \neq 0$, there exists a unique $\beta \in \mathbb{C}$ such that $\alpha\beta = 1$.

Assume
$$
\begin{align*}
\beta &= \frac{a - bi}{a^2 + b^2} \\
&= \frac{a}{a^2 + b^2} - \frac{b}{a^2 + b^2}i
\end{align*}
$$


$$
\begin{align*}
\alpha\beta &= (a + bi)(\frac{a - bi}{a^2 + b^2}) \\
&= \frac{a(a) + a(-bi) + (bi)(a) + (bi)(-bi)}{a^2 + b^2} \\
&= \frac{a^2 - abi + abi - b^2i^2}{a^2 + b^2} \\
&= \frac{a^2 - b^2(-1)}{a^2 + b^2} \\
&= \frac{a^2 + b^2}{a^2 + b^2} \\
&= 1
\end{align*}
$$
therefore a multiplicative inverse exists.

To show uniqueness, assume there are $\beta_1,\beta_2 \in C$ such that, $\alpha\beta_1=1$ and $\alpha\beta_2=1$. Then $\alpha\beta_1=1=\alpha\beta_2$ and $\beta_1=\beta_2=\frac{1}{\alpha}$


## 7. Show that $ \frac{-1 + \sqrt{3}i}{2} $ is a cube root of 1 (meaning that its cube equals 1).

$$
\begin{align*}
\sqrt[3]1 &= \frac{-1 + \sqrt{3}i}{2} \\
1 &= (\frac{-1 + \sqrt{3}i}{2})(\frac{-1 + \sqrt{3}i}{2})(\frac{-1 + \sqrt{3}i}{2}) \\
&= (-1-\sqrt{3}i)(\frac{-1 + \sqrt{3}i}{2}) \\
&= 1
\end{align*}
$$

## 8. Find two distinct square roots of $i$.


$$
\begin{align*}
\sqrt{i} = z &= a+bi\\
z^2 &= a^2-b^2+2abi \\
\end{align*}
$$

Recognizing $i = 0 + 1i = z^2 = (a^2-b^2) + 2abi$ we can set

$$
\begin{align*}
a^2-b^2 &= 0 \\
a^2 &= b^2 \\
a &= \pm b \\
\end{align*}
$$

Then,

$$
\begin{align*}
2abi &= 1i \\
2ab &= 1 \\
ab &= \frac{1}{2}
\end{align*}
$$

Since $a=\pm b$, $a^2 = \frac{1}{2}$. So $a = b = \sqrt{\frac{1}{2}} = \pm \frac{\sqrt{2}}{2}$

$$
\begin{align*}
z_1 &= a + bi &  &= \frac{\sqrt2}{2} + \frac{\sqrt2}{2}i  & & = \frac{\sqrt{2}}{2}(1 + i)\\
z_2 &= a + bi & &= -\frac{\sqrt2}{2} - \frac{\sqrt2}{2}i  & & = -\frac{\sqrt{2}}{2}(1 + i)\\
\end{align*}
$$

## 9. Find $x \in \mathbb{R}^4$ such that $ (4, -3, 1, 7) + 2x = (5, 9, -6, -8) $

Solving for $x$:

$$
\begin{align*}
(4, -3, 1, 7) + 2x &= (5, 9, -6, -8) \\
2x &= (1, 12, -7, -15) \\
x &= (\frac{1}{2}, 6, -3\frac{1}{2}, -7\frac{1}{2}) \\
\end{align*}
$$

## 10. Explain why there does not exist $\lambda \in \mathbb{C}$ such that

$$
\begin{align*}
\lambda(2 - 3i, 5+4i, -6+7i) = (12-5i, 7+22i, -32-9i)
\end{align*}
$$
Well, solving
$$
\begin{align*}
\lambda(2 - 3i) &= 12-5i \\
&= \frac{12-5i}{2-3i} \\
&= \frac{12-5i}{2-3i} \cdot \frac{2+3i}{2+3i}  \\
&=  \frac{39+26i}{13} \\
&=  3 + 2i
\end{align*}
$$
And then substituting

$$
\begin{align*}
\lambda(5+4i) &= 7 + 22i \\
(3+2i)(5+4i) &= 7+22i \\
7+2i &= 7+22i
\end{align*}
$$

So it holds for the second component, checking the third
$$
\begin{align*}
(3+2i)(-6+7i) &= -32-9i \\
-32+9i &\neq -32-9i \\
\end{align*}
$$

So it doesn't hold for the third.

## 11. Show that $(x+y) + z = x + (y+z)$ for all $x,y,z \in \mathbb{F}^n$

$$
\begin{align*}
(x+y) + z &= ((x_1,...,x_n) + (y_1,...,y_n)) + (z_1,...,z_n) \\
&=(x_1+y_1,...,x_n+y_n)+(z_1,...,z_n) \\
&=(x_1+y_1+z_1,...,x_n+y_n+z_n) \\
x+(y+z) &= (x_1,...,x_n) + ((y_1,...,y_n) + (z_1,...,z_n)) \\
&= (x_1,...,x_n) + (y_1+z_1,...,y_n+y_n) \\
&=(x_1+y_1+z_1,...,x_n+y_n+z_n)
\end{align*}
$$

## 12. Show that $(ab)x=a(bx)$ for all $x \in \mathbb{F}^n$ and all $a,b \in \mathbb{F}$

$$
\begin{align*}
(ab)x &= ab(x_1,...,x_n) \\
&=(abx_1,...,x_n) \\
a(bx) &= a(b(x_1,...,x_n)) \\
&= a(bx_1,...,bx_n) \\
&= (abx_1,...,abx_n) \\
\end{align*}
$$

## 13. Show that $1x=x$ for all $x \in \mathbb{F}^n$

$$
\begin{align*}
1x &= 1(x_1,...,x_n) \\
&=(1x_1,...,1x_n) \\
&=(x_1,...,x_n)
\end{align*}
$$

## 14. Show that $\lambda(x+y)=\lambda x + \lambda y$ for all $\lambda \in \mathbb{F}$ and all $x,y \in \mathbb{F}^n$
$$
\begin{align*}
\lambda(x+y) &= \lambda((x_1,...,x_n)+(y_1,...,y_n)) \\
&= \lambda(x_1+y_1,...,x_n+y_n) \\
&= (\lambda(x_1+y_1),...,\lambda(x_n+y_n)) \\
&= (\lambda x_1+\lambda y_1,...,\lambda x_n+\lambda y_n) \\
\lambda x + \lambda y &=  \lambda (x_1,...,x_n) + \lambda (y_1,...,y_n) \\
&= (\lambda x_1,...,\lambda x_n) + (\lambda y_1,...,\lambda y_n) \\
&= (\lambda x_1+\lambda y_1,...,\lambda x_n+\lambda y_n)
\end{align*}
$$

## 15. Show that $(a+b)x = ax + bx$ for all $a,b \in \mathbb{F}$ and all $x \in \mathbb{F}^n$
$$
\begin{align*}
(a+b)x &= (a+b)(x_1,...,x_n) \\
&= ((a+b)x_1,...,(a+b)x_n) \\
&= (ax_1+bx_1,...,ax_n+bx_n) \\
ax + bx &= a(x_1,...,x_n) + b(x_1,...,x_n) \\
&= (ax_1,...,ax_n) + (bx_1,...,bx_n) \\
&= (ax_1+bx_1,...,ax_n+bx_n)
\end{align*}
$$