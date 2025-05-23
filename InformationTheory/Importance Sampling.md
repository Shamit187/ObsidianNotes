Only works if we want to calculate expected value of $\phi(x)$

Instead of sampling from P(x)
Sample from Q(x), either uniform or Gaussian using [[Box Muller Method]]

![[Pasted image 20250518125028.png]]

in those samples, some of the items will have lower value in P than Q... Some will have higher value in P than Q...

If P(x) > Q(x) then that x is more important than we considered
If P(x) < Q(x) then x is less important 

for every sample point, we can generate $w_r=\frac{P(x)}{Q(x)}$

So to approximate
$$
\bar\phi = \frac{\sum_r w_r \phi(x_r)}{\sum_r w_r}
$$

We can show that 
$$
\bar\phi = \langle \phi \rangle
$$
but we cannot calculate variance of $\phi$
### Cautionary
It is better to use long tail distribution like [[Cauchy Distribution]] which will likely avoid horrible under weighting

![[Pasted image 20250519023746.png]]

### High Dimension Problem
In high dimension, importance sampling is really bad!
some points will dominate and through the entire mean off
