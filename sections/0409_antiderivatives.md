### Section 4.9 Antiderivatives
pg320: 7, 11, 15, 17, 19, 22, 25, 29, 31, 35, 39, 41, 46, 47, 53, 59, 63, 65, 67, 70, 73, 75, 79, 83, 86, 89, 92, 97, 111, 114

7\. Give the antiderivatives of $\dfrac{1}{x}$, for $x>0$.
>Solution
$\dint (\frac{1}{x})dx = \ln x + C$

11-22\. **Finding antiderivatives** Find all the antiderivatives of the following functions. Check your work by taking derivatives.
11\. $f(x) = 5x^4$
>Solution
$\dint f(x)dx = x^5 + C$

15\. $P(x) = 3\sec^2 x$
>Solution
$\dint P(x)dx = 3\tan x + C$

17\. $f(y) = -\frac{2}{y^3}$
>Solution
$\dint f(y)dy = -2 \int y^{-3}dy
= -2 \cdot \frac{1}{-3 + 1}y^{-3 + 1} + C = \frac{1}{y^2} + C$

19\. $f(x)=e^x$
>Solution
$\dint f(x)dx = e^x + C$

22\. $F(t) = \pi$
>Solution
$\dint F(t)dt = \pi t + C$

23–36\. **Indefinite integrals** Determine the following indefinite integrals. Check your work by differentiation.
25\. $\int (4\sqrt x - \frac{4}{\sqrt x})dx$
>Solution
$$
\begin{aligned}
\int (4\sqrt x - \frac{4}{\sqrt x})dx &= 4\int x^{\frac{1}{2}}dx  -4\int x^{-\frac{1}{2}}dx\\
&= 4\cdot \frac{1}{\frac{1}{2} + 1}x^{\frac{1}{2} + 1} - 4\cdot \frac{1}{-\frac{1}{2} + 1}x^{-\frac{1}{2} + 1} + C\\
&= \frac{8}{3}\sqrt{x^3} - 8\sqrt x + C
\end{aligned}
$$

29\. $\int (3x^{\frac{1}{3}} + 4x^{-\frac{1}{3}} + 6)dx$
>Solution
$$
\begin{aligned}
\int (3x^{\frac{1}{3}} + 4x^{-\frac{1}{3}}  + 6)dx &= 3\int (x^{\frac{1}{3}})dx + 4\int (x^{-\frac{1}{3}})dx + \int (6)dx\\
&= 3 \cdot \frac{1}{\frac{1}{3} + 1}x^{\frac{1}{3} + 1} + 4 \cdot \frac{1}{-\frac{1}{3} + 1}x^{-\frac{1}{3} + 1} + 6x + C\\
&= \frac{9}{4}x^{\frac{4}{3}} + 6x^{\frac{2}{3}} + 6x + C
\end{aligned}
$$

31\. $\int (3x+1)(4-x)dx$
>Solution
$$
\begin{aligned}
\int (3x+1)(4-x)dx &= \int (-3x^2 + 11x + 4)dx\\
&= -x^3 + \frac{11}{2}x^2 + 4x + C
\end{aligned}
$$

35\. $\int \frac{4x^4-6x^2}{x}dx$
>Solution
$$
\begin{aligned}
\int \frac{4x^4-6x^2}{x}dx &= \int 4x^3dx  - \int 6xdx\\
&= x^4 - 3x^2 + C
\end{aligned}
$$

37–46\. **Indefinite integrals involving trigonometric functions** Determine the following indefinite integrals. Check your work by differentiation.
39\. $\int (\sec^2 x - 1)dx$
>Solution
$\dint (\sec^2 x - 1)dx = \tan x - x + C$

41\. $\int (\sec^2 \th + \sec \th \tan \th)d\th$
>Solution
$\dint (\sec^2 \th + \sec \th \tan \th)d\th = \tan \th + \sec \th + C$

46\.$\int \csc^2 6x dx$
>Solution
$\dint \csc^2 6x dx = -\frac{1}{6}\cot 6x + C$

47–58\. **Other indefinite integrals** Determine the following indefinite integrals. Check your work by differentiation.
47\. $\int \frac{1}{2y}dy$
>Solution
$\dint \frac{1}{2y}dy = \frac{1}{2}\ln |y| + C$

53\. $\int \dfrac{1}{x\sqrt{x^2 - 25}} dx$
>Solution
$\dint \dfrac{1}{x\sqrt{x^2 - 25}} dx = \frac{1}{5}\sec^{-1} |\frac{x}{5}| + C$

