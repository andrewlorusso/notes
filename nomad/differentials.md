## Linear Approximations

The **linear approximation** (or linearization) of a differentiable function $f(x)$ at a point $x=a$ is the tangent line to the function at that point. We use it to approximate function values near $x=a$.

The formula for the linearization, denoted $L(x)$, is derived from the point-slope equation of a line:
*   **Point:** $(a, f(a))$
*   **Slope:** $m = f'(a)$

The equation of the tangent line is:
$L(x) = f(a) + f'(a)(x-a)$

For values of $x$ close to $a$, the function $f(x)$ is approximately equal to the tangent line $L(x)$:
$f(x) \approx L(x)$ for $x \approx a$

## Differentials

Differentials provide the language to describe the changes involved in linear approximation.

Let's consider a change in $x$ from a point $a$ to a new point $a + \Delta x$.

#### 1. Actual Change (on the function curve)

*   The change in $x$ is **$\Delta x$**.
*   The **actual change** in $y$ is the difference between the two function values:
    $$\Delta y = f(a + \Delta x) - f(a)$$

#### 2. Approximate Change (on the tangent line)

*   The **differential $dx$** is defined as being identical to the change in $x$. It's an independent variable.
    $$dx = \Delta x$$
*   The **differential $dy$** is the corresponding change in height *on the tangent line*. It is a dependent variable.
    $$dy = L(a + dx) - L(a)$$
    Using the formula for $L(x)$, we can find a simpler expression for $dy$:
    $$dy = [f(a) + f'(a)(a+dx-a)] - f(a) = f'(a)dx$$
    So, the definition of the differential $dy$ is:
    $$dy = f'(a)dx$$

### The Key Relationship

The core idea of linear approximation is that the actual change ($\Delta y$) is approximately equal to the differential change ($dy$).

$$\Delta y \approx dy$$

Substituting the formulas we found:
$$f(a + \Delta x) - f(a) \approx f'(a)dx$$
Since $\Delta x = dx$, this is the fundamental approximation.

### Example: Finding the Linear Approximation for $f(x) = \sqrt[3]{x}$ at $x=-8$

1.  **Identify the point and function:**
    *   $f(x) = \sqrt[3]{x} = x^{1/3}$
    *   $a = -8$

2.  **Find the necessary values:**
    *   $f(a) = f(-8) = \sqrt[3]{-8} = -2$
    *   $f'(x) = \frac{1}{3}x^{-2/3} = \frac{1}{3\sqrt[3]{x^2}}$
    *   $f'(a) = f'(-8) = \frac{1}{3\sqrt[3]{(-8)^2}} = \frac{1}{3\sqrt[3]{64}} = \frac{1}{3 \cdot 4} = \frac{1}{12}$

3.  **Plug into the correct linearization formula:** $L(x) = f(a) + f'(a)(x-a)$
    $$L(x) = -2 + \frac{1}{12}(x - (-8))$$
    $$L(x) = -2 + \frac{1}{12}(x+8)$$
