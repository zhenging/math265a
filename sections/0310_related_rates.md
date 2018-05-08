### Section 3.10 Related Rates
pg222: 5, 14, 19, 23, 28, 29, 32, 34, 37, 45, 50

5\. **Expanding square** The side of a square increase in length at a rate of $2m/s$.
a. At what rate is the area of the square changing when the sides are $10m$ long?
b. At what rate is the area of the square changing when the sides are $20m$ long?
c. Draw a graph of how the rate of changes of the area varies with the side length.
>Solution
Let $A$ be the area of the square, $x$ be the length of the side of the square and $t$ be the time. $A=x^2$ and $\frac{dx}{dt} = 2$. The rate of change of the area is as follows
$$
\frac{dA}{dt} = \frac{d}{dt}(x^2) = 2x \frac{dx}{dt}
$$
a. When $x=10$, $\dfrac{dA}{dt} = 2\cdot 10 \cdot \dfrac{dx}{dt} = 40m^2/s$.
b. When $x=20$, $\dfrac{dA}{dt} = 2\cdot 20 \cdot \dfrac{dx}{dt} = 80m^2/s$.
c. Graph (5). The rate of changes of the area with respect to side is $\dfrac{dA}{dx} = \dfrac{d}{dx}(x^2) = 2x$.

14\. **Piston compression** A piston is seated at the top of a cylindrical chamber with radius $5cm$ when it starts to moving into the chamber at a constant speed of $3cm/s$. What is the rate of change of the volume of the cylinder when the piston is $2cm$ from the base of the chamber?
>Solution
Let the volume of the cylinder be $V$, the radius of the cylinder be $r=5$, the height from the piston to the base is $h$, and the time be $t$.
$$
\begin{aligned}
V &= \pi r^2h = 25\pi h\\
\frac{dh}{dt} &= -3 \quad \text{(The height is decreasing when the piston moves downward)}\\
\frac{dV}{dt} &= \frac{d}{dt}(25\pi h) = 25\pi \frac{dh}{dt} = -75\pi (cm^3/s)
\end{aligned}
$$
The rate of change of the volume when the piston is $2cm$ from the base to the chamber is $-75\pi (cm^3/s)$.

19\. Filling a pool A swimming pool is $50m $long and $20m$ wide. Its depth decreases linearly along the length from $3m$ to $1m$. It is initially empty and is filled at a rate $1m^3/min$. How fast is the water level rising $250min$ after the filling begins? How long will it take to fill the pool?
>Solution
Let the volume of water in the pool be $V$, the length of water surface be $l|l \in [0, 50]$, the width be $w=20$, the water level be $h | h \in [0, 3]$, and the time be $t$. It follows that $\dfrac{dV}{dt} = 1 m^3/min$. After $250min$, $V = 250min \cdot 1m^3/min = 250m^3$.
1\. When $h \in [0, 2]$
$$
\begin{aligned}
\frac{l}{h} &= \frac{50}{2} = 25 \To l = 25h\\
V &= \frac{1}{2}l \cdot h \cdot w = \frac{1}{2} \cdot 25h^2 \cdot 20 = 250h^2 \\
V&=250 \To h=1 &\text{(1)}
\end{aligned}
$$
2\. When $h \in (2, 3]$, $l = 50$
$$
\begin{aligned}
V &= \frac{1}{2}(h+h-2) \cdot l \cdot w = \frac{1}{2}(2h-2) \cdot 50 \cdot 20 = 1000h-1000\\
V&=250 \To h=1.25 &\text{(2)}
\end{aligned}
$$
The result of $h$ of case $(2)$ is contradicted with its precondition $h \in (2, 3]$. Thus we conclude that the water level $h$ is $1m$ (case 1) after $250min$.
$$
\frac{dV}{dt} = \frac{d}{dt}(250h^2) = 500\cdot \frac{dh}{dt} = 1 \To \frac{dh}{dt} = 0.002 m/min
$$
After $250min$, the water level is rising $0.002 m/min$.
The maximum volume of water in the pool is $V=1000h-1000 = 1000\cdot 3 -1000= 2000m^3$. It will take $2000m^3/(1m^3/min) = 2000min$ to fill the pool.

