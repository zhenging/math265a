### Section 4.2 What Derivatives Tell Us

+ Increasing and Decreasing Functions
+ **Theorem 4.3** Test for Intervals of Increase and Decrease: $f'(x)>0$ or $f'(x)<0$.
+ Idenfitying Local Maxima and Minima
+ **Theorem 4.4** First Derivative Test
  + If $f'$ changes from positive to negative, $f$ has a local maximum at $c$.
  + If $f'$ changes from negative to positive, $f$ has a local minimum at $c$.
  + If $f'$ does not change sign, then $f$ has no local extreme value at $c$.
+ **Theorem 4.5** One Local Extremum Implies Absolute Extremum
+ Concavity and Inflection point
+ **Theorem 4.6** Test for Concavity
  + $f''>0 \To f \text{ is concave up}$
  + $f''<0 \To f \text{ is concave down}$
  + $f''$ changes sign at $c$, then $f$ has an inflection point at $c$.
+ **Theorem 4.7** Second Derivative Test for Local Extrema
  > Suppose that $f''$ is continuous on an open interval containing $c$ with $f'(c) = 0$.
  >+ If $f''(c)>0$, $f$ has a local minimum at $c$.
  >+ If $f''(c)<0$, $f$ has a local maximum at $c$.
  >+ If $f''(c)=0$, the test is inconclusive and $f$ may have a local maximum, local minimum, or neither at $c$.

#### Homework
p251: 6, 11, 15, 17, 23, 27, 30, 32, 37, 39, 45, 46, 49, 57, 65, 68, 71, 75, 81, 87, 91, 103

6\. Sketch a function that changes from concave up to concave down as $x$ increases. Describe how the second derivative of this functions changes?
>Solution
Graph (6). As $x$ increases, the second derivative changes from positive to negative at the point at which the concavity is changed from upward to downward.

11-14\. **Sketches from properties** Sketch a function that is continuous on $(-\infty, \infty)$ and has the following properties. Use a number line to summarize information about the function.
11\. $f'(x)<0$ on $(-\infty, 2)$; $f'(x)>0$ on $(2, 5)$; $f'(x)<0$ on $(5, \infty)$
>Solution
Graph (11).

15\. **Function from derivatives** The following figures give the graph of the derivative of a continuous function $f$ that passes through the origin. Sketch a possible graph if $f$ on the same set of axes. The graphs of $f$ are not unique.
>Solution
Graph (15).

17-26\. **Increasing and decreasing functions** Find the intervals on which $f$ is increasing and decreasing. Superimpose the graphs of $f$ and $f'$ to verify your work.
17\. $f(x) = 4-x^2$
>Solution
$$
\begin{aligned}
f'(x) &= -2x\\
f'(x) &=0 \To x=0 \\
x\in & (0, \infty) \To f'(x) <0 & x\in (-\infty, 0) \To f'(x) >0
\end{aligned}
$$
Graph (17). The function is increasing on $(-\infty, 0)$, and is decreasing on $(0, \infty)$.

23\. $f(x) = -\dfrac{x^4}{4} + x^3 -x^2$
>Solution
$$
\begin{aligned}
f'(x) &= -x^3+3x^2-2x \\
&= -x(x-1)(x-2)= 0 \\
\To & x=0, 1, 2 \\
x \in & (-\infty, 0) \To f'(x) >0 & x \in (0, 1) \To f'(x) <0\\
x \in & (1, 2) \To f'(x) >0 & x \in (2, \infty) \To f'(x) <0
\end{aligned}
$$
Graph (23). The function is increasing on $(-\infty, 0), (1, 2)$, and is decreasing on $(0, 1), (2, \infty)$.

