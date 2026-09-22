# Corrections: Proof, Logic, and Combinatorics

## Exercise Set A: Proof and logic

### 1. Sum of two even numbers

Let the two even numbers be $2m$ and $2n$, where $m,n\in\mathbb Z$. Their sum is

$$
2m+2n=2(m+n),
$$
which is divisible by $2$. Therefore the sum is even.

### 2. Induction formula

We prove

$$
1+2+\cdots+n=\frac{n(n+1)}{2}.
$$

For $n=1$, both sides equal $1$. Assume the statement holds for $n=k$:

$$
1+2+\cdots+k=\frac{k(k+1)}{2}.
$$

Then

$$
1+\cdots+k+(k+1)
=\frac{k(k+1)}{2}+k+1
=\frac{(k+1)(k+2)}{2}.
$$

This is the required formula with $n=k+1$, so the result holds for every positive integer $n$.

### 3. Odd square

If $n$ is odd, write $n=2k+1$. Then

$$
n^2=(2k+1)^2=4k^2+4k+1=2(2k^2+2k)+1,
$$
which is odd.

### 4. Multiplication preserves order

Since $a>b$, subtracting $b$ gives $a-b>0$. Since $c>0$,

$$
c(a-b)>0.
$$

Expanding gives $ac-bc>0$, hence $\boxed{ac>bc}$.

### 5. Divisibility by $3$

For a two-digit number $10a+b$,

$$
10a+b=9a+(a+b).
$$

The term $9a$ is divisible by $3$, so $10a+b$ and $a+b$ have the same remainder modulo $3$. Therefore $10a+b$ is divisible by $3$ exactly when $a+b$ is divisible by $3$.

## Exercise Set B: Counting and probability

### 6. Arrange 5 students

The first position has $5$ choices, then $4$, then $3$, then $2$, then $1$:

$$
5!=5\cdot4\cdot3\cdot2\cdot1=\boxed{120}.
$$

### 7. Choose a committee

Order does not matter, so use combinations:

$$
\binom{8}{3}=\frac{8\cdot7\cdot6}{3\cdot2\cdot1}=\boxed{56}.
$$

### 8. Draw a red ball

There are $4+3=7$ balls in total, with $4$ red balls. Thus

$$
\boxed{P(\text{red})=\frac47}.
$$

### 9. Dice total of $7$

There are $36$ equally likely ordered outcomes. The favourable outcomes are

$$
(1,6),(2,5),(3,4),(4,3),(5,2),(6,1),
$$
so

$$
\boxed{P(\text{total }7)=\frac{6}{36}=\frac16}.
$$

### 10. Four-digit numbers

All four digits must be used, and their order can be chosen in

$$
4!=\boxed{24}
$$

ways.

## Exercise Set C: Mixed reasoning

### 11. Choose 6 questions

The order of the chosen questions does not matter:

$$
\binom{10}{6}=\binom{10}{4}=\boxed{210}.
$$

### 12. Coefficient of $x^3$

By the binomial theorem, the coefficient is

$$
\binom{5}{3}=\boxed{10}.
$$

### 13. Exactly two heads

Choose which two of the three tosses are heads. There are $\binom{3}{2}$ such outcomes, each with probability $1/2^3$:

$$
P(\text{exactly two heads})=\binom{3}{2}\left(\frac12\right)^3=\boxed{\frac38}.
$$

### 14. Captain and vice-captain

The roles are different, so order matters. Choose the captain in $20$ ways and the vice-captain in $19$ ways:

$$
20\cdot19=\boxed{380}.
$$

### 15. Draw a yellow or blue ball

There are $10$ balls in total and $3+5=8$ that are yellow or blue. Therefore

$$
\boxed{P(\text{yellow or blue})=\frac{8}{10}=\frac45}.
$$
