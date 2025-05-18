Only works if we want to calculate expected value of $\phi(x)$

Instead of sampling from P(x)
Sample from Q(x)

![[Pasted image 20250518125028.png]]

in those samples, some of the items will have lower value in P than Q... Some will have higher value in P than Q...

If P(x) > Q(x) then that x is more important than we considered
If P(x) < Q(x) then x is less important 

for every sample point, we can generate $w_r=\frac{P(x)}{Q(x)}$

So to approximate
$$
\langle\phi\rangle = \frac{\sum_r w_r \phi(x_r)}{\sum_r w_r}
$$

