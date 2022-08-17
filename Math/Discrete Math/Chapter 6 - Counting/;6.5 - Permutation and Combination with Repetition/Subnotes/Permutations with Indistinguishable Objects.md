# Permutations with Indistinguishable Objects

[[;6.5 - Permutation and Combination with Repetition]]

---

Sometimes we deal with doing a permutation of **n elements,** where we have some indistinguishable objects to deal with. There are two ways we can go about this that are similar. 

Note that the $P(n, n) = n!$

---

## Notes
### How do we take the permutation of n elements where some objects are the same. 
![[Pasted image 20220809173318.png]]
Conceptually, since there are n1 objects that are the same, we divide out n1 permutations that get the exact same outcome. 

OR

We can think about it as choosing n positions for each set of indistinguishable objects. 
Say we have n1, n2, and n3 sizes for each set of 3 indistinguishable objects

Then we can do 
C(n, n1) * C(n - n1, n2) * C(n - n1 - n2, n3)

![[Pasted image 20220809173502.png]]

This is actually kind of how the proof works






### Prove it
![[Pasted image 20220809173324.png]]
![[Pasted image 20220809173330.png]]




## Examples


- ![[Pasted image 20220809173536.png]]
	- ![[Pasted image 20220809173546.png]]