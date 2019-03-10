### Section 3.6 The Chain Rule

+ The Chain Rule ([Proof](../misc/chain_rule.html))
  + Version 1: $\dfrac{dy}{dx} = \dfrac{dy}{du} \cdot \dfrac{du}{dx}$
  + Version 2: $\dfrac{d}{dx}[f(g(x))] = f'(g(x))g'(x)$
+ Chain Rule for Powers

#### Homework
p187: 3, 19-37odd, 41, 47, 51, 57, 60, 71, 87

3\. Fill in the blanks. The derivative of $f(g(x))$ equals $f'$ evaluated at **g(x)** multiplied by $g'$ evaluated at **x**.

19-34\. **Version 2 of the Chain Rule** Use version 2 of the Chain Rule to calculated the derivatives of the following composite functions.
19\. $y=(3x^2+7x)^{10}$
>Solution
$y' = 10(3x^2+7x)^9 \cdot (6x+7) = 10(6x+7)(3x^2+7x)^9$

21\. $y=\sqrt {10x+1}$
>Solution
$y' = \frac{1}{2}(10x+1)^{-\frac{1}{2}} \cdot 10 = \dfrac{5}{\sqrt {10x+1}}$

23\. $y=5(7x^3+1)^{-3}$
>Solution
$y' = 5\cdot(-3(7x^3+1)^{-4} \cdot (21x^2)) = \dfrac{-315x^2}{(7x^3+1)^4}$

25\. $y=\sec(3x+1)$
>Solution
$y' = \sec(3x+1)\tan(3x+1) \cdot (3+0) = 3\sec(3x+1)\tan(3x+1)$

27\. $y=\tan e^x$
>Solution
$y' = \sec^2 e^x \cdot e^x = e^x \sec^2 e^x$

29\. $y=\sin (4x^3+3x+1)$
>Solution
$y' = \cos (4x^3+3x+1) \cdot (12x^2 + 3) = (12x^2 + 3)\cos (4x^3+3x+1)$

31\. $y=\sin (2\sqrt x)$
>Solution
$y' = \cos (2\sqrt x) \cdot \frac{1}{\sqrt x} = \dfrac{\cos (2\sqrt x)}{\sqrt x}$

33\. $y=(\sec x + \tan x)^5$
>Solution
$y' = 5(\sec x + \tan x)^4 \cdot (\sec x\tan x + \sec^2 x) = 5\sec x(\sec x + \tan x)^5$

35-36\. Similar-looking composite functions Two composite functions are given that look similar, but in fact are quite different. Identify the inner function $u=g(x)$ and the outer function $y=u(x)$; then evaluate $\frac{dy}{dx}$ using the Chain Rule.
35\. a. $y=\cos^3 x$ &emsp; b. $y=\cos x^3$
>Solution
a. Inner function $u=g(x)=\cos x$, outer function $y=u(x) = x^3$.
$$
\frac{dy}{dx} = 3\cos^2 x \cdot (-\sin x) = -3\sin x \cos^2 x
$$
b. Inner function $u=g(x)=x^3$, outer function $y=u(x) = \cos x$.
$$
\frac{dy}{dx} = -\sin x^3 \cdot (3x^2) = -3x^2\sin x^3
$$

37\. **Chain Rule using a table** Let $h(x) = f(g(x))$ and $p(x) = g(f(x))$. Use the table to compute the following derivatives.
a. $h'(3)$ &emsp; b. $h'(2)$ &emsp; c. $p'(4)$
d. $p'(2)$ &emsp; e. $h'(5)$
| x     | 1 | 2  | 3  | 4  | 5   |
|-------|---|----|----|----|-----|
| f(x)  | 0 | 3  | 5  | 1  | 0   |
| f'(x) | 5 | 2  | -5 | -8 | -10 |
| g(x)  | 4 | 5  | 1  | 3  | 2   |
| g'(x) | 2 | 10 | 20 | 15 | 20  |
>Solution
a. $h'(3) = f'(g(3))\cdot g'(3) = f'(1)\cdot 20 = 5\cdot 20 = 100$
b. $h'(2) = f'(g(2))\cdot g'(2) = f'(5)\cdot 10 = -10 \cdot 10 = -100$
c. $p'(4) = g'(f(4))\cdot f'(4) = g'(1)\cdot (-8) = 2 \cdot (-8) = -16$
d. $p'(2) = g'(f(2))\cdot f'(2) = g'(3)\cdot 2 = 20 \cdot 2 = 40$
e. $h'(5) = f'(g(5))\cdot g'(5) = f'(2)\cdot 20 = 2 \cdot 20 = 40$

39-41\. **Chain Rule for powers** Use the Chain Rule to find the derivative of the following functiuons.
41\. $y=(1+2\tan x)^{15}$
>Solution
$y' = 15(1+2\tan x)^{14} \cdot (0 + 2\sec^2 x) = 30\sec^2 x(1+2\tan x)^{14}$

43-54\. **Repeated use of the Chain Rule** Calculate the derivative of gthe following functions.
47\. $\sin(\sin(e^x))$
>Solution
$$
\begin{aligned}
\frac{d}{dx}(\sin(\sin(e^x))) &= \cos(\sin(e^x)) \cdot \frac{d}{dx}(\sin(e^x))\\
&= \cos(\sin(e^x)) \cos e^x \frac{d}{dx}(e^x)\\
&= e^x \cos e^x \cos(\sin(e^x))
\end{aligned}
$$

