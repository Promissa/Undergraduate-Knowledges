# Vectors
## First Definition
A vector (with entries in the field $\mathbb{R}$ of real numbers) is an n-tuple (or sequence of length $n$)$$ \textbf v = (v_1, v_2, \cdots,v_n),\space v_i \in \mathbb{R} $$for some integer $n \geq 1$; $n$ is called the dimension of $\textbf v$. The set of all n-dimensional vectors is denoted by $\mathbb{R}^n$ (and called *real n space* or *n-dimensional Euclidean Space*)
## Equality of vectors
Two vectors $\textbf u = (u_1,u_2,\cdots,u_n)$, $\textbf v=(v_1,v_2,\cdots,v_n)$ are equal if $$\large u_1=v_1\space\wedge\space u_2=v_2\space\wedge\cdots\space\wedge u_n=v_n$$
## Row versus Column Vectors
$$\textbf v = (2,-1,5) =\bigg (\begin{aligned}2\\-1\\5\end{aligned} \space\space\bigg )$$
## Vector Addition
For  $\textbf u = (u_1,u_2,\cdots,u_n), \space \textbf v=(v_1,v_2,\cdots,v_n) \in \mathbb{R}^n$, we define $\textbf{u}+\textbf{v}\in\mathbb{R}^n$ by $$\large\textbf{u}+\textbf{v}=(u_1+v_1,u_2+v_2,\cdots,u_n+v_n)$$
## Scalar Multiplication
For $\textbf v = (v_1,v_2,\cdots,v_n)\in\mathbb{R}^n$ and $c\in\mathbb{R}$ we define $c\textbf v\in\mathbb{R}^n$ by $$\large c\textbf v = (c v_1, c v_2, \cdots, c v_n)$$
# The Dot Product
## Definition
If $\textbf a = <a_1, a_2, \cdots, a_n>,\space \textbf b = <b_1, b_2,\cdots, b_n>,\space \textbf a,\textbf b\in\mathbb{R}^n$, then the **dot product** is given by $$
\large \textbf a \cdot \textbf b=a_1b_1+a_2b_2+\cdots+a_nb_n=\sum_{i=1}^{n}a_ib_i
$$
## Projection
### Scarlar projection of $\textbf b$ onto $\textbf a$ 
$$\large comp_{\textbf{a}}{\textbf b} = \frac{\textbf a \cdot \textbf b}{|\textbf a|}$$
### Vector projection of $\textbf b$ onto $\textbf a$
$$
\large proj_{\textbf{a}}{b} = \frac{\textbf a \cdot \textbf b}{|\textbf a|^2}\textbf a
$$
### Orthogonal Projection of $\textbf b$ onto $\textbf a$
$$
\large orth_{\textbf a}{\textbf b} = \textbf b - proj_{\textbf{a}}{b}
$$
## Inequalities
### Cauchy-Schwartz Inequality
#### Vector Form
$$
|\textbf a \textbf b| \leq |\textbf a||\textbf b|\Leftrightarrow -1\leq\frac{|\textbf a \textbf b|}{|\textbf a||\textbf b|}\leq1
$$
#### Algebra Form
$$
\large\sum_{i=1}^n{a_i^2}\sum_{i=1}^n{b_i^2}\geq\sum_{i=1}^n(a_ib_i)^2
$$
### Triangle Inequality
$$
|\textbf a + \textbf b| \leq |\textbf a|+|\textbf b|
$$
## The Cross Product

If $\textbf a = <a_1, a_2, \cdots, a_n>,\space \textbf b = <b_1, b_2,\cdots, b_n>,\space \textbf a,\textbf b\in\mathbb{R}^n$, then the **cross product** is given by 
$$
 \left | \begin{array}{ccc}
 \textbf{i} & \textbf{j} & \cdots \\
 a_1 & a_2 & \cdots \\
 b_1 & b_2 & \cdots 
 \end{array} \right |
$$
# Determinant
## Definition
