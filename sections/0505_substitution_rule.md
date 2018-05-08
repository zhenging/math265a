### Section 5.5 Substitution Rule
p383: 1, 3, 5, 6, 17, 33, 34, 35, 41, 43, 45, 53, 54, 57, 67, 71, 79, 81, 90, 93

1\. On which derivative rule is the Substitution Rule based?
>Solution
The Substitution Rule is based on the Chain Rule of differentiation.

3\. The composite function $f(g(x))$ consists of an inner function $g$
and an outer function $f$. When doing a change of variables, which
function is often a likely choice for a new variable $u$?
>Solution
The inner function $g$ is often a likely choice for $u$.

5\. When using a change of variables $u = g(x)$ to evaluate the definite integral $\dint_a^b f(g(x))g'(x)dx$, how are the limits of integration transformed?
>Solution
$\dint_a^b f(g(x))g'(x)dx = \dint_{g(a)}^{g(b)} f(u)du$

6\. If the change of variables $u = x^2 - 4$ is used to evaluate the definite integral $\dint_2^4 f(x)dx$, what are the new limits of integration?
>Solution
The new limits will be $u(2) = 0$ and $u(4) = 12$.

17–32\. **Indefinite integrals** Use a change of variables to find the following indefinite integrals. Check your work by differentiation.
17\. $\dint 2x(x^2-1)^{99}dx$
>Solution
$$
\begin{aligned}
u = x^2-1, du &= 2xdx\\
\int 2x(x^2-1)^{99}dx &= \int u^{99}du\\
&= \frac{1}{100}u^{100} + C = \frac{1}{100}(x^2-1)^{100} + C
\end{aligned}
$$

33–38\. **Variations on the substitution method** Find the following integrals.
33\. $\dint \frac{x}{\sqrt {x-4}}dx$
>Solution
$$
\begin{aligned}
u = x-4, du &= dx, x=u+4\\
\int \frac{x}{\sqrt {x-4}}dx &= \int \frac{u+4}{\sqrt u}du\\
&= \int u^{1/2} + 4\int u^{-1/2}\\
&= \frac{2}{3}u^{3/2} + 8u^{1/2} + C = \frac{2}{3}(x-4)^{3/2} + 8\sqrt{x-4} + C
\end{aligned}
$$

34\. $\dint \frac{y^2}{(y+1)^4}dy$
>Solution
$$
\begin{aligned}
u = y+1, du &= dx, y=u-1\\
\int \frac{y^2}{(y+1)^4}dy &= \int \frac{(u-1)^2}{u^4}du\\
&= \int u^{-2}du - 2\int u^{-3}du + \int u^{-4}du\\
&= -\frac{1}{u} + \frac{1}{u^2}-\frac{1}{3u^3} + C = -\frac{1}{y+1} + \frac{1}{(y+1)^2}-\frac{1}{3(y+1)^3} + C
\end{aligned}
$$

35\. $\dint \frac{x}{\sqrt[3] {x+4}}dx$
>Solution
$$
\begin{aligned}
u=x+4, du &=dx, x=u-4\\
\int \frac{x}{\sqrt[3] {x+4}}dx &= \int \frac{u-4}{\sqrt[3] u}du\\
&= \int u^{2/3}du - 4\int u^{-1/3}du\\
&= \frac{3}{5}u^{5/3}-6u^{2/3} + C = \frac{3}{5}(x+4)^{5/3}-6(x+4)^{2/3} + C
\end{aligned}
$$

39–52\. **Definite integrals** Use a change of variables to evaluate the following definite integrals.
41\. $\dint_0^{\pi/2} \sin^2 \theta \cos \theta d\theta$
>Solution
$$
\begin{aligned}
u = \sin \theta, du &= \cos \theta d\theta\\
\int_0^{\pi/2} \sin^2 \theta \cos \theta d\theta &= \int_{\sin 0}^{\sin (\pi/2)} u^2 du\\
&= \frac{1}{3} u^3 \mid_0^1 = \frac{1}{3}
\end{aligned}
$$

43\. $\dint_{-1}^2 x^2e^{x^3+1}dx$
>Solution
$$
\begin{aligned}
u=x^3+1, du &= 2x^2dx\\
\int_{-1}^2 x^2e^{x^3+1}dx &= \frac{1}{3}\int_{u(-1)}^{u(2)}e^u du\\
&= \frac{1}{3}e^u \mid_0^9 = \frac{e^9-1}{3}
\end{aligned}
$$

45\. $\dint_{\pi/4}^{\pi/2} \frac{\cos x}{\sin^2 x} dx$
>Solution
$$
\begin{aligned}
u = \sin x, du &= \cos xdx\\
\int_{\pi/4}^{\pi/2} \frac{\cos x}{\sin^2 x} dx &= \int_{\sin (\pi/4)}^{\sin (\pi/2)} \frac{1}{u^2} du\\
&= -\frac{1}{u}\mid_{\frac{\sqrt 2}{2}}^1 = \sqrt 2 -1
\end{aligned}
$$

53–60\. **Integrals with $\sin^2 x$ and $cos^2 x$** Evaluate the following integrals.
53\. $\dint_{-\pi}^{\pi} \cos^2 x dx$
>Solution
$$
\begin{aligned}
\int_{-\pi}^{\pi} \cos^2 x dx &= \dint_{-\pi}^{\pi} \frac{1+\cos 2x}{2} dx\\
&= \frac{1}{2}(\int_{-\pi}^{\pi} dx + \frac{1}{2}\int_{-\pi}^{\pi} 2\cos 2x dx)\\
&= \frac{1}{2}(x + \frac{1}{2}\sin 2x)\mid_{-\pi}^{\pi} = \pi
\end{aligned}
$$