51\. $\sqrt{x + \sqrt x}$
>Solution
$$
\begin{aligned}
\frac{d}{dx}(\sqrt{x + \sqrt x}) &= \frac{1}{2\sqrt{x + \sqrt x}} \cdot \frac{d}{dx}(x + \sqrt x) \\
&= \frac{1 + \frac{1}{2 \sqrt x}}{2\sqrt{x + \sqrt x}} \\
&= \frac{2\sqrt x + 1}{4\sqrt{x^2 + x\sqrt x}}
\end{aligned}
$$

55-66\. **Combining rules** Use the Chain Rule combined with other differentiation rules to find the derivative of the following functions.
57\. $y= e^{x^2+1}\sin x^3$
>Solution
$$
\begin{aligned}
y' &= \frac{d}{dx}(e^{x^2+1}) \cdot \sin x^3 + e^{x^2+1} \cdot \frac{d}{dx}(\sin x^3) \\
&= \sin x^3 e^{x^2+1} \cdot \frac{d}{dx}(x^2+1) + e^{x^2+1} \cos x^3 \cdot \frac{d}{dx}(x^3) \\
&= 2x\sin x^3 e^{x^2+1} + 3x^2 e^{x^2+1} \cos x^3\\
&= xe^{x^2+1}(2\sin x^3 + 3x\cos x^3)
\end{aligned}
$$

60\. $y=\left(\dfrac{3x}{4x+3}\right)^5$
>Solution
$$
\begin{aligned}
y' &= 5\left(\frac{3x}{4x+3}\right)^4 \cdot \frac{d}{dx}(\frac{3x}{4x+3}) \\
&= 5\left(\frac{3x}{4x+3}\right)^4 \cdot \frac{3(4x+3)-3x(4)}{(4x+3)^2} \\
&= \frac{5(3x)^4}{(4x+3)^4} \cdot \frac{9}{(4x+3)^2} \\
&= \frac{3645x^4}{(4x+3)^6}
\end{aligned}
$$

68-72\. **Second derivatives** Find $\frac{d^2y}{dx^2}$ for the following functions.
71\. $y=e^{-2x^2}$
>Solution
$$
\begin{aligned}
y' &= e^{-2x^2} \cdot \frac{d}{dx}(-2x^2) \\
&= -4xe^{-2x^2}\\
y'' &= -4(1 \cdot e^{-2x^2} + x \cdot \frac{d}{dx}(e^{-2x^2}))\\
&= -4(e^{-2x^2} -4x^2e^{-2x^2}) \\
&= 4e^{-2x^2}(4x^2-1)
\end{aligned}
$$

87\. **Hours of daylight** The number of hours of daylight at any point on Earth fluctuates throughout the year. In the northern hemisphere, the shortest day is on the winter solstice and the longest day is on the summer solstice. At $40^{\circ}$ north latitude, the length of a day is approximated by
$$
D(t) = 12-3\cos \lb \frac{2\pi(t+10)}{365} \rb
$$
where $D$ is measured in hours and $0 \les t \les 365$ is measured in days, with $t=0$, with $t=0$ corresponding to January 1.
a. Approximately how much daylight is there on March 1 ($t=59$)?
b. Find the rate at which the daylight functions changes.
c. Find the rate at which the daylight function changes on March 1. Convert your answner to units of min/day and explain what this result means.
d. Graph function $y=D'(t)$ using a graphing utinity.
e. At what times of year is the length of day changing most rapidly? Least rapidly?
>Solution
a. $D(59) = 12-3\cos \lb \dfrac{2\pi(59+10)}{365} \rb \approx 10.88 hours$.
b. The rate of change is
$$
\begin{aligned}
D'(t) &= 3\sin \lb \dfrac{2\pi(t+10)}{365} \rb \cdot \frac{d}{dt}(\frac{2\pi(t+10)}{365})\\
&= 3\sin \lb \dfrac{2\pi(t+10)}{365} \rb \cdot \frac{2\pi}{365}\\
&= \frac{6\pi}{365}\sin \lb \dfrac{2\pi(t+10)}{365} \rb
\end{aligned}
$$
c. $D'(59) \approx 0.048 hour/day \To D'(59) \approx 2.88 min/day$. This means on March 1st, the days are getting longer by 2.88 minutes.
d. Graph (87d).
e. When $\sin \lb \dfrac{2\pi(t+10)}{365} \rb = 1, -1$, the length of day changes most rapidly; when $\sin \lb \dfrac{2\pi(t+10)}{365} \rb = 0$, the length of day changes least rapidly.
$$
\begin{aligned}
\sin \lb \dfrac{2\pi(t+10)}{365} \rb &= 1 \To t = 81.25 \\
\sin \lb \dfrac{2\pi(t+10)}{365} \rb &= -1 \To t=263.75 \\
\sin \lb \dfrac{2\pi(t+10)}{365} \rb &= 0 \To t=172.5, 355
\end{aligned}
$$
On Mar 22nd (t=81.25) and September 20th (t=263.75), the days changes most rapidly, and on June 21st (t=172.5) and December 21st (t=355), the days changes least rapidly.