27-38\. **Increasing and decreasing functions** Find the intervals on which $f$ is increasing and decreasing.
27\. $f(x) = 3\cos 3x$ on $[-\pi, \pi]$
>Solution
$$
\begin{aligned}
f'(x) &= -9\sin 3x\\
f'(x)&=0 \To x = 0, \pm \frac{\pi}{3}, \pm \frac{2\pi}{3}, \pm \pi\\
x\in & (-\pi, -\frac{2\pi}{3}) \To f'(x) >0 & x\in (-\frac{2\pi}{3}, -\frac{\pi}{3}) \To f'(x)<0 \\
x\in & (-\frac{\pi}{3}, 0) \To f'(x) >0 & x\in (0, \frac{\pi}{3}) \To f'(x) <0\\
x\in & (\frac{\pi}{3}, \frac{2\pi}{3}) \To f'(x)>0 &x\in (\frac{2\pi}{3}, \pi) \To f'(x) <0
\end{aligned}
$$
The function is increasing on $(-\pi, -\frac{2\pi}{3}), (-\frac{\pi}{3}, 0), (\frac{\pi}{3}, \frac{2\pi}{3})$, and is decreasing on $(-\frac{2\pi}{3}, -\frac{\pi}{3}), (0, \frac{\pi}{3}), (\frac{2\pi}{3}, \pi)$.

30\. $f(x) = x^2\sqrt{9-x^2}$ on $(-3, 3)$
>Solution
$$
\begin{aligned}
f'(x) &= 2x\sqrt{9-x^2} + x^2\cdot \frac{1}{2\sqrt{9-x^2}} \cdot (-2x)\\
&= \frac{18x-3x^3}{\sqrt{9-x^2}} = \frac{3x(6-x^2)}{\sqrt{9-x^2}}\\
f'(x) &=0 \To x= 0, \pm \sqrt 6\\
x\in & (-3, -\sqrt 6) \To f'(x) >0 & x\in (-\sqrt 6, 0) \To f'(x) <0\\
x\in & (0, \sqrt 6) \To f'(x)>0 & x\in (\sqrt 6, 3) \To f'(x)<0
\end{aligned}
$$
The function is increasing on $(-3, -\sqrt 6), (0, \sqrt 6)$, and is decreasing on $(-\sqrt 6, 0), (\sqrt 6, 3)$.

32\. $f(x) = \ln |x|$
>Solution
$$
\begin{aligned}
f'(x) &= \frac{1}{x}\\
f'(x) &\text{does not exist when }x=0\\
x \in & (-\infty, 0) \To f'(x)<0 &x \in (0, \infty) \To f'(x)>0
\end{aligned}
$$
The function is increasing on $(0, \infty)$, and is decreasing on $(-\infty, 0)$.

37\. $f(x) = \tan^{-1} (x^2)$
>Solution
$$
\begin{aligned}
f'(x) &= 2x \sec (x^2) = 0\\
f'(x) &=0 \To & x=0\\
x \in & (-\infty, 0) \To f'(x)<0 & x \in(0, \infty) \To f'(x)>0
\end{aligned}
$$
The function is increasing on $(0, \infty)$, and is decreasing on $(-\infty, 0)$.


39-48\. **First Derivative Test**
a. Locate the critical point of $f$.
b. Use the First Derivative Test to locate the local maximum and minimum.
c. Identify absolute maximum and minimum values of the function on the given interval (when they exist).
39\. $f(x) = x^2+3; [-3, 2]$
>Solution
$$
\begin{aligned}
f'(x) &= 2x\\
f'(x) &= 0 \To x=0\\
x \in & [-3, 0) \To f'(x)<0 &x \in (0, 2] \To f'(x)>0\\
f(0) &= 3 \quad f(-3) = 12 \quad f(2) = 7
\end{aligned}
$$
a. The critical point is $(0, 3)$.
b. As $f'$ changes from **negative** to **positive** as $x$ passes through the critical point $x=0$, $f$ has a local **minimum** at $x=0$, f(0) = 3.
c. The absolute **maximum** occurs at $(-3, 12)$, and the absolute **minimum** occurs at $(0, 3)$.

