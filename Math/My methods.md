
# My methods of solving problems

## Definitions
- Odd/Even Definition
	- 
	  >[!info] Definition of Odd and Even
	  >![[Pasted image 20220603180321.png]] 
	  >We can also use the modular arithmetic definition. Where even numbers mod 2 are 0, and odd numbers mod 2 are 1. 
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
- Defini1tion of a “multiple of"
	- ![[Pasted image 20220604202038.png]]
	- Note: 0 is a multiple of all numbers :p
	- And all numbers are technically multiples of 0 

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

- Decimal repreesntation, such as x + d is very powerful for some proofs. 


---

#### Tips

When dealing with rationals, good edge cases are when you have the same rational like $\sqrt{2}$ 

When considering cases for a and b, consider cases where they are the same but also different. 

## Working with proofs

- When constructing a proof, keep two thigns in mind:
	- Why does the proof work, why is the propostion itself true? 
		- To do this, look at examples, make tentative assumptions, and break the problem down into cases. Bring out all of your mathematical training :D
		- Also look a the conclusion and see how you can get to it. 
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
- Remember, when the general statement is “If x, then y”, then x is kind of like a premise. Don’t limit yourself to only using it. Still look at the statement that you want to rpove. 
- Some proofs require dealing with two values. Say incresaing function proofs, which generally mean you start at two x and y values where x  < y for something. 
- When you have some premise in a function, ACTUALLY utilize it later on. You might start with it, or you might use it later for something, but make sure you’re actually using it to its fully extent. 
	- For example, If we know a function is one to one and we have x != y, then we can conclude f(x) != f(y) using that premise. Or if we know it’s onto and we have y, we know there must be some x that exists. USE WHAT YOU HAVE WELL. predicate definitions help a lot. 
- Proofs **can** ask you to show something is **possible**, you can just show whether or not it works or not….use fundamental concepts. 
- When given an exist statement that just lets you conclude the inner statement. It is incredibly powerful 

##### Proofs with functioning 
- When using one to one or invertible as premise properties, make sure you use them effectively to ensure you can do the proof. 
- empty sets are usually very good and easy counterexamples when you have functions on sets. 



##### Times where you might have to do proof by cases

These are a few cases, but we may have more, such as when we KNOW two things are the possible cases that could occur. The most important thing is just to be aware when or when not you might have to do a proof by cases. 

- x ≥ y or something liek x≤ y
	- Can have a case where x = y or x > y 
- x $\neq y$
	- Can have a case where x < y or x > y
- | x |
	- We could say that x >  0 or x < 0 
	- If x < 0, then |x| = -x 
		- Since - times - (x is negaive) gives positive x
	- If x > 0, then |x| = x
- With modular arithmetic, a mod m
	- We can have multiople solutions, say 2a mod 6, we can have {0, 2, 4}





##### Proof structures


**In general, don’t make yourself think all proofs are with quantifiers. That’s not true at all, that’s limiting yourself.**

- Premise → Conclusion
	- You can just suppose the premise is true, then you have to show that the conclusion’s statement is true. The conclusion could any statement, such as a quantifier or some fact that you need to somehow show is true.
	- In my experience these may or may not be more abstract depending on what the conclusion is. 
- Proving a single statement
	- Quantifiers
		- Generally these always required you to start with an arbitrary variable, and then assume the premise (if there is one)one
		- This is just showing a single statement is true
	- Some random proposition
		- This will usually require a lot of definitions
		- For example, proving 2^{1/2} is irrational will require using definitions of rationals when doing a contradiction. 


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

- You don’t need to always prove k → k + 1 or k - 1 → k
	- This is ONLY for all integers
	- If you would want to do it for all odd integers, you’d need to show it for k → k + 2
	- Not only that, but say you wanted to show it for all multiples of 5, then k → k + 5 would be used and the base case would start at 5 or 0
- Make sure to conclude your inductin proofs by stating you proved the base case and the inductive step. 
- You need to make sure you base case matches up with your inductive step. 

---


