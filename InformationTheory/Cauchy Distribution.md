
### How to generate a cauchy distribution

Take a spinner in a graph
![[Pasted image 20250519013445.png]]

Make that spinner randomly spin into an angle, extend that line to get an intersection with x axis
![[Pasted image 20250519013525.png]]

If we spin uniformly, we get cauchy sample!
![[Pasted image 20250519013636.png]]

### Interesting Property of Cauchy

Does not have an expected value!
Some how it is stable! [[Stable Distribution]]

$$
P(x) = \frac{1}{\pi} \frac{1}{1+x^2}
$$
you cannot do this, it's infinite
$$
\mathbb{E}[x] = \frac{1}{\pi} \int_\infty^\infty \frac{x}{1+x^2} dx = \infty
$$
Which means, if you sample a lot of numbers, it keeps diverging!
if we cannot calculate mean, we also cannot calculate variance

It is long tail distribution, means, we can always get very large values!