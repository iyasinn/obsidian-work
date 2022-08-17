# Finite Probability

[[;7.1 - Introduction]]
[[Set]]

---

## Notes



### What is an experiment, sample space, outcome, and event?
>[!info] Definitions
>
>**Experiment**: A procedure that yields one of a given [[Set]] of possible outcomes
>
>**Sample Space**: The [[Set]] of all possible outcomes in an experiment. 
>
>**Event**: a [[Subsets|subset]] of the **sample space**.

### What is Laplace’s definition of probability?

>[!info] Probability
>
>If *S* is a **finite nonempty** sample space of **equally likely** outcomes, and *E* is an event, that is, a [[Subsets|subset]] of *S*, then the probability of *E*:
>
>$p(E)=\frac{|E|}{|S|}$
>


#### Explain the bounds of probability.

Since $0 \leq |E| \leq |S|$ because $E \subseteq S$
We know that by multiplying the inequality by $\frac{1}{|S|}$ 
$0 \leq \frac{|E|}{|S|} \leq 1$
Hence:
$0 \leq p(E) \leq 1$




### Why is set theory important for probability?
We can view the sample space as a set, and hence we can view events as subsets. This is helpful in making us decide what type of probability we are looking to find. 


### What does it mean for all outcomes to be equally likely? What does this mean about the probability of the outcomes, and the probability of the events?  

It means:
$\forall x \in S[p(x) = \frac{1}{|S|}]$

So the probability of any outcome is $\frac{1}{|S|}$

Hence, the probability of any event is just: 
$p(E) = |E| * \frac{1}{|S|} = \frac{|E|}{|S|}$

If the events were not equally likely, then really we’d be summing up all the individual probabilities of each outcome. 



### Explain multiplication and addition for probabilities?

These are like the [[Sum Rule Counting]] or [[Product Rule Counting]]

Product rule: Multiple events must occur at the same time, so we can multiply, as if we are multiplying sets to get the Cartesian product, and that represents the new total set of outcomes. 

Sum rule: When one event or another can occur, we can add them up. We will have to account for overlap though. 


##### Proof of product rule 
If a and b are mutually exclusive: 
p(A AND B) = |A AND B| / |S| =  |A| * |B| / |S| = |A| / |B| *   |B| / |S| = p(A) * p(B)





## Examples