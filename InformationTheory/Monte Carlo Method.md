

Monte Carlo Method tries to solve 2 problem
#### Problem 1
Generate samples $\{\bf{x}^{(r)}\}_{r=1}^R$ from a probability distribution...
Essentially sample some points... sounds stupidly easy???

#### Problem 2
To calculate expected result?
$$
\Phi = \langle \phi(x)\rangle = \int d^Nx P(x)\phi(x)
$$
Just calculate the expected value a function might get? (a multidimensional function... input with more than one value)

Sounds easy right? but if you are given random probability distribution, can you manually pick a point so that the probability weight is maintained? 

If we can solve problem 1... we can solve problem 2
by avg 
$$
\Phi = \frac{1}{R}\sum \phi(x)
$$
Important fact about Monte Carlo method -> [[Monte Carlo Method Dimension Invariance]]
