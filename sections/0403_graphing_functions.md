### Section 4.3 Graphing Functions

#### Graphing  Guidelines
1\. Identify domain or interval of interest.
2\. Exploit symmetry
3\. Find the first and second derivatives.
4\. Find critical points and possible inflection points.
5\. Find intervals on which the function is increasing/decreasing and concaveup/down.
6\. Identify extreme values and inflection points.
7\. Locate vertical/horizontal asymptotes and determine end behavior.
8\. Find the intercepts.
9\. Choose an appropriate graphing window and make a graph.

#### Homework
p262: 7, 11, 17, 24, 27, 33, 37, 56, 57, 71

7\. **Shape of the curve** Sketch a curve with the following properties
$f'<0$ and $f''<0$, for $x<3$; $f'<0$ and $f''>0$, for $x>3$;
>Solution
Graph (7).

9-14\. **Graphing polynomials** Sketch a graph of the following polynomials. Identify local extrema, inflection points, and x- and y-intercepts when they exist.
11\. $f(x)=x^4-6x^2$
>Solution
1\. **Domain** The domain is $(-\infty, \infty)$.
2\. **Symmetry** $f$ consists of only **even** powers of variable, it is an **even** function.
3\. **Derivatives**
$$
\begin{aligned}
f'(x) &= 4x^3-12x = 4x(x^2-3)\\
f''(x) &=12x^2-12 =12(x^2-1)
\end{aligned}
$$
4\. **Critical points and possible inflection points** The critical points are $x=0, \pm \sqrt {3}$, and the possible inflection points occur at $x=\pm 1$.
$$
\begin{aligned}
f'(x) &= 0 \To x=0, \pm \sqrt {3} \\
f''(x) &=0 \To x=\pm 1\\
\end{aligned}
$$
5\. **Increasing/decreasing and concavity** $f$ is increasing on $(-\sqrt {3}, 0), (\sqrt {3}, \infty)$, and is decreasing on $(-\infty, -\sqrt {3}), (0, \sqrt {3})$. $f$ is concave up on $(-\infty, -1), (1, \infty)$, and is concave down on $(-1, 1)$.
$$
\begin{aligned}
x \in (-\infty, -\sqrt {3}) \To f'(x)<0 &
\quad x \in (-\sqrt {3}, 0) \To f'(x)>0 \\
x \in (0, \sqrt {3}) \To f'(x)<0 & \quad x \in (\sqrt {3}, \infty) \To f'(x)>0\\
x \in (-\infty, -1) \To f''(x)>0 & \quad x \in (-1, 1) \To f''(x)<0\\
x \in (1, \infty) \To f''(x)>0\\
\end{aligned}
$$
6\. **Extreme values and inflection points** Because $f''$ changes sign at $x=\pm 1$, $f$ has inflection points $(-1, -5), (1, 5)$.
$$
\begin{aligned}
f''(-\sqrt 3) &= 12(3-1) = 24 > 0 &\To \text{Local minimum at } x=-\sqrt 3, f(-\sqrt 3) = -9\\
f''(0) &= 12(0-1) = -12 <0 &\To \text{Local maximum at } x=0, f(0) = 0\\
f''(\sqrt 3) &= 12(3-1) = 24 > 0 &\To \text{Local minimum at } x=-\sqrt 3, f(-\sqrt 3) = -9\\
f(-1)&=f(1)=-5\\
\end{aligned}
$$
7\. **Asymptotes** $f$ have neither vertical nor horizontal asymptotes. (Polynomial)
$$
\lim_{x \to \infty}{f(x)} = \infty \quad \lim_{x \to -\infty}{f(x)} = \infty
$$
8\. **Intercepts**
$$
\begin{aligned}
f(x) &=0 \To x=0, \pm \sqrt {6} &\quad \text {x-intercepts}\\
x&=0 \To f(x) = 0 &\quad \text{y-intercept}
\end{aligned}
$$
9\. Graph (11).

