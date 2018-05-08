### Section 2.6 Continuity
pg109: 2, 9, 10, 13, 16, 17, 20, 21, 23, 29, 35, 37, 45, 51, 53, 57, 61c, 73, 81, 93

2\. Give the three conditions that must satisfied by a function to be continuous at a point.
>Solution
In order for $f(x)$ to be continuous at point $a$, the following three conditions must hold:
1\. $f(a)$ is defined ($a$ is in the domain of $f$)
2\. $\dlim_{x \to a}{f(x)}$ exists.
3\. $\lim_{x \to a}{f(x)} = f(a)$ (the value of $f$ equals the limit of $f$ at $a$).

9-12\. **Discontinuities from a graph** Determine the points at which the following functions $f$ have discontinuities. For each point state the conditions in the continuity checklist that are violated.
9\. Graph (9).
>Solution
$f(x)$ has discontinuities at the following points:
1\. $x=1$, as $f(1)$ is not defined.
2\. $x=2$, as $\dlim_{x \to 2}{f(x)} \ne f(2)$.
3\. $x=3$, as $\dlim_{x \to 3^+}{f(x)} \ne \lim_{x \to 3^-}{f(x)}$, $\dlim_{x \to 3}{f(x)}$ does not exist.

10\. Graph (10).
>Solution
$f(x)$ has discontinuities at the following points:
1\. $x=1$, as $\dlim_{x \to 1}{f(x)} \ne f(1)$.
2\. $x=2$, as $\dlim_{x \to 2^+}{f(x)} \ne \lim_{x \to 2^-}{f(x)}$, $\dlim_{x \to 2}{f(x)}$ does not exist.
3\. $x=3$, as $f(3)$ is not defined.

13-20\. **Continuity at a point** Determine whether the following functions are continuous at $a$. Use the continuity checklist to justify your answer.
13\. $f(x) = \dfrac{2x^2 + 3x + 1}{x^2 + 5x}; a=5$
>Solution
1\. $f(5) = \dfrac{2 \times 5^2 + 3 \times 5 + 1}{5^2 + 5 \times 5} = \dfrac{33}{25}$, so $f(5)$ is defined.
2\. $f(x)$ is a rational function and the denominator of $f(5)$ is $5^2 + 5 \times 5 = 50 \ne 0$, so $\dlim_{x \to 5}{f(x)}$ exists and $\dlim_{x \to 5}{f(x)} = \frac{2 \times 5^2 + 3 \times 5 + 1}{5^2 + 5 \times 5} = \frac{33}{25}$.
3\. $\dlim_{x \to 5}{f(x)} = f(5)$.
Therefore, $f(x)$ is continuous at point $a=5$.

16\. $f(x) = \dfrac{1}{x-3}; a=3$
>Solution
1\. $f(3)$ is not defined.
2\. $\dlim_{x \to 3^+}{f(x)} = \infty$ and $\dlim_{x \to 3^-}{f(x)} = -\infty$, so $\dlim_{x \to 3}{f(x)}$ does not exist.
Therefore, $f(x)$ is not continuous at point $a=3$.

17\. $f(x) = \begin{cases}\dfrac{x^2-1}{x-1} &\text{if } x \ne 1 \\ 3 &\text{if } x =1\end{cases}; a=1$
>Solution
1\. $f(1) = 3$, so $f(1)$ is defined.
2\. $\dlim_{x \to 1}{f(x)} = \lim_{x \to 1}{\frac{x^2-1}{x-1}} = \lim_{x \to 1}(x+1) = 2$, so $\dlim_{x \to 1}{f(x)}$ exists.
3\. $\dlim_{x \to 1}{f(x)} \ne f(1)$.
Therefore, $f(x)$ is not continuous at point $a=1$.

20\. $f(x) = \begin{cases}\dfrac{x^2 + x}{x+1} &\text{if } x \ne -1 \\ 2 &\text{if } x =-1\end{cases}; a=-1$
>Solution
1\. $f(-1) = 2$, so $f(-1)$ is defined.
2\. $\dlim_{x \to -1}{f(x)} = \lim_{x \to -1}{\frac{x^2 + x}{x + 1}} = \lim_{x \to 1}(x) = -1$, so $\dlim_{x \to -1}{f(x)}$ exists.
3\. $\dlim_{x \to -1}{f(x)} \ne f(-1)$.
Therefore, $f(x)$ is not continuous at point $a=-1$.

21-26\. **Continuity on intervals**  Use theorem 2.10 to determine the intervals on which the following functions are continuous.
21\. $p(x) = 4x^5 - 3x^2 + 1$
>Solution
$p(x)$ is a polynomial function, so it is continuous at $\{x \mid x \in \mathbb{R} \}$.

23\. $f(x) = \dfrac{x^5 + 6x + 17}{x^2-9}$
>Solution
$f(x)$ is a rational function, so it is continuous for all $x$ at which the denominator is nonzero. The denominator factors as $(x+3)(x-3)$, so it is zero at $x=-3$ and $x=3$. Therefore, $f$ is continuous at $\{x \mid x \in (-\infty, -3) \cup (-3, 3) \cup (3, \infty)\}$.

