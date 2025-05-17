$z = re^{i\theta}$
which means, 1/z is essentially, inverting radius and negative angle
$1/z = \frac{1}{r} e^{-i\theta}$
- Step 1: Geometric Inversion / Reflection
- Step 2: Reflection

### Visualizing Inversion
![[Pasted image 20250517111111.png]]
In Unit circle, C it acts as a reflection, 
- internal points (r < 1) will get flipped to external (r > 1)
- external points will get to internal
- if any point is on C, it will stay on that point
- Denoted as $\mathcal{J}_C \mapsto \frac{1}{\bar{z}}$ 

We can generalize this mapping to any circle K
![[Pasted image 20250517111515.png]]
for any radius R,
- length becomes $R^2/p$ if initial length is $p$
- any point on the circumference stays there

Process:
1. Shift the origin to q, $z' = z-q$
2. Scale R to 1, $z' = \frac{1}{R}z$
3. invert, $z' = \frac{1}{\bar{z}}$
4. Scale back to original, $z' = Rz$
5. Fix origin, $z' = z + q$

All together:
$$
z = \frac{R^2}{\bar{z} - \bar{q}} + q
$$

### Similarity between Line Reflection $\mathcal{R}_L$  and  Circle Reflection $\mathcal{R}_C$

Line reflection:
- Divide the entire region into two parts
- Something in the line stays in the line
- Self inverse, apply twice, get the same result

![[Pasted image 20250517232933.png]]

$[ab]$ -> distance between $a$ and $b$

$\tilde a$ is the inverse of $a$ 
... so $[qa][q\tilde a] = [qb][q\tilde b] = R^2$
$[qa] / [q\tilde b] =[qb] / [q\tilde a]$ and $\angle qab = \angle q \tilde a \tilde b$ 
... two side has same ratio, one common angle... so a similar triangle
$[qa] / [q\tilde a] = [qb] / [q\tilde b] = [a b] / [\tilde a \tilde b]$
... Which would imply,
$[\tilde a \tilde b] = \frac{R^2}{[qa][qb]}[a,b]$


### $R_C$ switches a line to a fucking circle!!!!
Proof done using [[Inversion#Similarity between Line Reflection $ mathcal{R}_L$ and Circle Reflection $ mathcal{R}_C$]] 
Geometric proof, \[ Remember, Circle points generate $90^0$ angle with the radius\]

![[Pasted image 20250518030926.png]]
### $R_C$ keeps a circle a circle if the circle does not go through q!!!

![[Pasted image 20250518030937.png]]
