# Restricted Domains

[[;1.4 - Predicate Logic]]

---

## Why is restricting a domain important and useful?
If we are restricted to only using one specific domain, then we may want to restrict it through utilizing some domain restriciton. 

This restriction is merely a condition that the values must satisfy in order to be tested for the quantifer. 

---
## Explain how to generally restrict a domain
We can restrict a domain by simply putting the restriction next to the variable in the quantifier
![[Pasted image 20220517010911.png]]

The statement is read as “For every real number x **with** x < 0…”

This is how we explain the restriciton 


## How else can we restrict a domain for a $\forall$
We can use a conditional.

![[Pasted image 20220517011100.png]]

![[Pasted image 20220517011204.png]]

This works because anything that doesn’t fit the restriction is false, which instantly makes the conditional true, which won’t cause the statement to be false in general. It will only be false if we have false→true

We don’t use a conjunction because a conjunction implies that ALL x values have to fit the requirements of the restriction AND our condition, which isn’t the case. 

The case is that any x value that fits the restriction also needs to fit the condition. 


## How else can we restrict a domain for a $\exists$

![[Pasted image 20220517011322.png]]

The restriction is merely another requiremnt that can be added with a conjunction. 

We don’t use a conditional because if the restriction was false, then the conditioanl is true, creating a false postive and making the quantification true. 

So a conjunction ensures this is an extra restriction we add. 