45\. $f(x) = x^{2/3}(x-5); [-5, 5]$
>Solution
$$
\begin{aligned}
f'(x) &= \frac{d}{dx}(x^{5/3} - 5x^{2/3})\\
&= \frac{5}{3}x^{2/3} - \frac{10}{3}x^{-1/3}\\
&= \frac{5x-10}{3\sqrt[3]{x}}\\
f'(x) &= 0 \To x=2\\
f'(x) &\text{does not exist when }x=0\\
x \in & [-5, 0) \To f'(x)>0\\
x \in & (0, 2) \To f'(x)<0\\
x \in & (2, 5] \To f'(x)>0\\
f(0) &= 0 \quad f(2) = -3\sqrt[3]{4} \quad f(-5) = -10\sqrt[3]{25} \quad f(5) = 0
\end{aligned}
$$
a. The critical points are $(0, 0), (2, -3\sqrt[3]{4})$.
b. As $f'$ changes from **positive** to **negative** as $x$ passes through $x=0$, $f$ has a local **maximum** at $x=0, f(x) = 0$; as $f'$ changes from **negative** to **positive** as $x$ passes through $x=0$, $f$ has a local **minimum** at $x=2, f(x) = -3\sqrt[3]{4}$.
c. The absolute **maximum** occurs at $(0, 0)$ or $(5, 0)$, and the absolute **minimum** occurs at $(-5, -10\sqrt[3]{25})$.

<!-- pagebreak -->
46\. $f(x) = \dfrac{x^2}{x^2-1}; [-4, 4]$
>Solution
$$
\begin{aligned}
f'(x) &= \frac{d}{dx}[1 + (x^2-1)^{-1}]\\
&= \frac{-2x}{(x^2-1)^2}\\
f'(x) &= 0 \To x=0\\
f(x) &\text{has vertical asymptotes at }x=\pm 1\\
x\in & [-4, -1) \To f'(x) >0 & x\in (-1, 0) \To f'(x) >0\\
x\in & (0, 1) \To f'(x) <0 & x\in (1, 4] \To f'(x) <0\\
f(0) &= 0 \quad f(-4) = f(4) = \frac{16}{15}\\
\lim_{x \to -1^-}f(x) &= \infty \quad \lim_{x \to -1^+}f(x) = -\infty\\
\lim_{x \to 1^-}f(x) &= -\infty \quad \lim_{x \to 1^+}f(x) = \infty\\
\end{aligned}
$$
a. The critical point is $(0, 0)$.
b. As $f'$ changes from **positive** to **negative** as $x$ passes through $x=0$, $f$ has a local **maximum** at $x=0, f(x) = 0$.
c. $f(x)$ has no absolute maximum or minimum on $[-4, 4]$.

49-52\. **Absolute extreme values** Verify that the following functions satisfy the conditions of Theorem 4.5 on their domains. Then find the location and value of the absolute extrema guaranteed by the theorem.
49\. $f(x) = xe^{-x}$
>Solution
$$
\begin{aligned}
f'(x) &= e^{-x} - xe^{-x} = e^{-x}(1-x)\\
f'(x) &=0 \To x=1\\
x \in & (-\infty, 1) \To f'(x)>0 & x \in (1, \infty) \To f'(x)<0\\
f(1) &= \frac{1}{e}
\end{aligned}
$$
As $f'$ changes from **positive** to **negative** as $x$ passes through $x=1$, $f$ has a local **maximum** at $x=1, f(x) = \frac{1}{e}$. $f$ is continuous on its domain $(-\infty, \infty)$ and contains only one critical point $(1, \frac{1}{e})$, $f(1)=\frac{1}{e}$ is the absolute maximum of $f$. $f$ has no absolute minimum as $f$ grows arbitrarily large in the negative direction as $x \to -\infty$.

<!-- pagebreak -->
57-70\. **Concavity** Determine the intervals on which the following functions are concave up or concave down. Identify any inflection point.
57\. $f(x)=x^4-2x^3+1$
>Solution
$$
\begin{aligned}
f'(x) &= 4x^3-6x^2\\
f''(x) &= 12x^2-12x\\
f''(x) &=0 \To x =0, 1\\
x\in & (-\infty, 0) \To f''(x)>0\\
x\in & (0, 1) \To f''(x)<0\\
x\in & (1, \infty) \To f''(x)>0\\
f(0) &= 1 \quad f(1) = 0
\end{aligned}
$$
$f$ is concave up on $(-\infty, 0), (1, \infty)$, and is concave down on $(0, 1)$. The inflection points are $(0, 1), (1, 0)$.

