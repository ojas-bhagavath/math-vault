##### Theorem:

For any non-empty set $A$, there exists no [surjection](surjective%20function.md) from $A$ to the [power set](power%20set.md) $P(A)$ of $A$.  
In other words, the [cardinality](cardinal%20number.md) of $A$ is always less than that of $P(A)$.

##### Proof:

Let $f:A\to P(A)$ be a surjection.  
Notice that if $a\in A$, then $f(a)\in P(A)$, and $f(a)\subseteq A$.  
So, given any element $a\in A$, either $a\in f(a)$, or $a\notin f(a)$.

Consider the set $B:={a\in A:a\notin f(a)}$.  
Now $B$ is a subset of $A$ by [axiom of specification](zermelo-frankl-choice%20axioms.md), $B$ is a subset of $A$, hence an element in the co-domain of $f$.  
Now, since $f$ is a surjection, $B$ must have a preimage, say $x$, that is, $f(x)=B$.  
Now, either $x\in B$ or $x\notin B$.  
If $x\in B$ then by definition of $B$, $x\notin f(x)=B$.  
If $x\notin B$, then by definition of $B$, $x\in f(x)=B$.  
Which is absurd.  
Hence our assumption that $B$ has a preimage must be incorrect.  
Hence $f$ cannot be surjective.

---

tags: #theorem #proof #set_theory #analysis
