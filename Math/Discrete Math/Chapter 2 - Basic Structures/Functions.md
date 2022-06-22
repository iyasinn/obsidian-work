# Functions

[[;2.3 - Functions]]

[[Set]]

---
## Fundamental
###### Define a Function

A function is a specific type of “relation” between sets. 

>[!info] Function Definition
>Consider nonempty sets A and B
>
>A **Function** from A to B is an assignment of exactly one element of B to each element of A. 
>
>We can write: f(a) = b   where b is a **unique** element from set B assigned by the function f to an element of a. 
>
>The input is denoted by a, and the output, which can be denoted by b, can also be denoted by f(b)
>
>If f is a function from A to B, we write: 
>
>$f: A \to B$
>

We can also think of a function as a “machine".
$f : A \to B$ 
f is a machine that maps any element of A, the domain, to exactly one element in B, the co domain. 

Functions are also called “mappings” or “transformations.”

Assuming f is a function 
$\forall x \exists !y[f(x) = y]$
is in general what a function should satisfy. 

The output can be some image. 


![[Pasted image 20220622000715.png]]

![[Pasted image 20220622003006.png]]



---



###### What are the key requirements for some relationship to be a function? 
- Every element in the domain MUST map to an element in the output.
- Every input must produce exactly ONE output. Not 0, not more than 1, exactly one all the time. 
- A mapping that does not satisfy the above is just a relation, not a function. 

###### What 3 characteristics do we define for a function?

Consider $$f : A \to B$$
When defining a function, we always specify: Domain, Codomain, and Mapping. 
By defining Mapping, we also define Range, as it follows from the Mapping. 

- ***Domain***
	- The domain is the [[Set]] of all possible inputs, and in this case, is characterized as set A. Every element in this domain must map to some element in the codomain. 
		- Domain = $\{x | x \in A\}$
- ***Codomain***
	- The codomain is the [[Set]] of all possible outputs for the function f. It is characterized by set B. Not all the elements in the codomain need to be mapped to by an element in set A. However, no two elements in the codomain should be mapped to by an element in set A. 
		- Codomain = $\{x | x \in B\}$
- ***Range***
	- The range is the [[Set]] of elements in the codomain that actually get mapped to. It is a [[Subsets]] of the codomain. 
		- Range = $\{x \in B | \exists a \in A[f(a) = b]\}$
		- Or: Range = $\{f(a), a \in A | f(a) \in B\}$
- ***Mapping***
	- The function, denoted by f, is used to specifically take an element from the domain and map it to an element in the codomain. It is the actual relationship itself. Whenever talking about the mapping (onto, one-one), etc, we talk about **f** or whatever variable denotes the function mapping. 

![[Pasted image 20220622001136.png]]


![[Pasted image 20220622001232.png]]

###### How specific does the mapping in a function be? 

The mapping can really be anything. It can be some pattern, OR it can just be some specific mapping that you have specifically defined. 

But generally, the function **f**, is **applied** to each input element to get the output. Of course that mapping can be literally anything. 

###### Show how a function graphically looks usually

**Visualized as sets**

![[Functions 2022-06-22 00.14.05.excalidraw]]

We can also visualize more simply as 

![[Pasted image 20220622002053.png]]

Just like visualizing [[Quantifiers]]
###### Explain the notation for a function 
When defining a function, we
- Create some variable for the function (usually lowercase alphabetical character)
- Show the domain 
- Show the codomain 
- Define the mapping 

$f : A \to B$ such that “mapping”

Here, f is our function variable. 
$A \to B$ denotes that our domain is A, and our codomain is B. 
Finally, we have some “mapping”, this could be something we just show like graphically showing each connection, or some formula. 

Regardless, that “mapping” should allow you to get any f(x) from x where f(x) is an element of B, and x is an element of A

We could also say f(x) = y and then show how to get y

But the point is, **the output is always f(x), regardless of how your expression is organized**

- $f : \mathbb{Z} \to \mathbb{Z}, f(x) = x + 1$

Example of a function. Note how we give the variable name, the domain and codomain, and some mapping that allows us to take any element of the codomain and get an output in the codomain. 

If you get an output that isn’t in the codomain, then you do not have a function since your input doesn’t map to any valid image (ouptut)




























































###### Are functions technically just sets of orderd pairs? 
Technically, yes. 
We can consider each mapping in a function as an orderd pair. 
Furthermore, we will know than that a function is a [[Subsets]] of the [[Cartesian Product]] of the Domain X Co domain. Of course, many relatinos are subsets, but a function, which is a subset of all possible relations, exists. 




## Enahancement
