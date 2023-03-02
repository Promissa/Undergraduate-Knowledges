## Definition
In [Boolean logic]( https://en.wikipedia.org/wiki/Boolean_logic "Boolean logic"), the **majority function** (also called the **median operator**) is the [Boolean function]( https://en.wikipedia.org/wiki/Boolean_function "Boolean function") that evaluates to false when half or more arguments are false and true.
$$
\langle p_1,p_2,\cdots,p_n\rangle=Majority(p_1,p_2,\cdots,p_n)=\lfloor\frac{1}{2}+\frac{(\Sigma_{i=1}^{n} p_i)-1/2}{n}\rfloor
$$
## 3-bit Majority Function
### Logical Circuit
![[Pasted image 20230303014015.png]]

### Truth Table
![[Pasted image 20230303014120.png]]