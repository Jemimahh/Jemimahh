---
layout: post
title: "Hello, World: Why Gradient Descent Works"
tags: [Math, Optimization, ML]
---

This first post verifies that math renders and code highlights work.

Inline math: \( a^2 + b^2 = c^2 \).

Block math:

$$
\\theta_{t+1} = \\theta_t - \\eta \\nabla_\\theta \\mathcal{L}(\\theta_t)
$$

Python code block:

```python
def step(theta, grad, lr=0.1):
    return theta - lr * grad
print(step(2.0, grad=0.3))
