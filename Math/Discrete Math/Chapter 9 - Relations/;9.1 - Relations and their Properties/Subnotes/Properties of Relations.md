# Properties of Relations

[[;9.1 - Relations and their Properties]]
[[Relations ON a Set]]

---

Relations on sets have very interesting properties that can arise. 
Note: These are properties regarding the **entire** relation

[[Reflexive]]
[[Symmetric]]
[[Antisymmetric]]
[[Transitive]]


Extra properties (not as important)
[[asymmetric]]
[[irreflexive]]


**Tips for these properties**
- Loops are very useful. Not just for reflexivity, but also for transitivity. 
- Be mindful of an empty set of elements being relate and an empty set of edges, as well as empty set of elements AND edges. They are all a bit nuianced.


## Good questions

- **Very good problem** ![[Pasted image 20220706231441.png]] 
	- So, we have relations on some set n
	  So the cartesian product will have $n^2$ elements 
	  So how many of these will have ALL relations such that they are reflexive, aka it needs to have ALL (a, a), (b, b) ..and any other ones. If we had n unique elements, then we will have n elements required such that they are refleixve.
	  
	  so n * something will give us the total number of combinations. 
	  n^2 - n will remove all n elements of refleixve relations from the cartesian product, leaving us with n^2 - n remainng elements that we can or can’t have have, this ia  binary thing, so we end up having 2^(n^2 - n) potential ways to choose elements. The big thing was subtracting the set of all reflexive elements to see what combinatinos we needed to work with. **GOOD PROBLEM**
	- ![[Pasted image 20220706231611.png]]
	- ![[Pasted image 20220706232116.png]]
	- 
