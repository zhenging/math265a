### Section 3.5 Derivatives as Rates of Change

+ One-Dimensional Motion
+ Position and Velocity
+ Speed and Acceleration
+ Free Fall (_Ex3_)
+ Growth Models (_Ex4_)
+ Average and Marginal Cost (_Ex5_)

#### Homework
p177: 4, 10, 13, 17, 18, 23, 27, 31, 35, 39, 45, 48, 51

4\. What is the difference between the **velocity** and **speed** of an object moving in a straight line?

10\. **Airline travel** The following figure shows that position function of an airliner on an out-and-back trip from Seattle to Minneapolis, where $s=f(t)$ is the number of ground miles from Seattle $t$ hours after take-off at 6:00 am. The plane returns to Seattle 8.5 hours later at 2:30 pm. Graph (10)
a. Calculate the average velocity of the airliner during the first 1.5 hours of the trip ($0 \les t \les 1.5$).
b. Calculate the average velocity of the airliner between 1:30 pm and 2:30 pm ($7.5 \les t \les 8.5$).
c. At what time(s) is the velocity 0? Give a plausible explanation.
d. Determine the velocity of the airliner at noon ($t=6$) and explain why the velocity is negative.
>Solution
a. $s(0) = 0$ and $s(1.5) = 600$, it follows $v_{av} = \dfrac{s(1.5)-s(0)}{1.5-0} = 400 \ miles/hour$.
b. $s(7.5) = 300$ and $s(8.5) = 0$, it follows $v_{av} = \dfrac{s(8.5)-s(7.5)}{8.5-7.5} = -300 \ miles/hour$.
c. The velocity is 0 from 9:00 am to 11:00 am ($3 \les  t \les 5$). During this period, the plane's position is not changing. In other words, the change of rate of position is 0.
d. The slope of the tangent line at $t=6$ is $\dfrac{800-1600}{7-5} = -400$. The velocity is $-400 \ miles/hour$. As the plane is on its way back, the position is decreasing along the time, the velocity is negative.

11-16\. **Position, velocity, and acceleration** Suppose the position of an object moving horizontally after $t$ seconds is given by the following function $s=f(t)$, where $s$ is measured in feet, with $s$? $0$ corresponding to positive right of the origin.
a. Graph the position function.
b. Find and graph the velocity function. When is the object stationary, moving to the right, and moving to the left?
c. Determine the velocity and acceleration of the object at $t=1$.
d. Determine the acceleration of the object when its velocity is zero.
13\. $f(t) = 2t^2-9t+12$; $0 \les  t \les 3$
>Solution
a. Graph (13a).
b. Graph (13b). The velocity function is $v(t) = f'(t) = 4t-9$
$$
\begin{cases}
\text{stationary } \To v(t) = 0 \To t= \frac{9}{4}\\
\text{moving right } \To v(t) > 0 \To \frac{9}{4} <t \les 3 \\
\text{moving left } \To v(t) < 0 \To 0 \les t < \frac{9}{4}
\end{cases}
$$
c. The acceleration function is $a(t) = v'(t) = 4$. $t=1 \To v(1) = -5\ ft/s \text{ and } a(1)=4ft/s^2$.
d. $v(t) = 0 \To t=\frac{9}{4} \To a(\frac{9}{4}) = 4ft/s^2$

17\. **A stone thrown vertically** Suppose a stone is thrown vertically upward from the edge of a cliff with an initial velocity of $64ft/s$ from a height of $32ft$ above the ground. The height $s$ (in ft) of the stone above the ground $t$ seconds after it is thrown is $s=-16t^2+64t+32$.
a. Determine the velocity $v$ of the stone after $t$ seconds.
b. When does the stone reach its highest point?
c. What is the height of the stone at the highest point?
d. When does the stone strike the ground?
e. With what velocity does the stone strike the ground?
>Solution
a. $v(t) = s'(t) = (-32t+ 64)ft/s$
b. When the stone is at its highest point, $v(t)=0 \To t=2s$.
c. The highest point is $s(2) = 96ft$.
d. When the stone striks the ground, $s(t) = 0 \To t=2+\sqrt 6 \approx 4.45s$.
e. The velocity when the ston strikes ground is $v(2+\sqrt 6) = -32\sqrt 6 \approx -70.38ft/s$.

