Opposite to [[Episodic Task]], This type of task does not end...
So cannot formulate return function with simple reward sums

Concept we need is [[Discounting]]
Agent tries to maximize a discounted reward.
The [[Expected Return]] in this case,
$$
\begin{align}
	G_t &= R_{t+1} + \gamma R_{t+2} + \gamma^2 R_{t+1} + \dots = \sum \gamma^k R_{t+k+1} \\
	G_t &= R_{t+1} + \gamma G_{t+1}
\end{align}
$$


