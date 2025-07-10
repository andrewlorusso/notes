# Derivative of Exponential 

## Overview

The derivative of $e^u$ when $u$ is a function of $x$ is is $e^u$ with the chain rule times the derivative of $u$ with respect to $x$  

The derivative of an exponential is itself with the chain rule 


## Exponential

A negative number can not be raised to an even radical, That would cause it to be imaginary
Derivation of the derivative of b^x Let B(X) = b^x, b >0
Assume B'(0) exists. By appliing the limit definiton to the derivitive at x = 0 we conculde

$$ B'(0) = \lim_{h \to 0} \frac{b^{0+h} - b^0}{h} = \lim_{h \to 0} \frac{b^h - 1}{h}. $$

If there is a composed function, we incorporate the Chain Rule:
$$ \frac{d}{dx}(e^{g(x)}) = e^{g(x)} g'(x) \quad \text{or} \quad \frac{d}{dx}(e^u) = e^u \frac{du}{dx}. $$


## Theorem: Derivative of $b^x$

Let $y = b^x$, then $\frac{dy}{dx} = \frac{d}{dx}(b^x) = b^x \ln b$. Incorporating the Chain Rule, we have
$$ \frac{d}{dx}(b^{g(x)}) = b^{g(x)} g'(x) \ln b \quad \text{or} \quad \frac{d}{dx}(b^u) = b^u \frac{du}{dx}\ln b = b^u(\ln b)\frac{du}{dx} $$
Again, you should memorize the second, $u$ form of the derivative.


### **Proof**
$$
\begin{aligned} y &= b^x && \text{original equation} \\ y &= e^{\ln b^x} && \text{log properties} \\ y &= e^{x \ln b} && \text{log properties} \\ \frac{dy}{dx} &= e^{x(\ln b)}\left(\frac{d}{dx}x(\ln b)\right) \qquad && \text{differentiate both sides, Chain Rule} \\ \frac{dy}{dx} &= e^{x(\ln b)}(\ln b) && \text{$\ln b$ is a constant} \\ \frac{dy}{dx} &= b^x (\ln b) && \text{log properties} \end{align*}
\begin{flushright}
\textit{QED}
\end{aligned}
$$
- Comments
-   (log property) If you take the natural log of something and then raise it to $e$ to that power that undo eachother (they are the same thing) this is becuase they are 1 to 1 inverse functions


### Implications

**Geometric**: Of all possible exponential functions  $y = b^x$, the function $f(x) = e^x$ is the one whose tangent tine at $(0,1)$ has a slope $f'(0)$ that is exactly $1$

**Derivative**: The function's derivative at a point $(x, e^x)$ is equal to the y-coordinate of the point
$$(e^x)^{\prime} = (e^x)$$

$e$ can be used to describe compound interest, and other forms of exponential growth, and exponential decline
Name: $e^x$ the natural exponential function. Natural because it used the natural base, and it grows at an exponential rate.