18\. **A stone thrown vertically on Mars** Suppose a stone is thrown vertically upward from the edge of a cliff on Mars (where the acceleration due to gravity is only about $12 ft/s^2$) with an initial velocity of $6 4ft/s$ from a height of $192 ft$ above the ground. The height $s$ (in ft) of the stone above the ground $t$ seconds after it is thrown is $s=-6t^2+64t+192$.
a. Determine the velocity $v$ of the stone after $t$ seconds.
b. When does the stone reach its highest point?
c. What is the height of the stone at the highest point?
d. When does the stone strike the ground?
e. With what velocity does the stone strike the ground?
>Solution
a. $v(t) = s'(t) = (-12t+ 64)ft/s$
>Solution
b. When the stone is at its highest point, $v(t)=0 \To t=\frac{16}{3} \approx 5.33s$.
c. The highest point is $s(\frac{16}{3}) = \frac{1088}{3} \approx 362.67ft$.
d. When the stone striks the ground, $s(t) = 0 \To t=\frac{\sqrt 544 + 16}{3} \approx 13.11s$.
e. The velocity when the ston strikes ground is $v(\frac{\sqrt 544 + 16}{3}) = -64\sqrt 2 \approx -93.30ft/s$.

21-24\. **Average and marginal cost** Consider the following cost functions.
a. Find the average cost and marginal cost functions.
b. Determine the average and margin cost when $x=a$.
c. Interpret values obtained in part (b).
23\. $C(x)=-0.01x^2+40x+100, 0 \les x \les 1500, a=1000$
>Solution
a. The average cost function is $\overline C(x) = C(x)/x = \dfrac{-0.01x^2+40x+100}{x}$. The marginal cost function $M(x) = C'(x) = -0.02x+40$.
b. $\overline C(1000) = 30.1$ and $M(1000) = 20$.
c. The average cost per item is \\$30.1 when producing 1000 items, and the cost of producing 1001st item is \$20.

27\. **Comparing velocities** A stone is thrown vertically into the air at an initial velocity of $96ft/s$. On Mars, the height $s$ (in ft) of the stone above the ground after $t$ seconds is $s=96t-6t^2$ , and on Earth, $s=96t-16t^2$. How much heigher will the stone travel on Mars than on Earth?
>Solution
Both the stones readch their respective highest point when the velocities are $0ft/s$.
$$
\begin{aligned}
v_{earth} &= \frac{d}{dx}(96t-16t^2) = 96-32t=0 \\
&\To t=3s \\
&\To s_{earth}(3) = 144ft\\
v_{mars} &= \frac{d}{dx}(96t-6t^2) = 96-12t=0\\
&\To t=8s \\
&\To s_{mars}(8) = 384ft
\end{aligned}
$$
The stone will travel $384-144=240ft$ higher on Mars than on Earth.

31\. **Velocity from position** The graph of $s=f(t)$ represents the position of an object moving along a line at time $t \ges 0$. Graph (31).
a. Assume the velocity of the object is $0$ when $t=0$. For what other values of $t$ is the velocity of the object zero.
b. When is the object moving in the positive direction and when is it moving in the negative direction?
c. Sketch a graph of the velocity function.
>Solution
a. $t=1, 2, 3$.
b. In the time period of $(0, 1)$ and $(2, 3)$, the object moving in positive direction; in the time period of $(1, 2)$ and $(3, \infty)$, the object is moving is negative direction.
c. Graph (31c).

33-36\. **Average and marginal profit** Let $C(x)$ represent the cost of producing $x$ items and $p(x)$ be the sale price per item if $x$ items are sold. The profit $P(x)$ of selling $x$ items is $P(x) = xp(x) - C(x)$ (revenue minus cost). The **average profit per item** when $x$ items are sold is $P(x)/x$ and the **marginal profit** is $dP/dx$. The marginal profit approximates the profit obtained by selling one more item given that $x$ items have already been sold. Consider the following cost functions $C$ and price functions $p$.
a. Find the profit function $P$.
b. Find the average profit function and marginal profit function.
c. Find the average profit and marginal profit if $x=a$ units have been sold.
d. Interpret the meaning the values obtained in part c.
35\. $C(x)=-0.04x^2+100x+800, p(x)=200, a=1000$
>Solution
a. The profit function is $P(x) = 200x- (-0.04x^2+100x+800)= 0.04x^2+100x-800$
b. The average profit function is $\overline P(x) = \dfrac{0.04x^2-100x-800}{x}$, and the marginal function is $M(x) = P'(x) = 0.08x+100$.
c. $\overline P(1000) = 139.2\$$ and $M(1000)=180\$$.
d. The average profit of selling 1000 units is \\$139.2 and the profit of 1001st unit is \$180.