15-20\. Graphing rational functions. Use the guidelines of this section to make a complete graph of $f$.
17\. $f(x) = \dfrac{3x}{x^2-1}$
>Solution
1\. **Domain** The domain is $(-\infty, -1), (-1, 1), (1, \infty)$.
2\. **Symmetry** $f(-x) = \frac{-3x}{(-x)^2-1} = -f(x)$, $f$ is an **odd** function.
3\. **Derivatives**
$$
\begin{aligned}
f'(x) &= \frac{3(x^2-1) - 3x\cdot 2x}{(x^2-1)^2} = -\frac{-3(x^2+1)}{(x^2-1)^2}\\
f''(x) &=-3 \cdot \frac{2x(x^2-1)^2 - (x^2+1)[2(x^2-1)\cdot 2x]}{(x^2-1)^4}\\
&= \frac{6x(x^2+3)}{(x^2-1)^3}
\end{aligned}
$$
4\. **Critical points and possible inflection points** Because there's no solution for $x$ in $f'(x)=0$, $f$ has no critical point. The possible inflection point occurs at $x=0$.
$$
f''(x) =0 \To x=0
$$
5\. **Increasing/decreasing and concavity** Because $f'<0$ for all $x$, $f$ is decreasing on its whole domain.
$f$ is concave up on $(-\infty, -1), (0, 1)$, and is concave down on $(-1, 0), (1, \infty)$.
$$
\begin{aligned}
x \in (-\infty, -1) \To f''(x)<0 & \quad x \in (-1, 0) \To f''(x)>0\\
x \in (0, 1) \To f''(x)<0 & \quad x \in (1, \infty) \To f''(x)>0
\end{aligned}
$$
6\. **Extreme values and inflection points** $f$ has no local extreme value. Because $f''$ changes sign at $x=0$, $f$ has an inflection point $(0, 0)$.
7\. **Asymptotes** $f$ has the vertical asymptotes $x=\pm1$ and the horizontal asymptote $y=0$.
$$
\begin{aligned}
\lim_{x \to -1^-}{f(x)} &= \lim_{x \to -1^-}\frac{\overbrace{3x}^{\text{negative constant}}}{\underbrace{x^2-1}_{\text{positive and approaches 0}}} = -\infty &
\lim_{x \to -1^+}{f(x)} &= \lim_{x \to -1^+}\frac{\overbrace{3x}^{\text{negative constant}}}{\underbrace{x^2-1}_{\text{negative and approaches 0}}} = \infty\\
\lim_{x \to 1^-}{f(x)} &= \lim_{x \to 1^-}\frac{\overbrace{3x}^{\text{positive constant}}}{\underbrace{x^2-1}_{\text{negative and approaches 0}}} = -\infty &
\lim_{x \to 1^+}{f(x)} &= \lim_{x \to 1^+}\frac{\overbrace{3x}^{\text{positive constant}}}{\underbrace{x^2-1}_{\text{positive and approaches 0}}} = \infty\\
\lim_{x \to \infty}{f(x)} &= \lim_{x \to \infty}\frac{3x}{x^2-1} = \lim_{x \to \infty}\frac{\frac{3}{x}}{1-\frac{1}{x^2}} = 0\\
\lim_{x \to -\infty}{f(x)} &= 0
\end{aligned}
$$
8\. **Intercepts**
$$
\begin{aligned}
f(x) &=0 \To x=0 &\quad \text {x-intercept}\\
x&=0 \To f(x) = 0 &\quad \text{y-intercept}
\end{aligned}
$$
9\. Graph (17).

