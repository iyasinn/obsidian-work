# Antisymmetric

[[Properties of Relations]]


---

## Notes
### Define antisymmetric

>[!info] Antisymmetric
>
>A relation R on set A is antisymmetric if there are no relations that go both ways, except for relations on the same elements. 
>
>So if (a, b) $\in R$, then it must be the case that (b, a) $\notin R$ unless $a = b$

Conceptually, antisymmetry is a ONE WAY relationship
That is, if there exists a relationship, it must be one way. If it isn’t one way, then we can say that the two elements we are relating are actually the same. 


a != b → (a,b) in R → (b, a) not in R

### Explain it in predicate logic
For R on set A
$$\forall x, y \in A [(a,b) \in R \land (b, a) \in R \to a = b] $$

equivalently
$$\forall x, y \in A [a \neq b \to \neg(aRb \land bRa)]$$
This is just the contrapositive. 
If a and b are not the same, it can’t be the case that (a, b) and (b, a) are in the relation. If a = b, then we don’t care. aRb AND bRa may both be in the relation, or only one of them might. 

### Is the empty set antisymmetric?

Yes, through a [[Vacouous and Trivial Proofs]] 
It vacuously fulfills the requirement for antisymmetric. 







## Examples
- ![[Pasted image 20220706230003.png]]
- ![[Pasted image 20220706230010.png]]
- ![[Pasted image 20220706230017.png]]
	- ![[Pasted image 20220706230022.png]]


