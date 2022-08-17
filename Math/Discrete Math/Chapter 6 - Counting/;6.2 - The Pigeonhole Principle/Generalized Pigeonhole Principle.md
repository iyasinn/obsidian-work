# Generalized Pigeonhole Principle

[[;6.2 - The Pigeonhole Principle]]
[[Pigeonhole Principle]]


---

The pigeonhole principle works in general for positive integers with k + 1 objects and k boxes, but we have a more general pigeonhole principle where there are more than nk objects, where n is some integer and k boxes. 

### What is the generalized pigeonhole principle? 
>[!info] Generalized Pigeonhole Principle
>
>If N objects are placed into k boxes, then there must be at least one box that has at least $\lceil$ N/k $\rceil$ objects

![[Pasted image 20220803001124.png]]
This conceptually makes sense. This just uses the division rule, where we divide out each of the objects into k boxes. If there is a leftover object, then we ceil it and say that there will definitely be a box that contains this extra leftover object. 


But interestingly, say ceil(N /  k ) = r
Then we have at least one box with r, and in this case we can likely say that IF evenly distributed, exactly one box

but if ceil(N / k) ≥ r, then it really depends, but regardless, we are GUARENTEED that we have r objects in at least one box for all values of ceil(N / k) larger than r. Do not overcomplicate this. 

### Prove the generalized pigeonhole principle

If N objects are placed into k boxes, and there are no boxes that have ceil(N/k) objects

If there are no boxes that have ceil(N/k) objects, then we can state that 

ceil(N/k) * k  ≥ N / k * k = N

there are no boxes with at least ceil(N/k) objects
So all k boxes contain less than ceil(N/k) objects
Which means that the number of total objects is less than N. Contradiction. WE said we had N boxes

![[Pasted image 20220802234208.png]]










### Given k boxes, and the requirement that one box needs at least r objects, how do we find N (total number of objects)

We need total number of objects

So ceil(N / k) = r
We need to find a value of N that makes this work

r * k objects for N
This technically works, but the value is too larger
Cuz we know each box wil definiitely have r objects in this case (when distributed evenly)
so there is definitely a box with r objects
but we could go smaller


(r - 1) * k
This wil place r - 1 objects into each box. Then we add 1, which means we will have 1 extra object we can but, ensuring at least one box has 1one object. 

NOTE: the piont is to GURANTEE we have at least one box with r objects. 
True, even with N - 10 objects, we might find a way to have a box with r objects, but since other configurations are possible, we need to find a way to gurantee we get what we want. 

![[Pasted image 20220802234926.png]]


So a good way to think about this is start building up adding objects, AVOIDING having r  objects.


### Even if you don’t have N = (r - 1) * k + 1 objects, could you still technically have a box with at least r objects?

Yes. But the point is to guarantee we have that box. If we have less than N objects, we can no longer guarantee that we have at least one box with r objects. 

A good way to think of it is that if we choose (r - 1) * k objects, and distribute them evenly, there is technically no way to avoid having a a box with r objects if we add another object, since every box wil have r - 1 ojbects. 

## Examples
- ![[Pasted image 20220802235129.png]]
	- We need at least 6 to get the same grade. ceil(N / 5) = 6, so that at least one grade is received by 6 ppl. 
	- 5 * 5 = 25, ensuring that if evenly distributed, at least 5 ppl have the same grade. SO need 26 ppl to ensure that at least 6 have the same grade
	- 26 students
	- ![[Pasted image 20220802235302.png]]
- ![[Pasted image 20220802235308.png]]
	- 4 suits. Need 3 to be in the same suit
	- ceil(N / 4) = 3
	- 4 * 2 + 1 = 9
	- Conceptually, we spread out 4, then another 4, now we need just one. This guarantees that if evenly distriubted, we have 9 cards
		- The issue with having 8 cards is that we can’t guranteed we have three cards in each suit. 
		- ![[Pasted image 20220802235953.png]]
		- .
		- For b, we need at least 3 hearts
		- There are 13 hearts, 52 - 13 = 39
		- So 39 cards could be picked and they wouldn’t be hearts, then 3 hearts left so 42 cards. If we picked 42 cards, we definitely woudl have to have picked hearts. 
		- ![[Pasted image 20220803000323.png]]
- ![[Pasted image 20220803000415.png]]
	- So first three digits form the area codes
	- So there are 25 million people, and they can be placed into k boxes 
	- NXX-XXXX = 8 million phone numbers
	- SO we can have the same phone numbers, but they can be distinct if we have different area codes. 
	- If phone numbers are boxes, then we have ceil(25 million / 8 million) = ceil(25/8).
	- So there is at leat one phoen number with 4 people, so to ensure we have no issues, we can have 4 area codes. So 4 ppl have the same number
	- ![[Pasted image 20220803001149.png]]
	- 
- ![[Pasted image 20220803001222.png]]
	- ceil(15 / 10) = 2
	- For one server to access all workstations, we need 15 connections. But the problem said we won’t do this. -
	- ![[Pasted image 20220803001743.png]]
	- ![[Pasted image 20220803001746.png]]
	- In this manner, if we chooose any 10 workstations, we are guranteed to have 1 that connects to all servers, or the 10 workstaionst that individually connefct to each servers. Regardless, we will always be able to activate cables specifically to certain servers. 
	- 