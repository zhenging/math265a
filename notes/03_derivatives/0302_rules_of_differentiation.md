### Section 3.2 Rules of Differentiation

+ Constant Rule
+ Power Rule
+ Constant Multiple
+ Sum Rule
+ The Derivative of $e^x$
+ Slope of Tangent line
+ Higher-order Derivatives

#### Homwork
p148: 3, 7, 11, 15, 16, 21, 24, 27, 29, 34, 35, 37, 41, 43, 46, 53, 69, 77

3\. Give a nonzero function that is its own derivative.
>Solution
$f(x) = e^x$

7-12\. **Derivatives of power and constant** functions Find the derivative of the following functions.
7\. $y=x^5$
>Solution
$y'(x) = 5x^4$

11\. $h(t) = t$
>Solution
$h'(t) = 1$

13-18\. **Derivatives of constant multiples of functions** Find the derivative of the following functions. See Example 4 of section 3.1 for the derivative of $\sqrt{x}$.
15\. $p(x) = 8x$
>Solution
$p'(x) = 8$

16\. $g(t) = 6{\sqrt {t}}$
>Solution
$g'(t) = 6 \times \frac{1}{2} \times t^{\frac{1}{2} - 1} = \frac{3}{\sqrt{t}}$

19-24\. **Derivatives of the sum of functions**. Find the derivative of the following functions.
21\. $f(x) = 10x^4-32x+e^2$
>Solution
$$
\begin{aligned}
f'(x) &= \frac{d}{dx}(10x^4-32x+e^2) \\
&= \frac{d}{dx}(10x^4) - \frac{d}{dx}(32x) + \frac{d}{dx}(e^2) \\
&= 10 \times \frac{d}{dx}(x^4) - 32 \times \frac{d}{dx}(x) + \frac{d}{dx}(e^2) \\
&= 10 \times 4x^3 - 32 \times 1 + 0 \\
&= 40x^3 -32
\end{aligned}
$$

24\. $s(t) = 4\sqrt{t} - \frac{1}{4}t^4 + t + 1$
>Solution
$$
\begin{aligned}
s'(t) &= \frac{d}{dt}(4\sqrt{t} - \frac{1}{4}t^4 + t + 1) \\
&= \frac{d}{dt}(4\sqrt{t}) - \frac{d}{dt}(\frac{1}{4}t^4) + \frac{d}{dt}(t) + \frac{d}{dt}(1)\\
&= 4 \times \frac{d}{dt}(\sqrt{t}) - \frac{1}{4} \times \frac{d}{dt}(t^4) + \frac{d}{dt}(t) + \frac{d}{dt}(1)\\
&= 4 \times \frac{1}{2\sqrt {t}} - \frac{1}{4} \times 4t^3 + 1 + 0 \\
&= \frac{2}{{\sqrt {t}}} - t^3 + 1
\end{aligned}
$$

25-28\. **Derivatives of products**. Find the derivative of the following functions by first expanding the expression. Simplify your answers.
27\. $h(x) = (x^2+1)^2$
>Solution
$$
\begin{aligned}
h(x) &= x^4 + 2x^2 + 1 \\
h'(x) &= \frac{d}{dx}(x^4 + 2x^2 + 1) \\
&= \frac{d}{dx}(x^4) + \frac{d}{dx}(2x^2) + \frac{d}{dx}(1) \\
&= 4x^3 + 4x
\end{aligned}
$$

29-34\. **Derivative of quotients** Find the derivative of the following functions by first simplifying the expression.
29\. $f(w) = \dfrac{w^3-w}{w}$
>Solution
$$
\begin{aligned}
f(w) &= w^2-1 \quad \text{for } w \ne 0\\
f'(w) &= \frac{d}{dw}(w^2-1) \\
&= \frac{d}{dw}(w^2)-\frac{d}{dw}(1) \\
&= 2w \quad \text{for } w \ne 0
\end{aligned}
$$