27-30\. **Limits of compositions** Evaluate the following limits and justify your answer.
29\. $\dlim_{x \to 1}(\frac{x+5}{x+2})^4$
>Solution
Because $f(x)=(\frac{x+5}{x+2})^4$ is a rational function, it is continuous at all points in its domain. Thus $\dlim_{x \to 1}{f(x)} = f(1) = (\frac{1+5}{1+2})^4 = 16$.

35\. **Intervals of continuity** Let $f(x) = \begin{cases} x^2 + 3x &\text{if } x \ges 1 \\ 2x &\text{if } x <1 \end{cases}$.
a. Use the continuity checklist to show that $f$ is not continuous at $1$.
b. Is $f$ continuous from the left or right at $1$?
c. State the interval(s) of continuity.
>Solution
a. When $x \ges 1$, $f(x) = x^2 + 3x$ is a polynomial function, it is continuous at all points in its domain. Thus $\dlim_{x \to 1^+}{f(x)} = f(1) = 1^2 + 3 \times 1 = 4$. When $x<1$, $f(x)=2x$ and $\dlim_{x \to 1^-}{f(x)} = f(1) = 2 \times 1 = 2$. Because $\dlim_{x \to 1^+}f(x) \ne \lim_{x \to 1^-}f(x)$, $\dlim_{x \to 1}f(x)$ does not exist. Thus $f$ is not continuoius at $1$.
b. $f$ is continuous from the right of $1$.
c. $f$ is continuous at $\{x \mid x \in (-\infty, 1) \cup [1, \infty)\}$.

37-42\. **Functions with roots** Determine the interval(s) on which the following functions are continuous. Be sure to consider right-and left-continuous at the endpoints.
37\. $f(x) = \sqrt{2x^2 -16}$
>Solution
$$
\begin{aligned}
2x^2 -16 \geq 0 &\To x \geq \sqrt{8} \text{ or } x \leq -\sqrt{8} \\
\lim_{x \to {\sqrt{8}}^+}f(x) &= \lim_{x \to {\sqrt{8}}^+}{\sqrt{2x^2 -16}}  \\
&= \sqrt{2({\sqrt{8}})^2 -16} = 0 &\text{Replacement Property} \\
\lim_{x \to {\sqrt{8}}^-}f(x) &\text{ does not exist.} \\
\lim_{x \to {-\sqrt{8}}^+}f(x) &\text{ does not exist.} \\
\lim_{x \to {-\sqrt{8}}^-}f(x) &= \lim_{x \to {-\sqrt{8}}^-}{\sqrt{2x^2 -16}}  \\
&= \sqrt{2({-\sqrt{8}})^2 -16} = 0 &\text{Replacement Property}
\end{aligned}
$$
$f(x)$ is continuous for all points of its domain $\{x \mid x \in (-\infty, -\sqrt{8}] \cup [\sqrt{8}, \infty)\}$.

43-46\. **Limits with roots** Determine the following limits and justify your answers.
43\. $\dlim_{x \to 3}{\sqrt{x^2 + 7}}$
>Solution
$f(x) = \sqrt{x^2 + 7}$ is continuous at points in its domain. $3$ is in its domain, so $\dlim_{x \to 2}f(x) = \dlim_{x \to 2}{ \sqrt{x^2 + 7}} =  \sqrt{3^2 + 7} = 4$.

47-52\. **Continuity and limits with transcendental functions** Determine the interval(s) on which the following functions are continuous, then evaluate the given limits.
51\. $f(x) = \dfrac{e^x}{1-e^x}$
>Solution
$f(x)$ is continuous for all points in its domain $\{x \mid x \ne 0\}$.
$$
\begin{aligned}
\lim_{x \to 0^+}\frac{e^x}{1-e^x} &= \lim_{x \to 0^+}\frac{\overbrace{e^x}^{\text{approach 1}}}{\underbrace{1-e^x}_{\text{negative and approaches 0}}} = -\infty \\
\lim_{x \to 0^-}\frac{e^x}{1-e^x} &= \lim_{x \to 0^-}\frac{\overbrace{e^x}^{\text{approach 1}}}{\underbrace{1-e^x}_{\text{positive and approaches 0}}} = \infty
\end{aligned}
$$

53\. **Intermediate Value Theorem and interest rates** Suppose \$5000 is invested in a savings account for 10 years (120 months), with an  annual interest rate of $r$, compounded monthly. The amount of money in the account after 10 years is $A(r) = 5000(1 + r/12)^{120}$.
a. Use the Intermediate Value Theorem to show there is a value of $r$ in $(0, 0.08)$ -  an interest rate between 0% and 8% - that allows you to reach your savings goal of \$7000 in 10 years/
b. Use a graph to illustrate your explanation in part(a); then approximate the interest rate required to reach your goal.
>Solution
a.
$$
\begin{aligned}
A(0) &= 5000(1 + 0/12)^{120} = 5000 \\
A(00.8) &= 5000(1 + 0.08/12)^{120} = 11098.20
\end{aligned}
$$
Because $A(r)$ is a polynomial, it is continuous on the interval $[0, 0.08]$, and also $A(0) = 5000  \le A(r)=7000 \le A(0.08) = 11098.20$, according to the Intermediate Value Theorem, there must be some value $c$ for $r$ between $[0, 0.08]$, that $A(c) = 7000$.
b. Graph (53).
$$
\begin{aligned}
5000(1 + c/12)^{120} &= 7000 \\
1+ c/12 &= (7/5)^{1/120} \\
c &= ((7/5)^{1/120} -1) \times 12\\
c &\approx 0.034
\end{aligned}
$$