21-36\. **More graphing** Make a complete graph of the following functions. If an intervals is not specified, graph the function on its domain. Use a graphing utility to check your work.
24\. $f(x) = x-3x^{2/3}$
>Solution
1\. **Domain** The domain is $(-\infty, \infty)$.
2\. **Symmetry** $f(-x) = -x -3(-x)^{2/3} \ne f(x) \ne -f(x)$, $f$ is neither even nor odd function.
3\. **Derivatives**
$$
\begin{aligned}
f'(x) &= 1-2x^{-\frac{1}{3}} = 1-\frac{2}{\sqrt[3]{x}}\\
f''(x) &= \frac{2}{3\sqrt[3]{x^4}}
\end{aligned}
$$
4\. **Critical points and possible inflection points** The critical point is $x=0, 8$. $f$ has no inflection points, as $f''$ is always positive.
$$
\begin{aligned}
f'(x)&=0 \To \frac{2}{\sqrt[3]{x}} = 1 \To x=8\\
f'(x)& \text{ does not exist when } x = 0
\end{aligned}
$$
5\. **Increasing/decreasing and concavity** $f$ is increasing on $(-\infty, 0), (8, \infty)$, and is decreasing on $(0, 8)$. $f$ is always concave up.
$$
\begin{aligned}
x\in & (-\infty, 0) \To f'(x) >0 \quad & x\in & (0, 8) \To f'(x) <0 \\
x\in & (8, \infty) \To f'(x) >0 \\
x\in & (-\infty, 0) \To f''(x) >0 \quad & x\in & (0, \infty) \To f''(x) >0
\end{aligned}
$$
6\. **Extreme values and inflection points** As $f'$ changes from positive to negative as $x$ passes through $x=0$, $f$ has a **local maximum** at $x=0, f(0) = 0$. As $f'$ changes from negative to positive as $x$ passes through $x=8$, $f$ has a **local minimum** at $x=8, f(8) = -4$. $f''(0)$ does not exist, so $f$ has no inflection point.
7\. **Asymptotes** $f$ has no horizontal or vertical asymptotes.
$$
\begin{aligned}
\lim_{x \to \infty}f(x) = \infty \quad & \lim_{x \to -\infty}f(x) = -\infty
\end{aligned}
$$
8\. **Intercepts**
$$
\begin{aligned}
f(x) = 0 \To x = 27 &\text{x-intercept at } (27, 0)\\
x = 0 \To y = 0 &\text{y-intercept at} (0, 0)
\end{aligned}
$$
9\. Graph (24).

<!-- pagebreak -->
27\. $f(x) = \sin x - x$ on $[0, 2\pi]$
>Solution
1\. **Domain** The domain is  $[0, 2\pi]$.
2\. **Symmetry** $f(-x) = \sin (-x) - (-x) = -\sin x + x = -f(x)$, $f$ is an **odd** function.
3\. **Derivatives**
$$
\begin{aligned}
f'(x) &= \cos x -1\\
f''(x) &= -\sin x
\end{aligned}
$$
4\. **Critical points and possible inflection points** $f$ has no critical points on its domain. The possible inflection point occurs at $x=\pi$.
$$
\begin{aligned}
f'(x) &= 0 \To \cos x = 1 \To x=0, 2\pi\\
f''(x) &= 0 \To \sin x = 0 \To x=0, \pi, 2\pi\\
\end{aligned}
$$
5\. **Increasing/decreasing and concavity** $f$ is always decreasing on its domain. $f$ is concave up on $(\pi, 2\pi)$, and is concave down on $(0, \pi)$.
$$
\begin{aligned}
x \in & (0, 2\pi) \To f'(x) <0\\
x \in & (0, \pi) \To f''(x) < 0 \quad & x \in & (\pi, 2\pi) \To f''(x) > 0
\end{aligned}
$$
6\. **Extreme values and inflection points** The absolute maximum occurs at point $(0, 0)$, and the absolute minimum occurs at point $(2\pi, -2\pi)$. Because $f''$ changes sign  at $x=\pi$, the point $(\pi, -\pi)$ is an inflection point.
$$
f(0) = 0 \quad  f(2\pi) = -2\pi \quad  f(\pi) =-\pi
$$
7\. **Asymptotes** $f$ has no vertical or horizontal asymptote.
8\. **Intercepts**
$$
\begin{aligned}
f(x) &=0 \To x=0 \To &\text{x-intercept at } (0, 0)\\
x&=0 \To f(x) = 0 \To &\text{y-intercept at } (0, 0)
\end{aligned}
$$
9\. Graph (27).

