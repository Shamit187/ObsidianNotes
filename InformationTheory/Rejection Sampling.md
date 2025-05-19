Wanting to sample from $P(x)$
Proposal density $Q(x)$

Also, another assumption
$$
c Q^*(X) > p^*(X), \text{ for all } x
$$
...
Ok so the idea is kinda like this...
![[Pasted image 20250519084408.png]]

You want to sample uniform points from a circle... but you only know how to sample from a rectangle... so you draw a large rectangle, sample from it. Draw a circle, the points in the circle should automatically be selected uniformly in a circle!! reject the points that don't exist inside the circle!

Same idea here...
![[Pasted image 20250519084645.png]]
You know how to sample from $cQ^*(x)$ ... so you uniformly sample from the space.
Then just take the points that only exists in $P^*(x)$

Way to generate sample from $cQ^*(x)$
- sample $x$ from $cQ^*(x)$
- sample $u$ from $\mathcal{U}(0,cQ^*(x))$
- accept the $x$ only if $u < P^*(x)$ or inside $P^*(x)$

Problem: if Q(x) is wildly different than P(x) then c has to be very large... rejection space will be large.
$\sigma_Q$ must be larger than $\sigma_P$ or else, no c will work

**But rejection sampling fails in higher dimension**