55-60\. **Applying the Intermediate Value Theorem**
a. Use the Intermediate Value Theorem to show that the following equations have a solution on the give interval.
b. Using a graphing utility to find all the solutions to the equation on the given interval.
c. Illustrate your answers with an appropriate graph.
57\. $x^3 -5x^2+2x = -1$; $(-1, 5)$
>Solution
a. Let $f(x) = x^3 -5x^2+2x + 1$, then we are looking for the solution of $f(x) = 0$.
$$
\begin{aligned}
f(-1) &= (-1)^3 - 5 \times (-1)^2 + 2 \times (-1) + 1 = -7\\
f(5) &= 5^3 - 5 \times 5^2 + 2 \times 5 + 1 = 11
\end{aligned}
$$
Because $f(x)$ is a polynomial, it is continuous on the interval $[-1, 5]$, and also $f(-1) = -7 \le f(x)=0 \le f(5) = 11$, according to the Intermediate Value Theorem, there must be some value $c$ for $x$ between $[-1, 5]$, that $f(c) = 0$.
b. The solutions are $x \approx -0.285, 0.778$, and $4.507$.
c. Graph (57).

61\. **Explain why or why not** Determine whether the following statements are true and give an explanation or counterexample.
c. If $a<b$, and $f(a) \leq L \leq f(b)$, then there is some value for $c$ in $(a, b)$ for which $f(c) = L$.
>Solution
False. The statement holds only if $f$ is continuous on interval $(a, b)$, otherwise, $f(c)$ may be not defined.

67-76\. **Miscellaneous limits** Evaluate the following limits.
73\. $\dlim_{x \to \infty}{\frac{{\tan^{-1} x}}{x}}$
>Solution
As $x \to \infty$, $\tan^{-1} x$ approaches $\frac{\pi}{2}$.
$$
\lim_{x \to \infty}{\frac{{\tan^{-1} x}}{x}} \to \frac{\frac{\pi}{2}}{\infty} \to 0
$$
Therefore $\dlim_{x \to \infty}{\frac{{\tan^{-1} x}}{x}} = 0$.

81\. **An unknown constant** Let $g(x) = \begin{cases}x^2 + x & \text{if } x < 1 \\ a & \text{if } x = 1 \\ 3x + 5 & \text{if } x > 1\end{cases}$
a. Determine the value of $a$ for which $g$ is continuous from the left at $1$.
b. Determine the value of $a$ for which $g$ is continuous from the right at $1$.
c. Is there a value of $a$ for which $g$ is continuous at $1$? Explain.
>Solution
a. When $a \to 1^-$, $a< 1$, we have $g(x) = x^2 + x$. $g(x)$ is a polynomial, so it is continuous for all the values of a, as long as $a<1$.
b. When $a \to 1^+$, $a> 1$, we have $g(x) = 3x + 5$. $g(x)$ is a linear function, so it is continuous for all the value of a , as long as $a >1$.
c. In order for $g(x)$ to be continuous at $1$,  three conditions must be satisfied.
1\. $g(1)$ is defined.
2\. $\dlim_{x \to 1}g(x)$ exists.
3\. $\dlim_{x \to 1}g(x) = g(a)$
$$
\begin{aligned}
g(1) = a\\
\lim_{x \to 1^-}g(x) &= \lim_{x \to 1^-}(x^2 + x)  \\
&= 1^2 + 1 =2&\text{Polynomial} \\
\lim_{x \to 1^+}g(x) &= \lim_{x \to 1^-}(3x + 5)\\
&= 3 \times 1 + 5 = 8 &\text{Sum Rule} \\
\end{aligned}
$$
Because $\dlim_{x \to 1^-}g(x) \ne \lim_{x \to 1^+}g(x)$,  $\dlim_{x \to 1}g(x)$ does not exist. There is no such value for $a$ that $g(x)$ can be continuous at $a$.

93-94\. **Removable  discontinuities** Show that the following function have a removable discontinuity at the give point. See exercise 91-92.
93\. $f(x)= \dfrac{x^2-7x+10}{x-2}$; $x=2$
>Solution
$$
\begin{aligned}
\lim_{x \to 2}f(x) &= \lim_{x \to 2}\frac{x^2-7x+10}{x-2} \\
&= \lim_{x \to 2}\frac{(x-2)(x-5)}{x-2} \\
&= \lim_{x \to 2}(x-5) &\text{Replacement Property}\\
&= 2 - 5 = -3
\end{aligned}
$$
Therefore, the discontinuity of $f$ at $x=2$ is removable, as $\dlim_{x \to 2}f(x)$ exists.
