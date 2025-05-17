We can unify the return of both [[Episodic Task]] & [[Continuing Task]]
$$
G_t = \sum_{k = t+1}^T \gamma^k R_{t+k+1}
$$
in Episodic task, $T$ is finite and $\gamma$ is 1
in Continuing task, $T$ is $\infty$ and $\gamma$ < 1