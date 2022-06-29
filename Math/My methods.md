
# My methods of solving problems

## Definitions
- Odd/Even Definition
	- 
	  >[!info] Definition of Odd and Even
	  > ![[Pasted image 20220603180321.png]]
	- We can also use the modular arithmetic definition. Where even numbers mod 2 are 0, and odd numbers mod 2 are 1. 
- Definition of a perfect square
	- ***A number m is a perfect square if it can be written in terms of an number n such that*** $m = n^2$**
- Definition of an Irrational number.
	- ![[Pasted image 20220603201343.png]]
	- ****An integer k $\geq$ 2 is “prime” if there do not exist two integers a, b, such k = ab***
	- ![[Pasted image 20220603205818.png]]
		- $\forall k [\neg \exists a \exists b[a \geq 2 \land b \geq 2 \land a * b = k] \to \text{k is prime}]$
		- 
	- ![[Pasted image 20220603205825.png]]
		- Note: Prime numbers also are included here. 5 is prime, and it is a multiple of 5 and 1, and since 5 is prime, then 5 is a multiple of itself, which counts. 
	- 
- Definition of a “multiple of"
	- ![[Pasted image 20220604202038.png]]


## General
#### Problem-Solving
ALWAYS HAVE TEST CASES
Watch Ishaan’s videos, THIS CONCEPT IS AMAZXING AND INCREDIBLY IMPORTANT IN EECS 203
Just like coding ;)


In your test cases, look at extreme cases 


Also, drawing/sketching is incredibly helpful 


Also write some statements to understand the quesitons 

So checking your work is incredibly important!!!!!!!!!!
I always given an answer the nmove on 

- Always look at edge cases




---

#### Tips

When dealing with rationals, good edge cases are when you have the same rational like $\sqrt{2}$ 

When considering cases for a and b, consider cases where they are the same but also different. 

#### Working with proofs

- When constructing a proof, keep two thigns in mind:
	- Why does the proof work, why is the propostion itself true? 
		- To do this, look at examples, make tentative assumptions, and break the problem down into cases. Bring out all of your mathematical training :D
- Proof by contradiction lets you assume the most things (for a conditional) and so it is a powerful technique. 
- Always remember the importance of definitions!
- After you finish writing your proof, read over it. Does each statement follow logically. Are you leaving out cases/hidden assumptions?
- Use **proof by contradiction** when you want to see if two statements are compatible or not.d
- Disproving something is the SAME as proving its negation! ANd proving something is the same as disproving its negation! (Disproving the negation is just a proof by contradiction), but proving something thorugh proving its negatino is like proof by contradiction but not actually a contradiciton. 
- Remember, if you want to see something general isn’t the case, proof by contradiction works
- You can have SUB proofs by contradiction, and they work VERY VERY WELL. 
	- Like when proving $\exists y \forall x [f(x) \neq y]$
	- To prove that something is not equal is very difficult. But to get a proof that it is equal is actually easier and easy to disprove. 
	- So when you choose your example for y, why not just assume the negation aka $\exists x [f(x) = y]$ and have a nice proof by contradiction to prove the inner statement. 
- Proof by contradiction is VERY, VERY strong when you prove that “nothing” works, because you can assume something works, and then get a contradiction.  
- **make sure to work backwards in proofs, just like ND proofs. 


## Exam 1
### Modular Arithmetic
#### Solving linear congruence
$ax \equiv b \pmod{m}$
- Check if a and m are relatively prime
	- **Unique solution**: Find the inverse of a, then solve. 
- If b is divisible by gcd(a, m)
	- **multiple solutions** Reduce the congruence by gcd(a, m), solve the new congruence, and find all congruent numbers in the range of unique solutions for our original congruence
-  if b is not divisible by gcd(a, m)
	- **no solutions**

#### Further ideas when dealing with multiple solutions 
$F * a \equiv b \pmod{m}$
- Note, the solution of is going to be within {0, 1… m- 1}
- So we can also just check ALL the remainders of F * a for all values of a in {0, 1… m-1}, which tells you all the values b can’t be. And if b isn’t any of these values, then that means you have no solution, too.
- Remember though that if the inverse of F exists, then you don’t really need to do this and you can just directly solve for the solution.  
- ***But the big idea to remember is that when we have a in a linear congruence, to solve for a means to find out what a is equivalent to. And a is just going to be equivalent to some number, or multiple numbers in {0, 1… m-1}***