65\. $f(x) = e^{-x^2/2}$
>Solution
$$
\begin{aligned}
f'(x) &= -xe^{-\frac{x^2}{2}}\\
f''(x) &= -e^{-\frac{x^2}{2}} -x(-xe^{-\frac{x^2}{2}})\\
&= e^{-\frac{x^2}{2}}(x^2-1)\\
f''(x) &=0 \To x=\pm 1\\
x\in & (-\infty, -1) \To f''(x)>0\\
x\in & (-1, 1) \To f''(x)<0\\
x\in & (1, \infty) \To f''(x)>0\\
f(-1) &= f(1) = \frac{1}{\sqrt e}
\end{aligned}
$$
$f$ is concave up on $(-\infty, -1), (1, \infty)$, and is concave down on $(-1, 1)$. The inflection points are $(-1, \frac{1}{\sqrt e}), (1, \frac{1}{\sqrt e})$.

<!-- pagebreak -->
68\. $h(t) = 2+\cos 2t; [-\pi, \pi]$
>Solution
$$
\begin{aligned}
h'(t) &= -2\sin 2t\\
h''(t) &= -4\cos 2t\\
h''(t) &= 0 \To t=\pm \frac{\pi}{4}, \pm \frac{3\pi}{4}\\
t\in & [-\pi, -\frac{3\pi}{4}) \To h''(t) <0
& t\in (-\frac{3\pi}{4}, -\frac{\pi}{4}) \To h''(t) >0\\
t\in & (-\frac{\pi}{4}, \frac{\pi}{4}) \To h''(t) <0
& t\in (\frac{\pi}{4}, \frac{3\pi}{4}) \To h''(t) >0\\
t\in & (\frac{3\pi}{4}, \pi] \To h''(t) <0\\
h(-\pi)&=h(\pi) = 3 \\
h(-\frac{3\pi}{4}) &= h(\frac{3\pi}{4})= 2 \\ h(-\frac{\pi}{4}) &= h(\frac{\pi}{4})= 2
\end{aligned}
$$
$f$ is concave up on $(-\frac{3\pi}{4}, -\frac{\pi}{4}), (\frac{\pi}{4}, \frac{3\pi}{4})$, and is concave down on $[-\pi, -\frac{3\pi}{4}), (-\frac{\pi}{4}, \frac{\pi}{4}), (\frac{3\pi}{4}, \pi]$. The inflection points are $(-\frac{3\pi}{4}, 2), (-\frac{\pi}{4}, 2), (\frac{\pi}{4}, 2), (\frac{3\pi}{4}, 2)$.

71-82\. **Second Derivative Test** Locate the critical point of the following functions. Then use the Second Derivative to determine whether they correspond to local maximum, local minimum, or neither.
71\. $f(x) = x^3-3x^2$
>Solution
$$
\begin{aligned}
f'(x) &= 3x^2-6x \\
f'(x) &= 0 \To x=0, 2\\
f''(x) &= 6x-6\\
f''(0) &=-6<0 \To \text{Local maximum at }x=0\\
f''(2) &=6>0 \To \text{Local minimum at }x=2\\
\end{aligned}
$$

<!-- pagebreak -->
75\. $f(x)=e^x(x-7)$
>Solution
$$
\begin{aligned}
f'(x) &= e^x+xe^x-7e^x = e^x(x-6)\\
f'(x) &=0 \To x=6\\
f''(x) &= e^x+xe^x-6e^x = e^x(x-5)\\
f''(6) &= e^6 >0 \To \text{Local minimum at } x=6
\end{aligned}
$$

