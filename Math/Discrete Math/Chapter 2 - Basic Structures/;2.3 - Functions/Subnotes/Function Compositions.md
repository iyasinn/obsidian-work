# Composite Functions

[[;2.3 - Functions]]
[[Functions]]
[[Inverse Functions]]

---

## Notes

### What is a function composition? 

![[Pasted image 20220629213652.png]]

So the inner function’s OUTPUT is used as the INPUT for the outer function

The domain of this is the domain of g, and the codomain is the codomain of f. 

Domain: Inner function
Codomain: Outer function

The range of of this function will be the range of the outer function given the range of the inner function as the input. 




![[Pasted image 20220629215737.png]]

### Visualize an inverse function with 3 sets

![[inverse function drawing]]



### If we know that f o g exists where g : A→ B and f: B → C, does g o f exist?
f o g maps A → C, starting with g and going to f

g o f would map B → C → B

This means the output of f, which is C is entered into g
So it must be the case that $C \subseteq A$, which is the input

**You must ALWAYS provide a legal input to any function**

### Hence, what must be true for a composition to work? 
The RANGE of the inner function must be a subset of the domain of the innner function. 

We don’t say codomain of inner function, why? Because technically if the range is inside the domain, then we don’t need to worry about any elements that are not in the domain of the outer function. 



### How do you prove function properties with composition? 

You prove them like regular function properties, given what you are told. Try proving these:
![[Pasted image 20220629215702.png]]

Lecture 13 has the answers. 



---


### How do compositions relate to [[Inverse Functions]]
We know that for an inverse of f, say $f^{-1}$
Then

$f of^{-1}(x) = x \iff f^{-1}of(x) = x$

Why? 

Because for an inverse function, firstly we know the output of one function will be the input of the other function due to bijectivity, so they do work.
And then 

![[inversestuff]]


This is over the top, but we could also just think of it as the fact the inverse loops back. 

![[Pasted image 20220629220628.png]]

## Examples

- ![[Pasted image 20220629215942.png]]
	- ![[Pasted image 20220629215948.png]]
- ![[Pasted image 20220629215953.png]]
	- ![[Pasted image 20220629215957.png]]
- ![[Pasted image 20220629220002.png]]
	- ![[Pasted image 20220629220034.png]]
- 