[[Markov Decision Process]] Works in an agent-environment interaction
![[Pasted image 20250517013024.png]]

[[Markov Decision Process]] and agent generates a pattern

S0 (initial state of the environment) -> A0 (Action by agent)
A0 -> R1 (reward provided by the environment) + S1 (next state by the environment)
S1 -> A1 (next action by agent)

S0, A0, R1, S1, A1, R2, S2, A2, ...
$$p(s',r|s, a) = Pr\{S_t = s', R_t=r| S_{t-1} = s, A_{t-1} = a\}$$
$$\sum_{s'\in S} \sum_{r\in R} p(s', r|s, a)$$
### Some Important value of this system
State-Transition Probability
$$p(s,a) = \sum_{r\in S} p(s', r | s, a)$$
Expected Rewards
$$r(s,a) \text{ or } \mathbb{E}_r(s, a) = \sum_{r\in S} r \times p (r | s, a)= \sum_{r\in S} r \sum_{s\in S} p(s', r | s, a)$$
I don't know why you would need this - Expected rewards for state, action, next-state 
$$r(s,a, s') = \sum_{r\in S} r \times p(r | s', a , s) = \sum_{r\in S} r \times \frac{p(s', r | s,  a) } { p(s' | s, a) } $$

