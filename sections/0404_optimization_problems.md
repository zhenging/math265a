### Section 4.4 Optimization Problems
pg269: 3, 7, 13, 17, 21, 25, 29, 37, 43, 51, 62a,b, 63a-d

3\. Suppose the objective function is $Q=x^2y$ and you know that $x+y=10$. Write the objective function first in terms of $x$ and then in terms of $y$.
>Solution
$$
\begin{aligned}
Q &= x^2(10-x) = -x^3+10x^2\\
Q &= (10-y)^2 y = y^3 -20y^2+100y
\end{aligned}
$$

7\. **Minimum perimeter rectangle** Of all Rectangles of area 100, which one has the minimum perimeter.
>Solution
Let the length and width of the rectangle be $x$ and $y$, the objective function to be minimumized is the perimeter of the rectangle $P$, it follows
$$
\begin{aligned}
xy &= 100\\
P &= 2(x+y) = 2(x+\frac{100}{x})\\
P' &= 2(1-\frac{100}{x^2}) = 0 \To x= \pm 10\\
x & \in (0, 100) \To x=10, y=10
\end{aligned}
$$

13\. **Minimum sum** Find positive numbers x and y satisfying the equation xy=12 such that the sum 2x+y is as small as possible.
>Solution
Let $f(x) = 2x+y$
$$
\begin{aligned}
xy &=12 \To y = \frac{12}{x}\\
f(x) &= 2x+\frac{12}{x}\\
f'(x) &= 2-\frac{12}{x^2} = 0 \To x = \pm \sqrt {6}\\
x &> 0, y>0 \To x = \sqrt {6}, y=2\sqrt 6
\end{aligned}
$$

17\. **Shipping crates** A square-based box-shaped shipping crate is designed to have a volume of $16ft^3$. The material used to make the base cost twice as much (per squaure foot) as the material in the sides, and the material used to make the top cost half as much (per square foot) as the material in the sides. What are the dimensions of the crate that minimize the cost of materials?
>Solution
Let the cost of the top be $1$ unit per square foot, the cost of the side is $2$ unit per square foot, the cost of the base is $4$ unit per square foot, the width and length of the crate be $x$, and the height of the crate be $h$. The objective function to be minimized is the cost $C$
$$
\begin{aligned}
x^2h &= 16 \To h = \frac{16}{x^2}\\
C &= x^2 \cdot 1 + 4 xh \cdot 2 + x^2 \cdot 4\\
&= 5x^2 + \frac{128}{x}\\
C'(x) &= 10x - \frac{128}{x^2} = 0 \To x = \sqrt[3]{12.8} \approx 2.34 ft \\
h &=\frac{16}{x^2} \approx 2.92 ft
\end{aligned}
$$

21\. **Walking and rowing** A boat on the ocean is 4mi from the near point on a straight shoreline; that point is 6 mi from a restaurant on the shore. A woman plans to row the boat straight to a point on the shore and then walk along the shore to the restaurant.
a. If she walks at 3mi/hr and rows at 2mi/hr, at which point on the shore should she land to minimize the total travel time?
>Solution
Let the distance from the point on the shoreline nearest to the boat to the point where the woman lands on the shore be $x$. The objective function to be minimized is the travel time $T$.
$$
\begin{aligned}
T &= \frac{\sqrt{4^2+x^2}}{2} + \frac{6-x}{3}\\
T'(x) &= \frac{x}{2\sqrt{x^2+16}} - \frac{1}{3} = 0 \To x=\pm \frac{8}{5}\sqrt{5}\\
x&\in (0, 6) \To x= \frac{8}{5}\sqrt{5} \approx 3.58 mi
\end{aligned}
$$

b. If she walks at 3mi/hr, what is the minimum speed at which she must row so that the quickest way to the restaurant is to row directly?
>Solution
Todo

25\. **Rectangles beneath a semicircle** A rectangle is constructed with its base on the diameter of a semicircle with radius 5 and with its two other vertices on the semicircle. What are the dimensions of the rectangle with maxmimum area.
>Solution
Let the angle AOB be $\th$, OB be $x$ and AB be $y$. The objective function to be maximumized is the area $A$.
$$
\begin{aligned}
x &= 5\cos \th \quad y= 5\sin \th\\
A &= 2xy = 25 \cdot 2\sin \th \cos \th = 25\sin 2\th\\
A'(\th) &= 50\cos 2\th = 0 \To \th = \frac{(2k+1)\pi}{4} &\text{k is an integer}\\
\th &\in (0, \frac{\pi}{2}) \To \th = \frac{\pi}{4}\\
x &= y = \frac{5}{2}\sqrt 2
\end{aligned}
$$
The length and width of the rectangle is $\frac{5}{2}\sqrt 2 \times 2 = 5\sqrt 2$ and $\frac{5}{2}\sqrt 2$.

