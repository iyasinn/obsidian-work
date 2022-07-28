# Principle of Mathematical Induction 

## What is the principle of mathematical induction defined as?

>[!info] Principle of Mathematical Induction 
> The principle of mathemtical induction allows us to prove that P(n) is true for all integers n in some well-ordered set such as the positive integers through **two steps**
> 
> **Basis step**: Verify P(1), or P(first value in set) is true
> **Inductive step:** Show that the conditional statement $p(k) \to p(k + 1)$ is true for all positive integers k 

If our inductive step is p(k) → p(k + 1), that means we proved it for every other integer (even if start at p(2) and odd if start at p(1))

---


## How can we write mathematical induction as a proposition?
$$p(1) \land \forall k [P(k) \to P(k + 1)] \to \forall n[P(n)]$$

---


## Explain the basis step

In the basis step, you just have to look at the first value in your set and see it works. This is extremely important to do!

## Explain the inductive step 


In the inductive step, you must assume P(k) and then show P(k + 1) is true. 

It is important to note that we are not assuming P(k), we are assuming If P(k) is true, then P(k + 1) is true 

Really, all we’re showing is that P(k + 1) CANNOT be false when P(k) is true. d



#### What is the inductive hypothesis
P(k) being true is just called the **inductive hypothesis**

#### What is the inductive step really just:
It’s just a simple proof to show that if P(k) true, then P(k + 1) true. We can prove it with a direct proof usually, or a contradiction, or anything really.

[[;1.7 - Introduction to proofs]]



## Once you complete the basis and the inductive step, how can we conclude this works for all numbers?

![[Pasted image 20220611152238.png]]