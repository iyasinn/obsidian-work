# Symmetric

[[Properties of Relations]]


---

## Notes
### Define a symmetric relation 
>[!info] Symmetric
>
>For a relation R on set A
>A relation is symmetric if (b, a) $\in R$ whenever (a, b) $\in R$ for all a, b $\in A$
>
>So essentially whenever a relation goes both ways for two vertices. 

![[Pasted image 20220706220607.png]]

![[Pasted image 20220706220612.png]]


### Explain in predicate logic

If a relation M on set B is symmetric, then 
$$\forall a, b \in B [aMb \iff bMa]$$

We can simplify this to

$$\forall a, b \in B [aMb \to bMa]$$

The reason we can do that is if we ever have a case of xMy is false  and yMx is true , then that will be true, sure, but eventually due to the nature of a for all statement, we will cycle back to yMx → xMy and then we will have True → false, which is false. 

This is much easier to deal with in proofs. 


### Is the empty set symmetric?
Yes. Since it fulfills the predicate (it has no elements, hence the premise is always false for the universal quantification, and hence it is [[Vacouous and Trivial Proofs |Vacuously True]]





### Graphically showcase a relation
![[Symmetric 2022-07-06 22.02.39.excalidraw]]

