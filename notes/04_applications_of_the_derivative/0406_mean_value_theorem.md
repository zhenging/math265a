### Section 4.6 Mean Value Theorem

+ Theorem 4.9 - Mean Value Theorem: $\dfrac{f(b)-f(a)}{b-a} = f'(c)$. (_Proof_)
+ Theorem 4.10 - Zero Derivative Implies Constant Function
+ Theorem 4.11 - Functions with Equal Derivatives Differ by a Constant
+ Theorem 4.12 - Intervals of Increase and Decrease. (_Proof_)

#### Homework
p288: 5, 7, 9, 13, 16, 17, 18, 19, 23, 29, 30, 33, 37

5\. Draw the graph of a function for which the conclusion of the Mean Value Theorem does not hold.
>Solution
Graph (5).

7-14\. **Rolle's Theorem** Determine whether Rolle's Theorem applies to the following functions on the given interval. If so, find the point(s) that are guaranteed to exist by Rolle's Theorem.
7\. $f(x) = x(x-1)^2; [0, 1]$
>Solution
1\. $f$ is a polynomial, it is continuous and differentiable everywhere.
2\. $f(0) = f(1) = 0$
3\. Rolle's Theorem applies in this case.
$$
\begin{aligned}
f'(x) &= (x-1)^2 + 2x(x-1)\\
&= 3x^2-4x+1\\
&= (3x-1)(x-1)\\
f'(x) &= 0 \To x=\frac{1}{3}, 1\\
x &\in (0, 1) \To x=\frac{1}{3} &\text{result}
\end{aligned}
$$

9\. $f(x)=\cos 4x; [\pi/8, 3\pi/8]$
>Solution
1\. $f$ is continuous and differentiable on $[\pi/8, 3\pi/8]$.
2\. $f(\frac{\pi}{8}) = f(\frac{3\pi}{8}) = 0$
3\. Rolle's Theorem applies in this case.
$$
\begin{aligned}
f'(x) &= -4\sin 4x\\
f'(x) &= 0 \To x=\frac{k\pi}{4} &\text{k is integer}\\
x &\in (\frac{\pi}{8}, \frac{3\pi}{8}) \To x=\frac{\pi}{4} &\text{result}
\end{aligned}
$$

<!-- pagebreak -->
13\. $g(x)=x^3-x^2-5x-3;[-1, 3]$
>Solution
1\. $f$ is a polynomial, it is continuous and differentiable everywhere.
2\. $f(-1) = f(3) = 0$
3\. Rolle's Theorem applies in this case.
$$
\begin{aligned}
f'(x) &= 3x^2-2x-5\\
&= (3x-5)(x+1)\\
f'(x) &= 0 \To x=\frac{5}{3}, -1\\
x &\in (-1, 3) \To x=\frac{5}{3} &\text{result}
\end{aligned}
$$

16\. Drag racer acceleration The fastest drag racers can reach a speed of $330 mi/hr$ over a quater-mile in $4.45$ seconds (from a standing start). Complete the following sentence about such a drag racer. At some point during the race, the maximum acceleration of the drag racer is at least ______ mi/hr/s.
>Solution
The avarage acceleration is $\frac{330 mi/hr}{4.45s} \approx 74.2 mi/hr/s$. The maximum acceleration of the drag ract is at least $74.2 mi/hr/s$.

17-24\. **Mean Value Theorem**
a. Determine whether the Mean Value Theorem applies to the following functions on the given interval $[a, b]$.
b. If so, find or approximate the points that are guaranteed to exist by the Mean Value Theorem.
c. Make a sketch of the function and the line that passes through $(a, f(a))$ and $(b, f(b))$. Mark the points $P$ (if they exist) at which the slope of the function equals the slope of the secant line. Then sketch the tangent line at $P$.
17\. $f(x)=7-x^2;[-1, 2]$
>Solution
$f$ is a polynomial, it is continuous and differentiable everywhere. The **MVT** applies. Graph (17).
$$
\begin{aligned}
f'(x) &= -2x\\
&= \frac{f(2)-f(-1)}{2-(-1)}\\
&= \frac{3-6}{3} = -1\\
&\To x= \frac{1}{2}
\end{aligned}
$$

<!-- pagebreak -->
18\. $f(x)=3\sin 2x;[0, \pi/4]$
>Solution
$f$ is continuous and differentiable on $[0, \pi/4]$. The **MVT** applies. Graph (18).
$$
\begin{aligned}
f'(x) &= 6\cos 2x\\
&= \frac{f(\frac{\pi}{4}) - f(0)}{\frac{\pi}{4} - 0}\\
&= \frac{3-0}{\frac{\pi}{4}} = \frac{12}{\pi}\\
&\To x=\frac{\cos^{-1} \frac{2}{\pi}}{2} \approx 0.44
\end{aligned}
$$

