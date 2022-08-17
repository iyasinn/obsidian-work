# The Product Rule
[[Basic Counting Principles]]

---

## Notes

### Explain the product rule 🟨

>[!info] Product rule
>![[Pasted image 20220718142812.png]]
>![[Pasted image 20220718142900.png]]


So if we can break a procedure down into multiple tasks, such as choosing some letter m times, then if we can see how many ways there are to do **each** task, then we can multiply them together to get the total number of ways to do the given task. 

Note the big idea is to **break a task down**!
Take a big problem and make it smaller and smaller! :D



### Explain how the product rule can be thought of for sets?

It can be thought of taking the Cartesian product of sets, and the size of the Cartesian product is the count we get from applying the product rule. 

Each task is a SET
The cartesian  product of these sets will give the preocedure

Where the n tuple, say a 2-tuple, (a, b), will represent the choice for the first task and then the second task. Very useful in allowing us to test what we’ve don

The cardinatliy of the cartesina product is the total way to do the tasks.  

## Examples
- ![[Pasted image 20220719043603.png]]
	- ![[Pasted image 20220719043619.png]]

![[Pasted image 20220719043644.png]]

![[Pasted image 20220719043821.png]]

![[Pasted image 20220719043838.png]]
Here, we have (n)(n-1)(n-2)…(n - (m - 1))

The reason we go to m - 1 and not n - m  is because we are subtracting the number of elements that can be mapped to. n - m tells us that m elements from the inputs have mapped to some element in the output

So n - (m - 1) was the last element to get mapped to 

Just note that you have to be careful with the bounds. 

![[Pasted image 20220719044645.png]]

![[Pasted image 20220719044704.png]]
