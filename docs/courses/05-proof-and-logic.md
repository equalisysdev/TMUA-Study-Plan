# Course 5: Proof and Logic

A lesson-first course for writing reliable arguments, using counterexamples, and choosing an appropriate proof structure.

## How to use this course

Write definitions before manipulating symbols. A numerical pattern can suggest a claim, but only an argument covering every allowed case proves it.

## Prerequisites

You should be comfortable with integers, algebraic notation, implication, and basic set language.

## Learning outcomes

- write direct proofs using definitions
- distinguish a statement from its converse and contrapositive
- use contradiction and induction
- disprove universal claims with precise counterexamples
- test whether a conclusion really follows from its assumptions

## Lesson 1: Direct proof

To prove an implication $P -> Q$, assume `P` and use valid steps to reach `Q`. For parity, write an even integer as `2k` and an odd integer as `2k+1`.

**Worked example:** If $a=2m$ and $b=2n$, then $a+b=2(m+n)$, which is even. The proof works for arbitrary integers `m` and `n`.

## Lesson 2: Converse and contrapositive

The converse of $P -> Q$ is $Q -> P$ and may be false. The contrapositive is $not Q -> not P$ and is logically equivalent to the original statement.

**Worked example:** The contrapositive of “if $n^2$ is odd then `n` is odd” is “if `n` is even then $n^2$ is even”. Proving this is straightforward by writing $n=2k$.

## Lesson 3: Counterexamples and contradiction

One counterexample disproves a universal claim. To prove by contradiction, assume the claim is false and derive an impossibility.

**Worked example:** “Every prime is odd” is false because `2` is prime and even. For a contradiction proof that $\\sqrt{2}$ is irrational, assume it equals a fraction in lowest terms and show both numerator and denominator must be even.

## Lesson 4: Induction

Induction has two required parts: prove the base case, then prove that truth at $n=k$ implies truth at $n=k+1$. The induction hypothesis may only be used for the case `k`.

**Worked example:** For $1+2+...+n=n(n+1)/2$, the base case is true at $n=1$. Assuming the formula at `k`, add `k+1` and simplify to `(k+1)(k+2)/2`.

## Common errors

- proving only several examples
- confusing the converse with the original statement
- using an unproved claim inside a contradiction
- skipping the base case in induction
- giving a counterexample that does not satisfy the assumptions

## Checkpoint

Classify four claims as true or false and choose direct proof, contradiction, induction, or counterexample before writing the argument.

## Practice

Continue with [Proof and logic exercises](../exercises/chapters/05-proof-logic.md).
