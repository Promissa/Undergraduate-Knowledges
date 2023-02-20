# Vectors
## First Definition
A vector (with entries in the field $\mathbb{R}$ of real numbers) is an n-tuple (or sequence of length $n$)$$ \textbf v = (v_1, v_2, \cdots,v_n),\space v_i \in \mathbb{R} $$for some integer $n \geq 1$; $n$ is called the dimension of $\textbf v$. The set of all n-dimensional vectors is denoted by $\mathbb{R}^n$ (and called *real n space* or *n-dimensional Euclidean Space*)
## Equality of vectors
Two vectors $\textbf u = (u_1,u_2,\cdots,u_n)$, $\textbf v=(v_1,v_2,\cdots,v_n)$ are equal if $$u_1=v_1\space\wedge\space u_2=v_2\space\wedge\cdots\space\wedge u_n=v_n$$
## Row versus Column Vectors
$$\textbf v = (2,-1,5) =\bigg (\begin{aligned}2\\-1\\5\end{aligned} \space\space\bigg )$$
## Vector Addition
For  $\textbf u = (u_1,u_2,\cdots,u_n), \space \textbf v=(v_1,v_2,\cdots,v_n) \in \mathbb{R}^n$, we define $\textbf{u}+\textbf{v}\in\mathbb{R}^n$ by$$\textbf{u}+\textbf{v}=(u_1+v_1,u_2+v_2,\cdots,u_n+v_n)$$
## Scalar Multiplication
For $\textbf v = (v_1,v_2,\cdots,v_n)\in\mathbb{R}^n$ and $c\in\mathbb{R}$ we define $c\textbf v\in\mathbb{R}^n$ by $$c\textbf v = (c v_1, c v_2, \cdots, c v_n)$$
## The Dot Product
### Definition
If $\textbf a = <a_1, a_2, \cdots, a_n},\space \textbf b = <b_1, b_2,\cdots, b_n}\in\mathbb{R}^n $
### Projection
#### Scarlar projection of $\textbf b$ onto $\textbf a$ 
$$comp_a{\textbf b} = \frac{\textbf a \cdot \textbf b}{|\textbf a|}$$
#### Vector projection of $\textbf b$ onto $\textbf a$
$$
proj_a{\textbf b} = \frac{\textbf a \cdot \textbf b}{|\textbf a|^2}\textbf a
$$
### Inequalities
#### Cauchy-Schwartz Inequality
$$
|\textbf a \cdot \textbf b| \leq |\textbf a||\textbf b|
$$
#### Triangle Inequality
$$
|\textbf a + \textbf b| \leq |\textbf a|+|\textbf b|
$$