81\. $f(x)=2x^2\ln x - 11x^2$
>Solution
$$
\begin{aligned}
f'(x) &= 4x\ln x + 2x^2 \cdot \frac{1}{x} -22x= 4x(\ln x-5)\\
f'(x) &=0 \To x=e^5 &\text{the domain of f is } (0, \infty)\\
f''(x) &= 4\ln x + 4x\cdot \frac{1}{x} - 20= 4\ln x-16\\
f''(e^5) &= 4>0 \To \text{Local minimum at } x=e^5
\end{aligned}
$$

87\. Matching derivatives and functions. The following figures show the graphs of three functions (a-c). Match each function with its first derivatives (d-f) and its second derivative (g-i).

>Solution
$a \to f \to g \quad b \to d \to h \quad c \to e \to i$

90-93\. **Designer functions** Sketch the graph of a function that is continuous on $(-\infty, \infty)$ and satisfy the following sets of conditions.
91\. $f''(x)>0 \text{ on } (-\infty, -2)$; $f''(-2)=0$; $f'(-1)=f'(1) = 0$; $f''(2)=0$; $f'(3) = 0$; $f''(x)>0 \text{ on } (4, \infty)$.
>Solution
Graph (91).

103\. **Population Models** The population of a species is given by the function $P(t) = \frac{Kt^2}{t^2+b}$, where $t \ges 0$ is measured in years and $K$ and $b$ are postive numbers.
a. With $K=300$ and $b=30$, what is $\dlim_{t\to \infty}P(t)$, the carrying capacity of the population?
>Solution
$$
\begin{aligned}
\lim_{t\to \infty}P(t) &= \lim_{t\to \infty}\frac{300t^2}{t^2+30}\\
&= \lim_{t\to \infty}\frac{300}{1+\frac{30}{t^2}}\\
&=\frac{300}{1+0} = 300\\
\end{aligned}
$$
The carrying capacity is $300$.

<!-- pagebreak -->
b. With $K=300$ and $b=30$, when does the maximum growth rate occur?
>Solution
$$
\begin{aligned}
P'(t) &= \frac{d}{dt}(\frac{300t^2}{t^2+30})\\
&= \frac{600t(t^2+30) - 300t^2(2t)}{(t^2+30)^2}\\
&= \frac{18000t}{(t^2+30)^2}\\
P''(t) &= \frac{18000(t^2+30)^2 - 18000t[2(t^2+30) \cdot 2t]}{(t^2+30)^4}\\
&= \frac{(18000t^2+540000 - 72000t^2)(t^2+30)}{(t^2+30)^4}\\
&= \frac{540000-54000t^2}{(t^2+30)^3}\\
&= \frac{54000(10-t^2)}{(t^2+30)^3}\\
P''(t) &= 0 \To t = \sqrt 10 & t \ges 0\\
t \in & [0, \sqrt 10) \To P''(t) >0 \\
t \in & (\sqrt 10, \infty) \To P''(t) <0 \\
P'(\sqrt 10) &= \frac{18000\sqrt {10}}{40^2} = \frac{45\sqrt {10}}{4}
\end{aligned}
$$
As $P''$ changes from **postive** to **negative** as $t$ passes through $t=\sqrt 10$, $P'$ has a local maximum at $t=\sqrt {10}, P'(\sqrt 10) = \frac{45\sqrt {10}}{4} \approx 35.58$.

c. For arbitrary postive values of $K$ and $b$, when does the maximum growth rate occur(in terms of $K$ and $b$)?
>Solution
$$
\begin{aligned}
P'(t) &= \frac{2bKt}{(t^2+b)^2}\\
P''(t) &= \frac{2bK(b-3t^2)}{(t^2+30)^3}\\
P''(t) &= 0 \To t= \sqrt{\frac{b}{3}}\\
t \in & [0, \sqrt{\frac{b}{3}}) \To P''(t) >0
& t \in (\sqrt{\frac{b}{3}}, \infty) \To P''(t) <0
\end{aligned}
$$
As $P''$ changes from **postive** to **negative** as $t$ passes through $t=\sqrt {\frac{b}{3}}$, $P'$ has a local maximum at $t=\sqrt {\frac{b}{3}}$.
