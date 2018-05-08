### Section 5.1 Approximating Areas Under Curves

+ Area under a Velocity Curve
+ Approximating Areas by Riemann Sums
  + Riemann Sum (Left, Right and Midpoint)
  + Sigma (Summation) Notation
  + Riemann Sums Using Sigma Notation

#### Homework
p336: 5, 9, 10a, 13, 15, 19, 21, 25, 31, 34, 37, 39, 41a-d, 42a-c, 47, 51, 55, 59, 67

5\. Suppose the interval $[1, 3]$ is partitioned into $n = 4$ subintervals. What is the subinterval length $\Delta x$? List the grid points $x_0, x_1, x_2, x_3$, and $x_4$. Which points are used for the left, right, and midpoint Riemann sums?
>Solution
$\Delta x = \frac{3-1}{4} = \frac{1}{2}$, $x_k=a + k\Delta x$, for $k=0, 1, 2, 3, 4$
$x_0=1, x_1=1.5, x_2=2, x_3=2.5, x_4=3$
$x_0, x_1, x_2, x_3$ will be used for left Riemann sums.
$x_1, x_2, x_3, x_4$ will be used for right Riemann sums.
$1.25, 1.75, 2.25, 2.75$ will be used for midpoint Riemann sums.

9\. Approximating displacement The velocity in feet/second of an object moving along a line is given by $v = 3t^2 + 1$ on the interval $0 \les t \les 4$.
a. Divide the interval $[0, 4]$ into $n = 4$ subintervals, $[0, 1], [1, 2], [2, 3]$ and $[3, 4]$. On each subinterval, assume the object moves at a constant velocity equal to the value of $v$ evaluated at the midpoint of the subinterval and use these approximations to estimate the displacement of the object on $[0, 4]$ (see part (a) of the figure).
b. Repeat part (a) for $n = 8$ subintervals (see part (b) of the figure).
>Solution
The length of each subinterval is $\Delta t = \frac{4-0}{n} = \frac{4}{n}$. The value of $t^*_k$ for midpoint Riemann sum is $t^*_k = 0 + (k-\frac{1}{2})\Delta t$. The displacement of the object on $[0, 4]$ is the midpoint Riemann sum, that is
$$
\begin{aligned}
s(t) &= \sum^n_{k=1}v(t^*_k)\Delta t\\
&= \sum^n_{k=1}[3(k-\frac{1}{2})^2 (\Delta t^2) + 1]\cdot \Delta t\\
&= \sum^n_{k=1}[3(\Delta t)^3\cdot \frac{(2k-1)^2}{2}  + \Delta t]\\
&= 3(\frac{4}{n})^3 \cdot (\frac{1}{2})^2 + \frac{4}{n} + 3(\frac{4}{n})^3 \cdot (\frac{3}{2})^2 + \frac{4}{n} + \cdots + 3(\frac{4}{n})^3 \cdot (\frac{2n-1}{2})^2 + \frac{4}{n}\\
&= \frac{48}{n^3}[1^2+3^2 + \cdots + (2n-1)^2] + \frac{4}{n} \cdot n\\
&= \frac{48}{n^3}[4(1^2+2^2+\cdots+n^2)-4(1+2+\cdots + n) + 1+1+\cdots +1] +4\\
&= \frac{192}{n^3}\cdot\frac{n(n+1)(2n+1)}{6} - \frac{192}{n^3}\cdot \frac{n(n+1)}{2} + \frac{48}{n^3} \cdot n + 4\\
&= \frac{32(n+1)(2n+1)}{n^2} - \frac{96(n+1)}{n^2} + \frac{48}{n^2} + 4\\
&= 68-\frac{16}{n^2}
\end{aligned}
$$
When $n=4$, $s(4) = 67$; when $n=8$, $s(4) = 67.75$.

10\. **Approximating displacement** The velocity in feet/second of an object  moving along a line is given by $v = \sqrt{10t}$ on the interval $1\les t \les 7$.
a. Divide the interval $[1, 7]$ into $n = 3$ subintervals, $[1, 3], [3, 5]$ and $[5, 7]$. On each subinterval, assume the object moves at a constant velocity equal to the value of $v$ evaluated at the midpoint of the subinterval and use these approximations to estimate the displacement of the object on $[1, 7]$ (see part (a) of the figure).
>Solution
The length of each subinterval is $\Delta t = \frac{7-1}{n} = \frac{6}{n}$. The value of $t^*_k$ for midpoint Riemann sum is $t^*_k = 1 + (k-\frac{1}{2})\Delta t$. The displacement of the object on $[1, 7]$ is the midpoint Riemann sum, that is
$$
\begin{aligned}
s(t) &= \sum^n_{k=1}v(t^*_k)\Delta t\\
&=\sum^n_{k=1}\sqrt{10(1+\frac{2k-1}{2}\cdot \frac{6}{n})} \cdot \frac{6}{n}\\
&=\sum^n_{k=1}\frac{6\sqrt {10}}{n}\cdot \sqrt{\frac{6k+n-3}{n}}
\end{aligned}
$$
When $n=3$, $s(t) = 2\sqrt{10}\cdot (\sqrt 2 + \sqrt 4 + \sqrt 6)\approx 37.09$