29\. **Optimal garden** A rectangle flower garden with an area of $30 m^2$ is surrounded by a grass border $1m$ wide on two sides and $2m$ wide on the other two sides (see figure). What dimensions of hte garden minimize the combined area of the garden and borders?
>Solution
Let the length and width of the flower garden be $x$ and $y$. The objective function to be minimized is the combined area $A$.
$$
\begin{aligned}
xy &= 30\\
A &= (x+4)(y+2)\\
&= (x+4)(\frac{30}{x}+2)\\
&= 2x + \frac{120}{x} + 38\\
A'(x) &= 2-\frac{120}{x^2} = 0 \To x= \pm \sqrt {60}\\
x&>0 \To x= \sqrt {60}m, y= \sqrt {15}m
\end{aligned}
$$

37\. **Laying cable** An island is 3.5 mi from the nearest point on a straight shoreline; that point is 8 mi from a power station (see figure). A utility company plans to lay electrical cable underwater from the island to the shore and then underground along the shore to the power station. Assume that is costs $\$2400/mi$ to lay underwater cable and $\$1200/mi$ to lay underground cable. At what point should the underwater cable meet the shore in order to minimize the cost of the project?
>Solution
Let the distance from the point on the shoreline nearest to the island to the point where the company start to lay underground cable on the shore be $x$. The objective function to be minimized is the cost of the cable from underwater and underground $C$.
$$
\begin{aligned}
C &= \sqrt{3.5^2 + x^2} \cdot 2400 + (8-x) \cdot 1200\\
&= 2400\sqrt{3.5^2 + x^2} -1200x+9600\\
C'(x) &= \frac{2400x}{\sqrt{3.5^2 + x^2}} - 1200 = 0 \To x= \pm \frac{3.5}{\sqrt 3}\\
x &\in (0, 8) \To x = \frac{3.5}{\sqrt 3} \approx 2.02 mi
\end{aligned}
$$