19\. $f(x)=e^x;[0, \ln 4]$
>Solution
$f$ is continuous and differentiable on $[0, \ln 4]$. The **MVT** applies. Graph (19).
$$
\begin{aligned}
f'(x) &= e^x\\
&= \frac{f(\ln 4)-f(0)}{\ln 4 - 0}\\
&= \frac{4-1}{\ln 4} = \frac{3}{\ln 4}\\
&\To x = \ln(\frac{3}{\ln 4})
\end{aligned}
$$

23\. $f(x)=2x^{1/3}; [-8, 8]$
>Solution
$f'(x) = \dfrac{2}{3} x^{-\frac{2}{3}} = \dfrac{2}{3\sqrt[3]{x^2}}$
$f$ is continuous on $[-8, 8]$, but is not differentiable at point $x=0$. The **MVT** does not applies.

29\. **Mean Value Theorem graphs** By visual inspection, locate all points on the graph at which the slop of the tangent lines equals the average rate of change of the function on the interval $[-4, 4]$. Graph (29).
>Solution
$f(-4) = 1, f(4) = 4 \To f'(x) = \frac{4-(-1)}{4-(-4)}=\frac{3}{8}$

30\. **Avalanche forecasting** Avalanche forecasters measure the *temperature gradient* $dT/dh$, which is the rate at which the temperature in a snowpack *T* changes with respect to its depth *h*. If the temperature gradient is large, it may lead to a weak layer in the snowpack. When these weak layers collapse, avalanches occur. Avalanche forecasters use the following rule of thumb: If $dT/dh$ exceeds *10^{\circ}C/m* anywhere in the snowpack, conditions are favorable for weak-layer formation, and the risk of avalanche increases. Assume the temperature function is continuous and differentiable.
a. An avalanche forecaster digs a snow pit and takes two temperature measurements. At the surface $(h = 0)$, the temperature is $-12^{\circ}C$. At a depth of $1.1 m$, the temperature is $2^{\circ}C$. Using the Mean Value Theorem, what can he conclude about the temperature gradient? Is the formation of a weak layer likely?
>Solution
The average temperature gradient is $\dfrac{2-(-12)}{1.1-0} = \dfrac{14}{1.1} \approx 12.73^{\circ}C/m$. The formation of a weak layer is likely.

b. One mile away, a skier finds that the temperature at a depth of $1.4 m$ is $-1^{\circ}C$, and at the surface, it is $-12^{\circ}C$. What can be concluded about the temperature gradient? Is the formation of a weak layer in her location likely?
>Solution
The average temperature gradient is $\frac{-1-(-12)}{1.4-0} = \frac{11}{1.4} \approx 7.86^{\circ}C/m$. The formation of a weak layer is unlikely.

c. Because snow is an excellent insulator, the temperature of snow-covered ground is often near $0^{\circ}C$. Furthermore, the surface temperature of snow in a particular area does not vary much from one location to the next. Explain why a weak layer is more likely to form in places where the snowpack is not too deep.
>Solution
With the same temperature change, the shallower the snow is, the greater the temperature gradient is. Thus a weak layer is more likely formed in shallow snowpack.

d. The term isothermal is used to describe the situation where all layers of the snowpack are at the same temperature (typically near the freezing point). Is a weak layer likely to form in isothermal snow? Explain.
>Solution
In this case the temperature gradient is $0^{\circ}C/m$. A weak layer is unlikely to form in isothermal snow.

33\. **Running pace** Explain why if a runner completes a 6.2-mi (10-km) race in 32 min, then he must have been running at exactly 11mi/hr at least twice in the race. Assume the runner's speed at the finish line is zero.
>Solution
The avarage pace of the runner is $\frac{6.2mi}{\frac{32}{60} hr} = 11.625mi/hr$. By the MVT, the runner's speed was $11.625mi/hr$ at once. By the intermediate theorem, all speeds in $[0, 11.625] mi/hr$ were reached. Because the initial and final speed was $0mi/hr$, the speed of $11mi/hr$ was reached at least twice.

37\. **Equal Derivatives** Verifty that the function $f(x) = \tan^2 x$ and $g(x) = \sec^2 x$ have the same derivative. What can you say about the difference $f-g$? Explain.
>Solution
$$
\begin{aligned}
f'(x) &= 2\tan x(\sec^2 x)\\
g'(x) &= 2\sec x(\sec x \tan x) = 2\tan x(\sec^2 x)\\
f(x) - g(x) &= -1
\end{aligned}
$$
$f$ and $g$ have the same derivative, and the difference $f-g$ is a constant ($1$).
