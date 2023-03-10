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
For $a$ that $10^k a \in\mathbb Z \wedge 10^{k-1} a \notin \mathbb Z$, the non-terminating expansion is $0. a_1 a_2 \cdots a_{k-1}(a_k-1) 999\cdots$
### Proof.
Assume w.l.o.g. $a\ne 1$ and define a sequence of digits $a_0, a_1, a_2,\cdots \in\{0,1,\cdots, 9\}$ and a sequence of "remainders" $r_0, r_1, r_2,\cdots \in [0,1)$ recursively by $r_0 = a \space \wedge\space 10 r_{k-1}=a_k+r_k$ for $k\ge 1$. By induction we have $10 r_{k-1} \in [0,10)$, so that $a_k$ and $r_k$ are well-defined.
$r_1 = 10 a-a_1$
$r_2=10 (10 a-a_1)-a_2=10^2 a-10 a_1-a_2$
$r_3=10 (10^2 a-10 a_1-a_2)-a_3=10^3 a-10^2 a_1-10 a_2-a_3$ and
$r_k=10^k a - \sum_{i=1}^{k}10^{k-i}a_i$
Hence we have$$
\frac{r_k}{10^k}=a-\frac{a_1}{10}-\frac{a_2}{10^2}-\cdots-\frac{a_k}{10^k}=a-\sum_{i=1}^k \frac{a_i}{10^i}
$$Since $0\le r_k < 1$, this shows $a=\sum_{k=1}^{\infty}a_k 10^{-k}$
Moreover, assume $a=\sum_{i=1}^{\infty}a_i=\sum_{i=1}^{\infty}b_i$ and $n$ is the smallest index with $a_n \ne b_n$, we have $$
0=a-a=\sum_{k=0}^{\infty}(b_k-a_k)10^{-k}=\sum_{k=n}^{\infty}(b_k-a_k)10^{-k}
$$ Now $|b_n-a_n|\ge 1$ and $|a_k-b_k| \le 9$ for $k\ge n+1$. This gives$$
1\le \left|\sum_{k=n+1}^{\infty}(a_k-b_k)10^{n-k}\right| \le \sum_{k=n+1}^{\infty}|(a_k-b_k)|10^{n-k}\le \sum_{k=n+1}^{\infty}9\cdot10^{n-k} = \frac{9}{10}\frac{1}{1-1/10}=1
$$Hence equality should hold everywhere.
In particular, $|a_k-b_k|=9$ for $k \ge n+1$. This leaves $(a_k, b_k)=(0,9) \vee (9,0)$. If the first alternative holds for all $k\ge n+1$, the expansion $0. a_1 a_2\cdots$ would be terminating, contradiction. Similarly, the second alternative cannot hold for all $k\ge n+1$. Thus there exist $k, l \ge n+1$ such that $a_k-b_k>0 \wedge a_l-b_l<0$. But then the triangle inequality cannot hold with equality, so this is the final contradiction.
All above shows that the non-terminating decimal expansion of $a \in (0,1]$ is unique.
