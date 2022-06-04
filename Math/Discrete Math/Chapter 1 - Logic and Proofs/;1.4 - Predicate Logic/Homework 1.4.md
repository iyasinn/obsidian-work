# Homework 


# 1


# 2


# 3


# 4


# 5
a. There exists a student that spends more than 5 hours every weekday in class. 

b. Every student spends more than 5 hours every weekday in class.  

c. There exists a student that does not spend more than 5 hours every weekday in class. 

d. Every student does not spend more than 5 hours every weekday in class. ⭐
	Or: No student spends more than 5 hours every weekday in class. You can use “No”, “nobody”, etc. 
	
**This use of “no” or “nobody” is simple, so make sure not to overcomplicate it. If everybody doesn’t do something, then that’s the same as saying nobody does it.**

Could even use less than or equal to, it’s common sense. 




# 6


# 7

Domain: All people

a. Everyone who is a comedian is funny. 
	OR: For every person, if they are a comedian, then they are funny works too. 

b. Every person is a comedian and is funny. 
![[Pasted image 20220521134422.png]]

c. There exists someone who if they are a comediain, is funny. 
	There exists someone such that if they are a comedian, then they are funny. 
	There exists a person in the domain such that if the person is a comediene, then they are funny. 


	You can use **such taht** as awell. 

d. There exists someone who is a comedian and is funny. 

There is a funny comedian 

Some comedians are funny

Some funy pepole are comedians. 



There are many ways to render this is english
There is a funny comedian
There exists a comedian that is fujnny 
Some comediains are funny 


![[Pasted image 20220518003610.png]]


# 8


# 9
Domain: All students at your school.

a. 
There exists a student who can do both things
$\exists x(P(x) \land Q(x))$

b. 
but is like “and”

$\exists x[P(x) \land \neg{Q(x)}]$

-

c. 
 
$\forall x[P(x) \lor Q(x)]$


d. ⭐

$\neg \exists x [R(X) \lor Q(X)]$

$\forall x (-R(x) \land -Q(x))$


Neither should be possible

