# Combinations with Repetition

[[;6.5 - Permutation and Combination with Repetition]]

---
## Notes


This usually occurs when we have n types, and we need to choose r of the n types, but we can have repetition:
- 4 different jars, and 10 blue marbles to place in each of them.


### How do you do r-combinations of n objects with repetition? 
We can utilize the balls and bars method. 
We use a bit string to represent “boxes” for our situation
| | | would represent 5 boxes. So if we have n types, we have n - 1 boxes, or n - 1 
Then the 0s represent our indistinguishable elements. 

So we will have a bit string of size n + r - 1
And we can either choose where to place the n - 1 ones, or where to place the r zeros.

>[!info] Approach
>![[Pasted image 20220809165531.png]]

This is really about when you have to choose r elements with n types for each element and we need a combination of these elements, rather than a permutation. 
Need to select a SET of these elements. 


### Look at this example of how the method works:

![[Pasted image 20220809165615.png]]
![[Pasted image 20220809165621.png]]
![[Pasted image 20220809165630.png]]

![[Pasted image 20220809165636.png]]




### Prove the method:
![[Pasted image 20220809170850.png]]




### How do we do balls and bars with constraints?
### What’s usually distinguishable and indistinguishable for balls and bars?

Generally, the balls are the same, and the boxes are different

Everything is about exploration. There is no specific method, but these can be good ways to think about what needs to be done. 

Actually now that I think about it, we are just choosing elements with repetition. So really it’s mor elike we have r elements to choose, but each element has n types. 


- What if the boxes are the same?
	- Then we have to divide by (n - 1)! because all jars are distinct
	- Though we could just try to find a different conceptual approach 
- What if the marbles are different? 
	- We will have to devise a different method, but likely we could see for each of the placements of distinct marbles, how many ways can we make that into another distinct placement aka spread out the remaining marbles.
- Boxes same and Balls different? 
- Then it’s really a matter of how we can spread things out. This will really just become a lot more complex in its own manner though.

### Why doesn’t $\frac{n^r}{r!}$ work?

WRONG
We can first consider the r-permutations, of which there are $r^n$

Now, let’s think: There are r! Ways to order around any of the r objects in a permutation, and these r! orderings all represent the exact same combination. 

So we can do: $\frac{r^n}{r!}$

There are not always r! Ways to get a given permutation. aaaa
Only one way to get aaaa. So the issue is that we end up having too many cases. 

### Overall, summarize permutations and combinations with and without repetition

![[Pasted image 20220809171545.png]]




## Examples
- ![[Pasted image 20220809171128.png]]
	- ![[Pasted image 20220809171134.png]]
- ![[Pasted image 20220809171330.png]]
	- ![[Pasted image 20220809171340.png]]
- ![[Pasted image 20220809171418.png]]