Well studied approach to balance exploration and exploitation in k-bandit algorithm
Computes a special "Action-Value"
In Special Case
- We need prior distribution knowledge
- Tractable (Polynomial Time) and leads to optimal solution
- Cannot be generalized to all reinforcement learning
"The Gittins-index approach is an instance of Bayesian methods, which assume a known  
initial distribution over the action values and then update the distribution exactly after  
each step (assuming that the true action values are stationary). In general, the update  
computations can be very complex, but for certain special distributions (called conjugate  
priors) they are easy. One possibility is to then select actions at each step according  
to their posterior probability of being the best action. This method, sometimes called  
posterior sampling or Thompson sampling, often performs similarly to the best of the  
distribution-free methods"