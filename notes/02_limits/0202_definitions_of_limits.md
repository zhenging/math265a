### Section 2.2 Definitions of Limits

+ Limit of a Function (Arbitrarily large and sufficiently close)
+ The value of $L$ (limit) depends upon the value of $f$ near $a$, but it does not depend on the value of $f(a)$.
+ Find limits from a graph and a table (_Ex1, 2_)
+ One-Sided Limits: $\dlim_{x \to a^+}f(x) = L, \dlim_{x \to a^-}f(x) = L$
+ **Relationship** Between _One-sided_ and _Two-sided_ Limits
+ Function with jumps and some strange behavior ($\dlim_{x\to 0+}\cos \frac{1}{x}$ does not exist).

#### Homework
p65: 2, 7, 10, 11, 15, 17, 19, 21, 24, 25, 31, 37, 41

2\. True or false: When $\dlim_{x \to a}f(x)$ exists, it always equals $f(a)$. Explain.
>Solution
The statement is false. $f(a)$ is not necessarily defined.

7\. **Finding limits from a graph** Use the graph of $h$ in the figure to find the following values, if they exist
a. $h(2)$ &emsp; b. $\dlim_{x \to 2}h(x)$
c. $h(4)$ &emsp; d. $\dlim_{x \to 4}h(x)$
e. $\dlim_{x \to 5}h(x)$
>Solution
a. $h(2) = 5$ &emsp; b. $\dlim_{x \to 2}h(x) = 3$ &emsp; c. $h(4)$ is undefined. &emsp; d. $\dlim_{x \to 4}h(x) = 1$ &emsp; e. $\dlim_{x \to 5}h(x) = 2$

10\. **Finding limits from a graph** Use the graph of $f$ in the figure to find the following values, if they exist.
a. $f(2)$ &emsp; b. $\dlim_{x \to 2}f(x)$ &emsp; c. $\dlim_{x \to 4}f(x)$ &emsp; d. $\dlim_{x \to 5}f(x)$
>Solution
a. $f(2) = 2$ &emsp; b. $\dlim_{x \to 2}f(x) = 4$ &emsp; c. $\dlim_{x \to 4}f(x) = 4$ &emsp; d. $\dlim_{x \to 5}f(x) = 2$

11\. **Estimate a limit from tables** Let $\displaystyle f(x) = \frac{x^2 - 4}{x-2}$.
a. Calculate $f(x)$ for each value for $x$ in the following tables.
b. Make a conjecture about the value of $\dlim_{x \to 2}\frac{x^2 - 4}{x-2}$.
| $x$ | 1.9 | 1.99 | 1.999 | 1.9999 | 2.1 | 2.01 | 2.001 | 2.0001 |
|-----|-----|------|-------|--------|-----|------|-------|--------|
| $f(x)$| 3.9|3.99 | 3.999 | 3.9999 | 4.1 | 4.01 | 4.001 | 4.0001 |
>Solution
a. See Table Above
b. $\dlim_{x \to 2}f(x) = 4$

15\. **Estimate a limit graphically and numerically** Let $f(x) = \dfrac{x-2}{\ln |x-2|}$.
a. Plot a graph of $f$ to estimate $\dlim_{x \to 2}f(x)$.
b. Evaluate $f(x)$ for values of $x$ near $2$ to support your conjecture in part(a).
| x | 1.99 | 1.999 | 1.9999 | 2.0001 | 2.001 | 2.01 |
|---|------|-------|--------| -------|-------|------|
|f(x) | 0.00217 | 0.00014 | 0.0000109 | -0.0000109 | -0.00014 | -0.00217 |
>Solution
a. Graph (15).
b. See Table Above
From the graph and table of $f(x)$, it appears that $\dlim_{x \to 2}f(x) = 0$

17\. **Estimate a limit graphically and numerically** Let $f(x) = \dfrac{1-\cos(2x-2)}{(x-1)^2}$.
a. Plot a graph of $f$ to estimate $\dlim_{x \to 1}f(x)$.
b. Evaluate $f(x)$ for values of $x$ near $1$ to support your conjecture in part(a).
| x | 0.99 | 0.999 | 0.9999 | 1.0001 | 1.001 | 1.01 |
|---|------|-------|--------|--------|-------|------|
|$f(x)$ | 1.9999333 | 1.9999993 | 2  | 2  1.9999993 | 1.9999333 |
>Solution
a. Graph (17).
b. See Table Above. From the graph and table of $f(x)$, it appears that $\dlim_{x \to 1}f(x) = 2$

19\. **One-sided limit and two-sided limit** Let $f(x) = \dfrac{x^2 -25}{x-5}$. Use tables and graphs to make a conjecture about the values of $\dlim_{x \to 5^+} f(x)$, $\dlim_{x \to 5^-} f(x)$, and $\dlim_{x \to 5} f(x)$, if they exist.
| $x$   | 4.99 | 4.999 | 4.9999 | 5.0001  | 5.001  | 5.01  |
|-------|------|-------|--------|---------|--------|-------|
|$f(x)$ | 9.99 | 9.999 | 9.9999 | 10.0001 | 10.001 | 10.01 |
>Solution
a. Graph (19).
b. See Table Above. From the graph and table of $f(x)$, it appears that $\dlim_{x \to 5^+}f(x) = 10$, $\dlim_{x \to 5^-}f(x) = 10$, and $\dlim_{x \to 5}f(x) = 10$

