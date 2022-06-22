# Subset Proofs

[[;2.1 - Sets]]
[[Subsets]]

Subset proofs are very interesting

#### How do you show that $B \subseteq A$?
You can approach this similar to a natural deduction problem, since really, we are proving: $$\forall x \in \mathbb{U} [x \in B \to x \in A]$$
To prove this, we can :
- Consider an arbitrary element x in the universe. 
- Assume x is an element of B. 
- Use that information to show that if it is an element of B, then it must be an element of A. 
- Conclude the proof by stating that this is true for all arbitrary elements and that B is a subset of A. 

![[Pasted image 20220619235045.png]]


#### How do you show that $B \nsubseteq A$

You merely need to find one element that is an element fo B but not an element of A

![[Pasted image 20220619235113.png]]

It is really just a proof by contradiction, as we assume it is a  subset of A, then find a counterexample

![[Pasted image 20220620003434.png]]




#### What two sets is every nonempty set ***guaranteed*** to have as a subset? Prove it

Every set is guaranteed to have the [[Empty Set]] and itself as its subsets. 

**Empty set proof for set $\mathbb{Z}$:** 
$$\forall x [x \in \emptyset \to x \in \mathbb{Z}]$$
The thing is, $x \in \emptyset \equiv F$
Since the empty set has no elements, so this is really just 
$$\forall x [F \to x \in \mathbb{Z}] \equiv T$$
This is vacuously true. 
This is av vacuous proof 
[[Vacouous and Trivial Proofs]]

**Set is a subset of itself proof**
$$\forall x [x \in \mathbb{Z} \to x \in \mathbb{Z}]$$
Equivalent to
$\forall x [x \notin \mathbb{Z} \lor x \in \mathbb{Z}] \to \forall x [T] \equiv T$

As seen, this is merely just trivially true, since it is always true. 
This ia Trivial proof
[[Vacouous and Trivial Proofs]]

![[Pasted image 20220620004057.png]]


#### What subsets does the $\emptyset$ have?
The only subset it has is itself, the empty set. 
Or phrased in another way
The only subset is the empty set

Regardless, it’s in the empty set in both cases. 


#### How do you show **equality** between two sets
To show equality between sets, we can merely show that they are both subsets of each other. That way we know they are equivalent. 

![[Pasted image 20220620005928.png]]

###### How can you show two sets are equivalent?
- Use set equivalences to convert one to another
- Show that one set is a subset of the other through the process outlined, but do so in both directions. 