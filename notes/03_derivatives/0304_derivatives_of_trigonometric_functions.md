### Section 3.4 Derivatives of Trigonometric Functions

+ Trigonometric Limits ([Proof](../misc/two_special_limits.html))
  + $\dlim_{x\to 0}\dfrac{\sin x}{x} = 1$
  + $\dlim_{x\to 0}\dfrac{\cos x - 1}{x} = 0$
+ Derivative of Sine and Cosine ([Proof](../misc/derivative_of_sine_and_cosine.html))
+ Derivative of the Trigonometric Functions
+ Higher-Order Trigonometric Functions ($y=\sin x, \frac{dy}{dx}, \frac{d^2y}{dx^2}, \frac{d^3y}{dx^3}$)

#### Homework
p167: 5, 7, 9, 19, 23, 27, 31, 32, 37, 43, 46, 57, 65, 68, 70, 71a,b

5\. Let $f(x) = \sin x$. What is the value of $f'(\pi)$?
>Solution
$f'(x) = \cos x \To f'(\pi) = \cos \pi = -1$

7-16\. **Trigonometric limits** Use Theorem 3.11 to evaluate the following limits.
7\. $\dlim_{x \to 0}\frac{\sin 3x}{x}$
>Solution
$$
\begin{aligned}
\lim_{x \to 0}\frac{\sin 3x}{x} &= \lim_{x \to 0}(3 \cdot \frac{\sin 3x}{3x}) \\
&= 3\lim_{t \to 0}\frac{\sin t}{t} &\text{Let t=3x} \\
&= 3 \times 1 = 3
\end{aligned}
$$

9\. $\dlim_{x \to 0}\frac{\sin 7x}{3x}$
>Solution
$$
\begin{aligned}
\lim_{x \to 0}\frac{\sin 7x}{\sin 3x} &= \lim_{x \to 0}\frac{\frac{\sin 7x}{7x} \cdot 7x}{\frac{\sin 3x}{3x} \cdot 3x} \\
&= \frac{7}{3} \left(\frac{\dlim_{x \to 0}\frac{\sin 7x}{7x}}{\dlim_{x \to 0}\frac{\sin 3x}{3x}}\right) \\
&= \frac{7}{3} \left(\frac{\dlim_{t \to 0}\frac{\sin t}{t}}{\dlim_{m \to 0}\frac{\sin m}{m}}\right) &\text{Let t=7x and m=3x}\\
&= \frac{7}{3} \times \frac{1}{1} = \frac{7}{3}
\end{aligned}
$$

17-28\. Calculating derivatives Find $dy/dx$ for the following functions.
19\. $y = e^{-x}\sin x$
>Solution
$$
\begin{aligned}
\frac{dy}{dx} &= (-1)\cdot e^{-x}\sin x + e^{-x}\cos x\\
&= e^{-x}\cos x - e^{-x}\sin x\\
&= e^{-x}(\cos x - \sin x)
\end{aligned}
$$

23\. $y = \dfrac{\cos x}{\sin x + 1}$
>Solution
$$
\begin{aligned}
\frac{dy}{dx} &= \frac{(-\sin x)(\sin x + 1) - \cos x(\cos x + 0)}{(\sin x + 1)^2} \\
&= \frac{-\sin x - \sin^2 x - \cos^2 x}{(\sin x + 1)^2} \\
&= \frac{-\sin x - 1}{(\sin x + 1)^2} \\
&= \frac{-1}{\sin x + 1} \\
\end{aligned}
$$

27\. $y = \cos^2 x$
>Solution
$$
\begin{aligned}
\frac{dy}{dx} &= (-\sin x)\cos x + \cos x(-\sin x) \\
&= -2\sin x \cos x \\
&= -\sin 2x
\end{aligned}
$$

29-31\. **Derivatives of other trigonometric functions** *Verify the following derivative formulas using the Quotient Rule.*
31\. $\dfrac{d}{dx}(\csc x) = -\csc x \cot x$
>Solution
$$
\begin{aligned}
\frac{d}{dx}(\csc x) &= \frac{d}{dx}(\frac{1}{\sin x}) \\
&= \frac{0 \cdot \sin x - 1 \cdot \cos x}{\sin^2 x} \\
&= \frac{-\cos x}{\sin^2 x} \\
&= -\csc x \cot x
\end{aligned}
$$

32-40\. **Derivative involving trigonometric functions**. *Find the derivative of the following functions.*
32\. $y= \tan x + \cot x$
>Solution
$y' = \sec^2 x- \csc^2 x$

37\. $y=\dfrac{\cot x}{1+\csc x}$
>Solution
$$
\begin{aligned}
y' &= \frac{(-csc^2 x)(1 + \csc x) - \cot x(0 - \csc x \cot x)}{(1 + \csc x)^2} \\
&= \frac{(-csc^2 x)(1 + \csc x) + \csc x \cot^2 x}{(1 + \csc x)^2} \\
&= \frac{(-csc^2 x)(1 + \csc x) + \csc x(\csc^2 x -1)}{(1 + \csc x)^2} \\
&= \frac{(-csc^2 x)(1 + \csc x) + \csc x(\csc x -1)(\csc x +1)}{(1 + \csc x)^2} \\
&= \frac{-csc^2 x + \csc x(\csc^ x -1)}{1 + \csc x} \\
&= \frac{-\csc x}{1 + \csc x} \\
\end{aligned}
$$

