$$
M(z) = \frac{az + b}{cz + d}
$$
Also known as
- linear
- bilinear
- linear fraction
- homographic

### Decomposition of Mobius Transformation
$$
\begin{align}
M(z) &= \frac{az + b}{cz + d} \\
&= \frac{a}{c} \times \frac{z + b/a}{z + d/c} \\
&= \frac{a}{c} \times \frac{z + d/c - d/c + b/a}{z + d/c} \\
&= \frac{a}{c} \times \frac{z + d/c}{z + d/c} + \frac{a}{c} \times \frac{b/a- d/c}{z + d/c} \\
&= \frac{a}{c} + \frac{\frac{cb - ad}{c^2}}{z + d/c}
\end{align}
$$
- $z + d/c$ : A translation
- $\frac{1}{z}$ : [[Inversion]]
- $z\frac{cb-ad}{c^2}$ : Rotation and Scaling
- $z+\frac{a}{c}$: A transformation

#### Singular Case
if $cb - ad  = 0$ then $M(z) = a/c$ no matter what z...  
> We assume that $cb - ad  \ne 0$