54\. $\dint_{-\pi}^{\pi} \sin^2 x dx$
>Solution
$$
\begin{aligned}
\int_{-\pi}^{\pi} \sin^2 x dx &= \dint_{-\pi}^{\pi} \frac{1-\cos 2x}{2} dx\\
&= \frac{1}{2}(\int_{-\pi}^{\pi} dx - \frac{1}{2}\int_{-\pi}^{\pi} 2\cos 2x dx)\\
&= \frac{1}{2}(x - \frac{1}{2}\sin 2x)\mid_{-\pi}^{\pi} = \pi
\end{aligned}
$$

57\. $\dint_{-\pi/4}^{\pi/4} \sin^2 2\theta d\theta$
>Solution
$$
\begin{aligned}
\int_{-\pi/4}^{\pi/4} \sin^2 2\theta d\theta &= \dint_{-\pi/4}^{\pi/4} \frac{1-\cos 4\theta}{2} d\theta\\
&= \frac{1}{2}(\int_{-\pi/4}^{\pi/4} d\theta - \frac{1}{4}\int_{-\pi/4}^{\pi/4} 4\cos 4\theta d\theta)\\
&= \frac{1}{2}(\theta - \frac{1}{4}\sin 4\theta)\mid_{-\pi/4}^{\pi/4} = \frac{\pi}{4}
\end{aligned}
$$

62–78\. **Additional integrals** Use a change of variables to evaluate the following integrals.
67\. $\dint \sin x \sec^8 x dx$
>Solution
$$
\begin{aligned}
u= \cos x, du &= -\sin x\\
\int \sin x \sec^8 x dx &= -\int \frac{1}{u^8}du\\
&= \frac{1}{7u^7} + C = \frac{1}{7}\sec^7 x + C
\end{aligned}
$$

71\. $\dint_2^3 \frac{x}{\sqrt[3] {x^2-1}}dx$
>Solution
$$
\begin{aligned}
u = x^2-1, du &= 2xdx\\
\int_2^3 \frac{x}{\sqrt[3] {x^2-1}}dx &= \frac{1}{2}\int_{u(2)}^{u(3)} u^{-\frac{1}{3}} du\\
&= \frac{3}{4}u^{\frac{2}{3}} \mid_3^8 = \frac{3}{4}(4-\sqrt[3] 9)
\end{aligned}
$$

<!-- pagebreak -->
79–82\. **Areas of regions** Find the area of the following regions.
79\. The region bounded by the graph if $f(x) = x\sin (x^2)$ and the x-axis between $x=0$ and $x=\sqrt \pi$.
>Solution
The area can be presented by $\dint_0^{\sqrt \pi} x\sin(x^2)dx$.
$$
\begin{aligned}
u=x^2, du &= 2xdx\\
\int_0^{\sqrt \pi} x\sin(x^2)dx &= \frac{1}{2} \int_{u(0)}^{u(\sqrt \pi)} \sin u du \\
&= -\frac{1}{2}\cos u \mid_0^{\pi} = 1
\end{aligned}
$$

81\. The region bounded by the graph if $f(x)=(x-4)^4$ and the x-axis between $x=2$ and $x=6$.
>Solution
The area can be presented by $\dint_2^6 (x-4)^4 dx$.
$$
\begin{aligned}
u=x-4, du &=dx\\
\int_2^6 (x-4)^4 dx &= \int_{u(2)}^{u(6)} u^4 du\\
& = \frac{1}{5}u^5 \mid_{-2}^2 = \frac{64}{5}
\end{aligned}
$$

90\. **Looking ahead**: **Integrals of $\tan x$ and $\cot x$**.
a. Use a change of variables to show that $\dint \tan x dx = -\ln |\cos x| + C = \ln |\sec x| + C$.
>Solution
$$
\begin{aligned}
u=\cos x, du &= -\sin x\\
\int \tan x dx &= \int \frac{\sin x}{\cos x} dx\\
&= -\int \frac{1}{u}du\\
&= -\ln |u| + C\\
&= -\ln |\cos x| + C\\
&= \ln |(\cos x)^{-1}| + C\\
&= \ln |\sec x| + C\\
\end{aligned}
$$

<!-- pagebreak -->
b. Show that $\dint \cot xdx =  \ln |\sin x| + C$.
>Solution
$$
\begin{aligned}
u= \sin x, du &=\cos x\\
\int \cot xdx &=  \int \frac{\cos x}{\sin x}dx\\
&= \int \frac{1}{u} du\\
&= \ln |u| + C = \ln |\sin x| + C
\end{aligned}
$$

93\. **Equal areas** The area of the shaded region under the curve $y=\dfrac{(\sqrt x - 1)^2}{2\sqrt x}$ on the interval $[4, 9]$ in (a) equals the area of the shaded region under the curve $y=x^2$ on the interval $[1, 2]$ in (b). Without computing areas, explain why. Graph (93).
>Solution
The shaded area in (a) is $\dint_4^9 \frac{(\sqrt x - 1)^2}{2\sqrt x}$.
$$
\begin{aligned}
u = \sqrt x - 1, du &= \frac{1}{2\sqrt x}dx\\
\int_4^9 \frac{(\sqrt x - 1)^2}{2\sqrt x} &= \int_{u(4)}^{u(9)} u^2 du\\
&= \int_1^2 u^2 du
\end{aligned}
$$
The shaded area in (b) is $\dint_1^2 x^2 dx$, which is the same with $\dint_1^2 u^2 du$.
