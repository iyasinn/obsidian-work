# Proof by Contraposition

[[;1.7 - Introduction to proofs]]

---
#### Why are direct proofs not always helpful?
Direct proofs make you prove $p \to q$

But in many cases, you may have a $p$ that is very difficult to work with, or a q that has an odd statement. 



So we can use this indirect proof technique: Proof by contraposition.

----

#### Explain how proof by contraposition conceptually works.

$$p \to q \equiv \neg q \to \neg p$$
The reason this conceptually works is this:
In a regular proof, we assume that p is true, and then show that q must be true as well. If q is false but our p is true, then we don’t have a proof.

So proof by contrapositive merely shows that if q is false (so -q is true), then that MEANS that -p is true, or that p is false. 

That way, if we get true → false, that means we got that q was false, and that p was true, which would be a disproof. 

So we’re showing the exact same rule for this. If q is true, then it doesn’t matter what p is, but if we get that ASSUMPTION that it’s false, then we have to GUARANTEE that p is false too to have a VALID PROOF. 

![[Pasted image 20220604211133.png]]

##### Graphic of the contrapositive
![[Pasted image 20220604211020.png]]





----

#### Outline how to approach a proof by contraposition 
Let’s say you have
$\forall x [P(x) \to Q(x)]$

You will state that you are doing a proof by contraposition (**Always ANNOUNCE your proof style**) 
Then state the contrapositive

$\forall x [\neg Q(x) \to \neg P(x)]$
Mkae sure to negate statements properly!

Then **LET** x be some arbitrary integer (don’t say ASSUME LOL)
Then assume that $\neg Q(x)$ is true

Youse that to prove $\neg P(x)$

Then state that the contrapositive is true for all values of x. 

Finally, conclude that [insert original statement] is true due to proof by contrapositive. 

---


#### When taking the negation of a statement in your proof, what must you be careful of? 

Make sure to apply demorgans properly. 

**If expression is odd, then a and b are odd**

First write it out as a propostion 

$$e\; odd \to a\; odd \land b \; odd$$
So the negation is 

$$\neg [a\; odd \land b \; odd] \to e \; odd \equiv a\; even \; \lor \; b \; even \to e \; odd$$

Note how “a and b odd" becomes “a or b odd” or “a odd or b odd”

Since this is the INCLUSIVE OR, we will need to show the cases where a odd b even, a even b odd , and both odd [Add link to proof by cases]

Also note when we have
**If e even, then a or b odd**

Then that would become

If a **and** b even, then e odd.

You have to remember DEMORGANS!!!!



#### Examples

- ![[Pasted image 20220604212003.png]]
	- ![[Pasted image 20220604212008.png]]
	- ![[Pasted image 20220604212015.png]]
- ![[Pasted image 20220604212023.png]]
	- ![[Pasted image 20220604212029.png]]

