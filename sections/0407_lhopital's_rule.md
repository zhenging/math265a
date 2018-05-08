### Section 4.7 L'Hopital's Rule
pg309: 3, 10, 13, 17, 22, 25, 29, 35, 41, 45, 48, 53, 57, 60, 63, 65, 69, 75, 87, 93

3\. Explain the steps used to apply l’Hôpital’s Rule to a limit of the form $0/0$.
>Solution
For $\dlim_{x \to a}\frac{f(x)}{g(x)}$
1\. Verify that $f(x)$ and $g(x)$ are differentiable on an open interval.
2\. Verify that $f(a) = g(a) = 0$, and $g'(a) \ne 0$.
3\. Apply L'hopital Rule, $\dlim_{x \to a}\frac{f(x)}{g(x)} = \dlim_{x \to a}\frac{f'(x)}{g'(x)}$.

10\. In terms of limits, what does it mean for the rates of growth of $f$ and $g$ to be comparable as $x\to \infty$?
>Solution
It means that $\dlim_{x \to \infty}{\frac{f(x)}{g(x)}} = M$, where $0<M<\infty$ is nonzero and finite.

13–22. **$0/0$ form** Evaluate the following limits using l’Hôpital’s Rule.
13\. $\dlim_{x \to 2}\frac{x^2-2x}{8-6x+x^2}$
>Solution
$$
\begin{aligned}
\dlim_{x \to 2}\frac{x^2-2x}{8-6x+x^2} &= \lim_{x \to 2}\frac{2x-2}{2x-6}\\
&= \lim_{x \to 2}\frac{x-1}{x-3} = \frac{2-1}{2-3} = -1
\end{aligned}
$$

17\. $\dlim_{x \to e}\frac{\ln x - 1}{x-e}$
>Solution
$$
\begin{aligned}
\dlim_{x \to e}\frac{\ln x - 1}{x-e} &= \lim_{x \to e}\frac{\frac{1}{x}-0}{1-0}\\
&= \lim_{x \to e}\frac{1}{x} = \frac{1}{e}
\end{aligned}
$$

22\. $\dlim_{z \to 0}\frac{\tan 4z}{\tan 7z}$
>Solution
$$
\begin{aligned}
\dlim_{z \to 0}\frac{\tan 4z}{\tan 7z} &= \lim_{z \to 0}\frac{4\sec^2 4z }{7\sec^2 7z} \\
&= \lim_{z \to 0}\frac{4 \cdot 1^2}{ 7 \cdot 1^2} = \frac{4}{7}
\end{aligned}
$$

23-36\. **$0/0$ form** Evaluate the following limits.
25\. $\dlim_{x \to \pi}\frac{\cos x + 1}{(x-\pi)^2}$
>Solution
$$
\begin{aligned}
\dlim_{x \to \pi}\frac{\cos x + 1}{(x-\pi)^2} &= \lim_{x \to \pi}\frac{-\sin x + 0}{2(x-\pi) \cdot 1}\\
&= \lim_{x \to \pi}\frac{-\cos x}{2} = \frac{1}{2}
\end{aligned}
$$

29\. $\dlim_{x \to \infty}\frac{e^{\frac{1}{x}} - 1}{\frac{1}{x}}$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}\frac{e^{\frac{1}{x}} - 1}{\frac{1}{x}} &= \lim_{t \to 0}\frac{e^t - 1}{t} &\quad \text {Let t=1/x}\\
&= \lim_{t \to 0}\frac{e^t}{1} = 1
\end{aligned}
$$

35\. $\dlim_{x \to 2}\frac{x^2-4x+4}{\sin^2 (\pi x)}$
>Solution
$$
\begin{aligned}
\lim_{x \to 2}\frac{x^2-4x+4}{\sin^2 (\pi x)} &= \lim_{x \to 2}\frac{2x-4}{2\pi \sin (\pi x)\cos (\pi x)}\\
&= \lim_{x \to 2}\frac{2x-4}{\pi\sin (2\pi x)}\\
&= \lim_{x \to 2}\frac{2}{\pi\cos (2\pi x) \cdot 2\pi}\\
&= \frac{2}{2\pi^2 \cdot 1} = \frac{1}{\pi^2}
\end{aligned}
$$