59–66\. **Particular antiderivatives** For the following functions $f$, find the antiderivative $F$ that satisfies the given condition.
59\. $f(x) = x^5 - 2x^{-2} + 1; F(1) = 0$
>Solution
$$
\begin{aligned}
\int f(x)dx &= \frac{x^6}{6} + \frac{2}{x} + x + C\\
F(1) &= \frac{1^6}{6} + \frac{2}{1} + 1 + C = 0 \To C=\frac{19}{6}\\
F(x) &= \frac{x^6}{6} + \frac{2}{x} + x - \frac{19}{6}
\end{aligned}
$$

63\. $f(x) = 8x^3-2x^{-2}; F(1)=5$
>Solution
$$
\begin{aligned}
\int f(x)dx &= 2x^4 + \frac{2}{x} + C\\
F(1) &= 2(1)^4 + \frac{2}{1} + C = 5 \To C=1\\
F(x) &= 2x^4 + \frac{2}{x} + 1
\end{aligned}
$$

65\. $f(y) = \frac{3y^3 + 5}{y}; F(1) = 3$
>Solution
$$
\begin{aligned}
\int f(y)dy &= y^3 + 5\ln |y| + C\\
F(1) &= 1^3 + 5\ln (1) + C = 3 \To C = 2\\
F(y) &= y^3 + 5\ln |y| + 2
\end{aligned}
$$

67–76\. **Solving initial value problems** Find the solution of the follow ing initial value problems.
67\. $f'(x) = 2x-3; f(0) = 4$
>Solution
$$
\begin{aligned}
\int f'(x)dx &= x^2 - 3x + C\\
f(0) &= 0^2-3 \cdot 0 + C = 4 \To C= 4\\
f(x) &= x^2 - 3x + 4
\end{aligned}
$$

70\. $h'(t) = 6\sin 3t; h(\frac{\pi}{6}) = 6$
>Solution
$$
\begin{aligned}
\int h'(t)dt &= -2\cos 3t + C\\
h(\frac{\pi}{6}) &= -2\cos (3\cdot \frac{\pi}{6}) + C = 6 \To C = 6\\
h(t) &= -2\cos 3t + 6
\end{aligned}
$$

73\. $y'(t) = \frac{3}{t} + 6; y(1) = 8$
>Solution
$$
\begin{aligned}
\int y'(t)dt &= 3\ln |t| + 6t + C\\
y(1) &= 3\ln (1) + 6\cdot 1 + C= 8 \To C = 2\\
y(t) &= 3\ln |t| + 6t + 2
\end{aligned}
$$

75\. $y'(\th) = \dfrac{\sqrt 2 \cos^3 \th + 1}{\cos^2 \th}; y(\dfrac{\pi}{4}) = 3$
>Solution
$$
\begin{aligned}
\int y'(\th)d\th &= \sqrt 2\int \cos \th d\th + \int \sec^2 \th d\th\\
&= \sqrt 2 \sin \th + \tan \th + C\\
y(\dfrac{\pi}{4}) &= \sqrt 2 \sin (\frac{\pi}{4}) + \tan(\frac{\pi}{4})+ C = 3 \To C=1\\
y(\th) &= \sqrt 2 \sin \th + \tan \th + 1
\end{aligned}
$$

77–82\. **Graphing general solutions** Graph several functions that satisfy the following differential equations. Then find and graph the particular function that satisfies the given initial condition.
79\. $f'(x) = 3x + \sin \pi x, f(2)=3$
>Solution
Graph (79).
$$
\begin{aligned}
\int f'(x)dx &= \frac{3}{2}x^2 - \frac{1}{\pi}\cos \pi x + C\\
f(2) &= \frac{3}{2}(2)^2 - \frac{1}{\pi}\cos 2\pi + C = 3 \To C=\frac{1}{\pi} - 3\\
f(x) &= \frac{3}{2}x^2 - \frac{1}{\pi}\cos \pi x + \frac{1}{\pi} - 3
\end{aligned}
$$

83–88\. **Velocity to position** Given the following velocity functions of an object moving along a line, find the position function with the given initial position. Then graph both the velocity and position functions.
83\. $v(t)=2t + 4; s(0)=0$
>Solution
Graph (83).
$$
\begin{aligned}
\int v(t)dt &= t^2 + 4t + C\\
s(0) &= 0^2 + 4 \cdot 0 + C = 0 \To C = 0\\
s(t) &= t^2 + 4t
\end{aligned}
$$

86\. $v(t) = 2\cos t; s(0)=0$
>Solution
Graph (86).
$$
\begin{aligned}
\int v(t)dt &= 2\sin t + C\\
s(0) &= 2\sin (0) + C = 0 \To C = 0\\
s(t) &= 2\sin t
\end{aligned}
$$

