# Guidelines for Induction Proofs

[[;5.1 - Mathematical Induction]]
[[;1.7 - Introduction to proofs]]
[[Principle of Mathematical Induction]]

---

![[Pasted image 20220611175506.png]]


***Note: The guidelines here can be adapted to different types of problems***


1. Express the statement that needs to be proved as “for all n ≥ b, P(n)”. 
	1. For statements for positive integers, b = 1
	2. For statements with nonnegative integers, b = 0
	3. For anything else, you probably need to determine the value yourself by writing out the values of P(n) for small n values.
2. Write out “Basis Step” and then show that P(b) is true. Make sure you use the correct value for b.
3. Write out the words “Inductive Step” and state, and clearly identify, the inductive hypothesis, in the form “Assume that P(k) is true for an arbitrary fixed integer k ≥ b”. 
4. State what needs to be proved under the assumption that the hypothesis is true. Namely, this will be P(k)
5. Prove the statement P(k + 1)
	1. Generally, this is the most difficult part of an induction proof.
	2. Try to use the most promising truth strategy you can.
	3. Make sure to use your inductive hypothesis, since that’s what we’re starting with, just like in a regular $\forall x [a \to b]$ proof. 
	4. Make sure your proof is valid for small values of p. Namely, $p(k) \to p(k + 1)$ works for small values of b, such as b = 0, or b = 1, depending on what your smallest value is. It is incredibly important to test this!
6. Conclude the inductive step specifically by saying “This completes the inductive step”
7. After completing the basis step and the inductive step, state the conclusion, namely, “By mathematical induction, P(n) is true for all integers n with n ≥ b”

---


![[Pasted image 20220611165409.png]]