34\. $y = \dfrac{x^2-2ax+a^2}{x-a}$
>Solution
$$
\begin{aligned}
y &= \frac{(x-a)^2}{x-a} = x-a \quad \text{for }x \ne a \\
y' &= \frac{d}{dx}(x-a) \\
&= \frac{d}{dx}(x) - \frac{d}{dx}(a) \\
&= 1 \quad \text{for }x \ne a
\end{aligned}
$$

35-38\. **Equations of tangent lines**
a. Find an equation of the tangent line at $x=a$.
b. Use a graphing utility to graph the curve and the tangent line on the same set of axes.
37\. $y=e^x$; $a=\ln 3$
>Solution
Graph (37). Let $m_{tan}$ be the slope of the tangent line at $x=\ln 3$, $y' = \frac{d}{dx}(e^x) = e^x$ and $m_{tan} = e^{\ln 3} = 3$.
When $x= \ln 3$, $y = e^{\ln 3} = 3$, the equation of the tangent line at $x=\ln 3$ is $y-3 = 3(x- \ln 3)$ or $y = 3x + 3-3\ln 3$.

41\. **Finding slope location** Let $f(x) = 2x^3 - 3x^2 -12x + 4$
a. Find all points on the graph of $f$ at which the tangent line is horizontal.
b. Find all points on the graph of $f$ at which the tangent line has slope $60$.
>Solution
$$
\begin{aligned}
f'(x) &= \frac{d}{dx}(2x^3 - 3x^2 -12x + 4) \\
&= \frac{d}{dx}(2x^3)-\frac{d}{dx}(3x^2) -\frac{d}{dx}(12x) + \frac{d}{dx}(4) \\
&= 6x^2-6x -12
\end{aligned}
$$
a. When the tangent line is horizontal, the slope is $0$,
$$
\begin{aligned}
f'(x) &= 0 \\
6x^2-6x -12 &= 0 \\
6(x-2)(x+1) &= 0 \\
x = 2 &\text{ or } x=-1 \\
f(2) &= 2 \times 2^3 - 3 \times 2^2 -12 \times 2 + 4 = -16 \\
f(-1) &= 2 \times (-1)^3 - 3 \times (-1)^2 -12 \times (-1) + 4 = 11 \\
\end{aligned}
$$
At points $(2, -16)$ and $(-1, 11)$ the tangent line is horizontal.
b. When the tangent line has slope $60$,
$$
\begin{aligned}
f'(x) &= 60 \\
6x^2-6x -12 &= 60 \\
x^2-x-2 &=10 \\
(x-4)(x+3) &=0 \\
x = 4 &\text{ or } x=-3 \\
f(4) &= 2 \times 4^3 - 3 \times 4^2 -12 \times 4 + 4 = 36 \\
f(-3) &= 2 \times (-3)^3 - 3 \times (-3)^2 -12 \times (-3) + 4 = -41 \\
\end{aligned}
$$
At points $(4, 36)$ and $(-3, -41)$ the tangent line slope $60$.

43\. **Finding slope location** Let $f(x) = 4\sqrt{x} - x$.
a. Find all points on the graph of $f$ at which the tangent line is horizontal.
b. Find all points on the graph of $f$ at which the tangent line has slope $-\frac{1}{2}$.
>Solution
$$
\begin{aligned}
f'(x) &= \frac{d}{dx}(4\sqrt{x} - x) \\
&= \frac{d}{dx}(4\sqrt{x})-\frac{d}{dx}(x) \\
&= \frac{2}{{\sqrt {x}}} - 1
\end{aligned}
$$
a. When the tangent line is horizontal, the slope is $0$,
$$
\begin{aligned}
f'(x) &= 0 \To \frac{2}{{\sqrt {x}}} - 1 = 0 \To
\sqrt {x} = 2  &\To x = 4 \\
f(4) &= 4\sqrt{4} - 4 = 4
\end{aligned}
$$
At point $(4, 4)$ the tangent line is horizontal.
b. When the tangent line has slope $-\frac{1}{2}$,
$$
\begin{aligned}
f'(x) &= -\frac{1}{2} \To \frac{2}{{\sqrt {x}}} - 1 = -\frac{1}{2} \To \sqrt {x} &= 4 \To x &= 16 \\
f(16) &=  4\sqrt{16} - 16 = 0
\end{aligned}
$$
At point $(16, 0)$ the tangent line has slope $-\frac{1}{2}$.