33\. $f(x) = x\ln x$
>Solution
1\. **Domain** The domain is $(0, \infty)$.
2\. **Symmetry** $f$ is neither even nor odd function.
3\. **Derivatives**
$$
\begin{aligned}
f'(x) &= x\cdot \frac{1}{x} + 1\cdot \ln x = \ln x + 1\\
f''(x) &= \frac{1}{x}
\end{aligned}
$$
4\. **Critical points and possible inflection points** The critical point occurs at $x=\frac{1}{e}$.
$$
\begin{aligned}
f'(x) &= 0 \To \ln x = -1 \To x= \frac{1}{e}
\end{aligned}
$$
5\. **Increasing/decreasing and concavity** $f$ is increasing on $(\frac{1}{e}, \infty)$, and is decreasing on $(0, \frac{1}{e})$. $f$ is always concave up.
$$
\begin{aligned}
x\in & (0, \frac{1}{e}) \To f'(x) <0 \quad & x\in (\frac{1}{e}, \infty) \To f'(x) >0\\
x\in & (0, \infty) \To f''(x) >0
\end{aligned}
$$
6\. **Extreme values and inflection points** By the Second Derivative Test, $f$ has a local minimum at $x=\frac{1}{e}, f(\frac{1}{e}) = -\frac{1}{e}$. $f$ has no inflection point.
$$
\begin{aligned}
f(\frac{1}{e}) &= -\frac{1}{e}\\
f''(\frac{1}{e}) &= e > 0 \To \text{Local minimum}
\end{aligned}
$$
7\. **Asymptotes** $f$ has no vertical or horizontal asymptote.
$$
\lim_{x\to \infty} f(x) = \infty
$$
8\. **Intercepts**
$$
\begin{aligned}
f(x) &=0 \To \ln x = 0 \To x= 1 &\text{x-intercept at} (1, 0)\\
x&>0 \To &\text{No y-intercept}
\end{aligned}
$$
9\. Graph (33).

37\. $f(x) = \frac{1}{3}x^3-2x^2-5x+2$
>Solution
1\. **Domain** The domain is $(-\infty, \infty)$.
2\. **Symmetry** $f$ is a polynomial function and contains both even and odd powers of variables, it is neither even nor odd function.
3\. **Derivatives**
$$
\begin{aligned}
f'(x) &= x^2-4x-5 = (x-5)(x+1)\\
f''(x) &= 2x-4
\end{aligned}
$$
4\. **Critical points and possible inflection points** The critical points occur at $x=-1, 5$. The inflection point occurs at $x=2$.
$$
\begin{aligned}
f'(x) &=0 \To x=-1, 5\\
f''(x) &= 0 \To x=2
\end{aligned}
$$
5\. **Increasing/decreasing and concavity** $f$ is increasing on $(-\infty, -1), (5, \infty)$, and is decreasing on $(-1, 5)$. $f$ is concave up on $(2, \infty)$, and is concave down on $(-\infty, 2)$.
$$
\begin{aligned}
x\in & (-\infty, -1) \To f'(x)> 0 \quad & x \in (-1, 5) \To f'(x) <0\\
x\in & (5, \infty) \To f'(x)> 0\\
x\in & (-\infty, 2) \To f''(x) <0 \quad & x \in (2, \infty) \To f''(x) >0
\end{aligned}
$$
6\. **Extreme values and inflection points** By the Second Derivative Test, $f$ has a local maximum at $x=-1, f(-1) = \frac{14}{3}$, and a local minimum at $x=5, f(5) = -\frac{94}{3}$. Because $f''$ changes sign at $x=2$, $f$ has an inflection point $(2, -\frac{40}{3})$.
$$
\begin{aligned}
f(-1) &= \frac{1}{3} \cdot (-1)^3 - 2(-1)^2-5(-1) + 2 = \frac{14}{3}\\
f(5) &= \frac{1}{3} \cdot (5)^3 - 2(5)^2-5\cdot 5 + 2 = -\frac{94}{3}\\
f''(-1) &= 2 \cdot (-1) -4 = -6 <0 \To \text{Local maximum}\\
f''(5) &= 2 \cdot (5) -4 = 6 >0 \To \text{Local minimum}\\
f(2) &= \frac{1}{3} \cdot (2)^3 - 2(2)^2-5\cdot 2 + 2 = -\frac{40}{3}
\end{aligned}
$$
7\. **Asymptotes** $f$ has no vertical or horizontal asymptote.
$$
\lim_{x\to \infty} f(x) = \infty \quad \lim_{x\to -\infty} f(x) = -\infty
$$
8\. **Intercepts**
$$
\begin{aligned}
f(x) &= 0 \To x\approx -2.173, 0.353, 7.82 &\text{x-intercepts}\\
x&=0 \To f(x) = 2 &\text{y-intercept}
\end{aligned}
$$
9\. Graph (37).

