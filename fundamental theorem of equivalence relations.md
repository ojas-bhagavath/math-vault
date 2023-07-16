##### Theorem:

If $A$ is any non-empty set and if $R$ is any [equivalence relation](equivalence%20relation.md) on $A$, then the [quotient set](equivalence%20classes%20and%20quotient%20set.md) $A/R$ forms a [partition](partition%20of%20sets.md) of $A$, and conversely, any partition $P$ of $A$ induces an equivalence relation on $A$.

##### Proof:

$\implies$: Let $R$ be an equivalence relation on the set $A\neq\varnothing$.  
The quotient set is $A/R:={cl(a):a\in A}$.

Since $R$ is [reflexive](equivalence%20relation.md), $aRa$ for each $a$ in $A$, hence $\cup{cl(a):cl(a)\in A/R}=A$.

Suppose $cl(a)$ and $cl(b)$ are distinct elements of $A/R$, and let $x\in cl(a)\cap cl(b)$.  
$\implies x\in cl(a)\land x\in cl(b)$.

Since $x\in cl(a)$, it implies that $aRx$.  
And since $x\in cl(b)$, it implies that $bRx$, which implies that $xRb$ due to [symmetry](equivalence%20relation.md).

$aRx$ and $xRb$ imply that $aRb$ due to [transitivity](equivalence%20relation.md).  
Then if $y\in cl(a)\implies y\in cl(b)$, and $y\in cl(b)\implies y\in cl(a)$.  
Which in turn imply that $cl(a)=cl(b)$, which is a contradiction, hence distinct equivalence classes have to be disjoint.

Each [equivalence class](equivalence%20classes%20and%20quotient%20set.md) is trivially non-empty.  
Hence, the collection of equivalence classes defines a [partition](partition%20of%20sets.md) on $A$.

$\impliedby$: If $P:={A\_{\lambda}:\lambda\in\Lambda}$ is a partition on $A$, then  
$R=\cup{A\_{\lambda}\times A\_{\lambda}:\lambda\in\Lambda}$ is an equivalence relation on $A$.

---

tags: #theorem #proof #set_theory #analysis #algebra 
