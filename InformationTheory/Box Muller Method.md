Algorithm for generating sample for $\mathcal{N}(0,1)$ distribution from $\mathcal{U}(0,1)$ 
$$
\begin{align}
u_1, u_2 \sim \mathcal{U}(0,1) \\
n_1 = \sqrt{-2 \ln u_1} \cos{2\pi u_2} \\
n_2 = \sqrt{-2 \ln u_1} \sin{2\pi u_2} \\
\implies n_1, n_2 \sim \mathcal{N}(0,1) \\
\end{align}
$$

Proof is still not comprehensible