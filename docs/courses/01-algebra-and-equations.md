# Course 1: Algebra and Equations

A lesson-first course for manipulating expressions, solving equations, and controlling restrictions.

## How to use this course

Read one lesson, work the example without looking at the answer, then complete the linked practice chapter. Do not use a calculator unless a question explicitly allows it.

## Prerequisites

You should be comfortable with integer arithmetic, fractions, powers, and collecting like terms.

## Learning outcomes

By the end, you should be able to:

- factor and simplify expressions while preserving restrictions
- solve linear, quadratic, fractional, radical, exponential, and logarithmic equations
- use sign analysis and discriminants to reason about solutions
- choose an efficient algebraic route instead of expanding automatically

## Lesson 1: Expressions and factorisation

An expression is a value-producing combination of numbers and variables. An equation asserts that two expressions are equal. Factorisation reverses expansion and exposes structure.

Useful identities:

- $a(b+c) = ab+ac$
- $a^2-b^2 = (a-b)(a+b)$
- $a^2+2ab+b^2 = (a+b)^2$
- $a^2-2ab+b^2 = (a-b)^2$

**Worked example:** Factor $x^2-9x+20$.

Find two numbers with product `20` and sum `-9`: `-4` and `-5`. Therefore $x^2-9x+20 = (x-4)(x-5)$.

## Lesson 2: Equations and restrictions

Apply the same reversible operation to both sides. Before multiplying or dividing, record values that are not allowed. When squaring both sides, check every final answer in the original equation.

**Worked example:** Solve $1/(x-1) + 1/(x+1) = 1$.

The restrictions are $x \ne  1$ and $x \ne  -1$. Multiply by `(x-1)(x+1)`:

$(x+1)+(x-1)=x^2-1$

So $2x=x^2-1$, giving $x^2-2x-1=0$. Hence $x=1\pm\sqrt{2}$. Neither value violates the restrictions.

## Lesson 3: Quadratics and inequalities

For $ax^2+bx+c=0$, factorisation is often fastest. If it does not factor, use the quadratic formula:

$x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$

The discriminant $b^2-4ac$ tells you whether there are two, one, or no real roots. For inequalities, mark the roots on a number line and test the sign in each interval.

**Worked example:** Solve $x^2-5x+6 \le 0$.

Factor: $(x-2)(x-3) \\le 0$. The parabola is negative between its roots, so the answer is $2 \\le x \le  3$.

## Lesson 4: Powers, roots, and logarithms

Use the laws $a^m a^n=a^{m+n}$, $(a^m)^n=a^{mn}$, and $a^m/a^n=a^{m-n}$. For logarithms, $\log_a(x)=b$ means $a^b=x$, with $a>0$, $a \ne 1$, and $x>0$.

**Worked example:** Solve $3^{2x}-10(3^x)+9=0$.

Let $u=3^x$, where $u>0$. Then $u^2-10u+9=0$, so $(u-1)(u-9)=0$. Thus $3^x=1$ or $3^x=9$, giving $x=0$ or $x=2$.

## Common errors

- cancelling a factor without recording where it is zero
- accepting a value introduced by squaring
- forgetting endpoint inclusion in an inequality
- using the quadratic formula when a factorisation is immediate
- treating $\\sqrt{x^2}$ as `x` instead of `|x|`

## Checkpoint

Explain why restrictions must be checked in a fractional equation, then solve five mixed equations without notes.

## Practice

Continue with [Algebra and equations exercises](../exercises/chapters/01-algebra-equations.md).