44-48\. **High-order derivative** Find $f'(x)$, $f''(x)$, and $f^{(3)}x$ for the following functions.
46\. $f(x) = 3x^2 + 5e^x$
>Solution
$$
\begin{aligned}
f'(x) &= \frac{d}{dx}(3x^2 + 5e^x) = 6x + 5e^x \\
f''(x) &= \frac{d}{dx}(f'(x)) = \frac{d}{dx}(6x + 5e^x) = 6 + 5e^x \\
f^{(3)}x &= \frac{d}{dx}(f''(x)) = \frac{d}{dx}(6 + 5e^x) = 5e^x
\end{aligned}
$$

52-55\. **Derivatives from a graph** Let $F=f+g$ and $G = 3f-g$, where the graphs of $f$ and $g$ are shown in the figure. Find the following derivatives. Graph (52-55)
53\. $G'(2)$
>Solution
$$
\begin{aligned}
G'(x) &= \frac{d}{dx}(3f - g) \\
&= 3f'(x) - g'(x)\\
f'(2) &= -3 \text{ and } g'(2) = 1 \\
G'(2) &= 3f'(2) - g'(2) = 3 \times (-3) - 1 = -10
\end{aligned}
$$

69\. **Height Estimate** The distance an object falls(when released from rest, under the influence of Earth's gravity, and with no air resistance) is given by $d(t) = 16t^2$, where $d$ is measured in feet and $t$ is measured in seconds. A climber sits on a ledge on a vertical wall and carefully observes the time it takes for a small stone to fall from the ledge to the ground.
a. Compute $d'(t)$. What units are associated with the derivative and what does it measure.
b. If it takes $6$s for a stone to fall to the ground, how high is the ledge? How fast is the stone moving when it strikes the ground (in mil/hr)?
>Solution
a. $d'(t) = 32t$. $d'(t)$ is the velocity of the stone at time $t$ and is unit is feet per second.
b. The height is $d(t) = 16 \times (6)^2 = 576$ feet. The velocity when it strikes the ground is $d'(6) = 32 \times 6 = 192$ feet per second. When measured in miles per hour, $192$ feet per seconds is $192 \times \frac{3600}{5280} \approx 130.9$ miles per hours.

77\. **Computing the derivative of $f(x)=e^{2x}$**
a. Use the defition of the derivative to show that $\dfrac{d}{dx}(e^{2x}) = e^{2x} \cdot \dlim_{h \to 0}{\frac{e^{2h} -1}{h}}$.
>Solution
$$
\begin{aligned}
\frac{d}{dx}(e^{2x}) &= \lim_{h \to 0}{\frac{e^{2(x+h)} - e^{2x}}{h}} \\
&= \lim_{h \to 0}{\frac{e^{2x}(e^{2h} - 1)}{h}} \\
& = e^{2x} \cdot \lim_{h \to 0}\frac{e^{2h} - 1}{h}
\end{aligned}
$$

b. Show that the limit in part (a) is equal to $2$. (Hint: Factor $e^{2h} - 1$).
>Solution
$$
\begin{aligned}
\lim_{h \to 0}\frac{e^{2h} - 1}{h} &= \lim_{t \to 0}\frac{e^t - 1}{t/2} & (t = 2h)\\
&= 2\lim_{t \to 0}\frac{e^t - 1}{t} \\
&= 2 \times 1 = 2
\end{aligned}
$$

c. Use parts (a) and (b) to find the derivative of $f(x) = e^{2x}$
$$
\begin{aligned}
\frac{d}{dx}(e^{2x}) &= e^{2x} \cdot \lim_{h \to 0}\frac{e^{2h} - 1}{h} \\
&= e^{2x} \cdot 2 \\
&= 2e^{2x}
\end{aligned}
$$
