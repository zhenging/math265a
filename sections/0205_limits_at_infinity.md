### Section 2.5 Limits at Infinity

+ Limits at Infinity and Horizontal Asymptote: $\dlim_{x \to \pm \infty} f(x)=L$
+ Infinite Limites at Infinity: $\dlim_{x \to \pm \infty} f(x)=\pm \infty$
+ Limits at Infinity of Powers and Polynomials
+ End behavior (_Ex3_)
+ Slant Asymptote
+ End behavior and Asymptote of Rational Functions ($f(x) = \frac{p(x)}{q(x)}$)
+ End behavior of $e^x, e^{-x}, \ln x$, (_Ex6_)

#### Homework
p98: 5, 9, 11, 12, 15, 19, 21, 27, 30, 33, 35, _41_, 47, 49, 57, _77_

5\. Describe the end behavior of $f(x)=-2x^3$
>Solution
$$
\lim_{x \to \infty}(-2x^3) = -\infty \text{ and } \lim_{x \to -\infty}(-2x^3) = \infty
$$

9-14\. **Limits at infinity** Evaluate the following limits.
9\. $\dlim_{x \to \infty}(3 + \frac{10}{x^2})$
>Solution
$$
\lim_{x \to \infty}(3 + \frac{10}{x^2}) = \lim_{x \to \infty}(3) + \lim_{x \to \infty}(\frac{10}{x^2}) = 3 + 0 = 3
$$

11\. $\dlim_{\th \to \infty}{\frac{\cos \th}{\th ^2}}$
>Solution
$$
\begin{aligned}
&\because -1 \les \cos \th \les 1 \text{ and } {\th ^2} >0\\
&\therefore \frac{-1}{\th ^2} \les {\frac{\cos \th}{\th ^2}} \les \frac{1}{\th ^2}\\
&\text{According to Squeeze Theorem, we have} \lim_{\th \to \infty}{\frac{-1}{\th ^2}} = \lim_{\th \to \infty}{\frac{\cos \th}{\th ^2}} = \lim_{\th \to \infty}{\frac{1}{\th ^2}}\\
&\because \lim_{\th \to \infty}{\frac{-1}{\th ^2}} = \lim_{\th \to \infty}{\frac{1}{\th ^2}} = 0\\
&\therefore \lim_{\th \to \infty}{\frac{\cos \th}{\th ^2}} = 0
\end{aligned}
$$

12\. $\dlim_{x \to \infty}{\frac{3 + 2x + 4x^2}{x^2}}$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}{\frac{3 + 2x + 4x^2}{x^2}} &= \lim_{x \to \infty}{(3x^{-2} + 2x^{-1} + 4)} \\
&= \lim_{x \to \infty}(3x^{-2}) + \lim_{x \to \infty}(2x^{-1}) + \lim_{x \to \infty}(4) \\
&= 0 + 0 + 4 = 4
\end{aligned}
$$

15-24\. **Infinite limits at infinity** Determine the following limits.
15\. $\dlim_{x \to \infty}x^{12}$
>Solution
$\dlim_{x \to \infty}x^{12} = \infty$

19\. $\dlim_{x \to \infty}(3x^{12} - 9x^7)$
>Solution
$\dlim_{x \to \infty}(3x^{12} - 9x^7) = \infty$

21\. $\dlim_{x \to \infty}(-3x^{16}+2)$
>Solution
$\dlim_{x \to \infty}(-3x^{16}+2) = -\infty$

25-34\. **Rational functions** Evaluate $\dlim_{x \to \infty}f(x)$ and $\dlim_{x \to -\infty}f(x)$ for the following rational functions. Then give the horizontal asymptote of $f$ (if any).
27\. $\displaystyle f(x) = \frac{6x^2-9x+8}{3x^2 + 2}$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}{\frac{6x^2-9x+8}{3x^2 + 2}} &= \lim_{x \to \infty}{\frac{6x^2-9x+8}{3x^2 + 2} \cdot \frac{x^{-2}}{x^{-2}}} \\
&= \lim_{x \to \infty}{\frac{6-9x^{-1}+8x^{-2}}{3 + 2x^{-2}}} \\
&= \frac{6-0 + 0}{3 + 0} = 2
\end{aligned}
$$
As $x \to -\infty$, $\dlim_{x \to -\infty}{\frac{6x^2-9x+8}{3x^2 + 2}} = 2$ holds too. The line $y = 2$ is a horizontal asymptote.

