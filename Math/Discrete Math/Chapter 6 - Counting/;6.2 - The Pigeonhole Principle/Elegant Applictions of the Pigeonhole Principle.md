# Elegant Applications of the Pigeonhole Principle

[[;6.2 - The Pigeonhole Principle]]
[[Pigeonhole Principle]]

---

Sometimes the pigeonhole principle can be applied in clever and interesting ways.
It is hard to sometimes choose the boxes and objects, but it is crucial for solving the problem. 


### Useful theorem

![[Pasted image 20220803141700.png]]
![[Pasted image 20220803141723.png]]

![[Pasted image 20220803141729.png]]

#### Try proving this 

If we have distinct real numbers, then we can put these into a set and use the well ordering principle to have n + 1 of them be strictly increasing and then reversing that allows it to be strictly decreasing

![[Pasted image 20220803141917.png]]







### Examples


- ![[Pasted image 20220803134955.png]]
	- Let’s first deduce the minimum and maximum number of games
	  So we have 30 games for sure 
	  To have 44 games every day, that would mean we have at most 1320 games
	- ![[Pasted image 20220803135423.png]]
- ![[Pasted image 20220803135506.png]]
	- n + 1 integers not exceeding 2n, there must be an integer that divides one of the other integers
	  
	 Edge case is just n = 1
	 
	 We can choose ANY n + 1 integers as long as they don’t exceed 2n 
	 
	 Let’s think about it 
	 Let’s choose an integer in the n + 1 integers that should divide something else
	 
	 Call it m 
	 So let’s now consider looking only at n integers in the 2n integers
	 So really we need to show that any half of the 2n integers definitely contain something divisible by m
	 {1, 2, 3, 4, …..n, n + 1, n + 2, n + 3… 2n}
	
 	 
	 We know that the remainder for everything when divided by m is going to be 0, 1, 2, 3, ….m - 1
	 So there are m remainders 
	 We know at most that m ≤ 2n
	 ![[Pasted image 20220803141628.png]]
- ![[Pasted image 20220803142252.png]]
	- ![[Pasted image 20220803142256.png]]
	- ![[Pasted image 20220803142303.png]]