23\. **Ladder aginst the wall** A 13-foot ladder is leaning against a vertical wall. When Jack begins pulling the foot of the ladder away from the wall at a rate of $0.5 ft/s$. How fast is the top of the ladder slidding down the wall when the foot of the ladder is $5ft$ from the wall?
>Solution
Let the length of the ladder be $H$, the distance from the top of the ladder to the ground is $O$, the distance from the foot of the ladder to the wall be $A$, the angle between $H$ and $A$ be $\th$ and the time be $t$. It follows that $\dfrac{dA}{dt} = 0.5ft/s$. The rate of change of the distance from the top of the laddder to the ground is $\dfrac{dO}{dt}$.
$$
\begin{aligned}
\frac{dO}{dt} &= \frac{d}{dt}(\sqrt{H^2-A^2}) = \frac{d}{dt}(\sqrt{13^2-A^2})\\
&= \frac{1}{2\sqrt{169-A^2}} \cdot \frac{d}{dt}(169-A^2)\\
&= \frac{-2A}{2\sqrt{169-A^2}}\cdot \frac{dA}{dt}\\
&= \frac{-A}{\sqrt{169-A^2}}\cdot \frac{dA}{dt}\\
&= \frac{-A}{2\sqrt{169-A^2}}\\
\frac{dO}{dt} |_{A=5} &= \frac{-5}{2 \cdot \sqrt{169-(5)^2}} \approx -0.21ft/s
\end{aligned}
$$

28\. **Draining a water heater** A water heater that has the shap of a right cyclindrical tank with a radius of $1ft$ and a height of $4ft$ is being drained. How fast is water draining out of the tank (in $ft^3/min$) if the water level is dropping at $6 in/min?$
>Solution
Let the volume of the water be $V$, the radius of the tank is $r=1ft$, the height of the water level is $h$, and the time be $t$. The rate of change of the water volume is $\dfrac{dV}{dt}$. It follows that
$$
\begin{aligned}
V &=\pi r^2 \cdot h=\pi h \\
\frac{dh}{dt} &= -6in/min = -0.5ft/min\\
\frac{dV}{dt} &= \frac{d}{dt}(h\pi) = \pi \cdot \frac{dh}{dt} \approx -1.57ft^3/min
\end{aligned}
$$
The water voloume is decreasing at the rate of $1.57ft^3/min$ when the water level is dropping at $6in/min.$

29\. **Draining a tank** An inverted concial water tank with a height of $12ft$ and a radius of $6ft$ is drained through a hole in the vertex at a rate of $2ft^3/s$. What is the rate of change of the water depth when the water depth is $3ft$? (Hint: Use similar triangles)
>Solution
Let the volume of the water be $V$, the radius of water surface be $r$, the water depth be $h$, and the time be $t$. The rate of change of water volume is $\dfrac{dV}{dt} = -2ft^3/s$. The rate of change of water depth is $\dfrac{dh}{dt}$. It follows that
$$
\begin{aligned}
\frac{r}{h} &= \dfrac{6}{12} \To r=\frac{1}{2}h \\
 V&=\dfrac{1}{3}\pi r^2 h=\frac{\pi h^3}{12}\\
\frac{dV}{dt} &= \frac{d}{dt}(\frac{\pi h^3}{12}) = \frac{\pi h^2}{4} \cdot \frac{dh}{dt} = \frac{9\pi}{4} \cdot \frac{dh}{dt}=-2ft^3/s \\
\To \frac{dh}{dt} &= -2 \cdot \frac{4}{9\pi} \approx -0.28ft/s
\end{aligned}
$$
The water depth is decreasing at the rate of $0.28ft/s$ when the depth is $3ft$.

32\. **Filling a hemispherical tank** A hemispherical tank with a radius of $10m$ is filled from an infolow pipe at a rate of $3m^3/min$. How fast is the water level rising when the water level is $5m$ from the bottom of the tank? (Hint: The volume of a cap of thickness $h$ sliced from a sphere of radius $r$ is $\pi h^2(3r-h)/3$.)
>Solution
Let the water volume be $V$, the water level be $h$, the radius of water surface be $r$, and the time be $t$. The rate of change of water volume is $\dfrac{dV}{dt} = 3m^3/min$. The rate of change of the water level is $\dfrac{dh}{dt}$. It follows that
$$
\begin{aligned}
h&=5\\
r&=\sqrt{10^2 - (10-h)^2} = \sqrt {75}\\
V &= \frac{\pi h^2(3r-h)}{3}\\
\frac{dV}{dt} &= \frac{d}{dt}(\frac{\pi h^2(3r-h)}{3}) = (2\pi rh-\pi h^2)\cdot \frac{dh}{dt}
\\&=(2\pi \cdot \sqrt {75} \cdot 5 - \pi \cdot 5^2) \cdot \frac{dh}{dt} =3m^3/min\\
\To \frac{dh}{dt} &= \frac{3}{2\pi \cdot \sqrt {75} \cdot 5 - \pi \cdot 5^2} \approx 0.016m/min
\end{aligned}
$$
The water level is increasing at the rate of $0.016m/min$ when the water level is $5m$.

