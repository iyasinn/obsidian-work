# Logical Equivalence
[[;1.3 - Propositional Equivalence]]
[[Tautology, Contradiction, and Contingency]]
[[Biconditional]]

---

# 🟩Introduction
#####  What does Logically Equivalent mean? What is the notation?

>[!info]
>
>The compound propostions denoted by p and q are **logically equivalent** if $p \leftrightarrow q$ is a #tautology.
>
>The notation $p \equiv q$ denotes that p and q are logically equivalent.

###### What must you remember about the $\equiv$ symbol?
It is not a logical connective. You can't use it as such. 
All it means is that if $p \equiv q$, then when using the [[Biconditional]] operator, $p \leftrightarrow q$ is a #tautology.  

The ⇔ can also be used in place of $\equiv$

##### What does it mean for $p\leftrightarrow q$ to be a tautology?
Conceptually, it means the truth table for $p \leftrightarrow q$ must be true for ALL cases. 

Which only happens when the values of p and q are both true or when they are both false.

Which means we can also simply say that the truth tables of p and q have to be the same!

---


# 🟨How to determine if two compound propostions are equivalent? 

Since we know that $p \leftrightarrow q$ must be a tautology, that means that we can either manually check if $p \leftrightarrow q$  are the same, which merely means writing out the truth tables of p and q and seeing if they are equivalent.

It's easier to just do this all in one truth table though. 

###### What are the two ways to prove an equivalence
Truth table
or
Using other fundamental equivalences

##### What do we use to prove fundamental equivalences?

A truth talble

###### How do we form these fundamental equivalences that we use to prove if more complex equivalences are the same? 

The truth table is the most FUNDAMENTAL way to prove that two propostions are the same. But if we use this FUNDAMENTAL technique to make other equivalences, then we can prove these other equivalences are the same after having proved very basic cases. 





---

# Example



- Prove DeMorgan's law.  ![[Pasted image 20220511194039.png]]
	- ![[Pasted image 20220511194046.png]]
	  
	  We could also have a column for (¬(p ∨ q)) $\leftrightarrow$ (¬p ∧¬q)
	  
	  But it isn't a big deal. Just put it in for exams just in case.
	  But as seen here the two coluns are equiavlent and we can say that (¬(p ∨ q)) $\leftrightarrow$ (¬p ∧¬q) is a tuatuology, as both propostions are the same in both places. 
- Prove the distributive law for disjunction over conjunction ![[Pasted image 20220511194336.png]]
	- ![[Pasted image 20220511194343.png]]
	- Prove the conditional-disjunction equivalence
- Prove the conditional disjunction equivalence ![[Pasted image 20220511194856.png]]
	- ![[Pasted image 20220511194836.png]]

