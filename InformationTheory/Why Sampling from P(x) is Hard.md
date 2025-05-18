
P(x) can be a lot of complicated functions, some function maybe very difficult to even get the real value of. Let's make our life easier by saying we can at-least calculate P*(x). So that 
$$
P(x) = \frac{P^*(x)}{Z}
$$
for every x, we can calculate a value P*(x) which can be normalized to get actual P(x), we may not have the way to normalize the stuff... (Bayesian stuff can have scenarios where P*(x) is easier to calculate but P(x) is tough)

Btw, sometimes normalizing z is hard to calculate... like it's maybe easy for us to do it with calculus, but it's hard for a computer to do numerically

so, let's say in some area P(x) is large, some is small....  so more sample should come from those larger probability areas.
how would you know those areas if you don't iterate all the cases?
and if the possible state is large, it is impossible to iterate through all the case!

we can discretize stuff, but then we have to normalize, to normalize we have to iterate through all state

Few Sampling Method that can solve the issue
- [[Importance Sampling]] , only for estimating $\phi(x)$ \[Problem 2 in [[Monte Carlo Method]]\]
- [[Monte Carlo Method]]