34\. **Observing a launch** An observer stands $300ft$ from the launch site of a hot-air balloon. The balloon is launched vertically and maintains a constant upward velocity of $20ft/s$. What is the rate of chagne of the angle of elevation of the balloon when it is $400ft$ from the ground? The angle of the elevation is the angle $\th$ between the observer's line of sight to the balloon and the ground.
>Solution
Let the height of the balloon to the ground be $h$, the distance from the observer to the launch site be $d=300$, and the time be $t$. The rate of change of the $h$ is $\dfrac{dh}{dt}=20ft/s$. The rate of change of the angle is $\dfrac{d\th}{dt}$. It follows that
$$
\begin{aligned}
\th &= \tan^{-1}(\frac{h}{d}) = \tan^{-1}(\frac{h}{300})\\
\frac{d\th}{dt} &= \frac{1}{1+ (\frac{h}{300})^2} \cdot \frac{1}{300} \cdot \frac{dh}{dt}\\
&=\frac{300}{90000+h^2}\cdot 20\\
&=\frac{6000}{90000+h^2}\\
\frac{d\th}{dt} |_{h=400} &= \frac{6000}{90000+400^2} = \frac{3}{125} rad/s
\end{aligned}
$$

37\. **Another fishing story** An angler hooks a trout and begins reels in his line at $4in/s$. Assume the tip of the fishing rod is $12ft$ above the water and directly above the angler, and the fish is pulled horizontally directly twoward the angler. Find the horizontal speed of the fish when it is $20ft$ from the angler.
>Solution
Let the distance from the tip of the fishing rod to the fish be $H$, the distance from the angler to the fish be $A$, the height of the tip of the rishing rod above the water be $O=12ft$, and the time be $t$. The rate of change of $H$ is $\dfrac{dH}{dt} = -4in/s$. The rate of change of $A$ is $\dfrac{dA}{dt}$. It follows that
$$
\begin{aligned}
\frac{dA}{dt} &= \frac{d}{dt}(\sqrt {H^2-O^2}) = \frac{d}{dt}(\sqrt {H^2-144})\\
&= \frac{1}{2\sqrt{H^2-144}} \cdot \frac{d}{dt}(H^2-144)\\
&= \frac{2H}{2\sqrt{H^2-144}} \cdot \frac{dH}{dt}\\
&= \frac{H}{\sqrt{H^2-144}} \cdot \frac{dH}{dt}\\
A&=20, O=12 \To H = \sqrt{A^2+O^2} = \sqrt{544}\\
\frac{dA}{dt} &= \frac{\sqrt{544}}{20} \cdot (-4) \approx -4.66in/s
\end{aligned}
$$
The horizontal speed of the fish is $4.66in/s$ when the fish is $20ft$ from the angler.

44\. Filling two pools Two cylindrical swimming pools are being filled simultaneously at the same rate (in $m^3/min$). The smaller pool has a radius of $5m$, and the water level rises at a rate of $0.5m/min$. The larger pool has a radius of $8m$. How fast is the water level rising in the larger pool?
>Solution
For the smaller pool, let the water volume be $V_s$, the water level be $h_s$, and the radius be $r_s=5m$; for the larger pool, let the water volume be $V_l$, the water levelbe $h_l$, and the radius be $r_l=8m$; let the time be $t$. The rate of change of water volume is $\dfrac{dV_s}{dt} = \dfrac{dV_l}{dt}$. The rate of change of water level of smaller pool is $\dfrac{dh_s}{dt} = 0.5m/min$. It follows that
$$
\begin{aligned}
V_s &= \pi (r_s)^2 h_s = 25\pi h_s\\
\frac{dV_s}{dt} &= \frac{d}{dt}(25\pi h_s) = 25\pi\cdot \frac{dh_s}{dt} = 12.5\pi m^3/min\\
V_l &= \pi (r_l)^2 h_l = 64\pi h_l\\
\frac{dV_l}{dt} &= \frac{d}{dt}(64\pi h_l) = 64\pi\cdot \frac{dh_l}{dt} = 12.5\pi m^3/min \\
\To \frac{dh_l}{dt} &= \frac{12.5\pi}{64\pi} = \frac{25}{128} m/min
\end{aligned}
$$
The water level in the larger pool is rising at the rate of $\frac{25}{128} m/min$.

