# Relations

Relations represent our knowledge of the world
They are more general types of functions


Functions map every input to **exactly one** output, while relations do not have that restriction. 

In a relation, an input can map to 0, 1, or more outputs. 
ANYTHING


![[Pasted image 20220628194156.png]]

A **binary** relation from A to B will contain many pairs, and any pair in that relation will be called a **related pair** 
It will be a subset of A x B

Coordinated pairs represent EDGES


We can represent relations through: 
- Graphs 
	- ![[Pasted image 20220628194310.png]]
- Through sets of ordered pairs 
	- R = {(Amira, 1), (Amira, 2), (Shruti, 2)}
- As a matrix with binary representation 
	- ![[Pasted image 20220628194419.png]]
- Describing the relation (with proportional logic). In english, logic, with R in the middle.  
	- You map to anyone you have talked to in the past 3 days. 
	- ![[Pasted image 20220628194556.png]]
	- ![[Pasted image 20220628194634.png]]

R itself is just like funciton, some MAPPING that can be a mapping of any soorts, you can keep it informa.. 

Is a relation then just also known as
R = {(x, y) | R(x, y)}
Where R is the relation mapping

The set for an empty relation with no mapping will just be $\emptyset$, or the 0 matrix, or the predicate F (IMPROTANT WAY OF THINKING)




Relations have very interesting properties. 
Relations also need domain, codomain, and a mapping. 

### Reflexive 
Usually when domain = codomain 
xRx  EXISTS

It doesn’t need to be xRx for ALL mappings, instead, it JUST NEEDS to be the case that every element maps to itself. 

You can also just draw relations as one set, and draw arrows to see mapping **when** domain = codomain
And **arrows** = edge

![[Pasted image 20220628195026.png]]



### Symmetric










Can’t have symmetric and antisymmetric
Well, you can, for the empty set 


Empty set = symmetric, antisymmetric, and transitive

Set with max connections  = cartesian product = reflexive, antisymmetric, and transitive.

For a nonempty set you can’t have a combination with reflexive or symmetric 


Can’t have a relation that has NO properteis

To not be transitive, we need a counter example edge, but to make a counter example edge, we will need to be either symmetric or antisymmetric. 

Hold up, we can make a ←→ b → c
This is not reflexive, not symmetric because a b→ c only and not asymmetric because a←→b

What if we say
Only one property allowed
Works for reflexive. 

Can’t be reflexive, symmetric, antisymmetric, AND 

---

Can’t be non transitive, symmetric, antisymmetric

And then you can or can’t have reflexive to get two combinations. 




For properties like reflexive, transitive….given some R relation that describes something, it DEPENDS


![[Pasted image 20220630163444.png]]




---



# Lecture 16

![[Pasted image 20220630163536.png]]


A closure is just the smallest relation S that contains R, it’s an **extenstion** of R, but it has to have a specific property (reeflexiv,e symmetric, transitive, etc)

- Look at R
- See if it violates the proeprty
- Fix that violation

To fix the violation, we can’t manually do it
WE DO KNOW THOUGH that
if we take some set
and take the union
anything the original set already has doesn’t really change
but it does add new thing

And so if we took a set R, and we add another relation that we know is reflexive set only on all the elements of R
then we will get the minimal set with their union

---

You can’t remove edges for a closure, you only add what’s NEEDED
And the symmetric closure is the SMALLEST possible closure




![[Pasted image 20220630211014.png]]



![[Pasted image 20220630211032.png]]




# Graphs


Graphs and relations aren’t exactly the same

You’d have to turn the graph into a relation
If you do dthat, then you have have undirect graphs youd’ have to make two connections. 

Multiple edges have to be the EXACT same



Neighborhood is the set of all adjacent vertices
We can have an out neighborhood and an in neighborhood. 

![[Pasted image 20220704201924.png]]




![[Pasted image 20220704201941.png]]



Degree is just the number of ad

IT"‘S BASED ON EDGES NOT ELEMENTS

degrees counted twice

You can have PATHS of length 0 




