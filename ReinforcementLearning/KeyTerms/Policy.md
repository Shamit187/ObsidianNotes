Mapping from state to probability of selecting an action
Defined as $\pi$
$\pi(a|s)$ is the probability of choosing action $a$ while is state $s$ 

>Reinforcement learning algorithm is the "Way" to change policy while gathering experience

### Optimal Policy
In **Finite MDP** There will always be at-least one policy that is better than anything else
That is called Optimal Policy
$$
v_*(s) = \max_\pi v_\pi(s) \text{ for all } s \in \mathcal{S}
$$
Yes, for all v it is going to give the best result!
Because of the way [[Bellman Equation]] works, we can mathematically proof that v*(s) exist.  (Proof is beyond my capabilities now, hopefully one day I can understand it!)