45\. Filming a race A camera is set up at the starting line of a drag race $50ft$ from a dgragster at the startling line (camera 1 in the figure). Two seconds after the start of the race, the dragster has traveled $100ft$ and the camera is truning at $0.75 rad/s$ while filming the dragster. Graph (45).
a. What is the speed of the dragster at this point?
>Solution
Let the start point of the dragster be $O$, the point of camera 1 be $A$, the point of camera 1 be $B$, the point of the dragster be $C$, the angle CAO be $\th_1$, the angle CBO be $\th_2$, the distance of $AO$ be $D_1=50$, the distance of $BO$ be $D_2=100$, the the distance of $OC$ be $S$ and the time be $t$. The rate of change of $\th$ is $\dfrac{d\th_1}{dt} = 0.75 rad/s$.
The speed of the draster is $\dfrac{dS}{dt}$.
$$
\begin{aligned}
\tan \th_1 &= \frac{S}{D_1} =\frac{S}{50}\\
\frac{dS}{dt} &= \frac{d}{dt}(D_1 \tan \th) \\
&= 50 {\sec^2 \th_1} \cdot \frac{d\th_1}{dt}\\
&= 50(1 + \tan^2 \th_1) \cdot \frac{d\th_1}{dt}\\
&= 50(1 + (\frac{100}{50})^2) \cdot 0.75 = 187.5 ft/s
\end{aligned}
$$

b. A second camera (camera 2 in the figure) filming the dragster is located on the startling line 100ft away from the dragster at the start of the race. How fast is this camera turning 2 seconds after the start of the race?
>Solution
$$
\begin{aligned}
\th_2 &= {\tan^{-1} \frac{S}{D_2}} = \tan^{-1} (\frac{S}{100})\\
\frac{d\th_2}{dt} &= \frac{1}{1 + (\frac{S}{100})^2} \cdot \frac{1}{100} \cdot \frac{dS}{dt}\\
&= \frac{100}{10000+S^2}\cdot 187.5 \\
&= \frac{18750}{10000+S^2}\\
\frac{d\th_2}{dt} |_{S=100} &= \frac{18750}{10000+(100)^2} = 0.9375rad/s
\end{aligned}
$$
The second camera is turning at the rate of $0.9375rad/s$ 2 seconds after the start of race.

50\. **A lighthouse problem** A lighthouse stands $500m$ off of a straight shore, the focues beam of its light revolving four times each minute. As shown in the figure, $P$ is the point on shore closest to the lighthouse and $Q$ is the point on the shore $200m$ from $P$. What is the speed of the beam along the shore when it strikes the point $Q$? Describe how the speed of the beam along the shore varies with the distance between $P$ and $Q$. Neglect the height of the lighthouse.
>Solution
Let the point of the lighthouse be $O$, the angle $POQ$ be $\th$, the distance of $PQ$ be $S$, and the time be $t$. The rate of change of $\dfrac{d\th}{dt} = 4\cdot 2\pi rad/min = 8\pi rad/min$. The speed of the beam traveling from $P$ to $Q$ is $\dfrac{dS}{dt}$. The rate of change of the speed is $\dfrac{d}{dt}(\dfrac{dS}{dt})$. It follows that
$$
\begin{aligned}
\tan \th &= \frac{PQ}{PO} = \frac{S}{500} \To S = 500\tan \th\\
\frac{dS}{dt} &= \frac{d}{dt}(500\tan \th)\\
&= 500 {\sec^2 \th}\frac{d\th}{dt}\\
&= 500(1 + \tan^2 \th)\cdot 8\pi\\
&= 4000\pi(1 + (\frac{S}{500})^2)\\
&= \frac{4\pi S^2}{250} + 4000\pi\\
\frac{dS}{dt} |_{S=200} &= 4000\pi(1+(\frac{200}{500})^2)= 4640\pi m/min\\
\frac{d}{dt}(\frac{dS}{dt}) &= \frac{d}{dt}(\frac{4\pi S^2}{250} + 4000\pi) = \frac{4\pi S}{125}
\end{aligned}
$$
1\. The speed of the beam when it strikes point $Q$ is $4640\pi m/min$.
2\. The rate of change of speed is $\dfrac{d}{dt}(\dfrac{dS}{dt}) = \dfrac{4\pi S}{125} m/min^2$. As the distance between $PQ$ increases, the speed increases too.