11–16\. Approximating displacement The velocity of an object is given by the following functions on a specified interval. Approximate the displacement of the object on this interval by subdividing the interval into the indicated number of subintervals. Use the left endpoint of each subinterval to compute the height of
the rectangles.
13\. $v=\frac{1}{2t+1} (m/s)$, for $0  \les t \les 8; n=4$
>Solution
The length of each subinterval is $\Delta t = \frac{8-0}{4} = 2$. The value of $t^*_k$ for left Riemann sum is $t^*_k = 0 + (k-1)\Delta t = 2(k-1)$. The displacement of the object on $[0, 8]$ is the midpoint Riemann sum, that is
$$
\begin{aligned}
s(t) &= \sum^n_{k=1}v(t^*_k)\Delta t\\
&= \sum^n_{k=1}2\cdot \frac{1}{2\cdot 2(k-1) + 1}\\
&= \sum^n_{k=1}\frac{2}{4k-3}\\
&=\frac{2}{4\cdot 1 -3} + \frac{2}{4\cdot 2-3} + \frac{2}{4\cdot 3 -3} + \frac{2}{4\cdot 4 -3}\\
&= 2+ \frac{2}{5} + \frac{2}{9} + \frac{2}{13} \approx 2.78m
\end{aligned}
$$

15\. $v=4\sqrt{t+1}(mi/hr)$, for $0 \les t \les 15; n=5$
>Solution
The length of each subinterval is $\Delta t = \frac{15-0}{5} = 3$. The value of $t^*_k$ for left Riemann sum is $t^*_k = 0 + (k-1)\Delta t = 3(k-1)$. The displacement of the object on $[0, 15]$ is the midpoint Riemann sum, that is
$$
\begin{aligned}
s(t) &= \sum^n_{k=1}v(t^*_k)\Delta t\\
&= \sum^n_{k=1}3\cdot 4\sqrt{3k-3+1}\\
&= \sum^n_{k=1}12\sqrt{3k-2}\\
&= 12(\sqrt{1} + \sqrt{4} + \sqrt{7}  + \sqrt{10} + \sqrt{13})
&\approx 148.96m
\end{aligned}
$$

19–26\. Left and right Riemann sums Complete the following steps for the given function, interval, and value of $n$.
a. Sketch the graph of the function on the given interval.
b. Calculate $\Delta x$ and the grid points $x_0, x_1, \cdots x_n$.
c. Illustrate the left and right Riemann sums. Then determine which Riemann sum underestimates and which sum overestimates the area under the curve.
d. Calculate the left and right Riemann sums.
19\. $f(x)=x+1$ on $[0, 4]; n=4$
>Solution
a. Graph (19).
b. $\Delta x = \frac{4-0}{4}=1$
$x_k=a + k\Delta x$, for $k=0, 1, 2, 3, 4$
$x_0=0, x_1=1, x_2=2, x_3=3, x_4=4$
c. Graph (19c). The left Riemann sum underestimates the area and the right Riemann sum overestimates the area.
d. The left Riemann sum is
$$
\begin{aligned}
&f(x_0)\Delta x + f(x_1)\Delta x + f(x_2)\Delta x + f(x_3)\Delta x\\
&=1\cdot 1 + 2\cdot 1 + 3\cdot 1 + 4\cdot 1=10
\end{aligned}
$$
The right Riemann sum is
$$
\begin{aligned}
&f(x_1)\Delta x + f(x_2)\Delta x + f(x_3)\Delta x + f(x_4)\Delta x\\
&=2\cdot 1 + 3\cdot 1 + 4\cdot 1 + 5\cdot 1=14
\end{aligned}
$$


