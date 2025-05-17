Function of state / state-action pair
How good it is for the agent to stay in that state / How good it is for the agent to take that action in that state

Value functions are defined in terms of [[Expected Return]]

Mathematically, Value function, given that we are starting from $s$ and have a [[Policy]] $\pi$ 
$$
\begin{align}
v_\pi (s) &= \mathbb{E}[G_t | S_t = s] \\
&= \mathbb{E} \left[\sum_{k=1}^T \gamma^k R_{k+t+1} | S_t = s \right] \\
\end{align}
$$
If also defined for action then action-value function $q_\pi$ 
$$
\begin{align}
q_\pi (s) &= \mathbb{E}[G_t | S_t = s , A_t = a] \\
&= \mathbb{E} \left[\sum_{k=1}^T \gamma^k R_{k+t+1} | S_t = s, A_t = a \right] \\
\end{align}
$$

Value functions remain recursive
$$
\begin{align}
v_\pi (s) &= \mathbb{E}[G_t | S_t = s] \\
&= \mathbb{E}[R_{t+1} + \gamma G_{t+1} | S_t = s] \\
&= \sum_a \pi(a|s) \mathbb{E}[R_{t+1} + \gamma G_{t+1} | S_t = s, A_t = a]\\
&= \sum_a \pi(a|s) \sum_{s'}\sum_r p(r,s'|s,a) \mathbb{E}[r + \gamma G_{t+1} | S_t = s, S_{t+1} = s', A_t = a] \\
&\mathbb{E}[r + \gamma G_{t+1} | S_t = s, S_{t+1} = s', A_t = a] = \mathbb{E}[r + \gamma G_{t+1} | S_{t+1} = s'] \\ 
&= \sum_a \pi(a|s) \sum_{s'}\sum_r p(r,s|s,a) \mathbb{E}[r + \gamma G_{t+1} | S_{t+1} = s'] \\
&=\sum_a \pi(a|s) \sum_{s'}\sum_r p(r,s|s,a) \left[r + \gamma\mathbb{E}[ G_{t+1} | S_{t+1} = s']\right] \text{ r is now a constant} \\
&=\sum_a \pi(a|s) \sum_{s'}\sum_r p(r,s|s,a) \left[r + \gamma v(s')\right] 
\end{align}
$$
The final Equation is Called [[Bellman Equation]]
