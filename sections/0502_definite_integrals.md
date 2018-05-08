### Section 5.2 Definite Integrals
pg351: 3, 9, 11, 17, 21, 26, 29, 31, 37-40, 43, 47, 51, 55, 67, 69, 73

3\. When does the net area of a region equal the area of a region? When does the net area of a region differ from the area of a region?
>Solution
When **all the parts** of the region **lies above** the x-axis, the net area the region equals the area the region; when **parts** of the region lies below the x-axis, the net area differs from the area of the region.

9\. Use geometry to find a formula for $\int^a_0 xdx$, in terms of $a$.
>Solution
$\dint^a_0 x dx = \frac{a^2}{2}$

11–14\. **Approximating net area** The following functions are negative on the given interval.
a. Sketch the function on the given interval.
b. Approximate the net area bounded by the graph of $f$ and the x-axis on the interval using a left, right, and midpoint Riemann sum with $n = 4$.
11\. $f(x)=-2x-1; [0, 4]$
>Solution
a. Graph (11).
b. $\Delta x = \frac{4-0}{4} = 1$
1\) For the left Riemann sum, let $x^*_k = 0 + (k-1)\cdot 1 =k-1$. The value of the sum is
$$
\begin{aligned}
\sum^4_{k=1} f(x^*_k)\Delta x &= \sum^4_{k=1} [-2(k-1)-1]\cdot 1\\
&= \sum^4_{k=1} (-2k+1) = -2\cdot \frac{4\cdot (4+1)}{2} + 4\cdot 1 = -16
\end{aligned}
$$
2\) For the right Riemann sum, let $x^*_k = 0 + k\cdot 1 =k$. The value of the sum is
$$
\begin{aligned}
\sum^4_{k=1} f(x^*_k)\Delta x &= \sum^4_{k=1} (-2k-1)\cdot 1\\
&= -2\cdot \frac{4\cdot (4+1)}{2} - 4\cdot 1 = -24
\end{aligned}
$$
3\) For the mipoint Riemann sum, let $x^*_k = 0 + (k-\frac{1}{2})\cdot 1 =k-\frac{1}{2}$. The value of the sum is
$$
\begin{aligned}
\sum^4_{k=1} f(x^*_k)\Delta x &= \sum^4_{k=1} [-2(k-\frac{1}{2})-1]\cdot 1\\
&= \sum^4_{k=1} (-2k)= -2\cdot \frac{4\cdot (4+1)}{2} = -20
\end{aligned}
$$

15–20\. **Approximating net area** The following functions are positive and negative on the given interval.
a. Sketch the function on the given interval.
b. Approximate the net area bounded by the graph of $f$ and the x-axis on the interval using a left, right, and midpoint Riemann sum with $n = 4$.
c. Use the sketch in part (a) to show which intervals of $[a, b]$ make positive and negative contributions to the net area.
17\. $f(x)=\sin 2x; [0, \frac{3\pi}{4}]$
>Solution
ac. Graph (17).
b. $\Delta x = \frac{\frac{3\pi}{4} - 0}{4} = \frac{3\pi}{16}$
1\) For the left Riemann sum, let $x^*_k = 0 + (k-1)\cdot \frac{3\pi}{16} =\frac{3\pi}{16}(k-1)$. The value of the sum is
$$
\begin{aligned}
\sum^4_{k=1} f(x^*_k)\Delta x &= \sum^4_{k=1} \sin [2\cdot \frac{3\pi}{16} \cdot (k-1)]\cdot \frac{3\pi}{16}\\
&=\frac{3\pi}{16} \cdot \sum^4_{k=1} {\sin [\frac{3\pi}{8} \cdot (k-1))]} \approx 0.74
\end{aligned}
$$
2\) For the right Riemann sum, let $x^*_k = 0 + k\cdot \frac{3\pi}{16} $. The value of the sum is
$$
\begin{aligned}
\sum^4_{k=1} f(x^*_k)\Delta x &= \sum^4_{k=1} \sin [2\cdot \frac{3\pi}{16} \cdot k]\cdot \frac{3\pi}{16}\\
&=\frac{3\pi}{16} \cdot \sum^4_{k=1} {\sin \frac{3k\pi}{8}} \approx 0.15
\end{aligned}
$$
3\) For the mipoint Riemann sum, let $x^*_k = 0 + (k-\frac{1}{2})\cdot \frac{3\pi}{16}$. The value of the sum is
$$
\begin{aligned}
\sum^4_{k=1} f(x^*_k)\Delta x &= \sum^4_{k=1} \sin [2\cdot \frac{3\pi}{16} \cdot (k-\frac{1}{2})]\cdot \frac{3\pi}{16}\\
&=\frac{3\pi}{16} \cdot \sum^4_{k=1} {\sin [\frac{3\pi}{8} \cdot (k-\frac{1}{2}))]} \approx 0.53
\end{aligned}
$$

