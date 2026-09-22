# Course 2: Functions and Graphs

A lesson-first course for reading functions, transforming graphs, and reasoning about domains, ranges, and inverses.

## How to use this course

Sketch small diagrams as you read. After each lesson, complete a few questions from the practice chapter without relying on a graphing calculator.

## Prerequisites

You should be able to solve linear and quadratic equations and read coordinates on a graph.

## Learning outcomes

- interpret function notation and restrictions
- find domains, ranges, intercepts, and turning points
- apply graph transformations in the correct order
- compose functions and find inverses
- use intersections and monotonicity to count solutions

## Lesson 1: Function notation

A function assigns each allowed input exactly one output. In `f(x)`, `x` is the input and `f(x)` is the output. The domain is the set of allowed inputs; the range is the set of outputs produced.

**Worked example:** If $f(x)=3x-4$, then $f(5)=11$ and $f(-2)=-10$.

For $f(x)=\\sqrt{7-x}$, the domain requires $7-x \\\ge  0$, so $x \\le 7$.

## Lesson 2: Graphs and transformations

Starting from $y=f(x)$:

- $y=f(x)+a$ shifts up by `a`
- $y=f(x-a)$ shifts right by `a`
- $y=-f(x)$ reflects in the x-axis
- $y=f(-x)$ reflects in the y-axis
- $y=af(x)$ stretches vertically by factor `|a|`

The change inside the input acts in the opposite direction to the change outside it.

**Worked example:** $y=(x-3)^2-4$ comes from $y=x^2$ by shifting right 3 and down 4. Its vertex is `(3,-4)`.

## Lesson 3: Composite and inverse functions

Composition means substitution: $(f o g)(x)=f(g(x))$. To find an inverse, write $y=f(x)$, swap `x` and `y`, and solve for `y`. An inverse exists as a function only when the original function is one-to-one on the stated domain.

**Worked example:** For $f(x)=4x+1$, write $y=4x+1$, swap to $x=4y+1$, then $y=(x-1)/4$. Therefore $f^(-1)(x)=(x-1)/4$.

## Lesson 4: Intersections and solution count

Solutions of $f(x)=g(x)$ are x-coordinates where the graphs meet. To count solutions, compare shapes, turning points, asymptotes, and restrictions before calculating every intersection.

**Worked example:** Intersections of $y=1/x$ and $y=x-2$ satisfy $1/x=x-2$, with $x \ne  0$. Multiplying gives $x^2-2x-1=0$, so $x=1\pm\sqrt{2}$.

## Common errors

- confusing `f(x-a)` with a shift left
- finding a range without checking the domain
- assuming every function has an inverse
- forgetting that a denominator cannot be zero
- counting a graph intersection that lies outside the allowed domain

## Checkpoint

Given a transformed quadratic, state its vertex, domain, range, and inverse restrictions before solving any intersection.

## Practice

Continue with [Functions and graphs exercises](../exercises/chapters/02-functions-graphs.md).
