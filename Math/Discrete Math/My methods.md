
# My methods of solving problems


#### Solving inear congruences


$ax \equiv b \pmod{m}$
- Check if a and m are relatively prime
	- **Unique solution**: Find the inverse of a, then solve. 
- If b is divisible by gcd(a, m)
	- **multiple solutions** Reduce the congruence by gcd(a, m), solve the new congruence, and find all congruent numbers in the range of unique solutions for our original congruence
-  if b is not divisible by gcd(a, m)
	- **no solutions**



#### Translating to English
MAKE TEST CASES


#### Equivalences

- try going backwards. Like using reverse laws 

First translate very straightforwardly, then make it easy. 







#### Proving statemetns with quantifiers are the same
- Make sure you have a COMMON domain of discourse
- Make sure you state that the predicates themselves don’t really matter. They can represent anything
- Show how a **common** set of truth values are required for them both to be true. There shouldn’t be a scenario in which one of them is true and the other isn’t
	- We do this by proving if statement 1 is true, then statement 2 is true
	- And by showing that if statement 2 is true, then statement 1 is true. 
		- We could also potentially look at them being false
	- This works because being logically equivalent implies that the $\leftrightarrow$ is a tautology. 

 ---


#### Problem Solving
ALWAYS HAVE TEST CASES
Watch Ishaan’s videos, THIS CONCEPT IS AMAZXING AND INCREDIBLY IMPORTANT IN EECS 203
Just like coding ;)


In your test cases, look at extreme cases 


Also, drawing/sketching is incredibly helpful 


Also write some statements to understand the quesitons 

So checking your work is incredibly important!!!!!!!!!!
I always given an answer the nmove on 






#### Proving something is a tautology 
- Logical equivalences to make it True 
- Even easier, PROVE it can’t be false. Look at the secenario in which it might be false and prove it isn’t possible. 




WHEN DOING MATH PROBLEMS TALK ABOUT CONCEPTS YOU HAVE LEARNED, EVEN IF THEY ARE OBVIOUS






#### Working with quantifiers 
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