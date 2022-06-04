# 1

![[Pasted image 20220524162306.png]]

a. 
For all real numbers x there is a real number y such that x < y 
Simple: Every number is less than some other number. 
**This actually asserts that is no largest number! That’s so cool!**

b.  
For every real number x and every real number y, if x and y are greater than or equal to 0, then the product of x and y is greater than or equal to 0. 

Simple: The product of two non-negative real numbers is always non-negative.

c. 
For evey real number x and for every real number y there is a real number z such that xy = z

Simple: The product of any two real numbers is a real number. 

**This means that multiplication is “closed”**





# 2


# 3 ⭐
![[Pasted image 20220524163240.png]]



Q(x,y) = x has sent emails to y
The domain is all students in my class

a. There is a student that has sent an email to some other student. 

b. There is a student that has sent emails to all other studnets. 

c. Every student has sent an email to some other studnet. 

d. There is a student that has received an ameil from every other student. 

e. Every student has received an email from some other student. 

f. Every student has sent an email to every student.



![[Pasted image 20220525173912.png]]
**Think about when a predicate involves doing something to oneself.**

# 4


# 5 ⭐
![[Pasted image 20220524163803.png]]

a. 
Sarah Smith has visited www.att.com

b. 
There is a person that has visited www.imdb.org

c. 
There is a website that has been visited by Jose Orez

OR
**Jose Orez has visited some website**

**We don’t always need to talk about predicate caluclus in terms of the quantifier**

d. 
There is a website that has been visited by Ashok Puri and Cindy Yoon

e.
There is some person that is not David Belcher such for all the websites David Belcher has visited, they have visited that website. 



There is a person **other thatn** david belcher who has visited the same websites adavid belcher

