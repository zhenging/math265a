### Section 2.3 Techniques for Computing Limits

+ Limits of Linear Functions
+ Limits Raws, Sum, Difference, Constant Multiple, Product, Quotient, Power, Fractional Power
+ Limits of Polynomial and Rational Functions
+ One-sided Limits (Fractional Power)
+ Techniques other then direct substitution (**Algebriac manipulation**)
+ The slope of tangent line to the graphs of$f(x)=2^x$ at the point $P(0, 1)$. _($\ln 2$)_
+ The **Squeeze Theorem**

#### Homework
p77: 5, 10, 11, 21, 24, 25, 29, 33, 35, 39, 42, 46, 47, 51, 55, 65, 77, 84

1\. How is $\dlim_{x\to a}f(x)$ calculated if $f$ is a polynomial function?
>Solution
Direct substitution.

3\. For what values of $a$ does $\dlim_{x\to a}r(x) = r(a)$ if $r$ is a rational function?
>Solution
As long as $a$ is in the domain of $r$, $\dlim_{x\to a}r(x) = r(a)$ holds.

5\. Explain why $\dlim_{x \to 3}{\frac{x^2-7x+12}{x-3}} = \lim_{x \to 3}{(x-4)}$.
>Solution
$$
\begin{aligned}
f(x) &= \frac{x^2-7x+12}{x-3} \\
&= \frac{(x-3)(x-4))}{x-3} \\
&= x - 4 \quad \text{for } x \ne 3 \\
\end{aligned}
$$
Let $f(x) = \dfrac{x^2-7x+12}{x-3}$, and g(x) = $x-4$, that means $f(x)$ and $g(x)$ have the same graph, expect $f(x)$ is undefined when $x=3$. Therefore, the two functions have the same limits as $x$ approaches $3$, $\dlim_{x \to 3}{f(x)} = \lim_{x \to 3}{g(x)}$.

7\. Suppose $p$ and $q$ are polynomials. If $\dlim_{x\to 0}\dfrac{p(x)}{q(x)} = 10$, and $q(0) = 2$, find $p(0)$.
>Solution
$$
\begin{aligned}
\lim_{x\to 0}\dfrac{p(x)}{q(x)} &= 10 \To \dfrac{p(0)}{q(0)} = 10\\
p(0) &= 10 \cdot q(0) = 20
\end{aligned}
$$

10\. Suppose $f(x) = \begin{cases} 4 & \text{if } x \les 3 \\x+ 2 & \text{if } x > 3\end{cases}$, compute $\dlim_{x \to 3^-}f(x)$ and $\dlim_{x \to 3^+}f(x)$.
>Solution
$\dlim_{x \to 3^-}f(x) = 4$ &emsp; $\dlim_{x \to 3^+}f(x) = 5$

11-16\. **Limits of linear functions** Evaluate the following limits.
11\. $\dlim_{x \to 4}(3x-7)$
>Solution
$\dlim_{x \to 4}(3x-7) = 3 \times 4 - 7 = 5$

13\. $\dlim_{x \to -9}5x$
>Solution
$\dlim_{x \to -9}5x = 5\cdot (-9) = -45$

15\. $\dlim_{x \to 6}4$
>Solution
$\dlim_{x \to 6}4 = 4$

21-24\. **Applying limit laws** Assume $\ _{x \to 1}f(x) = 8$, $\dlim_{x \to 1}g(x) = 3$, and  $\dlim_{x \to 1}h(x) = 2$. Computing the following limits and state the limit laws used to justify your computations.
21\. $\dlim_{x \to 1}\lb{\dfrac{f(x)g(x)}{h(x)}}\rb$
>Solution
$$
\begin{aligned}
\lim_{x \to 1}\lb{\frac{f(x)g(x)}{h(x)}}\rb &= \frac{\dlim_{x \to 1}f(x)g(x)}{\dlim_{x \to 1}h(x)} &\quad\text{Quotient law} \\
& = \frac{\lb\dlim_{x \to 1}f(x)\rb\lb\dlim_{x \to 1}g(x)\rb}{2} &\quad\text{Product law} \\
& = \frac{8 \times 3}{2} = 12
\end{aligned}
$$

24\. $\dlim_{x \to 1}{\sqrt[3]{f(x)g(x)+3}}$
>Solution
$$
\begin{aligned}
\lim_{x \to 1}{\sqrt[3]{f(x)g(x)+3}} &= \sqrt[3]{\lim_{x \to 1}{(f(x)g(x)+3})} &\quad\text{Fractional power law}\\
&= \sqrt[3]{\lim_{x \to 1}f(x) \times \lim_{x \to 1}g(x)+\lim_{x \to 1}(3)} &\quad\text{Product law and Sum law} \\
&= \sqrt[3]{8 \times 3 + 3} \\
&= \sqrt[3]{27} = 3
\end{aligned}
$$

