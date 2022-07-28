# Strong Induction 

#### Define strong induction

>[!fail] Strong Induction
>![[Pasted image 20220613183449.png]]

In strong induction, we have the same thing as simple induction, but we get to use all the information we can

Doesn’t have to be →p(k+1), could also → p(k + 2) or → p(k) or → p(k + 4)

Adjust the range of your inductive hypothesis though

##### Explain the base case
Here, we just need to verify that P(1) or P(first value) is true. 

However, it is important to note that anything that can’t be used for the inductive step must ALSO be verified here. 

Usually, we assume 
$$p(a) \land p(a + 1) \land .... \land \; p(a + n)$$
And show that this is true. 

##### Explain the inductive step 

The inductive step requires you to assume P(i) for $$a \leq i \leq k$$ and use it to prove 
$$P(k + 1)$$

###### Why can we use all the previous propostions inside the inductive step? 
Because technically with simple induction, we prove P(k) → P(k + 1), and then we “climb” all the way to our desired n. 

To climb to it, we need to prove all the propostions along the way anyway, so it’s perfectly valid to assume all the previous propostions. 

If you are unsure of this, you can further confirm it by thinking about how If we only have P(1) and use it to prove P(2), then strong induction just says that when proving P(3) you can use P(1) and P(2). 
If you say “How can we know P(2)” is true, well you can just go to the smallest case and show P(1) allows for P(2), in this case the premise has one predicate, but as we prove P(3) we now have P(1) and P(2)
![[Pasted image 20220614010550.png]]





#### Why is strong induction more flexible than mathematical induction?

While the base steps are identical, strong induction has more to work with for the inductive step. Hence, it is more flexible, and thus easier to use. 

![[Pasted image 20220613183700.png]]





#### What is some other terminology for strong induction:
- Second principle of mathematical induction
- Complete induction 
	- Mathematical induction is thus called incomplete induction. This doesn’t mean it’s an incomplete technique, this is just misleading terminology. 

#### Infinite Ladder Analogy: Explain it
Consider the infinite ladder from 5.1

Strong induction allows us to state that we can reach all rungs if the following are true. : 
1. We can reach the first rung is true. 
2. For every positive integer k, if we can reach all the first k rungs, then we can reach the (k + 1)st rung is a true statement. 

##### Try this question. Why is it hard to do with mathematical induction.  ![[Pasted image 20220613213355.png]]

It’s hard to do with induction because we need to leverage information we have from before for this question. 
P(k) doesn’t tell us if we can reach P(k + 1)

P(k - 1) however, does tell us we can reach P(k + 1) since we know we can reach two rungs higher. 

Furthermore, for our base cases, we would need two. 
Since 
1 ≤ j ≤ k
And we use k - 1
1 ≤ k - 1
2 ≤ k

We need to prove P(1) and P(2) work.
P(1) and P(2) are true thanks to the problem statement, which states that we can reach the first and second rungs of the ladder. 

![[Pasted image 20220613213542.png]]




#### Infinite dominos analogy
![[Pasted image 20220613213750.png]]


![[Pasted image 20220613213818.png]]







#### When should you use strong induction over mathematical induction?


Generally, there is no rule. Usually we state that you should use strong induction over mathematical induction when you can’t see a clear and easy way to prove P(k) → P(k + 1)   or   P(k - 1) → P(k)

Then you should use strong induction, since it provides you with much more information. 

![[Pasted image 20220613213719.png]]



#### Explain the alternate (But equivalent) form of strong induction 
![[Pasted image 20220613223914.png]]

We need access to our base cases! That’s how we limit k!