$\forall x(-(R(X) V Q(X))$

Nobody has this talent 

Means everyobdy doesn’t have it
OrtizS
There isn’t someone that has it 



**HARD**

$\forall x[\neg P(x) \land \neg Q(x)]$

$\forall x \neg[P(x) \lor Q(x)]$

$\neg \exists x [P(x) \lor Q(x)]$

So there doesn’t exist someone who can speak russion or program 

**The not here is applying to the entier statement of p or q**



The first here is false because it asserts that all students only don’t have at least one, so there could be someone who can still speak russian, going against our statement. 

The second one implies that someone cuold also still know one of them, since you only need one false for an AND to be false. 

SO really, just make a statement, and COMPARE to the original phrase


![[Pasted image 20220521134830.png]]

# 10


# 11

a. true 
b. true 
c. false 
d. false 
e. true 
d. false 




# 12


# 13
domain is ALL INTEGERS 

a. true 
b. True → works for n = 0 
c. True → Works for n = 0

d. False, doesn’t work for negative numbers. 

# 14


# 15
Domain is all integers 

⭐

**Split your cases, negative, 0, positive**


a. True 
b. False 
c. True 
d. False


# 16



# 17
Domain: 0, 1, 2, 3, 4

We have a finite domain so we can exand these

a. $P(0) \lor P(1) \lor P(2) \lor P(3) \lor P(4)$

b. $P(0) \land P(1) \land  P(2) \land  P(3) \land  P(4)$

c. $\neg P(0) \lor \neg P(1) \lor \neg P(2) \lor \neg P(3) \lor \neg P(4)$

d. b. $\neg  P(0) \land \neg P(1) \land  P\neg (2) \land  \neg P(3) \land  \neg P(4)$

e. $\neg{(P(0) \lor P(1) \lor P(2) \lor P(3) \lor P(4))}$

f. $\neg{(P(0) \land P(1) \land  P(2) \land  P(3) \land  P(4))}$



# 18


# 19 ⭐ This problem is an example that you should EXPLORE

Not going to do all of these. But will do e

$((1 \neq 3 \rightarrow P(1)) \land (2 \neq 3 \rightarrow P(2)) \land (3 \neq 3 \rightarrow P(3)) \land (4 \neq 3 \rightarrow P(4)) \land (5 \neq 3 \rightarrow P(5)))$$\lor (\neg{P(1)} \lor \neg{P(2)} \lor \neg{P(3)} \lor \neg{P(4)} \lor\neg{P(5)})$

We can simplify. For all statements in the original that have true premises, that’s just equivalent to the conclusion, and for all statements that have false statements, that’s true, but since this is conjunction, we can use identity and remove that True by itself to get:


$(P(1) \land P(2) \land P(4) \land P(5)) \lor (\neg{P(1)} \lor \neg{P(2)} \lor \neg{P(3)} \lor \neg{P(4)} \lor\neg{P(5)})$


Now, conceptually, if all the propstions are true then this will become true as well. However, if there is one that is false, then the left statement will \betafalse, but the right will be true. 

If all proptions are false, the the right will \betatrue as well. 

Hence. this is a tautology

**THIS IS JUST TRUE**


# 20


# 21
a. 
True: Domain is everyone in eecs 203 
False: Domain is all students 



b. 
True: Domain is everyone older than 21
False: Domain is all children. 

c. 

True: Domain 2 siblings. 
False: Domain is one person from each family in the world. 


d.

True: Domain is one person from different families
False: Domain is 4 siblings. 


**OUr domains can be. limited in any way. Even by putting one person in the domain **

# 22


# 23

a. 
Domain is all people
$\exists x (C(x) \land H(x))$
Domain is in class
$\exists x (H(x))$


b. 
Domain is all people 
$\forall x (C(x) \rightarrow F(x))$
All ppl in class 
$\forall x (F(X))$

c. 
Domain is all people
$\exists x(C(X) \land \neg{B(x)})$
Domain is class 
$\exists x (\neg{B(x)})$

d.
Domai is all people
$\exists x[C(x) \land M(x)]$

Doman is class
$\exists x[M(x)]$

e. 
Domain is all people
$\forall x[C(x) \rightarrow \neg P(x)]$

Domain is all people in my class

$\forall x[\neg{P(x)}]$






# 24


# 25 ⭐

Domain is all people 
P(x) = x is perfect 
F(x) = x is your friend 

a. $\forall x {\neg P(x)}$
This is saying that of all people, no one can be perfect.
Original: No on eis perfect
WE can also think of it as there exists no one that is perfect, so the negation of the exiosenttial 

b. $\neg \forall x[P(x)]$
This is stating that not every one is perfect. So simply, it is not the case that everyone is perfect….so…some people can be. perfect, but not everyone. 

c. $\forall x [F(x) \rightarrow P(x)]$
This is stating that everyone who is your friend is perfect. We can use F(x) as a domain restriction. 

d. $\exists x [F(x) \land P(x)]$
Here, at least one of my friends is perfect. So to ensure that, we state that the person is my friend and perfect. 

e. $\forall x [F(x) \land P(x)]$

f. This is saying not everybody is my friend or someone is perfect. So I can have some friends, just not everybody being my friend. 

$\neg \forall x [F(x)] \lor \exists x[\neg P(x)]$

So either everyone is not my friend, or there exists someone who is not perfect. 

We can keep these separate, since we are analyzing two different cases. 


![[Pasted image 20220521170837.png]]
![[Pasted image 20220521170843.png]]
---




# 26


# 27 ⭐
a. Domain is all people in my school 
$\forall x [V(x)]$

b. Domain is all humans
$\exists x [S(x) \land \neg{H(x)}]$

c. Domain is all people in my school 
$\exists x [\neg{H(x)}]$

d. Domain is all people. 
$\forall x [C(x) \rightarrow T(x)]$

e. Domain is all people in my school 
$\exists x [C(x) \land \neg H(x)]$


**The important thing to note is that it’s actually better to have more general porpstions 

**Likely's
S(x,y) = person x can speak langauge y** 

**That y these predicates can be. used in more general cases.**** 

# 28


# 29 ⭐
T(x) = x is a tautology ✅

Is a contradiction just the negation of a tautology. Nope, because a contingency is also not a tautology. 

C(x) = x is a contradiction 


contingency is -C(x) and -T(x)….aka it is not a tautology or a contradiction,    so - (C(x) V T(x) )

Can’t say -C(x) or -T(x) since for this to be. true the proopsition could \betaa contingency or a propstions. 

So OR has a weakness here and conjunction is better 


Domain for x and y is ANY PROPSTION 

ANd hence we can put any propostion into the statmene 

….


a. $\exists x [T(x)]$

b. $\forall x [C(x) \rightarrow T(\neg{x})$

**If your domain is all propstions, technically you can apply logical operators to it. **

**This also goes for algebraic expressions. Don’t limit yourself!**

If x is a contradiction, and x is a propstion, then the negation of x is a tuatology. 

c. Can be. implies that some contingiencys with a disjunciton can turn into a tautology  ❌

MADE A MISTAKE. It’s not saying the disjunction of TWO contradictions are a tautology. It’s saying the disjucntion of a CONTINENCY. CONTINGECY IS NOT A TUATOLOGY AND NOT A CONTRADICTION 

$\exists x \exists y [C(x) \land C(y) \land T(x \lor y)]$


d. $\forall x \forall y [T(x) \rightarrow T(y) \rightarrow T(x \land y)]$

OR 

$\forall x \forall y [T(x) \land T(y) \rightarrow T(x \land y)]$

Two ways to do the restriction 


![[Pasted image 20220521171745.png]]

**Some ideas are a universal \. existential ideas. Like “can be” is existential while “all is” is a universal type of idea**



# 31 

a. $Q(0,0,0) \land Q(0,1,0)$

b. $Q(0,1,1) \lor Q(1,1,1) \lor Q(2, 1, 1)$

c. $\neg Q(0,0,0) \lor \neg Q(1,0,0)$

d. $\neg Q(0, 0, 1) \lor \neg Q(1, 0, 1) \lor \neg Q(2, 0, 1)$



# 33 ⭐
a. $\exists x [O(x) \land T(x)]$

Some old dogs can learn new tricks. 

$\neg \exists x [O(x) \land T(x)] \equiv \forall x [\neg O(x) \lor \neg T(x)]$

All dogs are not old or they cannot learn new tricks 

All olds dogs can’t learn new tricks

Or  

no dogs are old and can learn new tricks. 
OR

No old dog that can learn new tricks. 


b.
x is all rabits   
C(x) = know calculus


$\forall x [\neg C(x)]$
This states that no rabit knows calculus, 
Negation is 

$\neg \forall x[\neg C(x)] \equiv \exists x \neg [\neg C(x)] \equiv \exists x [C(x)]$

There exists a rabiit that knows calculus 


There is a rabbit that knows calculus also orks 

c. x is \alphabirds

Negation is

There exists a bird that cannot fly 


d. 

$\neg \exists x [T(x)]$ or $\forall x [\neg T(x)]$

Negation 

$\exists x [T(x)]$

There is a dog that can talk 

e. 

There is no one in this class who knows french and russian


$\forall x \neg (F(x) \land R(x))$
OR
$\neg \exists x [F(x) \land R(x)]$

SAME THING

“No one person” is like “It is not the case that someone exists” or “No person exists such that”


Which is equivalent to 

“All people do not do this this thing” where the not is applied to the entire expression. So here no one knows french or russian means we apply the not to the whole expression and now we can say “for all people, they don’t [Do the expression]”

Don’t overcomplicate lmao 


Negation is 

$\exists x [F(x) \land R(x)]$

There is someone in this class that knows french and russian 


![[Pasted image 20220523152039.png]]


![[Pasted image 20220523152045.png]]


# 35

a. $\exists x [x \leq 1]$

b. $\exists x [x > 2]$

c. $\forall x [x < 4]$

d. $\forall x [x \geq 0]$

e. $\exists x [(x \geq -1) \land (x \leq 2)]$

f. $\forall x[(x \geq 4) \land (x \leq 7)]$



# 36


# 37

Need to find counter examples. 
The domain is all integers. 

a. This is true. 

b. 0 is a counterexample. It is neither greater than itself, or less than itself.

c. x = 3 is a counterexample. This is false. 









# 38


# 39 ⭐

a. 
x = all passengers on an airline
This is more of a universal statement giving a rule. 
$\forall x [F(x, 25,000) \lor T(x, 25) \rightarrow E(x)]$

b. 
x is all people 
T(x, y) = x’s marathon time is less than y hours
M(x) = man
-M(x) = not man which implicitly means woman

$\forall x[(M(x) \land T(x, 3) \lor (\neg M(x) \land T(x, 3.5)) \rightarrow Q(x)]$

c. 
x is all students 
T(x, y) = x has taken y course hours 
M(x) = x has writtena masters thesis 
y = all course
G(x, y) = student got higher than or equal to y


$\forall x(Q(x) \rightarrow (T(x, 60) \lor (T(x, 45) \land M(x) and \forall y[G(x, B)])))$

I did it this way because technically you can still do those things and not receive a masters degree. These things must be. done, aka they are NECESSARY

Must is like necessary. So q must \betadone for p is like q is necesasry for p I feel. 


d. 

x = all student

$\exists x [T(x, 21) \land \forall y[G(x, A)])]$


![[Pasted image 20220521204036.png]]


# 40


# 41 ⭐

My goal is to write these in clear and easy to understand english this time. 

P is all printers 
j is all jobs

a. 

There is a printer such that if it is either out of service or busy, then there is a job that is lost  ❌

**Be very careful about if a predicate applies to one statement or an ENTIRE statement!**


b. 
If a printer is busy, then there is a print job that is queued.

c. There is a job such that if the job is queued and lost, then there is a printer that is out of service. 

d. If all printers are busy and all jobs are queued, then there is a job that is lost. 

# 42


# 43

a. 
$\exists d [M(d, 10)] \to \exists m[S(m)]$

If there exists a disk with more than 10 kb of free space, then at least one message can be saved 

b. 

$\exists a [A(a)] \to \forall m [T(m)]$
OR

$\exists a[A(a) \to \forall m[T(m)]]$



c. 
Each usually refers to all 
And whom is liek a restriction 
C(x) = x put on a special list
B(x) = x was biled 

$\forall x[\neg{C(x)} \to  B(x)]$



# 44


# 45
![[Pasted image 20220521205837.png]]

The first statement is true if and only if the statement is true for all x, and that means P(x) can be false, or p(x) is true and Q(x) is true. 

The second statement is true when for all P(x) there is a false P(x), or if all are true, then all Q(x) are true. 

Seems the same but it isn’t. 
The first statement is false if and only if P(x) is true, and Q(x) is false for at least one case. 
Second statement is not false if one P(x) is true only, since other P(x) being false instantly makes it false. 

**Think about falsneess with conditionals, way less scenarios to think about. **

Easy counterexample:

Only one P(x) is true and all Q(x) are false. 

Then the firsts statement will be false since we have one true → false, which will be false.

The second statement will be true since not all P(x) are true so the hypothesis is true, and hence the entire statement is true. 

Other approach:
Domain: x all real numbers. 
P(x) =     x > 0 
Q(x)}=    x = -1

First statement is false. If x > 0 true, and x = 5, then x != 1, and hence there is one false case and hence it is incorect. 

On the other hand, the second statement, the premise will be false, and hence it will always be true, since not all integers are greater than 0. 

![[Pasted image 20220523152614.png]]

# 46


# 47

![[Pasted image 20220521210828.png]]

Proving distribution over a disjunction of existential 

The first statement is false if and only if for all x, P(x) and Q(x) is false. 
If that’s the case, the second statement is false as well since P(x) false since all P(x) false and same with Q(x)

Second statement is false if and only if all P(x) are false, and also all Q(x) are false. If that’s the case then there exists no x such that P(x) or Q(x) are false, and so the first statement is false too.

![[Pasted image 20220523152647.png]]



# 48


# 49

![[Pasted image 20220523152726.png]]


# 50


# 51


# 52


# 53
The first statement is true if and only if there exists a P(x) that is true and there exists a Q(x) that is true. Let’s say P(a) is true and Q(b) is true. 

Then, the second statement will be false because P(x) and Q(x), while they can be true, are not true for the same variable x, P is true for x = a, and Q is true for x = b. 


Giving a simple counterexample works very well. 

![[Pasted image 20220523152820.png]]


# 55

Assuming the premises are true 

a. True

b. False 

c.   True


States if there is only one x such that -P(x), then it is not the case that all x are P(x)

True

Because there is definitely one x that is -P(x) 

![[Pasted image 20220523152848.png]]