30\. $f(x) = \dfrac{x^4+7}{x^5 + x^2 -x}$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}{\frac{x^4+7}{x^5 + x^2 -x}} &= \lim_{x \to \infty}{\frac{x^4+7}{x^5 + x^2 -x} \cdot \frac{x^{-5}}{x^{-5}}} \\
&= \lim_{x \to \infty}{\frac{x^{-1} + 7x^{-5}}{1 + x^{-3} - x^{-4}}} \\
& = \frac{0 + 0}{1 + 0 - 0} = 0
\end{aligned}
$$
As $x \to -\infty$, $\dlim_{x \to -\infty}{\frac{x^4+7}{x^5 + x^2 -x}} = 0$ holds too. The line $y = 0$ is a horizontal asymptote.

33\. $f(x) = \dfrac{40x^5+x^2}{16x^4 -2x}$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}{\frac{40x^5+x^2}{16x^4 -2x}} &= \lim_{x \to \infty}{\frac{40x^5+x^2}{16x^4 -2x} \cdot \frac{x^{-4}}{x^{-4}}} \\
&= \lim_{x \to \infty}{\frac{40x + x^{-2}}{16 - 2x^{-3}}} \\
& = \infty
\end{aligned}
$$
As $x \to -\infty$, $\dlim_{x \to -\infty}{\frac{40x^5+x^2}{16x^4 -2x}} = -\infty$. $f(x)$ has no horizontal asymptotes.

35-40\. **Slant(oblique) asymptotes** *Complete the following steps for the given functions.*
a. Use polynomial long division to find the slant asymptote of $f$.
b. Find the vertical asymptotes of $f$.
c. Graph $f$ and all its asymptotes with a graphing utility. Then sketch a graph of the function by hand, correcting any errors appearing in the computer-generated graph.
35\. $\displaystyle f(x) = \frac{x^2-3}{x + 6}$
>Solution
a.
$$
\begin{aligned}
f(x) &= \frac{x^2-3}{x + 6} = \frac{x^2-36}{x + 6} + \frac{33}{x+6} \\
&= x-6 + \frac{33}{x+6}
\end{aligned}
$$
The slant asymptote is $y =x-6$.
b. Try to determine the limits of $f(x)$ as $x \to -6$ from both right and left sides. Because $\dlim_{x \to -6+}f(x) = \infty$, $\dlim_{x \to -6-}f(x) = -\infty$, $f(x)$ has a vertical asymptote $x = -6$.
c. Graph (35c).

41-44\. **Algebraic functions** Evaluate $\dlim_{x \to \infty}f(x)$ and $\dlim_{x \to -\infty}f(x)$ for the following functions. Then give the horizontal asymptotes of $f$ (if any).
41\. $f(x) = \dfrac{4x^3+1}{2x^3 + \sqrt{16x^6 + 1}}$
>Solution
$$
\begin{aligned}
f(x) &= \frac{4x^3+1}{2x^3 + \sqrt{16x^6 + 1}} = \frac{4x^3+1}{2x^3 + \sqrt{16x^6 + 1}} \cdot \frac{x^{-3}}{x^{-3}} \\
&= \begin{cases}
\dfrac{4 + x^{-3}}{2 + \sqrt{16 + x^{-6}}}  \quad x \ges 0 \\
\dfrac{4 + x^{-3}}{2 - \sqrt{16 + x^{-6}}}  \quad x \lt 0
\end{cases}\\
\lim_{x \to \infty}f(x) &= \lim_{x \to \infty}(\frac{4 + x^{-3}}{2 + \sqrt{16 + x^{-6}}}) \\
&= \frac{4 + 0}{2 + \sqrt{16 + 0}} = \frac{2}{3}\\
\lim_{x \to -\infty}f(x) &= \lim_{x \to -\infty}(\frac{4 + x^{-3}}{2 - \sqrt{16 + x^{-6}}}) \\
&= \frac{4 + 0}{2 - \sqrt{16 + 0}} = -2
\end{aligned}
$$
$f(x)$ has the horizontal asymptotes $y = \dfrac{2}{3}$ and $y = -2$.