### Strong Induction
This is just mathematical induction…with more information :p
- For difficult base cases, be VERY VERY caerful. 
	- Like for example, for prcoesses where we multiply things, usually the base case if the process stops at P(1) is just 1….we just use the **multiplicative** identity. IT really depends. For sums, it’s usually 0. It can depend though. 
- Generally, a very good tip is to BREAK DOWN your original case, THEN apply the inductive step and build up your original case back (STRUCTURALLY) :D
- Strong induction is similar to mathematical induction where we don’t need to deal with just k → k + 1. With strong induction we can do things like k → k + 4…but we will need base cases. But we would always need those base cases even with k → k + 1. it all depends on SCENARIO. Just be careful of that. 
- In general, remember you can reprsent arbitrary numbers as things
	- So if you are told that something is written as the sume of primes, you can oh: p1 + p2 +….pk. 

---


### 2.2 -  Set Theory 
- Visualize a set as a “bucket”. It is not ordered.
- **Drawing sets in problems very, VERY helpful.**
- Set builder notation can have multiple predicates separated by a comma. 
- When using set builder notation, be smart about it. 
	- Example: The set of the sum of all primes
		- $A = {x \;\;\; | \;\;\; \exists y \exists z [Prime(y) \land Prime(z) \land x = y + z]}$
			- This is one way to write it, but it’s not the best way 
		- $A = \{y + z \;\;\; | \;\;\; Prime(y) \land Prime(z)\}$
			- This is even better. We can include expressions for our element (on the left), which is perfectly fine. 
- Nonnegative integers = natural numbers
- Lemma that (0, 1) is very useful to use as a proof where we say (0, 1) is a subset of something so it is uncountable. 
- WHen taking the UNION, ALWAYS ALWAYS look to make sure you don’t have overlap and if you do, make sure to remove it (inclusion exclusino principle),
- If $A \cap C$ then this is a subset of A and a subset of C (think conceptually)
- if X $\subseteq$ Y, then $X \cap Y$ = X   and   $X \cup Y$ = Y
- Set subtractio operator A - B is really just, remove anything in A that is in B



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
	- You can use this definition to turn these statements into **proropositions, which will then help you solve the problem. 
- After doing this, you can also use proof techniques like proof by contradiction and such, since you’re just trying to show that x in B → x in A, and so you can use any proof technique you really want. Usually direct proof works best. 
- **Note**: If you have other premises, don’t change what you assume, but you might need to use those other premises to help you solve the problem. 

**Method 2**
- Convert to set builder notation and work with the predicate 

We can also use logical equivalences for sets 

**Method 3**
We can use EQUIVALENCES
If we can use equivalences to show that $B = A - S$
Where S is any other set 
Or 
B = $A \cap S$
Or
B = A

This shows us that B is either smaller than, OR EQUAL to A

Is a cool technique, though may not be what the graders are expecting. It conceptually makes sense though. 


#### Showing that two sets are equivalent
There are a few ways to this. 
##### Show $B \subseteq A \land A \subseteq$
- You have to do two subset proofs. But after you do this, since both are a subset of each other, then you know they are equivalent. 

##### Use set Equivalences
- You can use the set equivalence rules to merely convert one set to the other. 
- Note that if you have to prove $B = A$, then you can start with B to get A, or you can start with A to get B. Either works. Technically this was also true for logical equivalence rules. 
- Always s

##### For fundamental set equivalence rules, you can convert to set builder notation and use basic set identity rules. 
- This is harder, but it would require writing sets in set builder notation, then working with the predicate for that set, manipulating it with fundamental logical equivalence laws. 

#### Inclusion Exclusion Questions
![[Pasted image 20220621165504.png]]






---

#### Inverse of sets







### Countability 
- Be very very careful of your bounds one doing countability proofs and make sure your domain and codomain mappings work out. 
- Modul is very helpful when you need to split some set into pieces for a bijective proof (trying to show a bijection exists.)
- Check every single possible edge case as much as you can (and remember, drawing is very very helpful)helpful
- Subtracting countably infinite from uncoutnably infinite usually still leaves you with uncountable infinite. Commonsense.

#### Showing cardinalities are equal
Schröder Bernstein
|A| < |B| $\land$ |B| > |A| $\to$ |A| = |B|