21–24\. **Identifying definite integrals as limits of sums** Consider the following limits of Riemann sums of a function $f$ on $[a, b]$. Identify $f$ and express the limit as a definite integral.
21\. $\dlim_{\Delta \to 0}\sum\limits^n_{k=1}({x^*_k}^2 + 1)\Delta x_k; [0, 2]$
>Solution
$$
\begin{aligned}
f(x) &= x^2 + 1\\
\lim_{\Delta \to 0}\sum\limits^n_{k=1}f(x^*_k)\Delta x_k &= \int^2_0 (x^2+1)
\end{aligned}
$$

25–32\. **Net area and definite integrals** Use geometry (not Riemann sums) to evaluate the following definite integrals. Sketch a graph of the integrand, show the region in question, and interpret your result.
26\. $\int^2_{-4}(2x+4)dx$
>Solution
Graph (26). The region consists of two triangles. One is below the axis with base 2 and height 1, the other one is above the axis with base 4 and height 8, so the net area is
$$
\begin{aligned}
\int^2_{-4}(2x+4)dx &= \frac{1}{2}\cdot 8 \cdot 4 - \frac{1}{2} \cdot 2 \cdot 4 = 12
\end{aligned}
$$

29\. $\int^4_0 \sqrt{16-x^2}dx$
>Solution
Graph (29). The region consists of a quarter circle of radius 4 which is above the x-axis, so the net area is
$$
\begin{aligned}
\int^4_0 \sqrt{16-x^2}dx = \frac{1}{4}\pi\cdot 4^2 = 4\pi
\end{aligned}
$$

31\. $\int^4_0 f(x)dx$, where $f(x)=\begin{cases}5 &\text{if } x\les 2\\ 3x-1 &\text{if } x\gt 2\end{cases} $
>Solution
Graph (31). The region consists of a rectangle and a trapezoid both of which are above the x-axis. The rectangle has width 2 and height 5. The trapezoid has a short base of 5, a longer base of 11 and a height of 2, so the net area is
$$
\begin{aligned}
\int^4_0 f(x)dx &= 5\cdot 2 + \frac{1}{2}\cdot (5+11)\cdot 2 = 26
\end{aligned}
$$

37-40\. **Net area from graphs** The accompanying figure shows four regions bounded by the graph of $y = x \sin x: R_1, R_2, R_3$, and $R_4$, whose areas are $1, \pi - 1, \pi + 1$, and $2\pi - 1$, respectively. (We verify these results later in the text.) Use this information to evaluate the following integrals.
>Solution
$$
\begin{aligned}
\int^{\pi}_0 x\sin x dx &= R_1 + R_2 = \pi \\
\int^{\frac{3\pi}{2}}_0 x\sin x dx &= R_1 + R_2-R_3= -1 \\
\int^{2\pi}_0 x\sin x dx &= R_1 + R_2-R_3-R_4= -2\pi \\
\int^{2\pi}_\frac{\pi}{2} x\sin x dx &= R_2-R_3-R_4= -2\pi-1
\end{aligned}
$$

43\. **Properties of integrals** Suppose that $\int^3_0 f(x)dx = 2, \int^6_3 f(x)dx = -5$, and $\int^6_3 g(x)dx = 1$. Evaluate the following integrals.
>Solution
$$
\begin{aligned}
\int^3_0 5f(x)d &= 5\cdot 2 = 10\\
\int^6_3 (-3g(x))dx &= -3 \cdot 1 = -3\\
\int^6_3 (3f(x) - g(x))dx &= 3\cdot (-5) -1 = -16\\
\int^3_6 (f(x) + 2g(x))dx &= -(-5 + 2\cdot 1) = 3\\
\end{aligned}
$$

47–52\. **Limits of sums** Use the definition of the definite integral to evaluate the following definite integrals. Use right Riemann sums and Theorem 5.1.
47\. $\int^2_0 (2x+1)dx$
>Solution
$$
\begin{aligned}
\int^2_0 (2x+1)dx &= \lim_{n \to \infty}\sum^n_{k=1}(2x^*_k + 1)\Delta x\\
&=\lim_{n \to \infty}[\frac{2}{n}\cdot \sum^n_{k=1}(2\cdot \frac{2k}{n} + 1)]\\
&=\lim_{n \to \infty}[\frac{8}{n^2}\cdot \sum^n_{k=1}(k) + \frac{2}{n}\cdot \sum^n_{k=1}(1)]\\
&=\lim_{n \to \infty}(\frac{8}{n^2}\cdot \frac{n(n+1)}{2} + \frac{2}{n}\cdot n)\\
&= \lim_{n \to \infty}(6+\frac{4}{n}) = 6
\end{aligned}
$$

