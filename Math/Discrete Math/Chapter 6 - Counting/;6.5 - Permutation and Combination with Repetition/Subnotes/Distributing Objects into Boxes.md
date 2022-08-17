# Distributing Objects into Boxes

[[;6.5 - Permutation and Combination with Repetition]]

---

## Notes

### Labeled Objects and Labeled Boxes


![[Pasted image 20220809185054.png]]

This is really just a permutation with unlabeled objects, weirdly. 
Let’s say we have abcdef
We have 2 boxes, each have 3 objects. 
We can say the first 3 spots are for the first box, and the last 3 for the last box. 
But since we place into these boxes, and order doesn’t matter, we divide by 3! for each of the two above boxes. 

So interestingly, we have 6 objects, and it’s just that we consider any in the first three to be the same. I’s not the same mathematical reasoning as the permutations with unlabeled objects, but it still works very well. 


#### What if our boxes don’t contain an element?
Then we divide out what is NOT Placed in a box, of which there will be the remaining number of objects factorial ways to order

Because we’re not just splitting into groups of what is placed in the box, we also have a group of what is NOT placed in the box. That is important to consider and understand. 



### Unlabeled objects into labeled boxes

We can use balls and bars and here we know repetition is allowed 