Find some function:
- Find a bijection from A → B or B → A (doesn’t use schroder bernstein)
- Using schorder bernstein
	- 1-1 from A→B and 1-1 from B→A
	-  onto from A→B and onto from B→A
	- 1-1 from A→B and onto from A→B
	- 1-1 from B→A and onto from B→A

![[My methods 2022-07-08 13.30.20.excalidraw]]



### Functions
- Functions have **TWO RULES**
	- Each input has one output
	- **ONe ppl forget**: ALL INPUTS ARE DEFINED> 
- Being a function to yourself or a function on set S means domain = codomain. 
- In explanations, even if it’s not an explicit proof, talking generally about how any number can be reached for onto or explaining why no two distinct numbers have the same output is very, very important in your proofs. 
- Don’t overcomplicate the method of reaching any number you need in onto proofs.
- There are LOTS of useful tricks for MAPPING functions
	- Odd even, multiples of some number, splitting the function to do different things for different domain values. Work hard to be very flexible in how you approach such questions. Also leveraging absolute value functions, or floor functions, turns out very well.
- Note: There is a **big** difference between **decreasing** and **strictly** **decreasing**, so you need to make sure that you keep that in mind as well as vice versa for increasing. 

#### Cheat sheet
- ![[Pasted image 20220710194028.png]]
- ![[Pasted image 20220710194118.png]]
- ![[Pasted image 20220710194132.png]]
- ![[Pasted image 20220710194139.png]]

#### Visualizing / Test Cases

Make sure you deal with edge cases in BOTH the domain and codomain. 

When dealing with the cartesian plane, drawing graphs of the functions is also very helpful.


![[Functions showcase|925]]

Note: Graphs like are valid as values
![[Pasted image 20220707235246.png]]


- When dealing with sets of real numbers, or intervals, a NUMBER LINE is very helpful to graph to help see what you are doing. 
	- ![[Pasted image 20220622003448.png]]

- Furthermore, a function proof where you use venn diagrams is a **valid way** to **define** functions to give **examples** or **counterexamples**
	- ![[Pasted image 20220624202312.png]]


![[Pasted image 20220626223354.png]]


#### Proving onto

Onto is also very useful.
If you know a function is onto, then remember that this means you know that any arbitrary value in the codomain you choose will have some value in the domain that it is the image of. 

Need to prove:

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
#### Proving one-one
To prove this, you must prove for 
f: A → B
$$\forall x, y \in A[f(x) = f(y) \to x = y]$$
- Pick an arbitrary x and arbitrary y, and assume that f(x) = f(y)\
- Use this to show that x = y
- You can now conclude the truth of the entire predicate. 
- You can also use the contrapositive, though usually it isn’t as useful but that depends on the case. If you have cases where x > y and x < y, then it might actually come in very handy. 
- If a function is 1-1, this is handy because then any f(x) = f(y), you know x = y straight away.



#### Proving not onto
We need to prove for f: A → B
$$\neg \forall y \in B \exists x \in A [f(x) = y] $$
Aka
$$\exists y \forall x [f(x) \neq y]$$
- We can choose some specific value of y to deal with as an example
- Now we need to prove $\forall x [f(x) \neq y]$
- This statement is kind of difficult to prove, because it’s hard to prove $f(x) \neq y$, but we can instead do a **proof by contradiction**, and show that this isn’t the case. 
- THIS IS MERELY ONE WAY TO APPROACH THIS
- Once we prove our statements, the proof is done. 
- This is the same as finding a counterexample with more work. 

#### Proving not one-one
Need to prove
$$\neg \forall x, y [f(x) = f(y) \to x = y]$$
Which is the same as proving

$\exists x,y [f(x) = f(y) \land x \neq y]$
So we can simply choose an x and y that serves as a counter example for the statement for which this is onto (hence proving this statement).

This is thus very simple to prove. 








#### Bijections
Things to think about 
- It is injective and surjective, and this can be used in a proof. 
- It has an inverse. So the inverse is also injective and surjective when mapped from the codomain to the domain.  
- Or, if you have the inverse, you can say f(x) ont to one, and f^-1 one to one, or you can say both directions are onto




