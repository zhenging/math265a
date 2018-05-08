### Section 1.0 Functions
pg51: 1a,c,e,f, 2-5, 7a,b,c 10, 12, 13a,c, 15a,d, 16a,c, 17, 20-23, 27, 29, 30a, 33, 35, 37, 40, 45, 48

1\. **Explain why or why not** Determine whether the following statements are true and give an explanation or counterexample?
a. A function could have the property that $f(-x) = f(x)$, for all $x$.
c. If $f$ is a linear function of the form $f(x)=mx+b$, then $f(u+v) = f(u) + f(v)$, for all $u$ and $v$.
e. The set ${x:|x+3| > 4}$ can be drawn on the number line without lifting your pencil.
f. $\log_{10}(xy) = ({\log_{10}x})({\log_{10}y})$.
>Solution
a. True. When $f(x)$ is an even function, the statement holds.
c. False. The statement is true only if $b$ is equal to $0$.
$$
\begin{aligned}
f(u + v) &= m(u+v) + b \\
f(u) + f(v) &= (mu + b) + (mv + b) = m(u+v) + 2b
\end{aligned}
$$
In order for $f(u+v) = f(u) +f(v)$, it follows that
$$
m(u+v) + b = m(u+v) + 2b \To b = 0
$$
e. False. When $x+3>0$, $x+3>4$, we have $x>1$; When $x+3<0$, $-x-3>4$, we have $x<-7$. Therefore the set is the union of two disjoint intervals $(-\infty, 7)$ and $x>1$.
f. False. $\log_{10}(xy) = {\log_{10}x} + {\log_{10}y}$, provided both $x>0$ and $y>0$

2\. **Domain and range** Find the domain and range of the following functions.
a. $f(x) = x^5 + \sqrt{x}$ &emsp; b. $g(y) = \dfrac{1}{y-2}$ &emsp; c. $h(z) = \sqrt{z^2-2z-3}$
>Solution
a. The domain is $\{x \mid x \ges 0\}$ and the range is $\{f(x) \mid f(x) \ges 0\}$.
b. The domain is $\{y \mid y \ne 2\}$ and the range is $\{g(y) \mid g(y) \ne 0\}$.
c. Because $z^2-2z-3 \ges 0$, it follows that
$$
\begin{gathered}
z^2-2z-3 \ges 0 \\
(z-3)(z+1)\ges 0 \\
z-3 \ges 0 \quad\&\quad z+1 \ges 0 \To z \ges 3\\
\text{or} \\
z-3 \les 0 \quad\&\quad z+1 \les 0 \To z \les -1
\end{gathered}
$$
Therefore the domain is $\{z \mid z \ges 3 \text{ or } z \les -1\}$ and the range is $\{h(z) \mid h(z) \ges 0\}$.

3\. **Equations of limits** Find an equation of the lines with the following properties. Graph the line.
a. The line passing through the points $(2, -3)$ and $(4, 2)$.
b. The line with slope $\frac{3}{4}$ and x-intercept $(-4, 0)$.
c. The line intercepts $(4, 0)$ and $(0, -2)$.
>Solution
a. The slope of the line is $\frac{2-(-3)}{4-2} = \frac{5}{2}$. The equation is $\frac{y-2}{x-4} = \frac{5}{2}$ or $y=\frac{5}{2}x - 8$.
b. The equation is $y-0 = \frac{3}{4}(x+4)$ or $y = \frac{3}{4}x + 3$.
c. The slope of the line is $\frac{-2-0}{0-4} = \frac{1}{2}$. The equation is $y = \frac{1}{2}x-2$.

4\. **Piecewise linear functions** The parking costs in a city garage are $\$2.00$ for the first half hour and $\$1.00$ for each additional half hour. Graph the function $C= f(t)$ that gives the cost of parking for $t$ hours, where $0 \les t \les 3$.
>Solution
Graph (4). The equation for $C$ is as follows:
$$
C = \begin{cases}
2 & \text{if } 0 \les t \les 1/2 \\
3 & \text{if } 1/2 \lt t \les 1 \\
4 & \text{if } 1 \lt t \les 3/2 \\
5 & \text{if } 3/2 \lt t \les 2 \\
6 & \text{if } 2 \lt t \les 5/2 \\
7 & \text{if } 5/2 \lt t \les 3
\end{cases}
$$

5\. **Graph absolute value** Consider the function $f(x)=2(x-|x|)$. Express the function in two pieces without using the absolute value. Then graph the function by hand. Use a graphing utility only to check your work.
>Solution
Graph (5).
$$
f(x) = \begin{cases}
0 & \text{if } x \ges 0 \\
4x & \text{if } x \lt 0
\end{cases}
$$

