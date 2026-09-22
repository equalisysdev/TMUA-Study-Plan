# Corrections: Calculus

## Exercise Set A: Differentiation

### 1. Differentiate

Using the power rule,

$$
f'(x)=4x^3-9x^2+2.
$$

### 2. Differentiate

Use the product rule:

$$
g'(x)=2xe^x+x^2e^x=e^x(x^2+2x).
$$

### 3. Differentiate

Rewrite $h(x)=x+x^{-1}$. Therefore

$$
h'(x)=1-x^{-2}=1-\frac{1}{x^2}.
$$

### 4. Find the gradient at $x=2$

$$
\frac{dy}{dx}=3x^2-12x+9.
$$

At $x=2$,

$$
3(2)^2-12(2)+9=12-24+9=\boxed{-3}.
$$

### 5. Find and classify the stationary points

$$
y'=3x^2-6x=3x(x-2),
$$
so $x=0$ or $x=2$. The corresponding points are $(0,2)$ and $(2,-2)$.

Since $y''=6x-6$, we have $y''(0)=-6<0$ and $y''(2)=6>0$. Thus

$$
\boxed{(0,2)\text{ is a local maximum},\qquad
\boxed{(2,-2)\text{ is a local minimum}}.
$$

## Exercise Set B: Integration

### 6. Integrate

$$
\int(3x^2-4x+5)\,dx=x^3-2x^2+5x+C.
$$

### 7. Integrate

Let $u=2x+1$, so $du=2\,dx$:

$$
\int(2x+1)^4\,dx=\frac{(2x+1)^5}{10}+C.
$$

### 8. Evaluate

$$
\int_0^2(x^2+3x)\,dx
=\left[\frac{x^3}{3}+\frac{3x^2}{2}\right]_0^2
=\frac{8}{3}+6
=\boxed{\frac{26}{3}}.
$$

### 9. Find the enclosed area

The curves meet when $x^2=4$, so $x=-2$ and $x=2$. The area is

$$
\int_{-2}^{2}(4-x^2)\,dx
=\left[4x-\frac{x^3}{3}\right]_{-2}^{2}
=\boxed{\frac{32}{3}}.
$$

### 10. Find $y$

Integrate the derivative:

$$
y=2x^3-2x^2+C.
$$

Using $y(1)=5$ gives $5=2-2+C$, so $C=5$. Hence

$$
\boxed{y=2x^3-2x^2+5}.
$$

## Exercise Set C: Graph interpretation

### 11. Find where $f$ is increasing

$$
f'(x)=3x^2-12x+9=3(x-1)(x-3).
$$

The derivative is positive outside the roots, so

$$
\boxed{x<1\text{ or }x>3}.
$$

### 12. Horizontal tangents

A horizontal tangent has derivative zero:

$$
y'=6x^2-18x+12=6(x-1)(x-2).
$$

Therefore

$$
\boxed{x=1\text{ or }x=2}.
$$

### 13. Instantaneously at rest

Velocity is the derivative of displacement:

$$
v(t)=s'(t)=3t^2-12t+9=3(t-1)(t-3).
$$

Thus the particle is at rest at

$$
\boxed{t=1\text{ and }t=3}.
$$

### 14. Local maximum and minimum

$$
y'=3x^2-3=3(x-1)(x+1),
$$
so the stationary points occur at $x=-1$ and $x=1$. Their coordinates are $(-1,3)$ and $(1,-1)$.

Because $y''=6x$, the point $(-1,3)$ is a local maximum and $(1,-1)$ is a local minimum.

### 15. Area and sign check

A sketch is necessary because the area between a curve and the axis is geometric area, not a signed integral. Check whether the curve crosses the $x$-axis in $[0,3]$; if it does, split the integral at each root and take the absolute value of each signed part:

$$
\text{area}=\int_0^3|f(x)|\,dx.
$$