21\. $f(x)=\cos x$ on $[0, \frac{\pi}{2}]; n=4$
>Solution
a. Graph (21).
b. $\Delta x = \frac{\frac{\pi}{2}-0}{4}=\frac{\pi}{8}$
$x_k=a + k\Delta x$, for $k=0, 1, 2, 3, 4$
$x_0=0, x_1=\frac{\pi}{8}, x_2=\frac{\pi}{4}, x_3=\frac{3\pi}{8}, x_4=\frac{\pi}{2}$
c. Graph (21c). The left Riemann sum overestimates the area and the right Riemann sum underestimates the area.
d. The left Riemann sum is
$$
\begin{aligned}
&f(x_0)\Delta x + f(x_1)\Delta x + f(x_2)\Delta x + f(x_3)\Delta x\\
&=\cos (0)\cdot \frac{\pi}{8} + \cos (\frac{\pi}{8})\cdot \frac{\pi}{8} +\cos (\frac{\pi}{4})\cdot \frac{\pi}{8} +\cos (\frac{3\pi}{8})\cdot \frac{\pi}{8} \\
&\approx 1.18
\end{aligned}
$$
The right Riemann sum is
$$
\begin{aligned}
&f(x_1)\Delta x + f(x_2)\Delta x + f(x_3)\Delta x + f(x_4)\Delta x\\
&=\cos (\frac{\pi}{8})\cdot \frac{\pi}{8} +\cos (\frac{\pi}{4})\cdot \frac{\pi}{8} +\cos (\frac{3\pi}{8})\cdot \frac{\pi}{8} + \cos (\frac{\pi}{2})\cdot \frac{\pi}{8}\\
&\approx 0.79
\end{aligned}
$$

25\. $f(x)=e^{\frac{x}{2}}$ on $[1, 4]; n=6$
a. Graph (25).
b. $\Delta x = \frac{4-1}{6}=0.5$
$x_k=a + k\Delta x$, for $k=0, 1, 2, 3, 4, 5, 6$
$x_0=1, x_1=1.5, x_2=2, x_3=2.5, x_4=3, x_5=3.5, x_6=4$
c. Graph (25c). The left Riemann sum underestimates the area and the right Riemann sum overestimates the area.
d. The left Riemann sum is
$$
\begin{aligned}
&f(x_0)\Delta x + f(x_1)\Delta x + \cdots + f(x_5)\Delta x\\
&=0.5(e^{0.5} + e^{0.75} + e^{1} + e^{1.25} + e^{1.5} + e^{1.75})\\
&\approx 10.11
\end{aligned}
$$
The right Riemann sum is
$$
\begin{aligned}
&f(x_1)\Delta x + f(x_2)\Delta x + \cdots + f(x_6)\Delta x\\
&=e^{0.75} + e^{1} + e^{1.25} + e^{1.5} + e^{1.75}+e^{2} \\
&\approx 12.98
\end{aligned}
$$

29–34\. **Midpoint Riemann sums** Complete the following steps for the given function, interval, and value of $n$.
a. Sketch the graph of the function on the given interval.
b. Calculate $\Delta x$ and the grid points $x_0, x_1, \cdots x_n$.
c. Illustrate the midpoint Riemann sums by sketching the appropriate rectangles.
d. Calculate the midpoint Riemann sums.

31\. $f(x)=\sqrt x$ on $[1, 3]; n=4$
>Solution
a. Graph (31).
b. $\Delta x = \frac{3-1}{4}=0.5$
$x_k=a + k\Delta x$, for $k=0, 1, 2, 3, 4$
$x_0=1, x_1=1.5, x_2=2, x_3=2.5, x_4=3$
c. Graph (31c).
d. Let $x^*_k$ be kth midpoint, $x^*_1 = 1.25, x^*_2 = 1.75, x^*_3 = 2.25, x^*_4 = 2.75$. The midpoint Riemann sum is
$$
\begin{aligned}
&f(x^*_1)\Delta x + f(x^*_2)\Delta x + f(x^*_3)\Delta x + f(x^*_4)\Delta x\\
&=0.5(\sqrt{1.25} + \sqrt{1.75} + \sqrt{2.25} + \sqrt{2.75})\\
&\approx 2.80
\end{aligned}
$$

34\. $f(x)=4-x$ on $[-1, 4]; n=5$
>Solution
a. Graph (34).
b. $\Delta x = \frac{4-(-1)}{5}=1$
$x_k=a + k\Delta x$, for $k=0, 1, 2, 3, 4, 5$
$x_0=-1, x_1=0, x_2=1, x_3=2, x_4=3, _5=4$
c. Graph (34c).
d. Let $x^*_k$ be kth midpoint, $x^*_1 = -0.5, x^*_2 = 0.5, x^*_3 = 1.5, x^*_4 = 2.5, x^*_5 = 3.5$. The midpoint Riemann sum is
$$
\begin{aligned}
&f(x^*_1)\Delta x + f(x^*_2)\Delta x + f(x^*_3)\Delta x + f(x^*_4)\Delta x\\
&=(4-(-0.5)) + (4-0.5) + (4-1.5) + (4-2.5) + (4-3.5)\\
&=12.5
\end{aligned}
$$

