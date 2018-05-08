### Section 3.8 Derivatives of Logarithmic and Exponential Functions
pg206: 3, 9, 13, 14, 15, **21**, 23, 27, 29, 31, 37, 41, **45**, 52, 55, **59**

3\. Show that $\frac{d}{dx}(\ln kx) = \frac{d}{dx}(\ln x)$, where $x>0$ and $k>0$ is a real number.
>Solution
$$
\begin{aligned}
\frac{d}{dx}(\ln kx) &= \frac{d}{dx}(\ln k + \ln x) \\
&= \frac{d}{dx}(\ln k) + \frac{d}{dx}(\ln x) \\
&= 0 + \frac{d}{dx}(\ln x) = \frac{d}{dx}(\ln x)
\end{aligned}
$$

9-22\. **Derivative involving $\ln x$** Find the following derivatives.
9\. $\dfrac{d}{dx}\ln 7x$
>Solution
$$
\begin{aligned}
\frac{d}{dx}\ln 7x = \frac{1}{7x} \cdot \frac{d}{dx}(7x) = \frac{1}{7x} \cdot 7 = \frac{1}{x}
\end{aligned}
$$

13\. $\dfrac{d}{dx}\ln |\sin x|$
>Solution
$$
\begin{aligned}
\frac{d}{dx}\ln |\sin x| = \frac{1}{\sin x} \cdot \frac{d}{dx}(\sin x) = \frac{\cos x}{\sin x} = \cot x
\end{aligned}
$$

14\. $\dfrac{d}{dx}(\dfrac{{\ln x^2}}{x})$
>Solution
$$
\begin{aligned}
\frac{d}{dx}(\frac{{\ln x^2}}{x}) &= \frac{\frac{1}{x^2} \cdot \frac{d}{dx}(x^2) \cdot x- {\ln x^2}\cdot 1}{x^2} = \frac{2- {\ln x^2}}{x^2}
\end{aligned}
$$

15\. $\dfrac{d}{dx}\left[\ln (\dfrac{x+1}{x-1})\right]$
>Solution
$$
\begin{aligned}
\frac{d}{dx}\left[\ln (\frac{x+1}{x-1})\right] &= \frac{x-1}{x+1} \cdot \frac{d}{dx}(\frac{x+1}{x-1}) \\
&= \frac{x-1}{x+1} \cdot \frac{1 \cdot (x-1) - (x+1) \cdot 1}{(x-1)^2}\\
&= -\frac{2}{x^2-1}
\end{aligned}
$$

21\. $\dfrac{d}{dx}\left(\dfrac{\ln x}{\ln x + 1}\right)$
>Solution
$$
\begin{aligned}
\frac{d}{dx}\left(\dfrac{\ln x}{\ln x + 1}\right) &= \frac{\frac{1}{x} \cdot (\ln x + 1) - \ln x \cdot (\frac{1}{x})}{(\ln x + 1)^2} \\
&= \frac{1}{x(\ln x + 1)^2}
\end{aligned}
$$

23-30\. **Derivative of $b^x$** Find the derivatives of following functions.
23\. $y=8^x$
>Solution
$y'= 8^x \ln 8$

27\. $y=x^3 \cdot 3^x$
>Solution
$y' = 3x^2 \cdot 3^x + x^3 \cdot 3^x \ln 3$

29\. $A = 250(1.045)^{4t}$
>Solution
$$
\begin{aligned}
A'&= 250 \cdot (1.045)^{4t} \cdot \ln 1.045 \cdot \frac{d}{dt}(4t)\\
&= 1000(1.045)^{4t} \ln 1.045
\end{aligned}
$$