39\. **Velocity of a marble** The position (in meters) of a marble rolling up along a long incline is given by $s=\dfrac{100t}{t+1}$, where $t$ is measured in seconds and $s=0$ is the starting point.
a. Graph the position function
b. Find the velocity function for the marble.
c. Graph the velocity function and give a description of the motion of the marble.
d. At what time is the marble $80m$ from the starting point?
e. At what time is the velocity $50m/s$?
>Solution
a. Graph(39a).
b. $v(t) = s'(t) = \dfrac{100(t+1)-100(1+0)}{(t+1)^2} = \dfrac{100}{(t+1)^2}$
c. Graph(39c).
d. $s(t) = \dfrac{100t}{t+1} = 80 \To t=4s$
e. $v(t) = 50 \To t=\sqrt 2 -1 \approx 1.41s$

45\. **Spring oscillations** A spring hangs from the ceiling at equilibrium with a mass attached to its end. Suppose you pufunctionll downward on the mass and release it 10 inches below its equilibrium position with an upward push. The distance $x$ (in inches) of the mass from its equilibrium position after $t$ seconds is given by the function $x(t) = 10\sin t -10 \cos t$, where $x$ is positive when the mass is above the equilibrium position.
a. Graph and interpret this function.
b. Find $\dfrac{dx}{dt}$ and interpret the meaning of this derivative.
c. At what times is the velocity of the mass zero?
d. The function gives here is a model for the motion of an object on a spring. In what ways is the model unrealistic?
>Solution
a. Graph (45a). The mass oscillates about the equilibrium point.
b. $\dfrac{dx}{dt}(10\sin t -10 \cos t) = 10\cos t + 10\sin t$.
c. The velocity at $t$ seconds is $v(t) = 10\cos t + 10\sin t$. $v(t) = 0 \To t=(\frac{\pi}{4} + k\pi)s$, where $k$ is an integer.
d. The gravity and friction are not considered in the situation.

48\. **Power and energy** Power and energy are often used interchangeably, but they are quite different. Energe is what makes matter move or heat up. It is measured in units of joules or Calories, where $1\ Cal = 4184J$. One hour of walking consumes roughtly $10^6J$, or $240 Cal$. On the other, power is the rate at which engery is used, which is measured in watts, where $1W=1J/s$. Other usful units of power are kilowatts ($1kw = 10^3w$) and megawatts($1mw=10^6w$). If energy is usede at a rate of 1kw for one hour, the total amount of energy used is 1 kilowatts-hour ($1kwh =3.6 \times 10^6J$). Suppose the cumulative energy used in a large building over a $24hr$ period is given by $E(t)=100t + 4t^2-\dfrac{t^3}{9}/kwh$, where $t=0$ corresponding to midnight.
a. Graph the energy function.
b. The power is the rate of energy consumption; that is $P(t) = E'(t)$. Find the power over the interval $0 \les t \les 24$.
c. Graph the power function and interpret the graph. What are the units of power in this case?
>Solution
a. Graph (48a).
b. $P(t) = E'(t) = -\dfrac{t^2}{3} + 8t + 100$, where $0 \les t \les 24$.
c. Graph (48c). The power usage is increasing in from $t=0$ to $t=12$ and is decreasing from $t=12$ to $t=24$. Its highest point is at $t=12$, and $P(12) = 148kw$. The unit of power is $kw$.

51\. **Bungee jumper** A women attached to a bungee cord jumps from a bridge that is $30m$ above a river. Her height is in meters above the river t seconds after the jump is $y(t)=15(1+e^{-t}\cos t)$, for $t \ges 0$.
a. Determine her velocity at $t=1$ and $t=3$.
b. Use a graphing utility to determine when she is moving downward and when she is moving upward during the first $10s$.
c. Use a graphing utility to estimate the maximum upward velocity.
>Solution
a. The velocity function $v(t) = y'(t) = -15e^{-t}(\sin t + \cos t)$.
$$
\begin{aligned}
t=1 \To v(1) &= -15e^{-1}(\sin 1 + \cos 1) \approx -7.62m/s \\
t=2 \To v(2) &= -15e^{-2}(\sin 2 + \cos 2) \approx 0.63m/s
\end{aligned}
$$
b. Graph (51b). Every time $v(t)=0$, the women is changing its moving direction.
$$
\begin{aligned}
&v(t)= -15e^{-t}(\sin t + \cos t) = 0\\
&\because e^{-t} > 0\\
&\therefore \sin t + \cos t = 0\\
&\therefore t= \frac{3\pi}{4} + k\pi &\text {where k is an integer.}\\
&\because 0 \les t \les 10\\
&\therefore t= \frac{3\pi}{4}, \frac{7\pi}{4}, \frac{11\pi}{4} \To t \approx 2.36s, 5.50s, 8.64s
\end{aligned}
$$
The women moves downward during $[0, 2.36)$, then moves upward during $(2.36, 5.50)$, then moves downward during $(5.50, 8.64)$, and finally moves upward during $(8.64, 10]$
c. The maximum upward velocity is approximately $0.65m/s$ at $t\approx 3.14s$.