25-32\. **Estimate limits** Evaluate the following limits
25\. $\dlim_{x \to 1}{(2x^3-3x^2+4x +5)}$
>Solution
$$
\begin{aligned}
\lim_{x \to 1}{(2x^3-3x^2+4x +5)} &= \lim_{x \to 1}(2x^3) - \lim_{x \to 1}(3x^2) + \lim_{x \to 1}(4x) + \lim_{x \to 1}{5} &\quad\text{Sum law and Difference law}\\
&= 2\lim_{x \to 1}(x^3) - 3\lim_{x \to 1}(x^2) + 4\lim_{x \to 1}(x) + 5 &\quad\text{Constant multiple power law}\\
&= 2(\lim_{x \to 1}x)^3 - 3(\lim_{x \to 1}x)^2 + 4\lim_{x \to 1}(x) + 5 &\quad\text{Power law}\\
&= 2 \times 1^3 - 3 \times 1^2 + 4 \times 1 + 5 \\
&= 8
\end{aligned}
$$

29\. $\dlim_{b \to 2}\frac{3b}{\sqrt{4b+1} -1}$
>Solution
$$
\begin{aligned}
\lim_{b \to 2}\frac{3b}{\sqrt{4b+1} -1} &= \lim_{b \to 2}\lb{\frac{3}{4} \cdot \frac{(\sqrt{4b+1} +1)(\sqrt{4b+1} -1)}{\sqrt{4b+1} -1}}\rb \\
&= \lim_{b \to 2}\lb{\frac{3}{4} \cdot {(\sqrt{4b+1} +1)}}\rb \\
&= \frac{3}{4}\lim_{b \to 2}{(\sqrt{4b+1} +1)} &\quad\text{Constant multiple law}\\
&= \frac{3}{4}\lb\lim_{b \to 2}{\sqrt{4b+1}} +\lim_{b \to 2}(1) \rb &\quad\text{Sum law}\\
&= \frac{3}{4}\lb\sqrt{\lim_{b \to 2}(4b+1)} + 1\rb &\quad\text{Fractional power law}\\
&= \frac{3}{4}(3+1) = 3
\end{aligned}
$$

33\. **One-sided limits** Let$f(x) = \begin{cases} x^2 + 1 & \text{if } x < -1 \\ \sqrt{x+1} & \text{if } x \ges -1\end{cases}$. Compute the following limits or state that they do not exist.
a. $\dlim_{x \to -1^-}f(x)$ &emsp; b. $\dlim_{x \to -1^+}f(x)$ &emsp; c. $\dlim_{x \to -1}f(x)$
>Solution
a. $x$ approaches $-1$ from the left side, so $x<-1$ and $f(x) = x^2 + 1$
$$
\begin{aligned}
\lim_{x \to -1^-}{f(x)} &= \lim_{x \to -1^-}{(x^2 + 1)} \\
&= \lim_{x \to -1^-}(x^2) + \lim_{x \to -1^-}(1) &\quad\text{Product law} \\
&= \lb\lim_{x \to -1^-}x\rb^2 + 1 &\quad\text{Power law} \\
&= (-1)^2 + 1 = 2
\end{aligned}
$$
b. $x$ approaches $-1$ from the right side, so $x>-1$ and $f(x) = \sqrt{x+1}$
$$
\begin{aligned}
\lim_{x \to -1^+}{f(x)} &= \lim_{x \to -1^+}{\sqrt{x+1}} \\
&= \lb\lim_{x \to -1^+}(x + 1)\rb^{1/2} &\quad\text{Fractional power law} \\
&= (0)^{1/2} = 0
\end{aligned}
$$
c. $\dlim_{x \to -1}f(x)$ does not exist.

35\. **One-sided limits**
a. Evaluate $\dlim_{x \to 2^+}\sqrt{x-2}$
b. Why we don't we consider evaluating $\dlim_{x \to 2^-}\sqrt{x-2}$?
>Solution
a. $\dlim_{x \to 2^+}\sqrt{x-2} = 0$
b. When $x$ approaches $2$ from the left side, $x < 2$ and $x - 2 <0$, that makes $\sqrt{x-2}$ a imaginary number.

39-52\. **Other techniques** *Evaluating the following limits, where $a$ and $b$ are fixed real numbers.*
39\. $\dlim_{x \to 1}\frac{x^2-1}{x-1}$
>Solution
$$
\begin{aligned}
\lim_{x \to 1}\frac{x^2-1}{x-1} &= \lim_{x \to 1}\frac{(x+1)(x-1)}{x-1} \\
& = \lim_{x \to 1}(x+1) &\quad \text{Replacement property}\\
& = 2 \\
\end{aligned}
$$

