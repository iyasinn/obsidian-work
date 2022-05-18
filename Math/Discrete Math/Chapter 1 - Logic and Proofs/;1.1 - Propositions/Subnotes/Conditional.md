# Conditional operator


>[!info] Conditional Operator
>
>![[Pasted image 20220509005057.png]]
>
>![[Pasted image 20220509005657.png]]
>

The conditional operator is an operator that is **difference** from what we expect in modern day english. It isn't about a hyothesis proving a conclusion. Instead, it is merely defined by the idea that it is ONLY false when the p is true and q is false. 

Think of the conditional as a promise! Some promise is made, so that when p is true, there is a promise that q will be true. if it's broken, then you have a falsy statement. But if the p never occurs, that promise will never be tested!

Another approach is to say that the conditional is like a **guarantee**, where **q** is guaranteed to happen if **p** happens. 
So, if **p** doesn't happen, that doesn't mean **q** can't happen, it just means there's no longer any **guarantee** of **q** occuring. Similar to the promise. 

Not only that, but the conditional is not a cause and effect relationship. Conditional statements are much more general than in regular english. The premise doesn't actually need to be related to the conclusion. This can cause weird propostioins to be formed, but regardless, the only point of the conditional is to create a proposition where you have a guaranteed q when p is true. Sure, q can be true in other cases, but the point is to ensure it will be true when p is true. And if it's false, then our proposition is false! 

- Helpful tips
	- ![[Pasted image 20220509012012.png]]

---
#### Truth Tables

![[Pasted image 20220509005708.png]]

An important thing to realize is that when p is false, ANYTHING can happen. 
The conditional is not saying that for **q** to be true **p** needs to be true. Instead all it's saying is that for **p** to be true, **q** needs to be true. 

That's how the implication works in the conditional. 

There is no condition on **q**. Hence, **q** can be true in any case. All that matters is that if **p** is true then **q** is true. 

---
#### **Different forms of the conditional p $\longrightarrow$ q**

![[Pasted image 20220509010207.png]]

As seen here, there are many forms of the conditional statement. 
We have **if p, then q**, and all that means is that if **p** is true, then **q** is true. If **p** is not true, then **q** can be anything.

We also p is sufficient for q. Which makes sense. If p is true, then MUST be sufficient for q being true. If it isn't sufficient, and q is false, then your statement is false. 

**p only if q** is importan too. this means that p can only be true if q is true as well, which makes sense. Note the restriction is on p! If p is false, then it doesn't matter what q is. But for p to be true, it is a requirement that q is true. 

	> You can receive an A in the course only if your score on the final 
        is at least 90%

This is a good example if **p only if q**. 
For the condition of recieving an A, you NEED at least a 90. However, getting a 90 does not guarantee an A. Getting a 90 doens't mean you'll get an A, instead it's the other way around, you can only have an A if you have a 90, but there might also be OTHER conditions as well. 

So that's why get A  $\longrightarrow$  receive 90 

is correct. If you don't get A, it could be for any reason. but if you get an A, that means you for sure recieved 90. You could also get a 90 and not receive an A. Again, 90 is a condition, but not necessarily the only condition. 

---
**q is necessary for p**
For this one, we can think of it as for p to be true, then we know that q has to be true. So in a way, q is necesary for p. 
q HAS to be true if we want p to be true, otherwise, p has to be false. 

So here, q is guranteed to occur for p, which is why its necessary for p. 
p cant be true without q though.l 

---
**p is sufficient for q**
This just means that if p is true, q should follow to be true as well. So for example if we receive an A, because 90 is a requirement, it's sufficient to say that receiving an A can prove we got a 90. 
However, NOTE the word SUFFICIENT. p can be false and q can still be true. p is sufficient but it is NOT NECESSARY, whilst the other way around, q is necessary for p 

In that way, p as a truth value should be sufficient to gurantee q. However, p being true is sufficient in guranteeing that q is true. But it's not necessary. q can still occur without p, p is sufficient, but it's not the only case. 

That's the thing, p is sufficient, but it's not the only thing that can cause q!

---
**q unless -p**

An example is 
Maria will find a good job unless she does not learn discrete mathematics. 

So what this is saying is that if maria does not learn discrete mathematics, then she is NOT guaranteed to find a good job. 

But if she does learn discrete math, then she is GURANTEED to learn q. 

So here, the unless doesn't mean Q CANT HAPPEN, instead, it means your guarantee is gone. 


---


### Conversion of conditional!

We convert $p\rightarrow q$ into $\neg p \lor q$

Why?

Well, they have the same truth tables
But also
If you think about it 

p $\rightarrow$ q is true when either p is false, or p is true AND q is true 

Which in this case

If p is false, then -p is true, and that makes the entire disjunction true
If p is true, which equates to false for -p, then q HAS to be true

This is pratically the same as the conditional!
And hence it's equivalent!

So the statement 

if i run, i am cool

is also

I don't run or I am cool


Also 


I am cool, unless I don't run 


I don't run or I am cool

Because this is q unless -p, so we already have -p!




#### Examples

- ![[Pasted image 20220509012535.png]]
	- ![[Pasted image 20220509012548.png]] ![[Pasted image 20220509012618.png]]
	  