45-50\. **Transcendental functions** Determine the end behavior of the following transcendental functions by evaluating appropriate limits. Then provide a simple sketch of the associated graph, showing asymptotes if they exist.
47\. $f(x) = 1 - \ln x$
>Solution
1\. As $x \to \infty$, $f(x)$ is negative and grows arbitrarily large in magnitude. $\dlim_{x \to \infty}f(x) = -\infty$. Thus $f(x)$ has no horizontal asymptote.
2\. As $x \to 0$ from the right side, $\dlim_{x \to 0^+}f(x) = \infty$. $f(x)$ has the vertical asymptote $x = 0$. Graph (47).

49\. $f(x) = \sin x$
>Solution
$f(x) = {\sin x}$ is a periodic function. It has no asymptote. Both $\dlim_{x \to \infty}f(x)$ and $\dlim_{x \to -\infty}f(x)$ do not exist.

52-61\. **Horizontal  and vertical asymptotes**
57\. $f(x) = \dfrac{x^2 - 9}{x(x-3)}$
>Solution
$$
\begin{aligned}
f(x) &= \frac{x^2-9}{x(x-3)} = \frac{(x+3)(x-3)}{x(x-3)} \\
&= \frac{x+3}{x} \quad x \ne 3 \\
\lim_{x \to 0^+}f(x) &= \lim_{x \to 0^+}{\frac{x+3}{x}} = \infty &\text{(1)} \\
\lim_{x \to 0^-}f(x) &= \lim_{x \to 0^-}{\frac{x+3}{x}} = -\infty &\text{(2)} \\
\lim_{x \to 3}f(x) &= \lim_{x \to 3}{\frac{x+3}{x}} = \frac{3+3}{3} = 2 &\text{(3)} \\
\lim_{x \to \infty}f(x) &= \lim_{x \to 3}{\frac{x+3}{x}} = 1 + 0= 1 &\text{(4)} \\
\lim_{x \to -\infty}f(x) &= \lim_{x \to 3}{\frac{x+3}{x}} = 1 + 0 = 1 &\text{(5)}
\end{aligned}
$$
1. According to **(1)** and **(2)**, $f(x)$ has the vertical asymptote $x=0$.
2. According to **(3)**, $x=3$ is not a vertical asymptote of $f(x)$.
3. According to **(4)** and **(5)**, $f(x)$ has the horizontal asymptote $y = 1$.

76-79\. **Looking ahead to sequences** A sequence is an infinite, ordered list of numbers that is often defined by a function. For example, the sequence ${2, 4, 6, 8,  \cdots}$ is specified by the function $f(x) = 2n$, where $n = 1, 2, 3, \cdots$ The limit of such a sequence is $\dlim_{n \to \infty}f(n)$, provided the limit exists. All the limit laws for limits at infinity may be applied to limits of sequences. Find the limit of the following sequences, or state that the limit does not exist.
77\. $\lb{0, \frac{1}{2}, \frac{2}{3}, \frac{3}{4}, \cdots }\rb$, which is defined by $f(n) = \dfrac{n-1}{n}$, for $n = 1, 2, 3, \cdots$
>Solution
$$
\begin{aligned}
\lim_{n \to \infty}f(n) &= \lim_{n \to \infty}{\frac{n-1}{n}} = \lim_{n \to \infty}{\frac{n-1}{n} \cdot \frac{n^{-1}}{n^{-1}}} \\
&= \lim_{n \to \infty}{\frac{1-n^{-1}}{1}} \\
&= \frac{1-0}{1} = 1
\end{aligned}
$$
