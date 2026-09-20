# Course 3: Calculus and Change

A lesson-first course for derivatives, integrals, curve behaviour, optimisation, and area.

## How to use this course

Work symbolically first. Draw a rough curve whenever a question asks about increase, decrease, maxima, minima, or roots.

## Prerequisites

You should be confident with algebra, powers, coordinates, and basic functions.

## Learning outcomes

- differentiate standard functions and composite expressions
- interpret a derivative as a gradient or rate of change
- classify stationary points using sign changes or the second derivative
- integrate standard functions and calculate area
- translate optimisation problems into a function of one variable

## Lesson 1: Derivatives

The derivative `dy/dx` measures the instantaneous rate at which `y` changes as `x` changes. For powers, `d(x^n)/dx = nx^(n-1)`. Constants differentiate to zero.

**Worked example:** If `y=x^3-4x`, then `dy/dx=3x^2-4`. At `x=2`, the gradient is `8`.

Use the product rule for `uv`: `(uv)'=u'v+uv'`. Use the chain rule when one function is inside another.

## Lesson 2: Stationary points and shape

A stationary point occurs where `dy/dx=0`. A sign change from positive to negative indicates a local maximum; negative to positive indicates a local minimum. The second derivative can also help: positive suggests a minimum and negative suggests a maximum.

**Worked example:** For `y=x^3-3x`, `dy/dx=3x^2-3`, so stationary points occur at `x=+-1`. Substitution gives `( -1,2)` and `(1,-2)`. The first is a local maximum and the second a local minimum.

## Lesson 3: Integration and area

Integration reverses differentiation. Add a constant for an indefinite integral: `integral x^n dx = x^(n+1)/(n+1)+C` for `n != -1`. A definite integral gives signed area; split or subtract regions when the curve crosses the axis.

**Worked example:** The area between `y=x` and `y=x^2` on `[0,1]` is `integral_0^1 (x-x^2) dx = [x^2/2-x^3/3]_0^1 = 1/6`.

## Lesson 4: Optimisation and modelling

Write the quantity to optimise in one variable, find critical points, and compare them with endpoints and any boundary values.

**Worked example:** For a rectangle with sides `x` and `10-x`, area is `A=x(10-x)=10x-x^2`. Then `A'=10-2x`, so the maximum occurs at `x=5`, with area `25`.

## Common errors

- forgetting the constant of integration
- confusing a stationary point with a maximum
- using signed area when the question asks for total area
- differentiating a product as if only one factor changed
- ignoring endpoints in an optimisation problem

## Checkpoint

For a cubic, produce a derivative sign chart, classify its stationary points, and calculate the area between it and an axis on a stated interval.

## Practice

Continue with [Calculus and change exercises](../exercises/chapters/03-calculus-change.md).