37\. **Displacement from a table of velocities** The velocities (in miles>hour) of an automobile moving along a straight highway over a two-hr period are given in the following table.
| t(hr)    | 0  |0.25| 0.5|0.75|1   |1.25|1.5 |1.75| 2  |
|:--------:|:--:|----|:--:|----|:--:|----|:--:|----|:--:|
| v(mi/hr) | 50 | 50 | 60 | 60 | 55 | 65 | 50 | 60 | 70 |
a. Sketch a smooth curve passing through the data points.
b. Find the midpoint Riemann sum approximation to the displacement on $[0, 2]$ with $n = 2$ and $n = 4$.
>Solution
a. Graph (37).
b. When $n=2$, $\Delta t=\frac{2-0}{2}=1$ and $t_k=0+k\Delta t$ for $k=0, 1, 2$; $t_0=0,t_1=1,t_2=2$. Let $t^*_k$ be the kth midpoint, $t^*_1=0.5, t^*_2=1.5$. The midpoint Riemann sum is
$$
\begin{aligned}
&v(t^*_1)\Delta t + v(t^*_2)\Delta t\\
&=v(0.5) + v(1.5) = 60 + 50 = 110
\end{aligned}
$$
When $n=4$, $\Delta t=\frac{2-0}{4}=0.5$ and $t_k=0+k\Delta t$ for $k=0, 1, 2, 3, 4$; $t_0=0,t_1=0.5,t_2=1,t_3=1.5,t_4=2$. Let $t^*_k$ be the kth midpoint, $t^*_1=0.25, t^*_2=0.75, t^*_3=1.25, t^*_4=1.75$. The midpoint Riemann sum is
$$
\begin{aligned}
&v(t^*_1)\Delta t + v(t^*_2)\Delta t + v(t^*_3)\Delta t + v(t^*_4)\Delta t\\
&=0.5(v(0.25) + v(0.75) + v(1.25) + v(1.75))\\
&=0.5(50+60+65+60)= 117.5
\end{aligned}
$$

39\. **Sigma notation** Express the following sums using sigma notation. (Answers are not unique.)
a. $1+2+3+4+5$ &emsp; b. $4+5+6+7+8+9$
c. $1^2+2^2+3^2+4^2$ &emsp; d. $1+\frac{1}{2}+\frac{1}{3}+\frac{1}{4}$
>Solution
$$
\begin{aligned}
1+2+3+4+5 &= \sum^5_{k=1}k\\
4+5+6+7+8+9 &= \sum^6_{k=1}(k+3)\\
1^2+2^2+3^2+4^2 &= \sum^4_{k=1}k^2\\
1+\frac{1}{2}+\frac{1}{3}+\frac{1}{4}&=\sum^4_{k=1}\frac{1}{k}\\
\end{aligned}
$$

41\. **Sigma notation** Evaluate the following expressions.
a. $\sum\limits^{10}_{k=1}k$ &emsp; b. $\sum\limits^6_{k=1}(2k+1)$ &emsp; c. $\sum\limits^4_{k=1}k^2$ &emsp; d. $\sum\limits^5_{n=1}(1+n^2)$
>Solution
$$
\begin{aligned}
\sum^{10}_{k=1}k &= \frac{10\cdot (10+1)}{2} = 55\\
\sum^6_{k=1}(2k+1) &= 2\cdot \frac{6\cdot (6+1)}{2} + 6 = 48\\
\sum^4_{k=1}k^2 &= \frac{4\cdot(4+1)\cdot(2\cdot 4+1)}{6} = 30\\
\sum^5_{n=1}(1+n^2) &= \frac{5\cdot(5+1)\cdot(2\cdot 5+1)}{6} + 5 = 60
\end{aligned}
$$


42\. **Evaluating sums** Evaluate the following expressions by two methods. (i) Use Theorem 5.1. (ii) Use a calculator.
a. $\sum\limits^{45}_{k=1}k$ &emsp; b. $\sum\limits^{45}_{k=1}(5k-1)$ &emsp; c. $\sum\limits^{75}_{k=1}(2k^2)$
>Solution
$$
\begin{aligned}
\sum^{45}_{k=1}k &= \frac{45 \cdot (45+1)}{2} = 1035\\
\sum^{45}_{k=1}(5k-1) &= 5\cdot \frac{45 \cdot (45+1)}{2} - 45 = 5130\\
\sum^{75}_{k=1}(2k^2) &= 2\cdot \frac{75 \cdot (75+1) \cdot (2\cdot 75 + 1)}{6} = 286900
\end{aligned}
$$