51\. $\int^4_1 (x^2-1)dx$
>Solution
$$
\begin{aligned}
\int^4_1 (x^2-1)dx &= \lim_{n \to \infty}\sum^n_{k=1}({x^*_k}^2 - 1)\Delta x\\
&= \lim_{n \to \infty}(\frac{3}{n}\cdot \sum^n_{k=1}[(1+\frac{3k}{n})^2 -1])\\
&= \lim_{n \to \infty}[\frac{3}{n}\cdot \sum^n_{k=1}(\frac{9k^2}{n^2} + \frac{6k}{n})]\\
&= \lim_{n \to \infty}[\frac{27}{n^3}\cdot \sum^n_{k=1}(k^2) + \frac{18}{n^2}\cdot \sum^n_{k=1}(k)]\\
&= \lim_{n \to \infty}[\frac{27}{n^3}\cdot \frac{n(n+1)(2n+1)}{6} + \frac{18}{n^2}\cdot \frac{n(n+1)}{2}]\\
&= \lim_{n \to \infty}[\frac{9(n+1)(2n+1)}{2n^2} + \frac{9(n+1)}{n}] = 9+9=18
\end{aligned}
$$

54–57\. **Approximating definite integrals** Complete the following steps for the given integral and the given value of $n$.
a. Sketch the graph of the integrand on the interval of integration.
b. Calculate $\Delta x$ and the grid points $x_0, x_1 \cdots x_n$, assuming a regular partition.
c. Calculate the left and right Riemann sums for the given value of $n$.
d. Determine which Riemann sum (left or right) underestimates the value of the definite integral and which overestimates the value of the definite integral.
55\. $\int^6_3 (1-2x)dx; n=6$
>Solution
a. Graph (55).
b. $\Delta x=\frac{6-3}{6} = 0.5$ and $x_0=3, x_1=3.5, x_2=4, x_3=4.5, x_4=5, x_5=5.5, x_6=6$.
c. For the left Riemman sum, let $x^*_k= 3+0.5(k-1)$. The value of sum is
$$
\begin{aligned}
\int^6_3 (1-2x)dx &= \sum^6_{k=1}(1-2[3+0.5(k-1)]) \cdot 0.5\\
&= 0.5\cdot \sum^6_{k=1} (-4-k)\\
&= -0.5 \cdot [(\sum^6_{k=1}(4) + \sum^6_{k=1}(k)]\\
&= -0.5\cdot (6\cdot 4 + \frac{6\cdot (6+1)}{2}) = -22.5
\end{aligned}
$$
For the right Riemman sum, let $x^*_k= 3+0.5k$. The value of sum is
$$
\begin{aligned}
\int^6_3 (1-2x)dx &= \sum^6_{k=1}[1-2(3+0.5k)] \cdot 0.5\\
&= 0.5\cdot \sum^6_{k=1} (-5-k)\\
&= -0.5 \cdot [(\sum^6_{k=1}(5) + \sum^6_{k=1}(k)]\\
&= -0.5\cdot (6\cdot 5 + \frac{6\cdot (6+1)}{2}) = -25.5
\end{aligned}
$$
d. The left Riemman sum overestimate the true value, and the right Riemman sum underestimate the true value.

<!-- pagebreak -->
67\. **More properties of integrals** Consider two functions $f$ and $g$ on $[1, 6]$ such that $\int^6_1 f(x)dx=10$, $\int^6_1 g(x)dx=5$, $\int^6_4 f(x)dx=5$, and $\int^4_1 g(x)dx=2$. Evaluate the following integrals.
>Solution
$$
\begin{aligned}
\int^4_1 3f(x)dx &= 3\cdot (10-5) = 15\\
\int^6_1 (f(x)-g(x))dx &= 10-5=5\\
\int^4_1 (f(x)-g(x))dx &= (10-5)-2=3\\
\int^4_6 (g(x)-f(x))dx &= \int^6_4 f(x)dx - \int^6_4 g(x)dx = (10-5)-(5-2) = 3\\
\int^6_4 8g(x)dx &= 8\cdot (5-2) = 24\\
\int^1_4 2f(x)dx &= 2 \cdot (5-10) = -10
\end{aligned}
$$

68–71\. **Area versus net area** Graph the following functions. Then use geometry (not Riemann sums) to find the area and the net area of the region described.
69\. The region between the graph of $y=-3x$ and the x-axis, for $-2 \les x \les 2$.
>Solution
Graph (69). The region abot the axis is a triangle with base 2 and height $f(-2) = 6$, and the region below the axis is a triangle with base 2 and height $-f(2)=6$, so the net area is $0$, and the area is $12$.

72–75\. **Area by geometry** Use geometry to evaluate the following integrals.
73\. $\int^6_1 |2x-4|dx$
>Solution
Graph (73). The region consist of two triangles above the x-axis, one with base 1 and height 2, and the other one with base 4 and height 8, so the nett area is $\frac{1}{2}\cdot 1 \cdot 2 + \frac{1}{2} \cdot 4 \cdot 8 = 17$.
