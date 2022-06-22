# Proof by Contradiction 

[[;1.7 - Introduction to proofs]]

---

#### Conceptually, explain how proof by contradiction works. 

A proof by contradiction conceptually assumes the opposite of our **situation** and tries to find some contradiction, which can be anything that’s just false. When you find that contradiction, you know your original proof is true. 

Diving deeper into it
If we want to prove that $p \to q$ is true
Then maybe we could find a way to show that 
$\neg p \to q$ , WHY?
Well if we can find out that q is actually false, then that means that $\neg p$ must be false, and so that p must be true. 

![[Pasted image 20220604233027.png]]

---
**Better approach to understanding**

**Proof by contradiction** leverages $\neg$ -***introduction***
See [[ND - Negation]]

A regular negation intro looks like this




![[Pasted image 20220605155305.png]]A proof by contradiction is similar, but in the opposite way. 
We assume that 

Assumption
$\neg p$
.
.
.
$F$

$\therefore p$

Technically, you would get $\neg \neg p$, but equates to $p$

***But why does this work?***

Well, the negation intro reasoning makes sense. 

Well, let’s say that we want to prove that p is true

So we want to show that 
$p \equiv T$

Which means we think
$\neg p \equiv F$

***This is called the law of the excluded middle, if something is true, it's opposite must be false.***

As you may know, an equivalence is like a biconditional

So we can get

$[\neg p \to F] \land [F \to \neg p]$

The right side is vacuously true 

So we get $\neg p \to F$

For this to be true, p must be true, so $\neg p$ is false, we can prov ethis.

We can expand

$\neg p \to F \equiv \neg \neg p \lor F \equiv p \lor F \equiv \neg p$

⭐
So our final statement is 

$$\neg p \to F \equiv p$$
So proof by contradiction says that if we can get $\neg p$ and GET FALSE, then that just means p was true, or that if we can get p and assume false, then $\neg p$ was true. 

This could be in the form of $\neg p \to (r \land \neg r)$
It doesn’t matter, the point is we are proving this contradiction and thus showing that p is true. 


A contradiction, aka FALSE, is anything that goes against the fundametnal laws, such as 1 = 2, or 4 is odd, or integer + integer = fraction. 

---

![[Pasted image 20220605160819.png]]



#### Outline how to do a problem through proof by contradiction. 

- First, begin by stating that you are using a proof by contradiction. 
- Then assume the negation of your original statement. 
	- NOTE: You are not assuming that your contradiction implies anything, you’re just assuming that it is true. 
- You don’t need to do things like **assuming** some arbitrary integer. Just simply state your contradiction of your ENTIRE original statement. Everything including the **quantifiers**
- Then play around with your statement until you find that contradiction, then can assume that the negation of your contradiction, aka the original statement, is true. 
	- This is like the negation intro. 

![[Pasted image 20220605174019.png]]

<iframe src="https://www.youtube.com/embed/huGWXh4l1M0?feature=oembed" height="113" width="200" allowfullscreen="" allow="fullscreen" style="aspect-ratio: 1.76991 / 1; width: 100%; height: 100%;"></iframe>


---
#### What must you be careful about when negating a statement

Make sure you rule of propositions

For all x, there exists a y such that if x and y are even, then y is even 
This is just
$$\forall x \exists y [\text{y even} \to  \text{x and y even}]$$

The negation of this is very important to get right!
$$\neg \forall x \exists y [\text{y even} \to \text{x and y even }]$$
$$\exists x \forall y \neg [\text{y even} \to \text{x and y even}]$$
Now here you must be very, very careful

$\neg [p \to q] \equiv \neg [\neg p \lor q] \equiv \neg \neg p \land \neg q \equiv p \land \neg q$

Furthermore, our conclusion that x and y are even
So really, it’s (x even) $\land$ (y even)

So the negation **is not** x and y odd.

It’s (x odd) $\lor$ (y odd)

[[De Morgan's Law]]

So our final assumption for the statement is 

$\exists x \forall y [\text{y even} \to \text{x odd OR y odd}]$

**So two things, make sure to negaet AND/OR statements properly, and make sure to negate conditionals properly. **



---


#### How do you do a proof by contradiction with a conditional statement? 
![[Pasted image 20220605175911.png]]


![[Pasted image 20220605175921.png]]

![[Pasted image 20220605175927.png]]





---

#### Examples
- ![[Pasted image 20220605180038.png]]
	- Let’s assume the negation. We can assume that only less than 4 days can fall on the same day of the week in any 22 days OR that at MOST, 3 days must fall on the same day of the week. 
	- But 22 / 7 is 1 + 1/7, which means 3 sets of 7 days plus one extra. 
	  Which means there will exist a day that occurs 4 times in the 22 days. 
	- So 22nd can be monday, the 15th monday, the 8th monday, and the 1st monday. THIS IS 4 DAYS, which is a contradiction, since we said at most only 3 days of the 22 days could be on the same day.
	- ![[Pasted image 20220605180929.png]]
	- Their approach was different.
	- 
- ![[Pasted image 20220605181003.png]]
	- 
	- ![[Pasted image 20220605181007.png]]
	- ![[Pasted image 20220605181015.png]]
	- 