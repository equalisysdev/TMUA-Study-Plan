# Course 6: Combinatorics and Probability

A lesson-first course for systematic counting, arrangements, selections, and probability models.

## How to use this course

Before calculating, decide whether order matters, whether repetition is allowed, and whether the outcomes are equally likely.

## Prerequisites

You should be comfortable with fractions, products, sums, and basic algebra.

## Learning outcomes

- apply the product and sum rules
- distinguish permutations from combinations
- count with restrictions and repeated objects
- calculate simple, conditional, and complementary probabilities
- find expected values and use binomial reasoning

## Lesson 1: Product and sum rules

If a process has `a` choices followed by `b` choices, it has `ab` outcomes. If alternatives are mutually exclusive with `a` and `b` outcomes, there are `a+b` outcomes.

**Worked example:** A 3-digit number using distinct digits from `1,2,3,4,5` has $5*4*3=60$ possibilities.

## Lesson 2: Arrangements and selections

An arrangement of `r` objects from `n` is $nPr=n!/(n-r)!$ because order matters. A selection is $nCr=n!/(r!(n-r)!)$ because order does not matter.

**Worked example:** A committee of 3 from 8 people can be chosen in $8C3=56$ ways. A captain and vice-captain from 10 people can be chosen in $10*9=90$ ways because the roles differ.

For repeated objects, divide by the factorial of each repetition count. For example, BANANA has `6!/(3!2!)` distinct arrangements.

## Lesson 3: Probability

For equally likely outcomes, $P(A)=number of favourable outcomes / total outcomes$. The complement rule is $P(not A)=1-P(A)$. For dependent stages, multiply conditional probabilities along a branch.

**Worked example:** The probability of exactly two heads in three fair tosses is `3/8`, because the favourable patterns are HHT, HTH, and THH.

## Lesson 4: Conditional probability and expectation

Conditional probability is $P(A|B)=P(A and B)/P(B)$. A probability tree keeps changing totals visible. The expected value of a discrete variable is the weighted sum $E(X)=sum of xP(X=x)$.

**Worked example:** A fair die has expected score $(1+2+3+4+5+6)/6=3.5$. For eight fair coin tosses, the expected number of heads is $8*(1/2)=4$.

## Common errors

- using permutations when order does not matter
- forgetting the first choice changes the next number of choices
- assuming events are independent without evidence
- counting the same outcome in multiple ways
- using $P(A and B)=P(A)P(B)$ for dependent events

## Checkpoint

For every counting question, write “order matters” or “order does not matter” before selecting a formula.

## Practice

Continue with [Combinatorics and probability exercises](../exercises/chapters/06-combinatorics-probability.md).