21\. **One-sided limit and two-sided limit** Use the graph of $f$ in the figure to find the following values, if they exist. If a limit doesn't exist, explain why.
a. $f(1)$ &emsp; b. $\dlim_{x \to 1^-}f(x)$ &emsp; c. $\dlim_{x \to 1^+}f(x)$ &emsp; d. $\dlim_{x \to 1}f(x)$
>Solution
a. $f(1) = 0$ &emsp; b. $\dlim_{x \to 1^-}f(x) = 1$ &emsp; c. $\dlim_{x \to 1^+}f(x) = 0$ &emsp;
d. $\dlim_{x \to 1}f(x)$ does not exist, because the limits of $f(x)$ as $x$ approaches $1$ from the left and right sides are not equal, $\dlim_{x \to 1^-}f(x) = 1$ and $\dlim_{x \to 1^+}f(x) = 0$.

24\. **One-sided limit and two-sided limit** Use the graph of $g$ in the figure to find the following values, if they exist. If a limit doesn't exist, explain why.
a. $g(-1)$
b. $\dlim_{x \to -1^-}g(x)$ &emsp; c. $\quad \dlim_{x \to -1^+}g(x)$ &emsp; d. $\quad \dlim_{x \to -1}g(x)$
e. $g(1)$ &emsp; f. $\dlim_{x \to 1}g(x)$
g. $\dlim_{x \to 3}g(x)$
h. $g(5)$ &emsp; i. $\dlim_{x \to 5^-}g(x)$
>Solution
a. $g(-1) = 3$
b. $\dlim_{x \to -1^-}g(x) = 2$ &emsp; c. $\dlim_{x \to -1^+}g(x) = 2$ &emsp; d. $\dlim_{x \to -1}g(x) = 2$
e. $g(1) = 2$ &emsp;
f. $\dlim_{x \to 1}g(x)$ does not exist, because the limits of $g(x)$ as $x$ approaches $1$ from the left and right sides are not equal, $\dlim_{x \to 1^-}g(x) = 4$ and $\dlim_{x \to 1^+}g(x) = 5$.
g. $\dlim_{x \to 3}g(x) = 4$
h. $g(5) = 5$ &emsp; i. $\dlim_{x \to 5^-}g(x) = 5$

25\. **Strange behavior near $x=0$**
a. Create a table of values of $\sin (1/x)$, for $x=\frac{2}{\pi}, \frac{2}{3\pi}, \frac{2}{5\pi}, \frac{2}{7\pi}, \frac{2}{9\pi}$, and $\frac{2}{11\pi}$. Describe the pattern of values you observe.
b. Why does a graphing utility have difficulty plotting the graph of $y = \sin (1/x)$ near $x=0$ (see figure)?
c. What do you conclude about $\dlim_{x \to 0} \sin (1/x)$?
| x    | $\frac{2}{\pi}$ | $\frac{2}{3\pi}$ | $\frac{2}{5\pi}$ |$\frac{2}{7\pi}$ |$\frac{2}{9\pi}$ |$\frac{2}{11\pi}$ |
|--------|---|----|---|----|---|----|
| $f(x)$ | 1 | -1 | 1 | -1 | 1 | -1 |
>Solution
a. See Table Above.
When $x = \frac{2}{(2n+1)\pi}$, $f(x) = (-1)^n$, where $n$ is a non-negative integer.
b. As $x \to 0$, $1/x \to \infty$, the values of $f(x)$ oscillate between $1$ and $-1$
c. $\dlim_{x \to 0} \sin (1/x)$ does not exist.

30-33\. **Calculator limits** Estimate the value of the following limits by creating a table of function values for $h=0.01, 0.001, 0.0001$ and $h=-0.01, -0.001, -0.0001$
31\. $\dlim_{h \to 0}(1 + 3h)^{2/h}$
| h   | 0.01  | 0.001 | 0.0001 | -0.0001 | -0.001 | -0.01|
|-----|-------|-------|--------|---------|--------|------|
| f(h) |369.36 | 399.82 | 403.07 | 403.79  | 407.08 | 442.23 |
>Solution
Let $f(h) = (1 + 3h)^{2/h}$
$\dlim_{h \to 0}f(h) \approx 403.43$

37\. **Limit by graphing** Use the zoom and trace features of a graphing utility to approximate $\dlim_{x \to 0}x \sin {\frac{1}{x}}$.
>Solution
Graph (37). $\dlim_{x \to 0}x \sin {\frac{1}{x}} = 0$

41\. **Postage rates** Assume that postage for sending a first-class letter in United States is $\$0.44$ for the first ounce (up to and including 1 oz) plus $\$0.17$ for each additional ounce (up to and including each additional ounce).
a. Graph the function $p = f(w)$ that gives the postage $p$ for sending a letter that weights $w$ ounces, for $0 < w \les 5$
b. Evaluate $\dlim_{w \to 3.3}f(w)$
c. Interpret the limits $\dlim_{w \to 1^+}f(w)$ and $\dlim_{w \to 1^-}f(w)$
d. Does $\dlim_{w \to 4}f(w)$ exists? Explain.
>Solution
a. Graph (41).
b. $ \dlim_{w \to 3.3}f(w) = 0.95$
c. $\dlim_{w \to 1^+}f(w) = 0.61$, it means that the postage for sending a letter slightly heavier than 1 oz is $\$0.61$; $\dlim_{w \to 1^-}f(w) = 0.44$, it means that the postage for sending a letter slightly less than 1 oz is $\$0.44$.
d. $\dlim_{w \to 4}f(w)$ does not exist, because the limits of $f(w)$ as $w$ approaches $4$ from the left and right sides are not equal, $\dlim_{w \to 4^-}f(w) = 0.95$ and $\dlim_{w \to 4^+}f(w) = 1.12$.
