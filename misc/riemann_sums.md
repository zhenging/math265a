### Riemann Sums

>Definition Regular Partition
Suppose $[a, b]$ is a closed interval containing $n$ intervals
$$
[x_0, x_1], [x_1, x_2], \cdots ,[x_{n-1}, x_n]
$$
of equal length $\Delta x = \frac{b-a}{n}$ with $a = x_0$ and $b=x_n$. The endpoints $x_0, x_1, x_2, \cdots , x_{n-1}, x_n$ of the subintervals are called **grid points**, and they carete > a **regular partition** of the interval $[a, b]$. In general, > the $kth$ grid point is
$$
x_k = a + k{\Delta x}, \text{ for } k=0,1,2,\cdots,n
$$

>Definition Riemann Sum
Suppose $f$ is defined on a closed interval $[a, b]$, which is divided into n subintervals of equal length ${\Delta x}$. If $x_k^*$ is any point in the kth subinterval $[x_{k-1}, x_k]$, > for $k=0,1,2,\cdots,n$, then
$$
f(x_1^*){\Delta x} + f(x_2^*){\Delta x} + \cdots + > f(x_n^*){\Delta x}
$$
is called a **Riemann Sum** for $f$ on $[a, b]$. This sum is
1\. a **left Riemann Sum** if $x_k^*$ is the left endpoint of $[x_{k-1}, x_k]$
2\. a **right Riemann Sum** if $x_k^*$ is the right endpoint of $[x_{k-1}, x_k]$
3\. a **midpoint Riemann Sum** if $x_k^*$ is the midpoint of $[x_{k-1}, x_k]$

**Example 2** Area under the sine curve
>Solution
Todo

**Example 3** A midpoint Riemann Sum
>Solution
Todo

**Example 4** Riemann Sum from Tables
>Solution
Todo

##### Sigma (Summation) Notation

>Theorem 5.1 Sums of Positive Integers
Let $n$ be a positive integers
$$
\begin{aligned}
&\sum_{k=1}^n c = cn &
&\sum_{k=1}^n k = \frac{n(n+1)}{2} \\
&\sum_{k=1}^n k^2 = \frac{n(n+1)(2n+1)}{6} &
&\sum_{k=1}^n k^3 = \frac{n^2(n+1)^2}{4}
\end{aligned}
$$

##### Riemann Sums Using Sigma Notation

>Definition Left, Right, and Midpoint Riemann Sums in Sigma Notation
Suppose $f$ is defined on a closed interval $[a, b]$, which is divided into n subintervals of equal length $\Delta x$. If $x^*_k$ is a point in the kth subinterval $[x_{k-1}, x_k]$, for $k=1, 2, \cdots n$, then the Riemann sum of $f$ on $[a, b]$ is $\sum^n_{k=1}f(x^*_k)\Delta x$. Three cases arise in practice.
1\. left Riemann sum if $x^*_k = a + (k-1)\Delta x$
2\. right Riemann sum if $x^*_k = a + k\Delta x$
3\. midpoint Riemann sum if $x^*_k = a + (k-\frac{1}{2})\Delta x$
