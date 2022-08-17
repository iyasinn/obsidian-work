# Assigning Probabilities

[[;7.2 - Probability Theory]]


---

## Notes

### For defining probability for unlikely or equally likely outcomes, what are two required conditions: 


>[!info] Requirements
>
>Let *S* be a sample space of an experiment with finite or a countable number of outcomes. 
>We assign a probability p(s) to each outcome *s*. 
>
>**Condition 1:**
>$\forall s \in S \; [0 \leq p(s) \leq 1]$
>
>**Condition 2:**
>$\sum\limits_{s \in S} \; [p(s) = 1]$

Condition 1 states that the probability of any outcome must be in [0, 1]
Condition 2 states that the sum of all possible outcomes must be 1. 
If we had infinite outcomes, then this would be a convergent series to 1. 

![[Pasted image 20220816215401.png]]

![[Pasted image 20220816215411.png]]








### What is a probability distribution? 

This is the function p from the set of all outcomes in the sample space to the real numbers [0, 1]

It does not have to be onto or 1-1, however, it must be a function. 

##### Explain how experiments are modeled with a probability distribution. 

![[Pasted image 20220816215831.png]]

So p(s) = $\lim\limits_{n \to \infty}[\frac{m}{n}]$

m: Number of times that m occurs in all of the n experiments
n: The total number of experiments

This accounts for equally likely or unequally likely probabilities, since now we aren’t just saying that p(s) = 1/|S|


### When modelling experiments with equally likely or not equally likely probabilities, how do we choose an appropriate function p(s) for each outcome? 

If all events are equally likely, then p(s) = 1 / |S|

However, if all outcomes are not equally likely, we will have to do some calculations. 

![[Pasted image 20220816221028.png]]


Here is an example of how to do so




### What is the uniform distribution? When is it used?

>[!info] Uniform Distribution
>
>![[Pasted image 20220816221104.png]]


### How can we define the probability of an event? 
>[!info] p(E)
>
>![[Pasted image 20220816221131.png]]


![[Pasted image 20220816221254.png]]




#### Using this definition, explain why p(E) = |E| / |S| for Laplace Definition, where events are equally likely 

Well, since all events are equally likely, we end up with |E| * 1/n = |E|/n and since n = |S| we have |E|/|S|


![[Pasted image 20220816221342.png]]







## Examples

