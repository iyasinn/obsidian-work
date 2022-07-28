# Composition of Relations

[[;9.1 - Relations and their Properties]]
[[Relations]]
[[Relations ON a Set]]

---

## Relation Compositions
### Explain the composite of a relation R and S

![[Pasted image 20220707132203.png]]

The composite **contains** all ordered pairs such that the first ordered value is passed through the first inner relation, then the outer relation, and the second ordered value is the output. 

Hence, the **composition** is just ANOTHER relation

### Explain in predicate logic
We state in predicate logic that for some given composition for R $\circ$ S

x (R $\circ$ S) y $\iff \exists z[xRz \land zRy]$
Which is the same as 
x (R $\circ$ S) y $\equiv z[xRz \land zRy]$


So x (R $\circ$ S) y is an element aka ordered pair of the relation if and only if there is some intermediary between them

### What requirement is needed for the domain and codomain of a relation, say $R \circ S$

In this case, we apply S first
So the codomain of S needs to be the domain of R
Aka each element in S needs to be assigned to an output of S that is an element of the domain of R

So you need to be able to find a relation that takes in a codomain value from S as the first ordered pair value and the domain in R as the second

We always go from inner to outer, like in function compositions [[Function Compositions]]

Technically this isn’t a requirement….since if R maps no elements, then it doesn’t matter, $R \circ S$ would just be an empty set (this isn’t like functions where a mapping is required)

So just be flexible about it 


### Can we compose multiple relations together?
Yes
We can have $R \circ S \circ T$ for example

## Relation Compositions on Sets

### Explain how we can compose relations with themselves? 
Let’s say we have a relation R **on set A**


To compose it with itself is $R \circ R$
This would just mean that for any ordered pair, say (x, y) $\in R \circ R$
then this must be equivalent to (by biconditional) 
$\exists z [xRz \land yRz]$

Domain and codomain match up, but they don’t really need to 

### Can you compose relations on themselves if they aren’t ON some specific set? 

You can, but ONLY if the codomain is a subset of the domain. Otherwise, you cannot. 



### Recursively define a relation on itself for any n times. 
![[Pasted image 20220707133435.png]]

Note that R^2 implies then that we have ONE intermediary, and R^3 will imply that we have 2 intermediaries. 

x($R^3$)y $\equiv$ $\exists z, n [xRz \land zRzn \land nRy]$


### Can we move around values in a composition of a relation to itself?
Yes
Say we have $R^{5}=R^{4}\circ R$
We can also say 
$= R \circ R^{4}=R^{3}\circ R^2=...$
As seen, since this is a relation on itself and the domain and codomain always map up, this will always be true. 


### Conceptually, how can we view relations composed with themselves, say $R \circ R$, and how to do problems with them? 
We can view it as saying that the “path” from the first element to the second needs to have some intermediary, whatever that is. If that’s the case, then our first and second element can form an ordered pair in the relation $R \circ R$

So it will take two relations to get from the start to the end (2 relationships)

So the ordered pair will be (some first value) passing through itself twice to get the second value. 

This is **the same as** going through some **path** in the graph twice





### How can we use compositions to see if a relation is transitive? 
![[Pasted image 20220707143316.png]]

**Inductionn is very very useful.**

Prove R^n subset R → R on set A is transitive

Induction is actually really really good here 

Show R^n + 1 is a transitive 

R^(n + 1) = R^n $\circ$ R

So assume we have x(R^n + 1)y and y(R^n + 1 z)




## Examples


- ![[Pasted image 20220707132847.png]]
	- ![[Pasted image 20220707132855.png]]


**Composing relations on themselves**
- ![[Pasted image 20220707133737.png]]
	- R2: {(1, 1), (2, 1), (3, 1), (4, 2)}
	- R3: {(1, 1), (2, 1), (3, 1), (4, 1)}
	- R4:{(1, 1), (2, 1), (3, 1), (4, 1)}
	-  R5 = R4
		- These end up becoming the same because we end up going back down to (1, 1) for all paths, and that is a loop to itself, aka it reflects to itself, so we can keep on doing 1R1 in our search for an intermediary.  
	- ![[Pasted image 20220707133742.png]]
	- ![[Pasted image 20220707133747.png]]