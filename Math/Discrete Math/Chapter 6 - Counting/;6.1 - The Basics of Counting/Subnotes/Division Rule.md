# Division Counting Rules

[[Basic Counting Principles]]

---

## Notes

### Explain the division rule 

>[!info] Division Rule
>![[Pasted image 20220721134410.png]]

The division rule is particularly useful when you have multiple ways to get one distinct object. 

So if you have n desired distinct objects, but your total count has k ways to get the n desired objects, then count / k = n 


![[Pasted image 20220802152413.png]]


So there are N total ways, some distinguishable, some indistinguishable to choose the object

If each DISTINGUISHABLE OBJECT can be chosen in k ways, then we have N / K objects

So that means each object has to be able to be chosen in k ways exactly, othewrise we’d probably have to do cases. 

### Explain it in terms of sets


The way a set works is by having distinct elements
This would thus assume that our choice, we have a set of ways to choose it 
but if we have NUMOBJECTS subsets that contain identicaly elements, we can divide by that cardinality 

So total way to choose things is the set that contains subsets and each subset represents an object, and the number of ways to choose that object is in the subsets. 

SO we can divide by those way sto divide them and get the number of subsets themselves. 


![[Pasted image 20220721134926.png]]

So to get the n sets we have to divide by d since they all have d elements, and we’re assuming the d elements are unique for each since the subsets are disjoint. 

![[Pasted image 20220721135056.png]]





## Examples 