89–94\. **Acceleration to position** Given the following acceleration functions of an object moving along a line, find the position function with the given initial velocity and position.
89\. $a(t) = -32; v(0)=20, s(0) = 0$
>Solution
$$
\begin{aligned}
\int a(t)dt &= -32t + C_v\\
v(0) &= -32 \cdot 0 + C_v = 20 \To C_v = 20\\
v(t) &= -32t + 20\\
\int v(t)dt &= -16t^2 + 20t + C_s\\
s(0) &= -16 \cdot 0^2 + 20 \cdot 0 + C_s = 0 \To C_s = 0\\
s(t) &= -16t^2 + 20t
\end{aligned}
$$

92\. $a(t) = 2\cos t; v(0) = 1, s(0) = 0$
>Solution
$$
\begin{aligned}
\int a(t) &= 2\sin t + C_v\\
v(0) &= 2\sin (0) + C_v = 1 \To C_v = 1\\
v(t) &= 2\sin t + 1\\
\int v(t)dt &= -2\cos t + t + C_s\\
s(0) &= -2 \cos (0) + 0 + C_s = 0 \To C_s = 2\\
s(t) &= -2\cos t + t + 2
\end{aligned}
$$

97-100\. **Motion with gravity** Consider the following descriptions of the vertical motion of an object subject only to the acceleration due to gravity. Begin with the acceleration equation $a(t) = v'(t) = g$, where $g = -9.8 m/s^2$.
97\. A softball is popped up vertically (from the ground) with a velocity of $30 m/s$.
a. Find the velocity of the object for all relevant times.
>Solution
$$
\begin{aligned}
\int a(t)dt &= gt + C_v\\
v(0) &= g \cdot 0 + C_v = 30 \To C_v = 30\\
 v(t) &= -9.8t + 30
\end{aligned}
$$

b. Find the position of the object for all relevant times.
>Solution
$$
\begin{aligned}
\int v(t)dt &= -4.9t^2 + 30t + C_s\\
s(0) &= -4.9 \cdot 0^2 + 30 \cdot 0 + C_s = 0 \To C_s = 0\\
s(t) &= -4.9t^2 + 30t
\end{aligned}
$$

c. Find the time when the object reaches its highest point. What is the height?
>Solution
$$
\begin{aligned}
s'(t) &= -9.8t + 30 = 0 \To t = \frac{30}{9.8} \approx 3.06s\\
s(\frac{30}{9.8}) &\approx 45.92m
\end{aligned}
$$
The object reaches it highest point at 3.06s and the height is 45.92m.

d. Find the time when the object strikes the ground.
>Solution
$$
\begin{aligned}
s(t) &= -4.9t^2 + 30t = 0 \To t = 0, \frac{30}{4.9}(\approx 6.12)
\end{aligned}
$$
The object strikes the ground at 6.12s.

110–113\. **Functions from higher derivatives** Find the function $F$ that satisfies the following differential equations and initial conditions.
111\. $F''(x) = \cos x, F'(0) = 3, F(\pi) = 4$
>Solution
$$
\begin{aligned}
\int F''(x)dx &= \sin x + C_1\\
F'(0) &= \sin (0) + C_1 = 3 \To C_1 = 3\\
F'(x) &= \sin x + 3\\
\int F'(x)dx &= -\cos x + 3x + C_2\\
F(\pi) &= -\cos (\pi) + 3 \pi + C_2 = 4 \To C_2 = 3-3\pi\\
F(x) &= -\cos x + 3x + 3-3\pi
\end{aligned}
$$

114\. **Mass on a spring** A mass oscillates up and down on the end of a spring. Find its position $s$ relative to the equilibrium position if its acceleration is $a(t) = \sin (\pi t)$, and its initial velocity and position are $v(0) = 3$ and $s(0) = 0$, respectively.
>Solution
$$
\begin{aligned}
\int a(t)dt &= -\frac{1}{\pi}\cos (\pi t) + C_v\\
v(0) &= -\frac{1}{\pi}\cos (\pi \cdot 0) + C_v = 3 \To C_v = 3 + \frac{1}{\pi}\\
v(t) &= -\frac{1}{\pi}\cos (\pi t) + 3 + \frac{1}{\pi}\\
\int v(t)dt &= -\frac{1}{\pi^2}\sin (\pi t) + (3 + \frac{1}{\pi})t + C_s\\
s(0) &= -\frac{1}{\pi^2}\sin (\pi \cdot 0) + (3 + \frac{1}{\pi}) \cdot 0 + C_s = 0 \To C_s = 0\\
s(t) &= -\frac{1}{\pi^2}\sin (\pi t) + (3 + \frac{1}{\pi})t
\end{aligned}
$$
