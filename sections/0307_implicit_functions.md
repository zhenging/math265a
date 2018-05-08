### Section 3.7 Implicit Functions
pg196: 5, 9, 13, 19, 21, 28, 33, 39, 47, 48, 53, 57, 73, 77

5-12\. **Implicit differentiation** Carry out the following steps.
a. Use implicit differentiation to find $\dfrac{dy}{dx}$.
b. Find the slope of the curve at the given point.
5\. $x^4+y^4=2; (1, -1)$
>Solution
$$
\begin{gathered}
\frac{d}{dx}(x^4+y^4) = \frac{d}{dx}(2) \\
4x^3 + 4y \frac{dy}{dx} = 0 \\
\frac{dy}{dx} = -\frac{x^3}{y} \To \frac{dy}{dx} |_{(1, -1)} = -\frac{1^3}{-1} = 1
\end{gathered}
$$

9\. $\sin y = 5x^4-5; (1, \pi)$
>Solution
$$
\begin{gathered}
\frac{d}{dx}(\sin t) = \frac{d}{dx}(5x^4-5)\\
\cos y \frac{dy}{dx} = 20x^3\\
\frac{dy}{dx} = \frac{20x^3}{\cos y} \To \frac{dy}{dx} |_{(1, \pi)} = \frac{20\cdot 1^3}{\cos \pi} = -20
\end{gathered}
$$

13-24\. **Implicit differentiation** Use implicit differentiation to find $\dfrac{dy}{dx}$.
13\. $\sin xy = x+y$
>Solution
$$
\begin{gathered}
\frac{d}{dx}(\sin xy) = \frac{d}{dx}(x+y)\\
\cos xy \frac{d}{dx}(xy) = 1 + \frac{dy}{dx} \\
\cos xy (1 \cdot y + x \cdot \frac{dy}{dx}) =\frac{dy}{dx} + 1 \\
y\cos xy  + x \cos xy \frac{dy}{dx} =\frac{dy}{dx} + 1\\
\frac{dy}{dx} = \frac{y\cos xy -1}{1-x\cos xy}
\end{gathered}
$$

19\. $x^3=\dfrac{x+y}{x-y}$
>Solution
$$
\begin{gathered}
\frac{d}{dx}(x^3) = \frac{d}{dx}\left (\frac{x+y}{x-y}\right ) \\
3x^2 = \frac{(1+\frac{dy}{dx})(x-y) -(x+y)(1-\frac{dy}{dx})}{(x-y)^2} \\
3x^2(x-y)^2 = x-y+(x-y)\frac{dy}{dx} - x-y+(x+y)\frac{dy}{dx}\\
3x^2(x-y)^2 = -2y + 2x\frac{dy}{dx}\\
\frac{dy}{dx} = \frac{3x^2(x-y)^2 +2y}{2x}
\end{gathered}
$$

21\. $6x^3+7y^3=13xy$
>Solution
$$
\begin{gathered}
\frac{d}{dx}(6x^3+7y^3) = \frac{d}{dx}(13xy)\\
18x^2+21y^2\frac{dy}{dx} = 13(y+x\frac{dy}{dx})\\
(21y^2-13x)\frac{dy}{dx} = 13y-18x^2 \\
\frac{dy}{dx} = \frac{13y-18x^2}{21y^2-13x}
\end{gathered}
$$

25-30\. **Tangent line** Carry out the following steps
a. Verify that the give point lies on the curve
b. Determine an equation of the line tangent to the curve at the given point.
28\. $x^3+y^3 = 2xy; (1, 1)$
>Solution
As $1^3+1^3 = 2\times 1 \times 1$, the point $(1, 1)$ lies on the curve.
$$
\begin{aligned}
\frac{d}{dx}(x^3+y^3) &= \frac{d}{dx}(2xy)\\
3x^2+3y^2\frac{dy}{dx} &= 2(y+x\frac{dy}{dx})\\
(3y^2-2x)\frac{dy}{dx} &= 2y-3x^2 \\
\frac{dy}{dx} &= \frac{2y-3x^2}{3y^2-2x}
\end{aligned}
$$
The slope of the tangent line at $(1, 1)$ is $\frac{2\times 1-3 \times 1^2}{3\times 1^2-2 \times 1} = -1$, the equation is $y-1=(-1)(x-1)$ or $y= -x+2$.

