---
tags:
  - function
---
# Exponential

## Overview

**Intuitive idea:** Functions that exhibit multiplicative growth (or decay) at a constant relative rate.

$$y = ab^x = ae^{kx}$$
- The bases are related by the formula $b = e^k$, or equivalently, $k = \ln(b)$.

### Forms
**Alternative forms which express the same relationship**
- Any function which can be expressed in one form can be expressed in the other.

- Both forms describe a **continuous function** (their graphs have no breaks). However, $y = ae^{kx}$ is used to represent **continuously compounded growth**. This describes the *process* by which growth occurs.
- The change is happening at every instant, not in discrete, countable steps. The constant $k$ represents this instantaneous rate of change. This is the result of compounding an infinite number of times over a time interval.

- The form $y = ab^x$ is typically used to represent growth or decay that occurs at discrete intervals. The base $b$ is the factor by which the quantity changes over one interval.

### Absolute Growth Rate

A quantity exhibits exponential growth if its **rate of change** is directly **proportional** to its **current amount**.
- The absolute growth rate (e.g., dollars per year) depends on the current size of the dependent variable, $y$.

**Relationship represented as a differential equation**
$$ \frac{dy}{dt} = ky $$
- If a phenomenon obeys this rule, it is, by definition, exponential.

#### Relative Growth Rate
- Rearranging the absolute growth rate equation reveals the relative growth rate:
$$ \frac{1}{y} \frac{dy}{dt} = k $$
- This shows that for exponential functions, the **relative growth rate is constant**, and is equal to $k$.

#### Solving the Differential Equation
- The exponential function is the solution to the differential equation $\frac{dy}{dt} = ky$.
- The process of solving for $y$ involves integration, which finds the aggregate result of this continuous change.
- The resulting exponential function, $y(t) = Ae^{kt}$, gives the current amount, $y$, at any given instant, $t$.

**Examples**
- A small population of bacteria grows slowly in absolute numbers.
- A large population of bacteria grows quickly in absolute numbers.
- The more money held in a bank account, the more interest is earned per year.


$$f(x) = a \cdot b^x$$

**Where**
- $a$: the initial value, where $a \neq 0$
- $b$: the growth factor, where $b > 0$ and $b \neq 1$
- $x$: the independent variable, where $x \in \mathbb{R}$

**Properties**
- Inverse: [logarithm]()

### Exponential Growth
- Exponential growth or decay is determined by the base value, $b$.
- If $b > 1$, the function models exponential growth.

**Natural Exponential Function**
- The exponential function where the base is [[euler's number|e]] and the initial value is 1.
$$f(x)=e^x$$

### Exponential Decay
- Exponential growth or decay is determined by the base value, $b$.
- If $0 < b < 1$, the function models exponential decay.
