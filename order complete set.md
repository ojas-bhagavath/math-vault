##### Theorem:

If $(A,\leq)$ is a [partially ordered set](partially%20ordered%20set.md), then the following are equivalent:

1. Every non-empty [bounded below](bounded%20sets.md) subset of $A$ has an [infimum](infimum%20and%20supremum%20of%20a%20subset.md) in $A$.
1. Every non-empty [bounded above](bounded%20sets.md) subset of $A$ has a [supremum](infimum%20and%20supremum%20of%20a%20subset.md) in $A$.

##### Proof:

$\implies$: Let $B$ be a non-empty bounded above subset of $A$, then $B$ has an upper bound in $A$, say $t_0$.

Consider the set $T:={x\in A:x \text{ is an upper bound of }B}$.  
Since $t\_{0}\in T$, $T$ is non-empty.

Fix some $b\in B$, then for any $x\in T$, by definition of $T$, $b\leq x$, hence $T$ is bounded below as $b$ is a lower bound of $T$.  
Hence by the hypothesis, $T$ must have an infimum, say $E$.

Since every element of $B$ is a lower bound of $T$, by definition of infimum, $x\leq E$ for any $x$ in $B$, hence $E$ is an upper bound of $B$.

If $y$ is any other upper bound of $B$, then $y$ belongs to $T$, and $E\leq y$.  
Hence, $E$ is a supremum of $B$.

$\impliedby$: This follows from the symmetry of the above argument.

##### Definition:

1. The first of the above properties is called **greatest lower bound property** or **GLB property**.
1. The second of the above properties is called **least upper bound property** or **LUB property**.
1. A set that has the above equivalent properties is said to be **order complete**.

---

tags: #theorem #proof #definition #order_theory #set_theory 