43\. **Crankshaft** A crank of radius $r$ rotates with an angular frequency $\omega$. It is connected to a piston by a connecting rod of length $L$ (see figure). The acceleration of the piston varies with the position of the crank according to the function
$$
a(\th) = \omega^2 r(\cos \th + \frac{r\cos 2\th}{L})
$$
For fixed $\omega$ and $r$, find the values of $\th$, with $\th \in [0, 2\pi]$, for which the acceleration of the piston is a maximum and minimum.
>Solution
$$
\begin{aligned}
a'(\th) &= \omega^2 r [(-\sin \th) + \frac{r}{L}\cdot (-2\sin 2\th)]\\
&= -\omega^2 r(\sin \th + \frac{2r\sin 2\th}{L})\\
&=-\omega^2 r\sin \th(1 + \frac{4r\cos \th}{L})\\
a'(\th) &= 0 \To \sin \th=0 \text{ or }1 + \frac{4r\cos \th} {L} = 0
\end{aligned}
$$
**case 1: $0<L<4r$**
$$
\begin{aligned}
\th &= 0, \pi, 2\pi, \cos^{-1} (-\frac{L}{4r}), 2\pi - \cos^{-1} (-\frac{L}{4r})\\
a(0) &= \omega^2 r(\frac{r}{L}+1)\\
a(\pi) &= \omega^2 r(\frac{r}{L}-1)\\
a(2\pi) &= \omega^2 r(\frac{r}{L}+1)\\
\cos \th &= -\frac{L}{4r} \To \cos 2\th = 2\cos^2\th -1  = \frac{L^2}{8r^2} - 1\\
a(\cos^{-1} (-\frac{L}{4r})&= \omega^2 r[-\frac{L}{4r} + \frac{r}{L} (\frac{L^2}{8r^2} - 1)]\\
&= \omega^2 r(-\frac{L}{8r} - \frac{r}{L})\\
a(2\pi - \cos^{-1} (-\frac{L}{4r})) &= a(\cos^{-1} (-\frac{L}{4r}) \\
&=\omega^2 r(-\frac{L}{8r} - \frac{r}{L})
\end{aligned}
$$
The absolute maximum occurs at $\th =0, 2\pi$, and the absolute minimum occurs at $\th = \cos^{-1} (-\frac{L}{4r}), 2\pi - \cos^{-1} (-\frac{L}{4r})$.
**case 2:$L > 4r$**
$$
\begin{aligned}
\th &= 0, \pi, 2\pi\\
a(0) &= \omega^2 r(\frac{r}{L}+1) \quad a(\pi) &= \omega^2 r(\frac{r}{L}-1) \quad a(2\pi) &= \omega^2 r(\frac{r}{L}+1)
\end{aligned}
$$
The absolute maximum occurs at $\th =0, 2\pi$, and the absolute minimum occurs at $\th = \pi$.

51\. **Maximum-volume cylinder in a sphere** Find the dimensions of the right circular cylinder of maximum volume that can be placed inside of a sphere of radius $R$.
>Solution
Let the radius of the base of the cylinder be $r$, and the height of the cylinder be $h$. The objective function to be maximized is the volume of the cylinder $V$.
$$
\begin{aligned}
r^2 + (\frac{h}{2})^2 &= R^2\\
V &= \pi r^2h\\
&= \pi h (R^2-\frac{h^2}{4})\\
V'(h) &= \pi R^2 - \frac{3}{4}\pi h^2 =0\To h= \frac{2}{3}\sqrt 3 R\\
r &= \sqrt{R^2-\frac{h^2}{4}} = \frac{\sqrt 6}{3}R\\
\end{aligned}
$$

62\. Turning a corner with a pole.
a. What is the length of the longest pole that can be carried horizontally around a corner at which a $3$-ft corridor and $4$-ft corridor meet at right angles?
>Solution
Let the part of the pole in the 3-ft corridor be $x$, and the part of the pole in the 4-ft corridor be $y$. The objective function to be maximized is $L$.
$$
\begin{aligned}
\frac{y}{4} &= \frac{x}{\sqrt{x^2-3^2}}\\
L &= x+y = x+ \frac{4x}{\sqrt{x^2-3^2}}\\
L'(x) &= 1 - \frac{36}{\sqrt{(x^2-9)^3}} = 0 \To x= \sqrt{\sqrt[3]{36^2} + 9} \approx 4.46 \\
y &= \frac{4x}{\sqrt{x^2-3^2}} \approx 5.41\\
L &= x + y \approx 9.87ft
\end{aligned}
$$

b. What is the length of the longest pole that can be carried horizontally around a corner at which a corridor is $a$ feet wide and a corridor is $b$ feet wide meet at right angles?
>Solution
Let the part of the pole in the a-ft corridor be $x$, and the part of the pole in the b-ft corridor be $y$. The objective function to be maximized is $L$.
$$
\begin{aligned}
\frac{y}{b} &= \frac{x}{\sqrt{x^2-a^2}}\\
L &= a+b = a + \frac{bx}{\sqrt{x^2-a^2}}\\
L'(x) &= 1- \frac{a^2b}{\sqrt{(x^2-a^2)^3}} = 0 \To x = \sqrt{\sqrt[3]{a^4b^2} + a^2}\\
y &= \frac{b\sqrt{\sqrt[3]{a^4b^2} + a^2}}{\sqrt[6]{a^4b^2}}
\\
L &= \sqrt{\sqrt[3]{a^4b^2} + a^2} + \frac{b\sqrt{\sqrt[3]{a^4b^2} + a^2}}{\sqrt[6]{a^4b^2}}
\end{aligned}
$$

63\. **Travel costs** A simple model for travel costs involves the cost of gasoline and the cost of a driver. Specifically, assume that gasoline costs $\$p/gallon$ and the vehicle gets $g$ miles per gallon. Also assume that the driver earn $\$w/hour$.
a. A plausible function to describe how gas mileage (in mi/gal) varies with speed is $g(v) = v(85-v)/60$. Evaluate $g(0), g(40), g(60)$ and explain why these values are reasonable.
>Solution
$$
\begin{aligned}
g(0) &= 0\\
g(40) &= \frac{40(85-40)}{60} = 30mi/gal\\
g(60) &= \frac{60(85-60)}{60} = 25mi/gal
\end{aligned}
$$
When the vehicle is stationary, it burns zero gas. As its speed increases from 40 mi/hr to 60 mi/hr, the gas mileage decreases, because the gas is burnt more sufficiently at a higher speed.

b. At what speed does the gas mileage function have its maximum?
>Solution
$g'(v) = \dfrac{17}{12}-\dfrac{v}{30} = 0 \To v= 42.5mi/hr$

c. Explain why the cost of a trip of length $L$ miles is $C(v) = Lp/g(v) + Lw/v$.
>Solution
1\. The total cost is the sum of cost of gas and cost of driver.
2\. The gas cost is $Lp/g(v)$.
3\. The driver cost is $Lw/v$.

d. Let $L=400mi$, $p=\$4/gal$, and $w=\$20/hr$. At what (constant) speed would the vehicle be driven to minimize the cost of the trip?
>Solution
$$
\begin{aligned}
C &= \frac{400 \times 4}{\frac{v(85-v)}{60}} + \frac{400 \times 20}{v} \\
&= \frac{96000}{85v-v^2} + \frac{8000}{v}\\
C'(v) &= 8000[\frac{-12(85-2v)}{(85v-v^2)^2} - \frac{1}{v^2}] = 0\\
\frac{12(2v-85)}{(85v-v^2)^2} &= \frac{1}{v^2}\\
v^2-194v+8245 &= 0\\
v &= \frac{194\pm \sqrt{194^2-4\times 8245}}{2} \approx 62.9, 131.1\\
v&\in (0, 85) \To v= 62.9mi/hr
\end{aligned}
$$
