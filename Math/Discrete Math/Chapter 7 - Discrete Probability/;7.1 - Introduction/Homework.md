# 1

There are four aces and 42 total cards

4/52





# 2


# 3


1/6





# 4


# 5

36 total outcomes 

How can we have even? 

3 odd numbers, 3 even numbers for each die 

3 * 3 is all combinations of even numbers. These are always even. 

3 * 3 is all combinations of odd numbers. These are also always even 

3 * 3 + 3 * 3 = 9 + 9 = 18

18/36






# 6


# 7


So we have a 6-tuple, and we need heads each time. 
So we have 2^6 total outcomes. And in only one way will we get a heads

1/2^6


**ALTERNATE**
Need to get heads each time, and it is 1/2 for a head. Multiply the probabilities

1/2 * 1/2 * 1/2….* 1/2* = 1/2^6






# 8


# 9


does NOT contain the queen of hearts. 



There are 52C5 poker hands 

One card we can’t have, queen of hearts, so 51C5 poker hands with this restriction

51C5/52C5


**ALternative**
How many hands contain the queen of hearts. 
One spot is queen of hearts. Then we have 51 * 50 * 49 / 3!
So divide that by 52C5

Then subtract by 1

Aka complement method 









# 10


# 11


Need the two given options. 

50C3/52C5




# 12


# 13
Contains no aces. 
There are 4 aces, so 52-4 = 48

48C5/52C5


# 14


# 15


# 16


# 17

To get a straight, you nee sequential cards. 

Once you choose a card though, the remaining cards are automatically chosen. 
Let’s think about the total rank: 

A 2 3 4 5 6 7 8 9 10 J Q K A

10 starting cards for our straight 

Once we have a starting card, the rest are determined. We are only looking for the event, so we can divide by 52C5

For each of the five cards, we need to pick a suit, so 4^5

(10 * 4^5)/(52C5)




# 18


# 19
Five different kinds, and not flush or straight. 
Flush is all cards of the same suit
Straight is 5 cards of sequential rank


Flush and straight are a part of this. 

P(flush)
A flush is when we have all cards same suit. 
So we can say (4 * 13C5)/52C5



Flush and straight can actually both happen. 
P(flush and straight) = (4 * 10)/52C5


So number of ways to have a flush or striaght: 
(4 * 13C5) + ((10 * 4^5)) - (4 * 10) = 15348




So now we need to find the probability of a 5 card poker hand with different cards of five kinds 
We can pick the suit and type of first card
We just need a set of five different cards 
(13C5 * 4^5)
5 different cards in a set, and we can give them each a suit. The cards are different so not suit overlaps.


(13C5 * 4^5  - 15348)/52C5 = 0.5011

**0.5011**


















# 20


# 21


Rolling a fair die. 
It must never come up an even number. 
3 odd numbers
3^6 combinations of odd numbers

3^6/6^6 = 0.015625










# 22


# 23
100/5 = 20
floor(100/7) = 14

7 and 5 are relatively prime. 
7 * 5= 35

floor(100/35) = 2

20 + 14 - 2 = 32

**32/100 numbers divisible by 5 or 7**



# 24


# 25

a.  1/50C6

Need to choose the correct set of 6 numbers 

Total number of sets of 6 numbers are 50C6
Only 1 set is correct



b. 1/52C6

c. 1/56C6

d. 1/65C6


# 26


# 27

so for n integers 
There are 6 integers for the winning numbers, 
We can select any 50

6/50


a. 6/40
b. 6/48
c. 6/56
d. 6/64








# 28


# 29



Need to choose 8 numbers, ak a set. 
100 positive integers 

1/100C8   probability of choosing the correct outcome. 





# 30


# 31



Michelle can have 3 spots, first second or 3rd. And for each of those, there are 99P2 people that need to be ordered

(3 * 99P2) / 100P3




# 32


# 33
a. 1/200P3

b. 1/(200^3)


# 34


# 35


18 red 18 black 
2 numbers are not blakc and red, 0 and 00 
1/38 for every number…equal opportunity 

a. 18/38

b. 18/38 * 18/38
Or
18 * 18 black s
38^2 outcomes


c. 2/38 

d.
P(no zeros) = 36/38
Five of these 
(36/38)^5



e. 
first 6 integers is 6 of them 
so 6/38 for first spin 
and 32/38 for second

(6 * 32)/38













# 36


# 37

(2, 6), (3, 5), (4, 4), (5, 3), (6, 2)
5/36 prob to get a total of 8 for two dices


For three numbers, this will be over 215, much larger
(1, 1, 6) 3 ways to organize this 
(1, 2, 5) 3 ways to organize 
(1, 3, 4) 3 
(2, 2, 4)  3
(2, 3, 3) 3

15 / 215


First way has a much higher probability 

# 38


# 39




# 40


# 41


# 42


# 43


# 44


# 45

a.  0.517
Fair die folled four times. 
Need at least one six. If no six, then we can say (5/6)^4 is the probability 




5^4 ways, 6^4 outcomes

1- 5^4/6^4 = 0.517



b. P(event) = 0.566

The probability is above 0.5



**Want to find another non recursive method. **



could we use a recursive sequence 

start at the beginning 
a_n = ways to do a strin g
a_0 = 1
a_1 = 6


a_2 = 36 - 1 = 35




a_n = (5 * a_{n-2}  +  5 * (a_{n-1} ))


Case 1: 6 used, so now 5 options for next then a_n-2 options remaining





![[Pasted image 20220816192252.png]]


This is the number of outomce sfor no double 6


So 1 - 0.566 = 0.434

![[Pasted image 20220816192450.png]]



**BRUH I'm SOLVING THE WRONG PROBLEM AYOOOOOOO**



rolling a pair of dice 24 times. 

36 outcomes 
1/36 to get a double 6 


For all of our outcomes

36^24   outcomes 

And we don't many any double 6s

35^24 / 36^24 = 0.508
1 - 0.508 = 0.491





c. First option more likely 



# 46


# 47


# 48


# 49


# 50


# 51


# 52

# 53

# 54

