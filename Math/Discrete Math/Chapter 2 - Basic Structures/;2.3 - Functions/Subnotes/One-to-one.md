# One-to-one functions

[[Function Classifications]]
[[Functions]]

---

### Notes

##### What is an injection relationship for a function?

>[!info]
>A function f is said to be an **injection** or **one-to-one** if and only if f(a) = f(b) implies that a = b for all a and be in the domain of f.
>
>If it’s one-to-one, then it’s injective. 

So essentially, every input will map to exactly one output, BUT, that input itself is the ONLY input that maps to that one output. 

So any output that is mapped to will be mapped to by that one input. 




##### Explain an injective function in predicate logic

A function is one-to-one if and only if:
$$\forall x, y \in D [f(x) = f(y) \to x =y]$$
Where D is the domain

![[Pasted image 20220627233518.png]]
![[Pasted image 20220627233526.png]]


###### Why don’t we have  $\forall x, y \in D [f(x) = f(y) \iff x =y]$
Because one of the statements in the predicate will be
$x =y \to f(x) = f(y)$ 
We already know this is trivially true, since we are dealing with a function. Thus, we get left with the original statement. 


##### Visualize a one-to-one function
![[Pasted image 20220627234746.png]]


##### When is a function where the domain/codomain = $\mathbb{R}$ injective?

![[Pasted image 20220627233726.png]]

![[Pasted image 20220627234210.png]]


When the function is strictly increasing or decreasing, it ensures that there is no output where there are two inputs. 
If it’s not strictly increasing, that means there are two outputs that have the same input. 

Furthermore, we can use the derivative, and state that a function is one to one when its derivative never equals 0. That ensures there are no turns. 
Now, if it does = 0, then it must only do so at one point. If that’s the case, and it doesn’t flip sign, then it’s fine. 



##### If a function is 1-1, what does this tell you about the cardinalites of the domain and codomain? 
[[Cardinality]]

### Examples
- ![[Pasted image 20220627233552.png]]
- ![[Pasted image 20220627233601.png]]
	- ![[Pasted image 20220627233606.png]]
- ![[Pasted image 20220627233610.png]]
	- ![[Pasted image 20220627233615.png]]
- ![[Pasted image 20220627233623.png]]
- ![[Pasted image 20220627233630.png]]
	- ![[Pasted image 20220627233637.png]]
- ![[Pasted image 20220627233644.png]]
- ![[Pasted image 20220627234432.png]]