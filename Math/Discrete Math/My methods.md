
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
- Definition of Prime numbers
	- ****An integer k $\geq$ 2 is “prime” if there do not exist two integers a, b, such k = ab***
	- ![[Pasted image 20220603205818.png]]
		- $\forall k [\neg \exists a \exists b[a \geq 2 \land b \geq 2 \land a * b = k] \to \text{k is prime}]$
		- 
	- ![[Pasted image 20220603205825.png]]
		- Note: Prime numbers also are included here. 5 is prime, and it is a multiple of 5 and 1, and since 5 is prime, then 5 is a multiple of itself, which counts. 


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

---


[[My methods]]






---



#### Definitions

![[Pasted image 20220526184858.png]]

## Modular Arithmetic
#### Solving inear congruences


$ax \equiv b \pmod{m}$
- Check if a and m are relatively prime
	- **Unique solution**: Find the inverse of a, then solve. 
- If b is divisible by gcd(a, m)
	- **multiple solutions** Reduce the congruence by gcd(a, m), solve the new congruence, and find all congruent numbers in the range of unique solutions for our original congruence
-  if b is not divisible by gcd(a, m)
	- **no solutions**





---




## 1.1 Propositions

#### Proving something is a tautology or contradiction 
- Logical equivalences to make it True 
- Even easier, PROVE it can’t be false. Look at the secenario in which it might be false and prove it isn’t possible. 




WHEN DOING MATH PROBLEMS TALK ABOUT CONCEPTS YOU HAVE LEARNED, EVEN IF THEY ARE OBVIOUS


#### Translating to English
MAKE TEST CASES


---


## 1.3 Equivalences



#### Equivalences

- try going backwards. Like using reverse laws
	- For example: -(-p V -q). You can do demorgan inside….or you can do demorgan outside. Both actually work out very well.  
- Also sometimes you can distirbute one term out, or another term out. Do it in a way such that your problem is MOST simplified.
- English 

First translate very straightforwardly, then make it easy. 





---




## 1.4 Quantificaiton 

#### Working with quantifiers 
###### Test Cases 


![[Drawing 2022-05-18 23.54.57.excalidraw]]

![[Pasted image 20220519004442.png]]


##### Showing that a for all is true/fasle
- True: Show that it works for all vlaues
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


## Natural Deduction 
- Be calm, when you form something, check every statement and see if it can do something with that statement when you are stuck.
- Generally when you see a negated large propstion, the point of it is to use it as a CONTRADICTION to get false. So make assumptions of its negation. Like if we have $\neg (p \land q)$, It’s probably best to try to find an assumption like P or an assumption like Q, which eventually lets us make $p \land q$ to have a contradiction in whichever case we’re dealing with.
- With quantiifers, be prepared to have some niteresting manipulation to use certain variables you have introduced.  

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
## Proving a natural deduction is False
So try to find a counter example 

It is a true proof when $\forall \text{truthValues} (\text{premise} \rightarrow \text{conclusion})$

So we need a counter example to when this is false

- So try to see when the conclusion is true, and apply those vlaues to the premise, and fill in any other values. 






 