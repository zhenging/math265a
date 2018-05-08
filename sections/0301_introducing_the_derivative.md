### Section 3.1 Introducing the Derivative
pg137: 4, 11, 14, 15, 17, 22, 25, 29, 33, 39, 41, 46, 49, 53, 61, 73

4\. For a given function $f$, what does $f'$ represent?
>Solution
$f'$ is the derivative of function $f$ and $f'(x)$ represents the slope of the tangent line (instantaneous rate of change) at the variable point $(x, f(x))$.

11-16\. **Equations of tangent lines by definition (1)**.
a. Use definition (1) (p. 128) to find the slope of the line tangent to the graph of $f$ at $P$.
b. Determine an equation of the tangent line at point $P$.
c. Plot the graph of f and the tangent line at $P$.
11\. $f(x) = x^2 - 5$; $P(3, 4)$
>Solution
$$
\begin{aligned}
f'(x) &= \lim_{h \to 0}{\frac{(x+h)^2-5 - (x^2 -5)}{h}} \\
&= \lim_{h \to 0}{\frac{2hx + h^2}{h}} \\
&= \lim_{h \to 0}(2x+h) &\text{Replacement property}\\
&= 2x + 0 = 2x
\end{aligned}
$$
a. The slope of tangent line at point $P(3, 4)$ is $f'(3) = 2 \times 3 = 6$.
b. The equation of the tangent line at point $P(3, 4)$ is $y-4 = 6(x-3)$ or $y=6x-14$
c. Graph (11).

14\. $f(x) = 5$; $P(1, 5)$
>Solution
a. The derivative of $f$ is $f'(x) = \lim_{h \to 0}{\frac{5-5}{h}} = 0$. The slope of tangent line at point $P(1, 5)$ is $f'(1) = 0$.
b. The equation of the tangent line at point $P(1, 5)$ is $y-5 = 0(x-1)$ or $y=5$
c. Graph (14).

15\. $f(x) = \dfrac{1}{x}$; $P(-1, -1)$
>Solution
$$
\begin{aligned}
f'(x) &= \lim_{h \to 0}{\frac{\frac{1}{x+h} - \frac{1}{x}}{h}} \\
&= \lim_{h \to 0}{\frac{x-(x+h)}{hx(x+h)}} \\
&= \lim_{h \to 0}(-\frac{1}{x(x+h)}) &\text{Replacement property}\\
&= -\frac{1}{x(x+0)} = -\frac{1}{x^2}
\end{aligned}
$$
a. The slope of tangent line at point $P(-1, -1)$ is $f'(-1) = -\frac{1}{(-1)^2} = -1$.
b. The equation of the tangent line at point $P(-1, -1)$ is $y-(-1) = -1 \times [x-(-1)]$ or $y=-x-2$
c. Graph (15).

17-26\. **Equations of tangent lines by definition (2)**.
a. Use definition (2) (p. 129) to find the slope of the line tangent to the graph of $f$ at $P$.
b. Determine an equation of the tangent line at point $P$.
17\. $f(x) = 2x + 1$; $P(0, 1)$
>Solution
$$
\begin{aligned}
f'(x) &= \lim_{h \to 0}{\frac{2(x+h) + 1 - (2x+1)}{h}} \\
&= \lim_{h \to 0}{\frac{2h}{h}} \\
&= \lim_{h \to 0}(2) &\text{Replacement property}\\
&= 2
\end{aligned}
$$
a. The slope of tangent line at point $P(0, 1)$ is $f'(0) = 2$.
b. The equation of the tangent line at point $P(0, 1)$ is $y-1 = 2 (x-0)$ or $y=2x+1$