---

#### Cheat sheet of divisiblity
- ![[Pasted image 20220605221152.png]]
- ![[Pasted image 20220605221221.png]]
	- Like every mathemtaical expression, this is just a predicate too. 
- ![[Pasted image 20220605225512.png]]
- 


#### Ideas with proofs
- An EXTREMELY important technique is looking at the POSSIBLE solutions for a modulo. If two expression shave the same POSSIBLE solutions for a modulo, then they are the same. If they only have the same possible solution out of the many, then they are only the same if some property is upheld to ensure that is taken into accouint. Finally, if they can’t ever have the same remainder, then they are never the same. 
### 1.1 Propositions

#### Proving something is a tautology or contradiction 
- Logical equivalences to make it True 
- Even easier, PROVE it can’t be false. Look at the secenario in which it might be false and prove it isn’t possible. 

#### Showing a biconditional is true
For $p \iff q$
- start at p and see if you can get q, so $p \to q$
- start at q and see if you can get p, so $q \to p$
- It’s okay if there are middle steps, like some s is involved, and $p \to s$ but then $s \to q$
- Just make sure to keep your thoughts organized in your head. Start with p, then start with q, and make sure things workout. 

---


#### Making expressions from truth tables
- Look at this problem 
	- ![[Pasted image 20220604154017.png]]
		- Solution 
			- ![[Pasted image 20220604154031.png]]
- The approach is to make sure you think about a situation that gives you exactly what you want. Like for w, we know it is true when p false, so maybe have that -p, then we know it is true only when we have q and r, so maybe something like q and -r needs to be true, because in any other case, they aren’t both true. 

#### Cheat Sheet for Propostions
- ![[Pasted image 20220606173916.png]]
- ![[Pasted image 20220606173927.png]]
- ![[Pasted image 20220606173957.png]]

#### Translating to english tips
- Neither a nor b = not (a or b)
- Not a or b = not (a or b)
- 
### 1.3 Equivalences



#### Equivalences

- try going backwards. Like using reverse laws
	- For example: -(-p V -q). You can do demorgan inside….or you can do demorgan outside. Both actually work out very well.  
- Also sometimes you can distirbute one term out, or another term out. Do it in a way such that your problem is MOST simplified.
- English 
- If you see two things that look very very similar but flipped, maybe try doing reverse DeMorgan’s law on one of them. It may be very very helpful. 

First translate very straightforwardly, then make it easy. 





---




### 1.4 Quantificationton 

#### Working with quantifiers 
##### Test Cases 


![[Drawing 2022-05-18 23.54.57.excalidraw|650]]

![[Pasted image 20220519004442.png|525]]


##### Showing that a for all is true/fasle
- True: Show that it works for all values
- False: Show ONE counterexample 

##### Showring that a exists is true /false
- True: Show that it works for at least one value
- False: Show that it doesn’t work for all values




##### Nested quantifiers: English translations
- Always remember to explain in english if some pair of values is “distinct”
- Always talk about the domain of discourse very specifically 
- You don’t always need the quantifirs first in your english translations. (Not a big thing to worry about)
- With nested quantifiers, sometimes that can cause situations where someone is doing something to oneself. Plan i that is an issue or if it doesn’t matter. If it does matter, make some restriction around it so that doesn’t happen. 
- It’s okay to have nested quantifiers within your quantification. Just make sure everything makes sense. 


##### Others


- Always write out the domain 
- When trasnalting a restricted statement to english, using words like “who” works well. Everyone “who” is something, does semething else for example.
- When universally the domain, say people, don’t do something, you can use words like “nobody”, “no person”
- You can translate sentences literally (for ever x, if they are y, then they are z) or “every x x that is y is z.” or “every y is z”. Use common sense.
- Usually conjunctions with universal quantifiers cause extreme statements. Use them carefully . 
- “Such that” is a nice phrase to use  
- Remember, there are many ways to render a statement in english. So many synonyms you can use. 
- Always compare your english statement BACK to the original \



###### Logical Equivalence testing
- Define an arbitaryar domain and arbitaryar predicat (since equivalences works with all domains and all predicates) for quantiifers