#### Inverses
- Make sure your function is actually bijective to see if it has an inverse. This is very similar to just a one to one and onto proof. 
- Inverse can also be used to see if a function is bijective. If you can construct an inverse that is a valid function, and it can map as a bijection to the original, that means the function is bijective. 
- Note that a given mapping for an inverse require TWO properties to be true
	- $f(f^{-1}(x)) = x$
	- $f^{-1}(f(x)) = x$
	- Note, it can be the case that only one of these are true but not both. Regardless, these must both be true for the function’s inverse to be a valid inverse.
	- **When checking if two expressions are inverses of each other, or if some new expression is a valid inverse, you need to prove that both of the statements are true** 
- Invertible = has an inverse

#### Compositions
- Make sure that the range of the inner function and domain of the outer function actually map up. 
- The compositions of two bijective must be bijective

#### Applying functions to sets
- You can apply functions to sets. This just ends up giving you another set
	- Power set is a good example. P(s) is the power set, which is just a function applied to a set. 
- if a function has an inverse and say $x \in f(S)$ where S ia  set, then that means $f^{-1}(x) \in S$ since this means x was in the codomain of f: S → B for example, and hence the inverse of x should give us an element in S
	- Note that if the function doesn’ thave an inverse but we try something like this, we get very weird results. Works well if the function is bijective aka actually has an inverse. 
- The empty set is usually a very good test input (if the set in question is not required to be nonempty), or even forming the empty set for example. 







### Relations
- When you have to determine if a relation is symmetric, reflexive, or transitive etc., don’t just eyeball whether it has a property or doesn’t. If it doesn’t have a property, then give counterexamples. If it does, then just do a mini proof (unless the question asks you for a full proof)
- Be very careful with considering all cases
- Keep your relation rules very rigerous
	- If x = y + 1 means (x, y)
	- Then -y = -x + 1 means (-y, -x), keep the rules specific
- Any element in a relation is an ordered pair
	- Important to always think like that so you prevent odd outcomes with compositions. 
- ![[Pasted image 20220709135310.png]]
	- This is the XOR of two relations (technically a set concept)


##### Cheat Sheet
![[Pasted image 20220710201032.png]]
![[Pasted image 20220710201046.png]]
![[Pasted image 20220710201102.png]]



##### Empty relations
- Assume empty relation on empty set
   Thanks, to for all statements being vacuously true on empty sets: 
	- Reflexive
	- Antisymmetric
	- Symmetric
	- Transitive
	- Irreflexive
	- Asymmetric
- Assume empty relation on nonempty set
	- Not reflexive (elements in set have no relation to themselves since relation is empty) 
	- Symmetric
	- Antisymmetric
	- Transitive
	- Irreflexive
	- Asymmetric

They are quite similar, but this is all a matter of understanding $\forall$ statements.





##### Properties
- Reflexivity
	- Remember, all elements need to be in the relation. So try to see if it could be the case that there aren’t some elements in the relation.
- Symmetry 
	- 

##### Combining relations
- Since relations are sets, you can combine them as normal
- Note that you can also combine relations and say that it’s equivalent to some other given relation (if you know that’s the case of course) since it’s really just a set. 
- Complement of a relation is all edges not in that relation
	- 
- Inverse is all ordered pairs reversed
	- Also interesting ways to express this
		- Inverse relation of R is R = {(f(a), a)) | a ∈A}
		- R^-1 = {(b, f^-1{b}) | b ∈B}
		- This was assuming the relation was kind of like a function. And we know it’s one to one and onto.
- When finding the cardinality of relations you added, make sure you consider the fact that they might have overlaps of elements that you need to consider. 
##### Relation compositions
- For these, conceptually think about when or when not the given relation implies there must be middle elements in relations like R^2
	- It’s all really just a matter of practice. 

## extra add later



![[Pasted image 20220708012729.png]]



![[Pasted image 20220709160503.png]]



## Exam 3

### Counting

#### Techniques
- You can place certain objects first, then place the rest depending on the remaining positions. 
- You can use the complement, aka subtracting from the total number of opportunities
- You can do cases (useful in general)
- 