37-44\. **$\infty/\infty$ form** Evaluate the following limits.
41\. $\dlim_{x \to \infty}\frac{\ln(3x+5)}{\ln(7x+3) + 1}$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}\frac{\ln(3x+5)}{\ln(7x+3) + 1} &= \lim_{x \to \infty}\frac{\frac{3}{3x+5}}{\frac{7}{7x+3}}\\
&= \lim_{x \to \infty}\frac{3(7x+3)}{7(3x+5)}\\
&= \lim_{x \to \infty}\frac{21x+9}{21x+35}\\
&= \lim_{x \to \infty}\frac{21 + 0}{21 + 0} = 1\\
\end{aligned}
$$

45–50. **$0\cdot \infty$ form** Evaluate the following limits.
45\. $\dlim_{x \to 0}x\csc x$
>Solution
$$
\begin{aligned}
\lim_{x \to 0}x\csc x &= \lim_{x \to 0}\frac{x}{\sin x}\\
&= \lim_{x \to 0}\frac{1}{\cos x} = \frac{1}{1} = 1
\end{aligned}
$$

48\. $\dlim_{x \to \infty}(\csc(\frac{1}{x})(e^{\frac{1}{x}} - 1))$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}(\csc(\frac{1}{x})(e^{\frac{1}{x}} - 1)) &= \lim_{x \to \infty}\frac{e^{\frac{1}{x}} - 1}{\sin \frac{1}{x}}\\
&= \lim_{t \to 0}\frac{e^t - 1}{\sin t} &\quad \text{Let t=1/x}\\
&= \lim_{t \to 0}\frac{e^t}{\cos t} = \frac{1}{1} = 1
\end{aligned}
$$

51-54\. **$\infty-\infty$ form** Evaluate the following limits.
53\. $\dlim_{\theta \to \frac{\pi}{2}^-}(\tan \theta - \sec \theta)$
>Solution
$$
\begin{aligned}
\lim_{\theta \to \frac{\pi}{2}^-}(\tan \theta - \sec \theta) &= \lim_{\theta \to \frac{\pi}{2}^-}\frac{\sin \theta -1}{\cos \theta}\\
&= \lim_{\theta \to \frac{\pi}{2}^-}\frac{\cos \theta}{-\sin \theta} = \frac{0}{-1} = 0
\end{aligned}
$$

<!-- pagebreak -->
55–68\. **$1^\infty, 0^0, \infty^0$ forms** Evaluate the following limits or explain why they do not exist. Check your results by graphing.
57\. $\dlim_{\theta \to \frac{\pi}{2}^-}(\tan \theta)^{\cos \theta}$
>Solution
$$
\begin{aligned}
(\tan \theta)^{\cos \theta} &= e^{\ln(\tan \theta) \cdot \cos \theta}\\
L &= \lim_{\theta \to \frac{\pi}{2}^-}\ln(\tan \theta) \cdot \cos \theta\\
&= \lim_{\theta \to \frac{\pi}{2}^-}\frac{\ln(\tan \theta)}{\sec \theta}\\
&= \lim_{\theta \to \frac{\pi}{2}^-}\frac{\frac{\sec^2 \theta}{\tan \theta}}{\sec \theta \tan \theta}\\
&= \lim_{\theta \to \frac{\pi}{2}^-}\frac{\sec \theta}{\tan^2 \theta}\\
&= \lim_{\theta \to \frac{\pi}{2}^-}\frac{\cos^2 \theta}{\sin^2 \theta}= \frac{0}{1^2} = 0\\
\lim_{\theta \to \frac{\pi}{2}^-}(\tan \theta)^{\cos \theta} &= e^L =1
\end{aligned}
$$

