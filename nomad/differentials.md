## Linear Approximations

The **linear approximation** (or linearization) of a differentiable function $f(x)$ at a point $x=a$ is the tangent line to the function at that point. It is used to approximate function values near $x=a$.

The formula for the linearization, denoted $L(x)$, is derived from the point-slope equation of a line:
*   **Point:** $(a, f(a))$
*   **Slope:** $m = f'(a)$

The equation of the tangent line is:
$L(x) = f(a) + f'(a)(x-a)$

For values of $x$ close to $a$, the function $f(x)$ is approximately equal to the tangent line $L(x)$:
$f(x) \approx L(x)$ for $x \approx a$

## Differentials

Differentials provide the language to describe the changes involved in linear approximation.

Consider a change in $x$ from a point $a$ to a new point $a + \Delta x$.

#### 1. Actual Change (on the function curve)

*   The change in $x$ is **$\Delta x$**.
*   The **actual change** in $y$ is the difference between the two function values:
    $$\Delta y = f(a + \Delta x) - f(a)$$

#### 2. Approximate Change (on the tangent line)

*   The **differential $dx$** is defined as being identical to the change in $x$. It is an independent variable.
    $$dx = \Delta x$$
*   The **differential $dy$** is the corresponding change in height on the tangent line. It is a dependent variable.
    $$dy = L(a + dx) - L(a)$$

### Key Formula for the Differential dy

The definition of the differential $dy$ is derived from the change on the tangent line:
$$dy = [f(a) + f'(a)(a+dx-a)] - f(a) = f'(a)dx$$

This results in the fundamental formula for the differential $dy$:

> $$dy = f'(x)dx$$

### The Key Relationship

The core idea of linear approximation is that the actual change ($\Delta y$) is approximately equal to the differential change ($dy$).

$$\Delta y \approx dy$$

### Abuse of Notation

Treating a differential like a normal number can be considered an **abuse of notation**.

Strictly speaking, the derivative symbol $\frac{dy}{dx}$ is a single operator representing the result of a limit and is not a fraction. However, by formally defining the differentials $dx$ and $dy = f'(x)dx$, the derivative can be treated *as if* it were a fraction.

Multiplying both sides of the equation $f'(x) = \frac{dy}{dx}$ by $dx$ is a procedural shortcut. This action is justified by the formal definition of differentials. Therefore, while this practice may appear to be an "abuse" of the original limit notation, it is a mathematically valid and powerful technique.