7\. **Graphing equations** Graph the following equations. Use a graphing utility only to check your work.
a. $2x-3y+10 = 0$
b. $y=x^2=2x-3$
c. $x^2+2x+y^2+4y+1=0$
d. $x^2-2x=y^2-8y+5=0$
>Solution
Graph (7)

10\. **Intersection points** Graph the equations $y=x^2$ and $x^2+y^2-7y+8=0$. At what points do the curves intersect.
>Solution
Graph (10)
As $y = x^2$
$$
\begin{aligned}
y + y^2-7y+8 &= 0 \\
(y-3)^2 &= 1 \\
y = 4 \text{ or } y&=2 \To x=\pm 2 \text{ or } \pm \sqrt{2}
\end{aligned}
$$
The intersection points are $(2, 4), (-2, 4), (\sqrt{2}, 2), (-\sqrt{2}, 2)$.

12\. **Publishing cost.** A small publisher plans to spend \$1000 for advertising a paperback book and estimate the pricing cost is \$2.50 per book. The publisher will receive \$7 for each book sold.
a. Find the function $C=f(x)$ that gives the cost of producing $x$ books.
b. Find the function $R=g(x)$ that gives the revenue of selling $x$ books.
c. Graph the cost and revenue functions and find the number of books that must be sold for the publisher to break even.
>Solution
a. $C = 2.5x+1000$
b. $R = 7x$
c. Graph (12). In order for the publisher to break even, $C = R$.
$$
\begin{aligned}
2.5x + 1000 = 7x \\
x = 1000/4.5 \approx 223
\end{aligned}
$$

13\. **Shifting scaling** Starting with the graph of $f(x) =x^2$, plot the following functions. Use a graphing utility only to check your work.
a. $f(x+3)$ &emsp; c. $-f(3x)$
>Solution
Graph (13).

15\. **Composite functions** Let $f(x) = x^3$, $g(x)=\sin x$, and $h(x) = \sqrt{x}$.
a. Evaluate $h(g(\pi/2))$ &emsp; d. Find the domain of $g \circ f$
>Solution
a. $h(g(\pi/2)) = h(\sin (\pi/2)) = \sqrt{\sin (\pi/2)} = 1$
d. $g \circ f = g(f(x)) = g(x^3) = \sin {(x^3)}$. Its domain is $\{x \mid x \in \mathbb{R}\}$.

16\. **Composite functions** Find functions $f$ and $g$ such that $h = f \circ g$
a. $h(x) = \sin(x^2+1)$ &emsp; c. $h(x) = e^{\cos 2x}$
>Solution
a. $f(x) = \sin x$ and $g(x)=x^2+1$
c. $f(x) = e^x$ and $g(x)=\cos 2x$

17-20\. Simplifying difference quotients Evaluate and simplify difference quotients $\dfrac{f(x+h)-f(x)}{h}$ and $\dfrac{f(x)-f(a)}{x-a}$.
17\. $f(x) = x^2-2x$
>Solution
$$
\begin{aligned}
\frac{f(x+h)-f(x)}{h} &= \frac{(x+h)^2 - 2(x+h) - (x^2-2x)}{h}\\
&= \frac{x^2+2xh+h^2-2x-2h-x^2+2x}{h} \\
&= \frac{2xh+h^2-2h}{h} \\
&= 2x+h-2
\end{aligned}
$$

20\. $f(x) = \dfrac{7}{x+3}$
>Solution
$$
\begin{aligned}
\frac{f(x+h)-f(x)}{h} &= \frac{\frac{7}{x+h+3} - \frac{7}{x+3}
}{h}\\
&= \frac{\frac{7}{x+h+3} - \frac{7}{x+3}
}{h} \times \frac{(x+h+3)(x+3)}{(x+h+3)(x+3)}\\
&= \frac{7(x+3-x-h-3)}{h(x+h+3)(x+3)} \\
&= \frac{-7h}{h(x+h+3)(x+3)} \\
&= \frac{-1}{(x+h+3)(x+3)} \\
\end{aligned}
$$

22-23\. **Propertites pf logarithms and exponentials** Use properties of logarithms and exponential, not a calculator, for the following exercises.
22\. Solve the equation $48=6e^{4k}$ for $k$.
>Solution
$$
\begin{aligned}
48&=6e^{4k} \\
e^{4k} &= 8 \\
\ln (e^{4k}) &= \ln 8 \\
4k &= \ln 8 \\
k &= \frac{\ln 8}{4}
\end{aligned}
$$