When making a translation from english to logic. 

Look at when your logical statement is true, and look at when it’s false. SEE IF THIS LINES UP WITH THE ORIGINAL STATEMENT.


##### Uniqueness
- When writing a quantification of uniqueness, you show there exists an element that has the property, and then that for all other elements, if they have that property, then they must be our original element. 
	- Or that if they are not our original element, they don’t have that property.
- And when showing double uniquness, or only two objects exist, make sure you show that they are not equal. Good tip. 

#### Cheat sheet 
- ![[Pasted image 20220606184327.png]]



### Natural Deduction 
- Be calm, when you form something, check every statement and see if it can do something with that statement when you are stuck.
- Generally when you see a negated large propstion, the point of it is to use it as a CONTRADICTION to get false. So make assumptions of its negation. Like if we have $\neg (p \land q)$, It’s probably best to try to find an assumption like P or an assumption like Q, which eventually lets us make $p \land q$ to have a contradiction in whichever case we’re dealing with.
- With quantiifers, be prepared to have some niteresting manipulation to use certain variables you have introduced.  
- If you are doing negation intro with $\neg p$ then when you do the negation intro, make sure to write $\neg \neg p$

##### Forming different answers
No one way to approach these. It’s all about doing lots of practice. 
- Answer with an implies
	- Start with assuming the start then assuming the end. Don’t be too rigerous. If it has multiple implies maybe start with looking at the first antecedent as the beginning presumption
- Answer with OR
	- Maybe you can assume the negation of that and do a negation introduction 
	- Maybe you can do an or elim on a previous line to assume the entire conclusion (or assume part of the conclusion)
	- Maybe you can find a way to FORM one of the two parts of the OR statement and then do an OR Intro. Many many different techniques to do this. 
- AND 
	- You need to form BOTH parts of the statement 
	- Could maybe do it with an or elim but very unlikely
	- You could try assuming the negation of each part 

#### Cheat sheet tips
- ![[Pasted image 20220606193042.png]]
- ![[Pasted image 20220606193106.png]]
- 

### Proving a natural deduction is False
So try to find a counter example 

It is a true proof when $\forall \text{truthValues} (\text{premise} \rightarrow \text{conclusion})$

So we need a counter example to when this is false

- So try to see when the conclusion is true, and apply those vlaues to the premise, and fill in any other values. 










#### Different contradictions you can find
- One side is even, the other is odd
- Integer + Integer = fraction  
- One side is divisibile by some number, while the other side isn’t 
- 


#### Proof with modular
- Always take steps to take your poof and use the definition of modular equivalence to turn it into an equation, usually in the form $a \equiv b \pmod{m}$ to $a = b + mk$
- Be careful not to start your proof by assuming the thing you want to prove. That causes big issues!
	- ![[Pasted image 20220605154657.png]]


- Look at this overview of proof techniques
	- ![[Pasted image 20220605190330.png]]
	- ![[Pasted image 20220605190406.png]]
	- ![[Pasted image 20220605190421.png]]
- Proof techniques for quantified statements
	- You can combine this without proof techniques
	- ![[Pasted image 20220605190509.png]]
	- ![[Pasted image 20220605190530.png]]
- WLOG is very, very important. Sometimes it makes your proof more straightforward, and, and don’t need to waste time. Usually important when order doesn’t matter. 
	- ![[Pasted image 20220605190621.png]]





.
.
.
Proof by cases you get one contradiction, and one truth value 

For a disproof of an exists

And contradiction requires arbitrary 



## Exam 2

### Mathematical Induction

---


### Strong Induction

- For difficult base cases, be VERY VERY caerful. 
	- Like for example, for prcoesses where we multiply things, usually the base case if the process stops at P(1) is just 1….we just use the **multiplicative** identity. IT really depends. For sums, it’s usually 0. It can depend though. 


---


### Set Theory 
- Visualize a set as a “bucket”. It is not ordered.
- **Drawing sets in problems very, VERYRY helpful.**
- Set builder notation can have multiple predicates separated by a comma. 
- When using set builder notation, be smart about it. 
	- Example: The set of the sum of all primes
		- $A = {x \;\;\; | \;\;\; \exists y \exists z [Prime(y) \land Prime(z) \land x = y + z]}$
			- This is one way to write it, but it’s not the best way 
		- $A = \{y + z \;\;\; | \;\;\; Prime(y) \land Prime(z)\}$
			- This is even better. We can include expressions for our element (on the left), which is perfectly fine. 

