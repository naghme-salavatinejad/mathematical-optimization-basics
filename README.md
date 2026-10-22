# Mathematical Optimization: Gradient Descent from Scratch

## Overview

This project implements the **Gradient Descent** optimization algorithm from the ground up using only `NumPy`. Instead of relying on high-level machine learning libraries, this implementation focuses on the fundamental mathematical principles of calculus and iterative optimization.

## Mathematical Background

The goal is to minimize a convex objective function $f(x)$. The update rule is derived from the first-order Taylor expansion, moving in the direction of the negative gradient:

$$x_{t+1} = x_t - \eta \cdot \nabla f(x_t)$$

Where:

* $x_t$: Current position.
* $\eta$ (eta): Learning rate (step size).
* $\nabla f(x_t)$: The gradient (derivative) of the function at $x_t$.

## Implementation Details

* **Objective Function:** $f(x) = x^2$
* **Gradient:** $f'(x) = 2x$
* **Tools used:** Python, NumPy, Matplotlib.

## How to Run

1. Ensure you have Python installed.
2. Install dependencies:

```bash
pip install numpy matplotlib
```
