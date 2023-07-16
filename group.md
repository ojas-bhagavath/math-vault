Let $G$ be a non-empty set equipped with a binary operation $\circ$, then the ordered pair $(G,\circ)$ is said to form a group if it satisfies the following axioms:

1. **Closure**: For every pair of elements $x$, $y$ in $G$, the product $x\circ y$ is also an element of $G$
1. **Associativity**: For every triplet of elements $x$, $y$, and $z$ in $G$, the following holds $(x\circ y)\circ  z=x\circ (y\circ  z)$
1. **Existence of identity**: There exists an element $e$ in $G$ such that $e\circ x = x\circ e = x$ for every element $x$ in $G$. Such $e$ is said to be the identity of $(G,\circ )$
1. **Existence of inverse**: For each element $x$ in $G$, there exists an element $x^{-1}$ in $G$ such that $x\circ x^{-1}=x^{-1}\circ x=e$. Such $x^{-1}$ is called as the inverse of $x$ in $(G,\circ )$.

*Note*: Closure is omissible in the definition as  binary operation on a set itself will imply that the 'product' of any two elements under that operation will belong to the set.

---

#### Insights:

* A group can be seen as a set and an operation defined on pairs of elements of the set, but also, a group can be seen as a collection of [actions on a symmetric object](https://youtube.com/shorts/EYYNH0TH7ZA?feature=share). This makes more sense when we study [Dihedral Groups](Dihedral%20Groups.md), [Symmetric Groups](Symmetric%20Groups.md), and [Cayley's Theorem](Cayley's%20Theorem.md).

---

tags: #algebra #group_theory #definition