60\. $\dlim_{x \to \infty}(1+\frac{1}{x})^{\ln x}$
>Solution
$$
\begin{aligned}
(1+\frac{1}{x})^{\ln x} &= e^{\ln(1+\frac{1}{x}) \cdot \ln x}\\
L &= \lim_{x \to \infty}{\ln(1+\frac{1}{x}) \cdot \ln x}\\
&= \lim_{x \to \infty}\frac{\ln(1+\frac{1}{x})}{\frac{1}{\ln x}}\\
&= \lim_{x \to \infty}\frac{\frac{1}{1+\frac{1}{x}} \cdot (-\frac{1}{x^2})}{-\frac{1}{\ln^2 x} \cdot \frac{1}{x}}\\
&=\lim_{x \to \infty} \frac{\ln^2 x}{x+1}\\
&=\lim_{x \to \infty} \frac{2\ln x \cdot \frac{1}{x}}{1+0}\\
&=\lim_{x \to \infty} \frac{2\ln x}{x}\\
&=\lim_{x \to \infty} \frac{2 \cdot \frac{1}{x}}{1}=\lim_{x \to \infty} \frac{2}{x} = 0\\
\lim_{x \to \infty}(1+\frac{1}{x})^{\ln x} &= e^L = 1
\end{aligned}
$$

<!-- pagebreak -->
63\. $\dlim_{x \to 0}(e^{ax} + x)^{\frac{1}{x}}$, for a constant $a$.
>Solution
$$
\begin{aligned}
(e^{ax} + x)^{\frac{1}{x}} &= e^{\ln (e^{ax} + x)\cdot \frac{1}{x}} = e^{\frac{\ln (e^{ax} + x)}{x}}\\
L &= \lim_{x \to 0}{\frac{\ln (e^{ax} + x)}{x}}\\
&= \lim_{x \to 0}\frac{\frac{1}{e^{ax} + x}\cdot (ae^{ax} + 1)}{1}\\
&= \lim_{x \to 0}\frac{ae^{ax} + 1}{e^{ax} + x} = \frac{ae^0 + 1}{e^0 + 0} = a+1\\
\lim_{x \to 0}(e^{ax} + x)^{\frac{1}{x}} &= e^L = e^{a+1}
\end{aligned}
$$

65\. $\dlim_{x \to 0+}(\tan x)^x$
>Solution
$$
\begin{aligned}
(\tan x)^x &= e^{\ln (\tan x) \cdot x}\\
L &= \lim_{x \to 0+}{\ln (\tan x) \cdot x}\\
&= \lim_{x \to 0+}\frac{\ln (\tan x)}{\frac{1}{x}} \\
&= \lim_{x \to 0+}\frac{\frac{1}{\tan x} \cdot \sec^2 x}{-\frac{1}{x^2}} \\
&= \lim_{x \to 0+}\frac{-x^2}{\sin x\cos x} \\
&= \lim_{x \to 0+}\frac{-2x}{\cos (2x)} = \frac{0}{1} = 0\\
\lim_{x \to 0+}(\tan x)^x &= e^L = 1
\end{aligned}
$$

69-80\. **Comparing growth rates** Use limit methods to determine which of the two given functions grows faster, or state that they have comparable growth rates.
69\. $x^{10}; e^{0.01x}$
>Solution
By **theorem 4.15**, $e^{0.01x} $ grows faster than $x^{10}$ as $x \to \infty$.

75\. $x^{20}; 1.00001^x$
>Solution
By **theorem 4.15**, $1.00001^x$ grows faster than $x^{20}$ as $x \to \infty$.

<!-- pagebreak -->
85-96\. **Miscellaneous limits by any means** Use analytical methods to evaluate the following limits.
87\. $\dlim_{x \to \infty}(\sqrt {x-2} - \sqrt {x-4})$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}(\sqrt {x-2} - \sqrt {x-4}) &= \lim_{x \to \infty}(\sqrt {x-2} - \sqrt {x-4}) \cdot \frac{\sqrt {x-2} + \sqrt {x-4}}{\sqrt {x-2} + \sqrt {x-4}}\\
&= \lim_{x \to \infty}\frac{2}{\sqrt {x-2} + \sqrt {x-4}}\\
&= \frac{2}{\infty + \infty} = 0
\end{aligned}
$$

93\. $\dlim_{x \to \infty}\frac{\log_2 x}{\log_3 x}$
>Solution
$$
\begin{aligned}
\lim_{x \to \infty}\frac{\log_2 x}{\log_3 x} &= \lim_{x \to \infty}\frac{\frac{\ln x}{\ln 2}}{\frac{\ln x}{\ln 3}}\\
&= \lim_{x \to \infty}\frac{\ln 3}{\ln 2} = \frac{\ln 3}{\ln 2}
\end{aligned}
$$
