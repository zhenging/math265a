### Section 2.7 Precise Definition of Limits

+ Moving Toward a Precise Definition
+ Limit Proofs:
  1. Find $\delta$.
  2. Write a proof.
+ Justifying Limits Laws
+ Infinite Limits
+ Limits at Infinity

#### Homework
p121: 5, 9, 10, 15, 19

5\. State the precise definition of $\dlim_{x \to a}f(x) = L$.
>Solution
Assume that $f(x)$ exists for all $x$ in some open interval containing $a$, except possibly at $a$, we say that the limit of $f(x)$  as x approaches $a$ is $L$, written
$$
\lim_{x \to a}f(x) = L
$$
if for any number $\varepsilon > 0$ there is a corresponding number $\delta > 0$, such that $|f(x) - L| < \varepsilon$ whenever $|x-a| < \delta$.

9\. **Determine values of $\delta$ from a graph** The function f in the figure satisfies $\dlim_{x \to 2}f(x) = 5$. Determine the largest value of $\delta > 0$ satisfying each statement.
a. If $0 < |x-2| < \delta$, then $|f(x) - 5| < 2$.
b. If $0 < |x-2| < \delta$, then $|f(x) - 5| < 1$.
>Solution
a. To satisfy that $f(x)$ is within 2 units of 5, $f(x)$ belongs to $(3, 7)$, it appears that x is within $1$ unit of $2$, so $\delta = 1$.
b. To satisfy that $f(x)$ is within 1 unit of 5, $f(x)$ belongs to $(4, 6)$, it appears that x is within $1/2$ unit of 2, so $\delta = 1/2$.

10\. **Determine values of $\delta$ from a graph** The function f in the figure satisfies $\dlim_{x \to 2}f(x) = 5$. Determine the largest value of $\delta > 0$ satisfying each statement.
a. If $0 < |x-2| < \delta$, then $|f(x) - 4| < 1$.
b. If $0 < |x-2| < \delta$, then $|f(x) - 4| < 1/2$.
>Solution
a. To satisfy that $f(x)$ is within 1 units of 4, $f(x)$ belongs to $(3, 5)$, it appears that x is within $1$ unit of $2$, so $\delta = 1$.
b. To satisfy that $f(x)$ is within 1/2 unit of 4, $f(x)$ belongs to $(7/2, 9/2)$, it appears that x is within $1/2$ unit of 2, so $\delta = 1/2$.

15\. **Finding a symmetric interval** The function $f$ in the figure satisfies  $\dlim_{x \to 2}f(x) = 3$. For each value of $\varepsilon$, find a value of $\delta > 0$ such that $|f(x) - 3| < \varepsilon  \text{ whenever } 0< |x-2| < \delta \quad \text{(2)}$.
a. $\varepsilon = 1$
b. $\varepsilon = \frac{1}{2}$
c. For any $\varepsilon  > 0$, make a conjecture about the corresponding value of $\delta$ satisfying $(2)$.
>Solution
a. For $\varepsilon = 1$, $f(x)$ belongs to $(2, 4)$, then $x$ would belongs to $(1, 5)$. The possible values for $\delta$ would be $1$ or $3$. Apparently $\delta = 3$ wouldn't work on the left side of $x=2$ on x-axis, so $\delta = 1$.
b. For $\varepsilon =  \frac{1}{2}$, $f(x)$ belongs to $(\frac{5}{2}, \frac{7}{2})$, then $x$ would belongs to $(\frac{3}{2}, \frac{7}{2})$. The possible values for $\delta$ would be $\frac{1}{2}$ or $\frac{3}{2}$. Apparently $\delta = \frac{3}{2}$ wouldn't work on the left side of $x=2$ on x-axis, so $\delta = \frac{1}{2}$.
c. For any given $\varepsilon > 0$, $\delta = \varepsilon$ would satisfy $(2)$.

19\. **Limit proofs** Use the precise definition of a limit to prove the following limits.
$\dlim_{x \to 1}(8x+5) = 13$
>Solution
Let  $\delta = \varepsilon / 8$ for any $\varepsilon > 0$. If $0 < |x-1| < \delta $, we have
$$
\begin{aligned}
0 &< |x-1| <  \varepsilon / 8 & \qquad \text{Simple replacement } \\
0 &< |8x-8| < ( \varepsilon / 8) * 8  &\qquad \text{Multiply 8 in all terms of the inequality} \\
0 &< |(8x+5) -13| <  \varepsilon & \\
0 &< |f(x) - L| <  \varepsilon & \qquad \text{Let f(x) = 8x + 5 and L = 13}
\end{aligned}
$$
Therefore, $\dlim_{x \to 1}f(x) = \dlim_{x \to 1}(8x+5) =13$.
