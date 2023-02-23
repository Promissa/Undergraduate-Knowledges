# Field
## Definition
An algebraic structure consisting of a set $F$ and two operations $(a, b) \mapsto a + b$  (addition) and $(a, b) \mapsto a\cdot  b = ab$ (multiplication), which satisfy the usual laws of algebra known from $\mathbb{R}$. 
In particular, there must exist two distinguished elements $0, 1 \in F$ satisfying $a + 0 = a$ and $a · 1 = a$ for  $\forall \space a \in F$, and all equations $a + x = b$ ($a, b \in F$) and $ax = b$ ($a, b \in F, a \neq 0$) must be **uniquely solvable** (thus providing definitions of differences $a - b = a + (-b)$ and quotients $\frac{a}{b} = a \cdot b^{-1}$)
## A Hierarchy of Number Systems
$$\mathbb N = \{{1,2,3,\cdots} \}$$
$$
	\mathbb Z  = \{ \cdots,-2,-1,\space0,\space1,\space2,\space3,\cdots\}
$$

$$
\mathbb Q = \{ c \in \mathbb R; \space c=\frac{p}{q}\space for \space some \space p\in\mathbb Z,\space q\in\mathbb N\}
$$
$$
\mathbb A = \{ c \in \mathbb R;\space \sum_{i=0}^{r}a_ic^i=0\space for \space some \space a_i \in \mathbb Z \space \wedge \space \prod a_i \ne0\}
$$
$$
\mathbb R
$$
$$
\mathbb C = \{a+bi;\space a,b\in \mathbb R\}
$$
The chain of inclusions:
$$
\mathbb N \subset \mathbb Z \subset \mathbb Q \subset \mathbb A \subset \mathbb R \subset \mathbb C
$$
## Decimal Expansion
### Lemma
Every real number $a\in (0,1]$ has a unique non-terminating decimal expansion $$ a=\sum_{k=1}^{\infty}a_k 10^{-k} $$with $a_k \in \{0,1,\cdots, 9\}$ for all $k$ and $a_k\ne 0$ for infinitely many $k$ 
For $a$ that $10^k a \in\mathbb Z \wedge 10^{k-1} a \notin \mathbb Z$, the non-terminating expan