42\. $\dlim_{t \to 2}\frac{3t^2-7t + 2}{2-t}$
>Solution
$$
\begin{aligned}
\lim_{t \to 2}\frac{3t^2-7t + 2}{2-t} &= \lim_{t \to 2}\frac{(3t-1)(t-2)}{2-t} \\
&= \lim_{t \to 2}(-3t+1) &\quad \text{Replacement property} \\
&= -5
\end{aligned}
$$

46\. $\dlim_{h \to 0}\frac{\frac{1}{5+h} - \frac{1}{5}}{h}$
>Solution
$$
\begin{aligned}
\lim_{h \to 0}\frac{\frac{1}{5+h} - \frac{1}{5}}{h} &= \lim_{h \to 0}\frac{\frac{5-(5+h)}{5(5+h)}}{h} \\
&= \lim_{h \to 0}\frac{-1}{25 + 5h} \\
&= \frac{-1}{25 + 5 \times 0} = -\frac{1}{25} &\quad \text{Rational function} \\
\end{aligned}
$$

47\. $\dlim_{x \to 9}\frac{\sqrt{x} - 3}{x-9}$
>Solution
$$
\begin{aligned}
\lim_{x \to 9}\frac{\sqrt{x} - 3}{x-9} &= \lim_{x \to 9}\frac{\sqrt{x} - 3}{(\sqrt{x} - 3)(\sqrt{x} + 3)} \\
&= \lim_{x \to 9}\frac{1}{\sqrt{x} + 3} &\quad \text{Replacement property} \\
&= \frac{\dlim_{x \to 9}(1)}{\dlim_{x \to 9}(\sqrt{x} + 3)} &\quad \text{Difference law} \\
&= \frac{1}{\sqrt{\dlim_{x \to 9}{x}} + \dlim_{x \to 9}{3}} &\quad \text{Fractional power law and Sum law} \\
&= \frac{1}{3 + 3} = \frac{1}{6} \\
\end{aligned}
$$

51\. $\dlim_{h \to 0}\frac{\sqrt{16+h} - 4}{h}$
>Solution
$$
\begin{aligned}
\lim_{h \to 0}\frac{\sqrt{16+h} - 4}{h} &= \lim_{h \to 0}\frac{(\sqrt{16+h} - 4)(\sqrt{16+h} + 4)}{h((\sqrt{16+h} + 4))} \\
&= \lim_{h \to 0}\frac{16 + h - 4^2}{h(\sqrt{16+h} + 4)} \\
&= \lim_{h \to 0}\frac{1}{\sqrt{16+h} + 4} \\
&= \frac{\dlim_{h \to 0}{(1)}}{\dlim_{h \to 0}{(\sqrt{16+h} + 4)}} &\text{Quotient law} \\
&= \frac{1}{\sqrt{\dlim_{h \to 0}{16 + h}} + \dlim_{h \to 0}{4}} &\text{Fractional power law and Sum law} \\
&= \frac{1}{\sqrt{16} + 4} = \frac{1}{8}
\end{aligned}
$$

55\. **Applying Squeeze Theorem**
a. Show that $-|x| \les x\sin {\frac{1}{x}} \les |x|$, for $x \ne 0$.
b. Illustrate the inequalities in part (a) with a graph
c. Use the Squeeze Theorem to show that $\dlim_{x \to 0}x\sin {\frac{1}{x}} = 0$
>Solution
a. For any real number $\theta$, $-1 \les \sin {\theta} \les 1$. Letting  $\theta = 1/x$ for $x \ne 0$, it follows that
$$
-1 \les \sin {\frac{1}{x}} \les 1
$$
Each term in this inequality is multipled by $|x|$ ($|x| >0$ as $x \ne 0$):
$-|x| \les |x|\sin {\frac{1}{x}} \les |x|$
When $x >0$, $|x| = x$, $-|x| \les x\sin {\frac{1}{x}} \les |x| $;
When $x<0$, $|x| = -x$,
$$
\begin{aligned}
-|x| &\les -x\sin {\frac{1}{x}} \les |x| \\
-|x| \times (-1) &\ges -x\sin {\frac{1}{x}} \times (-1)\ges |x| \times (-1) \\
|x| &\ges x\sin {\frac{1}{x}} \ges -|x| &\text{2}
\end{aligned}
$$
By combining (1) and (2),  we have $-|x| \les x\sin {\frac{1}{x}} \les |x|$, for $x \ne 0$.
b. Graph (55b).
c. Because $\dlim_{x \to 0}{(-|x|)} = \dlim_{x \to 0}{|x|} = 0$, the Squeeze Theorem implies that $\dlim_{x \to 0}x\sin {\dfrac{1}{x}} = 0$.

