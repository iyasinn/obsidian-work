# Pigeonhole Principle

[[;6.2 - The Pigeonhole Principle]]

---

## Notes

### What is the pigeonhole principle?

>[!info] Pigeonhole Principle
>The pigeonhole principle states:
>
>k $\in \mathbb{Z}^+$
>If k + 1 objects are placed in some way into k boxes, then there must be **at least one** box containing **at least two** or more objects. 
>
>k + 1 placed into k → $\exists x \in [k + 1]$ [x has two or more objects]
>


![[Pasted image 20220802174131.png]]

If we try to distribute them, we can place k pigeons into k different boxes, but then we will have the (k + 1)th pigeon, which will share a box with some other pigeon. 


![[Pasted image 20220802175016.png]]

### Prove the pigeonhole principle
We are proving the simple pigeonhole principle.
We can do a proof by contradiction.
Assume that k is a positive integer and k + 1 or more objects are placed into k boxes, and that there are no boxes containing two or more objects, so all boxes contain one or 0 objects. 

Since k + 1 pigeons are placed into k boxes, we can assume any ordering as long as they are placed. If we distribute evenly, then at the max we have k - 1 pigeons in k - 1 box, and 2 pigeons in 1 box. This yields a contradiction, since we said all boxes contain one pigeon. 

OR (better)
Since each box has exactly one pigeon, then at the max, we have k pigeons in k boxes. This is a contradiction, since we said there are k + 1 objects, no matter what the case, and we have found a case where this is false. 


![[Pasted image 20220802174819.png]]

### Explain a corollary of the pigeonhole principle regarding f: k + 1 → k   where $k \in \mathbb{Z}^+$

This function cannot be 1-1
![[Pasted image 20220802175105.png]]

#### Prove this:
For this function to be 1-1, $\forall x, y [f(x) = f(y) \to x = y]$

We can treat k + 1 as objects, and k as boxes. By the pigeonhole principle, there must be at least one box with at least two objects. In this case, there exists a value in the codomain that is mapped to by at least to values in the domain. 

If this is the case, there exists x1 and x2 such that f(x1) = f(x2) and x1 != x2, which goes against the definition of one to one. 

![[Pasted image 20220802175404.png]]


## Examples

![[Pasted image 20220802175458.png]]

![[Pasted image 20220802175504.png]]