47–52\. **Approximating areas with a calculator** Use a calculator and right Riemann sums to approximate the area of the region described. Present your calculations in a table showing the approximations for $n = 10, 30, 60$, and $80$ subintervals. Comment on whether your approximations appear to approach a limit.
47\. The region bounded by the graph of $f(x) = 4 - x^2$ and the x-axis on the interval $[-2, 2]$.
>Solution
$\Delta x=\frac{2-(-2)}{n}=\frac{4}{n}$, $x^*_k=-2+\frac{4k}{n}$. The right Riemman sum is
$$
A_n = \sum^n_{k=1}f(x^*_k)\Delta x = \sum^n_{k=1}[4-(-2+(\frac{4k}{n})^2)] \cdot \frac{4}{n}
$$

| n | 10  | 30  | 60 | 80 |
|---|-----|-----|----|----|
| $A_n$ | 10.56 | 10.6548 | 10.6637 | 10.665 |
It appreas that $A_n$ is approaching $10\frac{2}{3}$.

51\. The region bounded by the graph of $f(x) = \ln x$ and the x-axis on the interval $[1, e]$.
>Solution
$\Delta x=\frac{e-1}{n}$, $x^*_k=1+\frac{k(e-1)}{n}$. The right Riemman sum is
$$
A_n = \sum^n_{k=1}f(x^*_k)\Delta x = \sum^n_{k=1}\ln(1+\frac{k(e-1)}{n}) \cdot \frac{e-1}{n}
$$

| n | 10  | 30  | 60 | 80 |
|---|-----|-----|----|----|
| $A_n$ | 1.08436 | 1.02847 | 1.01428 | 1.01071 |
It appreas that $A_n$ is approaching $1$.


55–58. **Sigma notation for Riemann sums** Use sigma notation to write the following Riemann sums. Then evaluate each Riemann sum using Theorem 5.1 or a calculator.
55\. The right Riemann sum for $f(x)=x+1$ on $[0, 4]$ with $n=50$
>Solution
$\Delta x = \frac{4-0}{50} = \frac{2}{25}$, $x^*_k=0+k\Delta x = \frac{2k}{25}$ The right Riemman sum is
$$
\begin{aligned}
\sum^{50}_{k=1}f(x^*_k)\Delta x &= \sum^{50}_{k=1}\frac{2}{25}(\frac{2k}{25}+1)\\
&=\sum^{50}_{k=1}(\frac{4}{625}k + \frac{2}{25})\\
&=\frac{4}{625} \cdot \frac{50\cdot (50+1)}{2} + \frac{2}{25} \cdot 50 = \frac{304}{25}
\end{aligned}
$$

59–62\. **Identifying Riemann sums** Fill in the blanks with right, left, or midpoint; an interval; and a value of $n$. In some cases, more than one answer may work.
59\. $\sum\limits^4_{k=1}f(1+k)\cdot 1$ is a __right__ Riemann sum for $f$ on the interval __$[1, 5]$__ with __$n=4$__.

67\. **Displacement from a velocity graph** Consider the velocity function for an object moving along a line (see figure).
a. Describe the motion of the object over the interval $[0, 6]$.
b. Use geometry to find the displacement of the object between $t = 0$ and $t = 2$.
c. Use geometry to find the displacement of the object between $t = 2$ and $t = 5$.
d. Assuming that the velocity remains $10 m/s$, for $t \ges 5$, find the function that gives the displacement between $t = 0$ and any time $t \ges 5$.
>Solution
a. The velocity of the object steadily increases from $0m/s$ to $20m/s$ in the first second, stays at $20m/s$ from 1s to 3s, steadily decreases from $20 m/s$ to $10m/s$ from 3s to 5s and finally stays at $10m/s$ after 5s.
b. $s_{0-2} = \frac{1}{2} \cdot (1-0) \cdot 20 + (2-1) \cdot 20 = 30m$.
c. $s_{2-5} = (3-2) \cdot 20 + \frac{1}{2} \cdot (10+20) \cdot (5-3) = 50m$.
d. $s(t) = s_{0-2} + s_{2-5} + (t-5) \cdot 10 = 10t+30$