Someone has visisted the exact same websites as David Belcher ( but they could have visisted other websites too


f. There exists two people who have visited exactly the same websites 
and not visited any other websites. 


# 6


# 7

![[Pasted image 20220524165511.png]]
![[Pasted image 20220524165528.png]]



a. 
Abdallah does not like Japanese cuisine

b.
There exists someone who likes Korean cuisine, and every person likes mexican cuisine.
**some student at your school**
TALK ABOUT THE EXACT DOMAIN OF DISCOURSE GIVEN TO BE SPECIFIC 

c. There exists a cuisine such that MOnique likes it or Jay likes it. 
There is some cuisine that monique or jay like. 

**Look at the quantifiers very very carefully**
d. 

For any two **distinct** people, there is some cuisine they both do not like. 

If **distinctness** is presented, you HAVE TO TALK ABOUT THAT in your statement. 

e. There are two people such that they like and dislike the same cuisines. 

There are two students such taht that they like exactly the same cuisine

f. For any two people, there is some cuisine that they both like or dislike.  (a cuisine about which they have the same opinion)

**Be fluid in how you word things**


# 8




# 9 ⭐

![[Pasted image 20220524195615.png]]



a. 
$\forall x [L(x, Jerry)]$

b. 
$\forall x \exists y[L(x, y)]$

c. 
$\exists y \forall x[L(x, y)]$

d.  ⭐
$\neg \exists x \forall y [L(x, y)]$

![[Pasted image 20220525175059.png]]



e. 
$\exists x [\neg L(Lydia, x)]$

f. 
$\exists x \forall y [\neg L(y, x)]$

g. 
There is exactly one person whom everyone loves

So for this one person, everyone loves them. For everyone else, they are not loved by everyone. 

$\exists x \forall y[L(y, z) \land \forall z[z \neq x \to \exists d[-L(d, z)]]$ ✅




$\exists x \forall y[L(y, z) \land \forall z\forall a[L(a, z) \to z = x]$ ❌

Could also write this as

$\exists x \forall y[L(y, z) \land \forall z[\forall a [L(a, z)] \to z = x]]$

You have to keep the quantifier LOCAL 
You can’t just take it out, that’s against the rules as well. 
Don’t overthink this. 

![[Pasted image 20220525175222.png]]



h. 
There are exactly two people that lynn loves

$\exists a \exists b [a \neq b \land L(Lynn, a) \land L(Lynn, b) \land \forall z[L(Lynn, z) \to (z = a \lor z = b)]]$
![[Pasted image 20220525175606.png]]

i
Everyone loves himself or heself

$\forall x [L(x, x)]$
![[Pasted image 20220525175615.png]]

j.  ⭐

There is someone who loves no one beside himself or herself

$\exists x \forall y[L(x, x) \land (x \neq y \to \neg L(x, y))]$

My statement says there exists x asuch that they love themselves and for all y, if x != Y, then the don’t love y

BUT BICONDITIOANL WORKS HERE
They love y if and only if y is temselves

They love someone if and only if that person is themselves

**Biconditioanl is like saying there is only one specific case in which you do something otherwiseyou don’t. Try thinking more about when you can use it. **

![[Pasted image 20220525175629.png]]

# 10


# 11
![[Pasted image 20220524202856.png]]
![[Pasted image 20220524202911.png]]

S(x) = x is a student
F(x) = x is a faculty member
A(x, y) = x has asked y a question

Domain: All people associated with your school

a. 
A(Lois, Professor Michaels)

b. 
$\forall x [S(x) \to A(x, Professor\;Gross)]$

c. 

$\forall x [F(x) \to (A(x, Prof.\;Miller) \lor A(Prof.\;Miller, x)]$

d.⭐
$\exists x \forall y[S(x) \land (F(y) \to \neg A(x, y))]$
Chaining restriction shere
Are these equivalent? Well this states, there exists an x such taht for all y, x is a student, and if y is faculty then x has not asked y a question for all y. 
This should work. 

But this one is better because ti is imore concise. 

$\exists x [S(x) \land \forall y[F(y) \to \neg A(x, y)]]$

Or

![[Pasted image 20220525175943.png]]



e. 
$\exists x [F(x) \land \forall y[S(y) \to \neg A(y, x)]]$

![[Pasted image 20220525180001.png]]

f. 
$\exists x \forall y [S(x) \land (F(y) \to A(x, y))]$

**Using parentheses to separate helps a lot**

![[Pasted image 20220525180031.png]]


g.

$\exists x [F(x) \land \forall y[F(y) \land y \neq x \to A(x, y)]]$
Every “other” faculty member 

![[Pasted image 20220525180045.png]]

h. 

$\exists x \forall y[S(x) \land (F(y) \to \neg A(y, x))]$


![[Pasted image 20220525180116.png]]
# 12


# 13

![[Pasted image 20220524213810.png]]
![[Pasted image 20220524213824.png]]

M(x, y) = x has sent y an email
T(x, y) = x has telephoned y 
All e-mails are sent or received 

Domain si all students in your class

a. 
$\neg M(Chou,\; Koko)$

b.
$\neg M(Arlene,\;Sarah) \land \neg T(Arlene,\;Sarah)$

Remember to use $\land$, or apply the negation to the entire $\lor$

c. 
$\neg M(Deborah,\;Jose)$

d. 
$\forall x[M(x,\;Ken)]$

e. 
$\neg \exists x [T(x,\;Nina)]$

f. 
$\forall x [M(x, Avi) \lor T(x, Avi)]$

g. 
$\exists x \forall y[M(x, y)]$

h. ⭐
$\exists x \forall y[M(x,y) \lor T(x,y)]$


I think if they wanted to specifically imply doing one or the other for ALL people, they would say “sent an email message to eveyrone in your class, or telephoned everyone in your class. ”


i. 

$\exists x \exists y [x \neq y \land M(x,y) \land M(y,x))]$



**Note “different”**


j. 
$\exists x[M(x, x)]$

k. 
$\exists x \forall y[\neg M(y, x) \land \neg T(y, x)]$
We can do - and - because it spefically states that in the question 
We could also separete the quantifiers but no need to 


l. 
$\forall x \exists y[M(y, x) \lor T(y, x)]$


m.
$\exists x \exists y[M(x, y) land T(y, x)]$


n.

Is “between them” saying that together, they have emailed or messaged everyone in the class? 

$\exists x \exists y \forall z[M(x, z) \lor M(y, z) \lor T(x, z) \lor T(y, z)]$



**Think about in english which quantiifers apply to the entire expressions don’t. You have to be verey careful with this.**

# 14


# 15


# 16


# 17


# 18


# 19
![[Pasted image 20220524221105.png]]


Domain: All integers

a. 
$\forall x \forall y[x + y < 0]$

b. 
“Not necessarily” positive means IT CAN BE NEGATIVE 
Which means there exists a two positive integers that can be negative with sum

$\exists x \exists y[x > 0 \land y > 0 \land x - y \leq 0]$

Or even better, we’re saying this isn’t the case for ALL integers

$\neg \forall x \forall y [(x > 0 \land y > 0) \to x - y > 0]$

**Make sure to use ≤ when doing negation of > **


c. 
$\forall x \forall y[x^{2}+y^{2} \geq (x+y)^2]$


d. 
$\forall x \forall y[|x*y| = |x|*|y|]$




# 20


# 21
$\forall x \exists a \exists b \exists c \exists d[x > 0 \to x = a^{2}+b^{2}+c^{2}+d^{2}]$


# 22


# 23

![[Pasted image 20220524223020.png]]



a.
$\forall x \forall y [x < 0 \land y < 0 \to x * y > 0]$

b. 
$\forall x [x - x = 0]$

c. 
$\forall x \exists y \exists z [x > 0 \to ((y \neq z \land y^{2} = x \land z^{2}=x) \land \forall a(a^{2}= x \to a = y \lor a = z]$


d. 
$\neg \exists x \exists y[x < 0 \land \sqrt{x} = y]$


There does not exists a number less than 0 such that its square root yields a positive number. 

$\forall x \forall y[x < 0 \to \sqrt{x} \neq y]$
For all negative numbers, its sqrt is not equivalent to any real numbers


$\neg \exists x \forall y[x < 0 \land \sqrt{x} = y]$
Not an answer because it states a negative number does not have a a square root equivalent to all real numbers….this is true…but it doesn’t represent what our oriignal satement is saying. 



# 24


# 25



![[Pasted image 20220524224744.png]]

Domain: All real numbers


a. 
There is a real number x such that for every real number, xy = y

b. 
Any two negative real numbers will have a product greater than 0.

c. 
There exists a pair of real numbers such that the square of the smaller number is larger than the larger number. 


d. 

Any two real numbers have a real number sum. 

For every x and every y, there exists a z such that x + y = z


**DONT MIX UP INTEGER WITH REAL NUMBER**


# 26


# 27

![[Pasted image 20220524225755.png]]

Domain = All real integers

a. 
True

b. 
True → negative numbers work well

c. 
True

d. 
True → n = 1

e. 
True 
n = 1, m = 2 

f. 
Remember, all real integers

The product of two perfect squares, by lemma, (Homework 1 group work), must be 0 mod 4 or 1 mod 4
6 is 2 mod 4

So no solutions,

False 



# 28


# 29


# 30


# 31


# 32


# 33


# 34


# 35


# 36


# 37


# 38


# 39


# 40


# 41


# 42


# 43


# 44


# 45


# 46


# 47


# 48


# 49


# 50


# 51


# 52


# 53