#### Finding cardinalities
- The biggest thing here is to always **simplify** your function. For example
	- $\{\emptyset, \emptyset, \{\emptyset, \emptyset\}, \{\emptyset\}\}$
	  This is equivalent to 
	  $\{\emptyset, \{\emptyset\}\}$
	  
	  Note: $\{\emptyset, \emptyset\} \equiv \{\emptyset\}$
	- Make sure to FULLY simplify ALL SETS, including the ones that are elements.

#### How do you show that $B \subseteq A$ ?
**Method 1**
You can approach this similar to a natural deduction problem, since really, we are proving: $$\forall x \in \mathbb{U} [x \in B \to x \in A]$$
To prove this, we can :
- Consider an arbitrary element x in the universe. 
- Assume x is an element of B, whatever that is. 
- Use that information to show that if it is an element of B, then it must be an element of A. 
- Conclude the proof by stating that this is true for all arbitrary elements and that B is a subset of A. 
- This is like natural deduction
- When doing problems like this, you MUST use the definition of UNION/INTERSECTION/COMPLEMENT
	- This includes turning then into more useful propositions 
	- You can use this definition to turn these statements into **prpropositions, which will then help you solve the problem. 
- After doing this, you can also use proof techniques like proof by contradiction and such, since you’re just trying to show that x in B → x in A, and so you can use any proof technique you really want. Usually direct proof works best. 
- **Note**: If you have other premises, don’t change what you assume, but you might need to use those other premises to help you solve the problem. 

**Method 2**
- Convert to set builder notation and work with the predicate 

We can also use logical equivalences for sets 

#### Showing that two sets are equivalent
There are a few ways to this. 
##### Show $B \subseteq A \land A \subseteq$
- You have to do two subset proofs. But after you do this, since both are a subset of each other, then you know they are equivalent. 

##### Use set Equivalences
- You can use the set equivalence rules to merely convert one set to the other. 
- Note that if you have to prove $B = A$, then you can start with B to get A, or you can start with A to get B. Either works. Technically this was also true for logical equivalence rules. 

##### For fundamental set equivalence rules, you can convert to set builder notation and use basic set identity rules. 
- This is harder, but it would require writing sets in set builder notation, then working with the predicate for that set, manipulating it with fundamental logical equivalence laws. 

#### Inclusion Exclusion Questions
![[Pasted image 20220621165504.png]]






---

### Function /

#### Visualizing / Test Cases

![[Functions showcase|925]]

Note: Graphs like are valid as values



- When dealing with sets of real numbers, or intervals, a NUMBER LINE is very helpful to graph to help see what you are doing. 
	- ![[Pasted image 20220622003448.png]]

- Furthermore, a function proof where you use venn diagrams is a **valid way** to **define** functions to give **examples** or **counterexamples**
	- ![[Pasted image 20220624202312.png]]


![[Pasted image 20220626223354.png]]


#### Proving onto

- First write out your statement, that is very helpful. (logical statement) 
- The goal of an onto proof is to show $\forall y \exists x [f(x) = y]$ where y is in the codomain and x is in the domain. 
	- We need to show that for any arbitrary value in the codomain, there is always some value in the domain that maps to it, which we can do through a direct proof. 
- We can start by considering an arbitrary y in the codomain. Then we can consider an arbitrary x in the domain. 
- We can then try to find some expression to represent x that will ALWAYS give your desired y when you plug x into the function f. 
- **Make sure** that your expression for x is ALWAYS in the domain, and that it never goes outside that domain. 
- Make sure to specify your domains/codomains for your variables in general. 


- Try to do scratch work to solve for y and see if that could be plugged in 
- Make sure that your expression for whatever input you believe will give you your desired output is actually defined IN THE DOMAIN. 
	- If your domain is [0, 1], and your input is x = y + 4, then make sure your expression still works overall. 



![[Pasted image 20220623225210.png]]


![[Pasted image 20220624165600.png]]


![[Pasted image 20220628191356.png]]