22\. $f(x) = \dfrac{1}{2x + 1}$; $P(0, 1)$
>Solution
$$
\begin{aligned}
f'(x) &= \lim_{h \to 0}{\frac{\frac{1}{2(x+h)+1} - \frac{1}{2x+1}}{h}} \\
&= \lim_{h \to 0}{\frac{2x+1-2(x+h)-1}{h(2x+1)(2x+2h+1)}} \\
&= \lim_{h \to 0}(-\frac{2}{(2x+1)(2x+2h+1)}) &\text{Replacement property}\\
&= -\frac{2}{(2x+1)(2x+2 \times 0+1)} = -\frac{2}{(2x+1)^2}
\end{aligned}
$$
a. The slope of tangent line at point $P(0, 1)$ is $f'(0) = -\dfrac{2}{(2 \times 0 + 1)^2} = -2$.
b. The equation of the tangent line at point $P(0, 1)$ is $y-1 = -2 \times (x-0)$ or $y=-2x+1$

25\. $f(x) = \sqrt{x + 3}$; $P(1, 2)$
>Solution
$$
\begin{aligned}
f'(x) &= \lim_{h \to 0}{\frac{\sqrt{x + h + 3} - \sqrt{x + 3}}{h}} \\
&= \lim_{h \to 0}{\frac{\sqrt{x + h + 3} - \sqrt{x + 3}}{h} \times \frac{{\sqrt {x+h+3} + {\sqrt {x+3}}}}{{\sqrt {x+h+3} + {\sqrt {x+3}}}}} \\
&= \lim_{h \to 0}{\frac{(x+h+3) - (x+3)}{h({\sqrt {x+h+3}} + {\sqrt {x+3}})}} \\
&= \lim_{h \to 0}{\frac{h}{h({\sqrt {x+h+3}} + {\sqrt {x+3}})}} \\
&= \lim_{h \to 0}{\frac{1}{{\sqrt {x+h+3}} + {\sqrt {x+3}}}} &\text{Replacement Property}\\
& = \frac{1}{{\sqrt {x+0+3}} +{\sqrt {x+3}}} &\text{Q, FP, S}\\
&= \frac{1}{2 {\sqrt {x+3}}}
\end{aligned}
$$
a. The slope of tangent line at point $P(1, 2)$ is $f'(1) = \dfrac{1}{2 \times {\sqrt {1+3}}} = \dfrac{1}{4}$.
b. The equation of the tangent line at point $P(1, 2)$ is $y-2 = \dfrac{1}{4} \times (x-1)$ or $y=\dfrac{1}{4}x+\dfrac{7}{4}$

27-36\. **Derivatives and tangent lines**
a. For the following functions, find $f'(a)$.
b. Determine an equation of the line tangent to the graph of $f$ at point ($a, f(a))$ for the given value of $a$.
29\. $f(x) = 4x^2 + 2x$; $a=-2$
>Solution
a.
$$
\begin{aligned}
f'(x) &= \lim_{h \to 0}{\frac{4(x+h)^2 + 2(x+h) - (4x^2 + 2x)}{h}} \\
&= \lim_{h \to 0}{\frac{4x^2 + 8xh + 4h^2 + 2x + 2h - 4x^2 - 2x}{h}} \\
&= \lim_{h \to 0}{\frac{8xh + 4h^2 + 2h}{h}} \\
&= \lim_{h \to 0}(8x + 4h + 2) &\text{Repl Prop}\\
&= 8x + 4 \times 0 + 2 = 8x + 2 &\text{Polynomial}
\end{aligned}
$$
b. Let $m_{tan}$ be the slope of the tangent line at point $(a, f(a))$, as $a=-2$
$$
\begin{aligned}
f(a) &= 4(-2)^2 + 2(-2) = 12 \\
m_{tan} &= f'(a) = 8a+ 2=8 \times (-2) + 2 = -14
\end{aligned}
$$
The equation of the tangent line at point $(a, f(a))$ is $y-12 = -14(x+2)$ or $y=-14x-16$.