31\. **Exponential model** Application.
>Solution
a. $T(16) = 10\cdot 2^{-0.274 \times 16} * 60 \approx 28.7s$
b.
$$
\begin{aligned}
T(\frac{24000-22000}{1000}) &= T(2) = 10\cdot 2^{-0.274 \times 2} \approx  6.84 mins\\
T(\frac{30000-22000}{1000}) &= T(8) = 10\cdot 2^{-0.274 \times 8} \approx  2.19 mins\\
\end{aligned}
$$
The average rate of change of T is $\frac{T(8)-T(2)}{8-2} = -0.775 mins/1000ft$
c.
$$
\begin{aligned}
\frac{dT}{da} &= 10 \cdot 2^{-0.274a} \ln 2 \cdot (-0.274) \\
&= -2.74 \cdot 2^{-0.274a} \cdot \ln 2 \\
\end{aligned}
$$
At 30000ft, $a=8 \To \frac{dT}{da} \lvert_8 = -2.74 \cdot 2^{-0.274 \times 8} \cdot \ln 2 \approx -0.42mins/1000ft$. The time of consciousness is decreased by 0.42 minutes per 1000 ft at this height.

34-44\. **General Power Rule** Use the General Power Rule where appropriate to find the derivative of the following function.
37\. $g(y)=e^y\cdot y^e$
>Solution
$g'(y) = e^y \cdot y^e + e^y \cdot (e)y^{e-1} = e^y \cdot y^e + e^{y+1}y^{e-1}$

41\. $f(x) = (2x-3)x^{3/2}$
>Solution
$$
\begin{aligned}
f'(x) &= 2x^{3/2} + (2x-3)\cdot(\frac{3}{2}x^{1/2}) \\
&= 2x^{3/2} + 3x^{3/2} - \frac{9}{2}x^{1/2}\\
&= 5x^{3/2} - \frac{9}{2}x^{1/2}
\end{aligned}
$$

45-50\. **Derivatives of General Exponential Function (or $g(h)$)** Find the derivative of each function and evaluate the derivative at the given value of $a$.
45\. $f(x) = x^{\cos x }; a=\pi/2$
>Solution
$$
\begin{aligned}
f'(x) &= \frac{d}{dx}(e^{\ln x \cos x}) \\
&= e^{\ln x \cos x} \cdot \frac{d}{dx}(\ln x \cos x)\\
&= e^{\ln x \cos x}(\frac{1}{x}\cos x - \ln x\sin x) \\
&= x^{\cos x}(\frac{\cos x}{x} - \ln x\sin x)\\
f'(\pi/2) &= (\pi/2)^{\cos \pi/2}(\frac{\cos \pi/2}{\pi/2} - \ln \pi/2 \sin \pi/2) \\
&= 1 \cdot (0-\ln (\pi/2)) \\
&= -\ln (\pi/2)
\end{aligned}
$$

51-54\. **Tangenet line and general exponential functions.**
52\. Determine whether the graph of $y=x^{\sqrt x}$ has any horizontaql tangent lines.
>Solution
$$
\begin{aligned}
y' &= \frac{d}{dx}(e^{\ln x \sqrt x}) \\
&= e^{\ln x \sqrt x} \cdot \frac{d}{dx}(\ln x \sqrt x) \\
&= x^{\sqrt x} \cdot (\frac{1}{x} \cdot \sqrt x + \ln x \cdot \frac{1}{2\sqrt x}) \\
&= x^{\sqrt x}(\frac{2 + \ln x}{2\sqrt x})\\
y'&=0 \&\& x >0 \To 2+\ln x = 0 \To x=e^{-2}\\
y(e^{-2}) &= (e^{-2})^{\sqrt {e^{-2}}} = \sqrt[e] {e^{-2}}
\end{aligned}
$$
Therefore, the graph has a horizontal line at point $(e^{-2}, \sqrt[e] {e^{-2}})$.

55-60\. **Derivatives of logarithmic functions** Calculate the derivative of the following functions.
55\. $y=4\log_3(x^2-1)$
>Solution
$$
\begin{aligned}
y' &= \frac{4}{(x^2-1)\ln 3} \cdot \frac{d}{dx}(x^2-1) \\
&= \frac{8x}{(x^2-1)\ln 3}
\end{aligned}
$$

59\. $y=\dfrac{1}{\log_4 x}$
>Solution
$$
\begin{aligned}
y' &= -\frac{1}{(\log_4 x)^2} \cdot \frac{1}{x\ln 4}\\
&= -\frac{1}{x\ln 4 (\dfrac{\ln x}{\ln 4})^2} \\
&= -\frac{\ln 4}{x\ln^2 x}
\end{aligned}
$$
