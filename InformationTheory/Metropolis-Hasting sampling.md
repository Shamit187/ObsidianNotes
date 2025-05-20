Inspiration
You start with an initial distribution, but slowly move the distribution toward points where the probability might be the larger...
Uses a step by step method

- Fix a guess distribution, it's parameter is dependent on $X_0$, the initial state
- Sample a new value $\tilde X$. 
- Calculate $P(\tilde X)/ P(X_0) \times Q(X_0 | \tilde X)/Q(\tilde X | X_0) = \alpha$
- if $\alpha > 1$ then $\tilde X$ is gold!, the distribution is going to right places!, we take that as the new state
- else, we may take the new sample, but with a lower probability to encourage exploration