33\. $f(x) = \sqrt{2x + 1}$; $a=4$
>Solution
a.
$$
\begin{aligned}
f'(x) &= \lim_{h \to 0}{\frac{\sqrt{2(x+h) + 1} - \sqrt{2x + 1}}{h}} \\
&= \lim_{h \to 0}{\frac{\sqrt{2(x+h) + 1} - \sqrt{2x + 1}}{h} \times \frac{{\sqrt {2(x+h)+1} + {\sqrt {2x+1}}}}{{\sqrt {2(x+h)+1} + {\sqrt {2x+1}}}}} \\
&= \lim_{h \to 0}{\frac{(2x+2h+1) - (2x+1)}{h({\sqrt {2(x+h)+1}} + {\sqrt {2x+1}})}} \\
&= \lim_{h \to 0}{\frac{2h}{h({\sqrt {2x+2h+1}} + {\sqrt {2x+1}})}} \qquad \text{Replacement Property}\\
&= \lim_{h \to 0}{\frac{2}{{\sqrt {2x+2h+1}} + {\sqrt {2x+1}}}} \\
& = \frac{2}{{\sqrt {2x+0+1}} +{\sqrt {2x+1}}} \qquad \text{Q, FP, S}\\
&= \frac{1}{\sqrt {2x+1}}
\end{aligned}
$$
b. Let $m_{tan}$ be the slope of the tangent line at point $(a, f(a))$, as $a=4$
$$
\begin{aligned}
f(a) &= \sqrt {2 \times 4 +1} = 3 \\
m_{tan} &= f'(a) = \frac{1}{\sqrt {2a+1}} = \frac{1}{\sqrt {2 \times 4 +1}} = \frac{1}{3}
\end{aligned}
$$
The equation of the tangent line at point $(a, f(a))$ is $y-3 = \dfrac{1}{3}(x-4)$ or $y=\dfrac{1}{3} x + \dfrac{5}{3}$.

37-40\. **Lines tangent to parabolas**
a. Find the derivative function $f'$ fpr the following function.
b. Find an equation of the line tangent to the graph of $f$ at point $(a, f(a))$ for the given value of $a$.
c. Graph $f$ and the tangent line.
39\. $f(x) = 5x^2 - 6x + 1$; $a=2$
>Solution
a.
$$
\begin{aligned}
f'(x) &= \lim_{h \to 0}{\frac{5(x+h)^2-6(x+h)+1-(5x^2-6x+1)}{h}} \\
&= \lim_{h \to 0}{\frac{5x^2+10xh+10h^2-6x-6h+1-(5x^2-6x+1)}{h}} \\
&= \lim_{h \to 0}{\frac{10xh+10h^2-6h}{h}} \\
&= \lim_{h \to 0}(10x + 10h - 6) \quad\text{Repl Prop}\\
&= 10x + 10 \times 0 - 6 = 10x-6 \quad\text{Polynomial}
\end{aligned}
$$
b. Let $m_{tan}$ be the slope of the tangent line at point $(a, f(a))$, as $a=2$
$$
\begin{aligned}
f(a) &=5(2)^2 -6 \times 2 +1 = 9 \\
m_{tan} &= f'(a) = 10a-6 = 10 \times 2 -6 = 14
\end{aligned}
$$
The equation of the tangent line at point $(a, f(a))$ is $y-9 = 14(x-2)$ or $y=14x-19$.
c. Graph (39).

41\. **A derivative formula**
a. Use the definition of the derivative to determine $\frac{d}{dx}(ax^2 + bx + c)$, where $a$, $b$, and $c$ are constants.
b. Use the result of part (a) to find $\frac{d}{dx}(4x^2-3x + 10)$.
>Solution
a.
$$
\begin{aligned}
\frac{d}{dx}(ax^2 + bx + c) &= \lim_{h \to 0}{\frac{a(x+h)^2+b(x+h)+c-(ax^2+bx+c)}{h}} \\
&= \lim_{h \to 0}{\frac{ax^2+2axh+ah^2+bx+bh+c-(ax^2+bx+c)}{h}} \\
&= \lim_{h \to 0}{\frac{2axh+ah^2+bh}{h}} \\
&= \lim_{h \to 0}(2ax+ah+b) &\text{Repl Prop}\\
&= 2ax+(a \times 0)+b = 2ax+b &\text{Polynomial}
\end{aligned}
$$
b. $\frac{d}{dx}(4x^2-3x + 10) = (2x \times 4)-3 = 8x-3$