41-48\. Second-order derivative Find $y^n$ for the following functions.
43\. $y = e^x\sin x$
>Solution
$$
\begin{aligned}
y' &= (e^x)\sin x + e^x(\cos x)\\
&= e^x(\sin x + \cos x)\\
y'' &= (e^x)(\sin x + \cos x) + e^x(\cos x - \sin x) \\
&= 2e^x\cos x
\end{aligned}
$$

46\. $y = \tan x$
>Solution
$$
\begin{aligned}
y' &= \sec^2 x \\
y'' &= (\sec x\tan x)\sec x + \sec x(\sec x\tan x) \\
&= 2\sec^2 x\tan x
\end{aligned}
$$

56-61\. Calculating derivatives Find $dy/dx$ for the following functions.
57\. $y = x\cos x\sin x$
>Solution
$$
\begin{aligned}
\frac{dy}{dx} &= (1) \cdot \sin x \cos x + x[\cos x \cdot \cos x + \sin x \cdot (-\sin x)]\\
&= \sin x \cos x + x(\cos^2 x - \sin^2 x)\\
&= \frac{1}{2}\sin 2x + x\cos 2x
\end{aligned}
$$

62-65\. Equations of tangent lines
a. Find the equation of the line tangent to the following curves at given value of $x$.
b. Use a graphing utility to plot the curve and the tangent line.
65\. $y = \dfrac{\cos x}{1-\cos x}$; $x = \dfrac{\pi}{3}$
>Solution
$$
\begin{aligned}
y' &= \frac{-\sin x(1-\cos x) - \cos x(\sin x)}{(1-\cos x)^2}\\
&= \frac{-\sin x}{(1-\cos x)^2}\\
y'(\frac{\pi}{3}) &= \frac{-\frac{\sqrt {3}}{2}}{(1-\frac{1}{2})^2} = -2\sqrt{3} \\
y(\frac{\pi}{3}) &= \frac{\frac{1}{2}}{1-\frac{1}{2}} = 1
\end{aligned}
$$
The equation of the tangent line is $y - 1 = -2\sqrt{3}(x - \dfrac{\pi}{3})$ or $y = -2\sqrt{3} + \frac{2\sqrt{3}\pi}{3} + 1$
b. Graph (65).

68\. Matching Match the graphs of the functions in a-d with the graphs of their derivatives in A-D. Graph (68).
>Solution
$a \to D$ &emsp; $b \to B$ &emsp; $c \to A$ &emsp; $d \to C$

70\. **Damped sine wave** The graph of $f(t) = e^{-kt}\sin t$ with $k>0$ is called a *damped* sine wave; it is used in a variety of applications such as modeling the vibrations of a shock absorber.
a. Use a graphing utility to graph $f$ for $k=1, \frac{1}{2}$, and $\frac{1}{10}$ to understand why these curves are called damped sine waves. What effect does $k$ have on the behavior of the graph?
b. Compute $f'(t)$ for $k=1$, and use it to determin where the graph of $f$ has a horizontal tangent.
c. Evaluate $\dlim_{t \to \infty}e^{-t}\sin t$ by using the Squeeze Theorem. What does the result say about the oscillations of a damped sine wave?
>Solution
a. Graph (70). As $k$ becomes smaller, the amplitude of the graph on the left side of y-axis is getting smaller and smaller, the amplitude of the graph on the right side of y-axis is getting larger and larger.
b.
$$
\begin{aligned}
&k=1 \To f(t) = e^{-t}\sin t\\
&f'(t) =(-1)e^{-t}\sin x + e^{-t}\cos x = e^{-t}(\cos x  - \sin x)\\
&\text{In order for f has a horizontal tangent line, } f'(t) = 0\\
&\because e^{-t} > 0\\
&\therefore \cos x  - \sin x = 0 \text{ or } \cos x = \sin x\\
&\therefore x = \frac{\pi}{4} + n\pi \text{ (n is an integer.)}
\end{aligned}
$$
c. When $t$ approaches $\infty$, the amplitude of the graph approaches $0$.
$$
\begin{aligned}
&\because -1 \les \sin t \les 1 \text{ and } e^{-t} > 0\\
&\therefore -e^{-t} \les e^{-t}\sin t \les e^{-t}\\
&\because \lim_{t \to \infty}{-e^{-t}} = 0 = \lim_{t \to \infty}{e^{-t}}\\
&\therefore \lim_{t \to \infty}e^{-t}\sin t = 0
\end{aligned}
$$

71\. **A differential equation** A differential equation is an equation involving an unknow function and its derivatives. Consider the differential equation $y''(t) + y(t) = 0$.
a. Show that $y = A\sin t$ satisfies the equation for any constant $A$.
>Solution
$$
\begin{aligned}
y' &= A\cos t\\
y'' &= -A\sin t \\
y''(t) + y(t) &= -A\sin t + A\sin t = 0
\end{aligned}
$$

b. Show that $y = B\cos t$ satisfies the equation for any constant $B$.
>Solution
$$
\begin{aligned}
y' &= -A\sin t\\
y'' &= -A\cos t \\
y''(t) + y(t) &= -A\cos t + A\cos t = 0
\end{aligned}
$$