56\. **Local max/min of $x^{1/x}$** Use analytic methods to find all local extreme points of the function $f(x) = x^{1/x}$, for $x>0$. Verify your work using a graphing utility.
>Solution
$$
\begin{aligned}
f'(x) &= \frac{d}{dx}(e^{\ln x \cdot \frac{1}{x}})\\
&= e^{\ln x \cdot \frac{1}{x}} \cdot [\frac{1}{x} \cdot \frac{1}{x} + \ln x \cdot (-\frac{1}{x^2})]\\
&= x^{\frac{1}{x}}(\frac{1}{x^2} - \frac{\ln x}{x^2})\\
&= x^{\frac{1}{x} - 2}(1-\ln x)\\
f'(x) &=0 \To 1-\ln x = 0 \To x = e\\
x \in & (0, e) \To f'(x) >0\\
x \in & (e, \infty) \To f'(x) <0
\end{aligned}
$$
Because $f'$ changes from positive to negative as $x$ passes through the critical point $x=e$, $f$ has a local maximum, $f(e) = \sqrt[e]{e}$.

<!-- pagebreak -->
57-60\. **Designer function** Sketch a continuous function $f$ on some interval that has the properties described.
57\. The function $f$ has an inflection point but no local extrema.
>Solution
Graph (57).

71\. **Height vs Volume** The figure shows six containers, each of which is filled from the top. Assume that water is poured into the containers at a constant rate and each container is filled in 10 seconds. Assume also that the horizontal cross sections of the containers are always circles. Let $h(t)$ be the depth of water in the container at time $t$, for $0 \les t \les 10$.
a. For each container, sketch a graph of the function $y=h(t)$, $0 \les t \les 10$.
>Solution
Graph (71a-f).

b. Explain why $h$ is an increasing function.
>Solution
The water is being pouring in at a constant rate, so the water level is always increasing. Thus $h$ is an increasing function.

c. Describe the concavity of the function. Identify inflection points when they occur.
>Solution
(a) $h(t)$ has no concavity.
(b) $h(t)$ is alway concave down.
(c) $h(t)$ is alway concave up.
(d) $h(t)$ is concave down at first half and concave up at second half.
(e) $h(t)$ has no concavity at the first, second and third straight parts, and is concave down at the lower middle part and concave up at the higher middle part.
(f) $h(t)$ is concave down at first half and concave up at second half.

d. For each container, where does $h'$ have an absolute maximum on $[0, 10]$.
>Solution
(a) $h'(t)$ is constant, so it has no absolute maximum.
(b) The maximum of $h'(t)$ occurs at $t=0$.
(c) The maximum of $h'(t)$ occurs at $t=10$.
(d) The maximum of $h'(t)$ occurs at $t=0, 10$.
(e) The maximum of $h'(t)$ occurs at the first and last straight parts of $h(t)$.
(f) The maximum of $h'(t)$ occurs at $t=0, 10$.