60-67\. **Evaluating limits** *Evaluating the following limits, where $c$ and $k$ are constants.*
65\. $\dlim_{h \to 0}\frac{(5+h)^2 - 25}{h}$
>Solution
$$
\begin{aligned}
\lim_{h \to 0}\frac{(5+h)^2 - 25}{h} &= \lim_{h \to 0}\frac{h^2 + 10h + 25 - 25}{h} \\
&= \lim_{h \to 0}\frac{h^2 + 10h}{h} \\
&= \lim_{h \to 0}{(h + 10)} \\
&= 0 + 10 = 10 &\quad \text{Polynomial}\\
\end{aligned}
$$

70-76\. Useful factorization formula Calculate the following limits using the factorization formula $x^n-a^n = (x-a)(x^{n-1} + x^{n-2}a + \cdots + xa^{n-2} + a^{n-1})$ where $n$ is a positive integer and $a$ is a real number.
71\. $\dlim_{x\to 1}\dfrac{x^6-1}{x-1}$
>Solution
$$
\begin{aligned}
\lim_{x\to 1}\dfrac{x^6-1}{x-1} &= \lim_{x\to 1}\dfrac{(x-1)(x^5+x^4+x^3+x^2+x+1)}{x-1}\\
&= 1+ 1+1+1+1+1 = 6
\end{aligned}
$$

74. $\dlim_{x\to a}\dfrac{x^n-a}{x-a}$
>Solution
$$
\begin{aligned}
\lim_{x\to a}\frac{x^n-a}{x-a} &= \lim_{x\to a}\frac{(x-a)(x^{n-1} + x^{n-2}a + \cdots + xa^{n-2} + a^{n-1})}{x-a}\\
&= \lim_{x\to a}(x^{n-1} + x^{n-2}a + \cdots + xa^{n-2} + a^{n-1})\\
&= a^{n-1} + a^{n-2}a + \cdots + a\cdot a^{n-2} + a^{n-1}\\
&= na^{n-1}
\end{aligned}
$$

77-80\. **Limits involving conjugates** Evaluate the following limits.
77\. $\dlim_{x \to 1}\frac{x-1}{\sqrt{x} -1}$
>Solution
$$
\begin{aligned}
\lim_{x \to 1}\frac{x-1}{\sqrt{x} -1} &= \lim_{x \to 1}\frac{(\sqrt{x} -1)(\sqrt{x} +1)}{\sqrt{x} -1} \\
&= \lim_{x \to 1}(\sqrt{x} + 1) \\
& = 1 + 1 = 2
\end{aligned}
$$

84\. **A problem from relative theory** Suppose a spaceship of length $L_0$ is travelling at a high speed $v$ relative to an observer. To the observer, the ship appears to have a smaller length given by the *Lorentz contraction formula* $L = L_0 \sqrt{1 - \dfrac{v^2}{c^2}}$, where $c$ is the speed of light.
a. What is the observed length $L$ of the ship if it is travelling at $50\%$ of the speed of light?
b. What is the observed length $L$ of the ship if it is travelling at $75\%$ of the speed of light?
c. In parts (a) and (b), what happens to $L$ as the speed of the ship increases?
d. Find $\dlim_{v \to c^-}(L_0 \sqrt{1 - \dfrac{v^2}{c^2}})$ and explain the significance of this limit.
>Solution
a. When $v = 0.5c$, $L = L_0 \sqrt{1 - \frac{(0.5c)^2}{c^2}} = \frac{\sqrt{3}}{2}L_0$
b. When $v = 0.75c$, $L = L_0 \sqrt{1 - \frac{(0.75c)^2}{c^2}} = \frac{\sqrt{7}}{4}L_0$
c. As the speed increases, $L$ decreases.
d.
$$
\begin{aligned}
\lim_{v \to c^-}(L_0 \sqrt{1 - \frac{v^2}{c^2}}) &= L_0 \lim_{v \to c^-}( \sqrt{1 - \frac{v^2}{c^2}}) \\
&= L_0 \sqrt{\lim_{v \to c^-}(1 - \frac{v^2}{c^2})} \\
&= L_0 \sqrt{\lim_{v \to c^-}(1) - \lim_{v \to c^-}(\frac{v^2}{c^2})} \\
&= L_0 \sqrt{1 - 1} = 0
\end{aligned}
$$
When the the speed of the ship approaches the speed of light (but will never exceed it), the observer will hardly see the ship because the length of the ship approaches $0$.
