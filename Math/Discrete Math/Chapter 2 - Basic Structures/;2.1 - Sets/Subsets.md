# Subsets 

[[;2.1 - Sets]]
[[Set]]

It is possible for multiple sets to have similar elements. There are ***relationships*** between these sets 

#### What is a subset? What is a super set? 
>[!info] Subset and Superset
> A set **B** is a subset of another set **A** if and only if all elements in B are contained within A. In this case, A is a superset since it contains set B

![[Pasted image 20220619233951.png]]


#### What is the notation for a subset? 
$\subseteq$ = Is a subset of 
This is a predicate, and is either true or false
$B \subseteq A$ means “B is a subset of A”

$\nsubseteq$   =  Not a subset of. It should only have 1 line below, though. 


#### Showcase $B \subseteq A$ in predicate logic. 

$\forall x \in \mathbb{U} [x \in B \to x \in A]$

If B is a subset of A if and only if this statement is guaranteed to be true. 

$B \subseteq A \iff \forall x \in \mathbb{U} [x \in B \to x \in A]$

This states that for all elements in the domain, if those elements are in B, then they are in A. If this is the case, then B is a subset of A. 
#### What would $B \subseteq A$ look like in a Venn diagram? 

This is assuming they are proper subsets

![[Subsets 2022-06-19 23.40.43.excalidraw]]

![[Pasted image 20220620004250.png]]

#### Explain how a set can be a subset of itself? 
The statement 
$\forall x \in \mathbb{U} [x \in A \to x \in A]$
Will always be trivially true. See [[Subset Proofs]]

So a set can be a subset of itself. 


#### What is a proper subset? Notation? Predicate?

A proper subset is a set that is **NOT** equivalent to the superset. 

The notation is $B \subsetneq A$ which is again a predicate

$\forall x \in \mathbb{U} [x \in B \to x \in A] \land \exists x [x \in A \land x \notin B]$

This states that all elements of B must be in A, and that there must be an element of A that is not in B, hence A is larger. 

![[Pasted image 20220620004800.png]]

![[Pasted image 20220620004811.png]]

So here A is a proper subset of B. If it was not a proper subset, the **then the sizes should be the same**