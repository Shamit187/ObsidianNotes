![[Pasted image 20250517071125.png]]
$$
v(s) = \sum_a \pi(a|s) \sum_r \sum_{s'} p(r, s' | s, a) \left[ r + \gamma v(s')\right]
$$

So... $v(s)$ is actually a linear combination of all the other states that can be derived from $s$ 
$$v(s) = \sum_{\text{s' that can be derived from s}} c v(s')$$
You want to change [[Policy]] function $\pi(a|s)$ so that this equation is satisfied!