31-36\. Second derivative Find $\dfrac{d^2y}{dx^2}$.
33\. $x+y=\sin y$
>Solution
$$
\begin{aligned}
\frac{d}{dx}(x+y) &= \frac{d}{dx}(\sin y) \\
1 + y' &= \cos y \cdot y'\\
y' &= \frac{1}{\cos y -1}\\
\frac{d^2y}{dx^2} &= \frac{d}{dx}(y') =\frac{d}{dx}\left(\frac{1}{\cos y -1}\right) \\
&=\frac{\sin y}{(\cos y -1)^2} \cdot y'\\
&=\frac{\sin y}{(\cos y -1)^2} \cdot \frac{1}{\cos y -1}\\
&=\frac{\sin y}{(\cos y -1)^3}
\end{aligned}
$$

37-44\. **Derivatives of functions with rational exponents** Find $\dfrac{dy}{dx}$.
39\. $y= (5x+1)^{2/3}$
>Solution
$\frac{dy}{dx} = \frac{2}{3}(5x+1)^{-1/3} = \frac{2}{3\sqrt[3] {5x+1}}$

45-50\. **Implicit differentiation with rational exponents** Determine the slope of the following curves at the given point.
47\. $\sqrt[3] x + \sqrt[3] {y^4} = 2; (1, 1)$
>Solution
$$
\begin{gathered}
\frac{d}{dx}(\sqrt[3] x + \sqrt[3] {y^4}) = \frac{d}{dx}(2)\\
\frac{1}{3\sqrt[3] {x^2}} + \frac{4\sqrt[3]y}{3}\cdot y'= 0 \\
y' = -\frac{1}{4\sqrt[3]{x^2y}}\\
y'|_{(1, 1)} = -\frac{1}{4\sqrt[3]{1^2 \times 1}} = -\frac{1}{4}
\end{gathered}
$$

48\. $(x+y)^{2/3} = y; (4, 4)$
>Solution
$$
\begin{gathered}
\frac{d}{dx}(x+y)^{2/3} = y'\\
\frac{2}{3\sqrt[3]{x+y}} \cdot (1+y') = y'\\
\frac{2}{3\sqrt[3]{x+y}} = (1- \frac{2}{3\sqrt[3]{x+y}}) y' \\
y' = \frac{2}{3\sqrt[3]{x+y} - 2}\\
y'|_{(4, 4)} = \frac{2}{3\sqrt[3]{4+4} - 2} = \frac{1}{2}
\end{gathered}
$$

52-54\. **Multiple tangent lines** Complete the following steps.
a. Find equations of all lines tangent to the curve at the given point.
b. Graph the tangent line on the given graph.
53\. $x+y^2-y=1; x=1$
>Solution
$$
\begin{aligned}
\frac{d}{dx}(x+y^2-y) &= \frac{d}{dx}(1) \\
1+2y\frac{dy}{dx} -\frac{dy}{dx} &= 0\\
\frac{dy}{dx} &= \frac{1}{1-2y} \\
x=1 \To 1+y^2-y&=1 \To y(y-1)=0 \To y=0, 1\\
\frac{dy}{dx} \lvert_{(1, 0)} &= \frac{1}{1-2\times 0} = 1\\
\frac{dy}{dx} \lvert_{(1, 1)} &= \frac{1}{1-2\times 1} = -1
\end{aligned}
$$
a. The equations of the tangent lines are $y-0=(1)(x-1)$ and $y-1=(-1)(x-1)$, or $y=x-1$ and $y=-x+2$.
b. Graph (53b).

57\. **Vertical tangent line**
a. Determine the points where the curve $x+y^2-y=1$ has a vertical tangent line (see Exercise 53).
b. Does the curve have any horizontal tangent lines. Explain.
>Solution
a. From *Exercise 53*, we have $\dfrac{dy}{dx} = \dfrac{1}{1-2y}$. To have a vertical tangent line, let the denominator of $\dfrac{1}{1-2y}$ be zero.
$$
\begin{aligned}
1-2y &= 0 \To y=\frac{1}{2}\\
x+y^2-y&=1 \To x= \frac{5}{4}
\end{aligned}
$$
At point $(\frac{5}{4}, \frac{1}{2})$, the curve has a vertical tangent line.
b. To have a horizontal tangent line, let $\dfrac{1}{1-2y} = 0$. As there is no solution for the equation, there is no horizontal tangent line.

73\. Cobb-Douglas production function The output of an economic system $Q$, subject to two inputs, such as labor $L$ and captial $K$, is often modeled by the Cobb-Douglas production function $Q=cL^aK^b$. When $a+b=1$, the case is called constant returns to scale. Suppose $Q= 1280, a=\frac{1}{3}, b=\frac{2}{3}$ and $c=40$.
a. Find the rate of change of captical with respect to labor $dK/dL$.
>Solution
$$
\begin{aligned}
Q=1280, &a=\frac{1}{3}, b=\frac{2}{3}, c=40 \To 1280=40L^{1/3}K^{2/3} \\
\frac{d}{dL}(1280) &= 40(\frac{1}{3}L^{-2/3}K^{2/3} + \frac{2}{3}L^{1/3}K^{-1/3}\cdot \frac{dK}{dL})\\
0 &= \frac{40}{3}L^{-2/3}K^{2/3} + \frac{80}{3}L^{1/3}K^{-1/3}\cdot \frac{dK}{dL} \\
L^{-1}K + 2\frac{dK}{dL} &= 0\\
\frac{dK}{dL} &= -\frac{K}{2L}
\end{aligned}
$$

b. Evaluate the derivative in part (a) with $L=8$ and $K=64$.
>Solution
$L=8, K=64 \To \dfrac{dK}{dL} = -\frac{64}{2\times 8} = -4$.

77-79\. Use implicit differentiation if needed to find $dy/dx$ for each equation of the following pairs. Use the derivatives to explain why the families of curves form orthogonal trajectories.
$y=mx; x^2+y^2=a^2$, when $m$ and $a$ are constants.
>Solution
$$
\begin{aligned}
&\text{(1) } y =mx \To \frac{dy}{dx} = \frac{d}{dx}(mx) = m = \frac{y}{x}\\
&\text{(2) } x^2+y^2=a^2 \To \frac{d}{dx}(x^2+y^2)=\frac{d}{dx}(a^2)\\
&2x + 2y \cdot \frac{dy}{dx} = 0\\
&\frac{dy}{dx} = -\frac{x}{y}
\end{aligned}
$$
For any intersection point $(x, y)$, we have $\frac{y}{x}$ and $-\frac{x}{y}$ that are negative reciprocals.
