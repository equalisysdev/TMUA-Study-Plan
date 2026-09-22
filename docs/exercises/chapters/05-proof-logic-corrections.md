# Corrections: Proof and Logic

## Foundation

### 1. Even sum
Write the integers as $2m$ and $2n$. Their sum is $2(m+n)$, hence even.

### 2. Odd product
Write the integers as $2m+1$ and $2n+1$. Their product is $4mn+2m+2n+1=2(2mn+m+n)+1$, hence odd.

### 3. Odd square
If $n=2k+1$, then $n^2=4k^2+4k+1=2(2k^2+2k)+1$, hence odd.

### 4. Divisibility
If $n=6k$, then $n=3(2k)$, so $3\mid n$.

### 5. Counterexample
$2$ is prime but is not odd.

### 6. Counterexample
Take $a=2,b=1$. Then $ab=2$ is even, but $b$ is odd.

### 7. Converse
The converse is: $\boxed{\text{if }n\text{ is even, then }4\mid n}$.

### 8. Decide truth
The converse is false: $n=2$ is even but is not divisible by $4$.

### 9. First two odd numbers
The first two odd numbers are $1$ and $3$, and $1+3=\boxed4$.

### 10. Finite checking
The first 100 cases only establish the claim for those cases; a later integer could fail. A universal statement needs a general argument.

## Core technique

### 11. Induction
Base case $n=1$ is true. If $1+\cdots+k=k(k+1)/2$, then adding $k+1$ gives $(k+1)(k+2)/2$. Hence the formula holds for all $n\ge1$.

### 12. Induction
For $n=1$, the sum is $1=1^2$. If the sum to $k$ is $k^2$, then adding $2(k+1)-1$ gives $k^2+2k+1=(k+1)^2$.

### 13. Induction
At $n=1$, $2>1$. If $2^k>k$, then $2^{k+1}>2k\ge k+1$ for $k\ge1$. Thus $2^n>n$.

### 14. Irrationality of $\sqrt2$
Suppose $\sqrt2=a/b$ in lowest terms. Then $a^2=2b^2$, so $a$ is even, say $a=2c$. This gives $b^2=2c^2$, so $b$ is even, contradicting lowest terms.

### 15. No largest integer
If $N$ were largest, then $N+1$ would be an integer greater than $N$, a contradiction.

### 16. Contrapositive
The contrapositive of “if $n^2$ is odd then $n$ is odd” is $\boxed{\text{if }n\text{ is even, then }n^2\text{ is even}}$, which follows from $n=2k$.

### 17. Always even
$$n^2+n=n(n+1).$$ Consecutive integers include an even one, so the product is always even.

### 18. Three consecutive integers
Write them as $n,n+1,n+2$. Modulo $3$, one is congruent to $0$, so their sum is divisible by $3$; equivalently $3n+3=3(n+1)$.

### 19. Counterexample
Take $x=1/2$: $x^2=1/4<1/2=x$, so the claim is false.

### 20. Logical notation
“At least one of $A$ and $B$ is true” is $\boxed{A\lor B}$.

## TMUA challenge

### 21. Three consecutive integers
Among three consecutive residues modulo $3$, one is $0$. Therefore one of the integers is divisible by $3$.

### 22. Four consecutive integers
Among four consecutive integers there is a multiple of $4$ and at least one even number besides it, giving a factor $8$ in total; there is also a multiple of $3$. Hence the product is divisible by $8\cdot3=24$.

### 23. Infinitely many primes
If the primes were $p_1,\ldots,p_r$, consider $N=p_1p_2\cdots p_r+1$. No listed prime divides $N$, so $N$ has a new prime factor, contradiction.

### 24. Rational product
If $a=p/q$ and $b=r/s$ with nonzero integers $q,s$, then $ab=pr/(qs)$, which is rational.

### 25. Irrational sum
Yes. If both $a$ and $b$ were rational, then $a+b$ would be rational. Therefore $a+b$ irrational implies at least one of $a,b$ is irrational.

### 26. One-to-one
If $f$ is strictly increasing and $f(a)=f(b)$, neither $a<b$ nor $b<a$ can hold. Hence $a=b$, so $f$ is one-to-one.

### 27. Counterexample
The bounded sequence $a_n=(-1)^n$ is bounded but alternates between $-1$ and $1$, so it does not converge.

### 28. Same parity integers
Let $u=x+y$ and $v=x-y$, both even integers. Then $2x=u+v$ and $2y=u-v$, so $x,y$ are integers. Also $x+y$ even means $x,y$ have the same parity.

### 29. Divisibility
Modulo $n+1$, $n\equiv-1$, so $n^2+1\equiv2$. Thus $n+1\mid n^2+1$ only when $n+1\mid2$. For positive $n$, $\boxed{n=1}$.

### 30. Euclid's lemma
The theorem states: if $p$ is prime and $p\mid ab$, then $p\mid a$ or $p\mid b$. If $p\nmid a$, then $\gcd(p,a)=1$, so Bezout gives $up+va=1$. Multiplying by $b$ shows $b=upb+vab$, and both terms except possibly the first are divisible by $p$; hence $p\mid b$.
