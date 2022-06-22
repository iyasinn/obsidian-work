# Proving a $\forall$ Theorem with a $\to$

[[;1.7 - Introduction to proofs]]
[[Universal Quantifier]]
[[Conditional]]

---


## How do you generally prove a theorem in the form: $\forall x [P(x) \to Q(x)]$

To prove this, we generally have to first create an arbitrary variable c that represents all elements in the domain

Then we prove 
$$P(c) \to Q(c)$$

We only need to prove this by showing that Q(c) is true if P(c) is true. In all other cases it doesn’t matter if P(c) is false, as the proof doesn’t worry about that, see [conditional] notes if you want to check it out.

This ensures we don’t get the case where P(x) is true and Q(x) is false. 

Finally, once you prove this for an arbitrary c, you know it’s true for 
$$\forall x [P(x) \to Q(x)]$$





![[Pasted image 20220604193738.png]]

![[Pasted image 20220604193801.png]]