23\. Solve the equation $\log (x^2) + 3\log x = \log 32$ for $x$. Does the answer depend on the base of the log in the equation
>Solution
$$
\begin{aligned}
\log (x^2) + 3\log x &= \log 32 \\
\log (x^2) + \log (x^3) &= \log 32 \\
\log (x^{2+3}) &= \log 32 \\
x^5 &= 32\\
x &= 2
\end{aligned}
$$
The answer does not depend on the base of the log in the equation.

27\. **Find inverse** *Find the inverse on the specified interval and express in the form $y=f^{-1}(x)$. Then graph $f^{-1}$.*
27\. $f(x) = x^2-4x+5$, for $x>2$
>**Solotion**
$$
\begin{aligned}
y &= x^2-4x+5 \\
y &= (x-2)^2 + 1 \\
x-2 &= \pm {\sqrt {y-1}}\\
x &= 2 + \sqrt{y-1} &\text{Because } x > 2\\
\end{aligned}
$$
Therefore the inverse function of $f(x)$ is $f^{-1}(x) = 2 +\sqrt {x-1}$.

29\. **Degrees and radians**
a. Convert $135^{\circ}$ to radian measure.
b. Conert $4\pi/5$ to degree measure.
>**Solotion**
a. $135^{\circ} = 135 \times (\pi/180) \text{radians} = 3\pi/4 \text{ radians}$
b. $4\pi/5 = 4/5 \times 180^{\circ} = 144^{\circ}$

30\. Graphing sin and cosine functions use shifts and scalings to graph the folliwng functions, and identity the amplitude and peroid.
a. $f(x) = 4\cos(x/2)$
>Solution
Graph (30). The amplitude is $4$ and the peroid is $4\pi$.

33\. **Matching** Match each function a-f with the corresponding graphs A-F.
a. $f(x) = -\sin x$ &emsp; b. $f(x) = \cos 2x$
c. $f(x) = \tan(x/2)$ &emsp; d. $f(x) = -\sec x$
e. $f(x) = \cot 2x$ &emsp; f. $f(x) = \sin x^2$
>Solution
a-> F &emsp; b->E &emsp; c->D
d-> B &emsp; e->C &emsp; f->A

34-35\. **Intersection Points** *Find the points at which the curves intersect on the given interval*
35\. $y=\sin x$ and $y=-\frac{1}{2}$ on $(0, 2\pi)$
>Solution
$$
\begin{aligned}
&\because \sin x = -\frac{1}{2} \\
&\therefore x = 2k\pi + \frac{7\pi}{6} \text{or } 2k\pi + \frac{11\pi}{6} \text{k is an integer} \\
&\because x \in (-\pi/2, \pi/2)\\
&\therefore x=\frac{7\pi}{6}, \frac{11\pi}{6}
\end{aligned}
$$

36-42\. **Inverse sines and cosines** With out using a calculator, evaluate or simplifythe following expressions.
37\. $\cos^{-1}{\frac{{\sqrt {3}}}{2}}$
>Solution
$\cos(\pi/6) = \frac{{\sqrt {3}}}{2} \To \cos^{-1}{\frac{{\sqrt {3}}}{2}} = \pi/6$

40\. $\cos(\cos^{-1}(-1))$
>Solution
$\cos(\cos^{-1}(-1)) = -1$

44-51\. **Right-triangle relationships** Draw a right triangle to simplify the give expressions. Assume $x>0$ and $0 \les \theta \les \pi/2$
45\. $\sin(\cos^{-1}(x/2))$
>Solution
Graph (45). Let $\cos \beta =x/2$, then $\cos^{-1}(x/2) = \beta$
$$
\begin{aligned}
&\sin(\cos^{-1}(x/2)) = \sin \beta \\
&\because \sin^2 \beta + \cos^2 \beta = 1 \\
&\therefore \sin \beta = \pm \sqrt{1-x^2/4} \\
&\because x > 0 \text{ and } \cos^{-1}(x/2) = \beta\\
&\therefore 0 \les \beta \lt \pi/2 \\
&\therefore \sin \beta \lt 0 \\
&\therefore \sin \beta = \sqrt{1-x^2/4} \\
\end{aligned}
$$
Therefore, $\sin(\cos^{-1}(x/2)) = \sqrt{1-x^2/4}$

48\. $\csc^{-1}(\sec \theta)$
>Solution
$\csc^{-1}(\sec \theta) = \pi/2 - \theta$. See Graph (48).
