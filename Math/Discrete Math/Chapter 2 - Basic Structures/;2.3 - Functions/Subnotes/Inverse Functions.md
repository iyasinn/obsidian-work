# Inverse Functions

[[;2.3 - Functions 1]]
[[Functions]]

---

## Notes

### What is an inverse function? 

>[!info] Inverse Function
>
> Consider an function f: A → B    such that f(a) = b
> 
> The inverse of is denoted by $f^{-1}$
>$f^{-1}: B -> A$ such that $f^{-1}$(b) = a
>
> The domain and codomain are flipped
> 
> And as such
> 
> f(a) = b when $f^{-1}(b)$ = a
> 
> Thus: $$\forall a \in A \forall b \in B [f(a) = b \iff f^{-1}(b) = a]$$
> 
> For an inverse function to occur, it needs to be the case that the function for which you are finding the inverse is a [[Bijective]] function





**This is like another machine**

*Note: Inverses exist for SPECIFIC functions. A given function may or may not have an inverse. However, the identity of the sets in hand may come into play.*

![[Pasted image 20220629211755.png]]

![[Pasted image 20220629211801.png]]

![[Pasted image 20220629211810.png]]

### When you have to find the inverse, what do you specifically need to provide? 
You need to provide the new domain and codomain, as well as a new mapping. The new mapping could be a new function, expression, or you simply list out the mappings.

Just like how we can say f(a) = 1, f(b)=2 when listing out mapping, or drawing a diagram, we can do the same thing with the inverse. After all, the inverse is just a **function**

### Why does a function need to be [[Bijective]] to have an inverse? 

##### If it’s not a [[One-to-one]] function
Then, this means multiple inputs can have the same output. 
However, for the inverse function, since the outputs and inputs flip, that means one input for the inverse can have multiple outputs. Hence, the inverse function wouldn’t exist as it is not a function. 

![[Pasted image 20220629212331.png]]


##### If it’s not [[Onto]]

If it is not onto, that means not all outputs have an input for f. 

But, for $f^{-1}$, since the outputs and inputs flip, that means there will be some inputs that now don’t have an output. 

A function requires that all inputs have an output that is defined, exactly one output, hence this would not be a function and the inverse does not exist.

![[Pasted image 20220629212318.png]]


### What does it mean for a function to be ***invertible***
A function is **invertible** if it is a [[Bijective]] function, since that means it has an inverse.

Functions without inverses are not invertible.



### How do you prove that two expressions are inverses?

This is very important.
If we have f(x) and g(x) and we suspect they are inverses

We have to show that f(g(x)) = x

And


g(f(x)) = x





## Examples
![[Pasted image 20220629212728.png]]