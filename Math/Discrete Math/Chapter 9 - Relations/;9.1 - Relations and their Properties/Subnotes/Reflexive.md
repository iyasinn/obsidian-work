# Reflexivity

[[Properties of Relations]]

---

## Notes
### Define reflexivity for relations

>[!info] Reflexive
>
>A relation R on set A is reflexive if for all elements in A, they relate to themselves.
>
>Predicate Logic: R is transitive $\iff$ $\forall a \in A[aRa] \equiv \forall a \in A [(a, a) \in R]$

![[Pasted image 20220706213045.png]]


### How would you prove/disprove reflexivity? 

Since this is a for all statement, choose an arbitrary element a and show that it relates to itself. 

To disprove, just find one counterexample. 

### What should you be careful about regarding reflexivity

Check ever single part of the domain, including edge cases. Make sure to break things down!

Also be sure to consider elements that have no edges, but are still on the graph (just by themselves). These also need to be reflexive, at least to themselves. 

### Is the empty set for a graph (so no vertex and no edges) reflexive?
No, it is not. 
The empty set has no elements to relate to themselves, and hence it is not considered reflexive. 

### What would a reflexive relation look like graphically?

![[Reflexive 2022-07-06 21.49.56.excalidraw]]

We can also use the fact that the empty set is clearly [[irreflexive]] as proof as to why it is not reflexive, since a set cannot be both reflexive and irreflexive.



## Examples

- ![[Pasted image 20220706213116.png]]
	- R1 not reflexive, 3R3 not true
	  R2 not reflexive, 2R2 not true
	  R3 reflexive
	  R4 not reflexive, no 2R2
	  R5 reflexive
	  R6 not reflexive
	- ![[Pasted image 20220706213216.png]]
- ![[Pasted image 20220706213226.png]]
  ![[Pasted image 20220706213236.png]]
	- ![[Pasted image 20220706213245.png]]
- ![[Pasted image 20220706213249.png]]
	- Yes, since all positive integers divide itself
	- Note: If it was all integers, this would be false since 0 does not divide 0
	- Currently, the (0, 0) pair is not in the relation, due to this fact (if it was all integers). Just be mindful of what you’re visualizing
	- ![[Pasted image 20220706213329.png]]