43-46\. **Derivative calculations** Evaluate the derivative of the following function at the give point.
46\. $A=\pi r^2$; $r=3$
>Solution
$$
\begin{aligned}
A'(r) &= \lim_{h \to 0}{\frac{\pi (r+h)^2 - \pi r^2}{h}} \\
&= \lim_{h \to 0}{\frac{\pi r^2 + 2\pi rh + \pi h^2  - \pi r^2}{h}} \\
&= \lim_{h \to 0}{\frac{2\pi rh + \pi h^2}{h}} \\
&= \lim_{h \to 0}(2\pi r + \pi h) &\text{Repl Prop}\\
&= 2\pi r + \pi \times 0 =2\pi r&\text{Polynomial} \\
A'(3) &= 2\pi \times 3 = 6\pi
\end{aligned}
$$

49\. **Matching the function with derivatives** Match the functions $a-d$ in the first set of figures with the derivative functions $A-D$ in the next set of figures. Graph (49).
>Solution
a -> D &emsp; b -> C &emsp;  c -> B &emsp; d -> A

53\. **Where is the function continuous? Differentiable?** Use the graph of $f$ in the figure to do the following.
a. Find the values of $x$ in $(0, 3)$ at which $f$ is not continuous.
b. Find the values of $x$ in $(0, 3)$ at which $f$ is not differentiable.
c. Sketch a graph of $f'$.
>Solution
a. When $x=1$, $f$ is not continuous.
b. When $x=1, 2$, $f$ is not differentiable.
c. Graph (53).

61-62\. Analyzing slopes Use the points A, B, C, D and E in the following graphs to answer these questions.
a. At which points is the slope of the curve negative?
b. At which points is the slope of the curve positive?
c. Useing A-E, list the slopes in descreasing order.
61\. Graph (61).
>Solution
a. The slope of the curve is negative at points $C, D$.
b. The slope of the curve is positive at points $A, B, E$.
c. $A, B, E, D, C$

73-76\. **Find the function** The following limits represent the slope of a curve $y = f(x)$ at the point $(a, f(a))$. Determine a function $f$ and a number $a$; then calcluate the limit.
73\. $\dlim_{x \to 2}{\dfrac{\frac{1}{x+1} - \frac{1}{3}}{x-2}}$
>Solution
$$
\begin{aligned}
m_{tan} &= \lim_{x \to a}\frac{f(x)-f(a)}{x-a} &\text{(1)} \\
\lim_{x \to 2}{\frac{\frac{1}{x+1} - \frac{1}{3}}{x-2}} &= \lim_{x \to 2}{\frac{\frac{1}{x+1} - \frac{1}{2+1}}{x-2}} &\text{(2)}
\end{aligned}
$$
Compare (1) and (2), we have $f(x) = \dfrac{1}{x+1}$, and $a=2$.
$$
\begin{aligned}
\lim_{x \to 2}{\frac{\frac{1}{x+1} - \frac{1}{3}}{x-2}} &= \lim_{x \to 2}{\frac{\frac{1}{x+1} - \frac{1}{3}}{x-2} \times \frac{3(x+1)}{3(x+1)}}  \\
&= \lim_{x \to 2}{\frac{3-(x+1)}{3(x+1)(x-2)}} \\
&= \lim_{x \to 2}{\frac{2-x}{3(x+1)(x-2)}} \\
&= \lim_{x \to 2}{\frac{-1}{3x+ 3}} &\text{Replacement Property} \\
&= \frac{-1}{3 \times 2 + 3} = -\frac{1}{9} &\text{Polynomial}
\end{aligned}
$$
