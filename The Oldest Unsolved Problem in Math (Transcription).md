---
created: 2024-03-07T22:16
updated: 2024-03-07T22:32
---
This is a video about the oldest unsolved problem in math that dates back 2000 years. Some of the brightest
mathematicians of all time have tried to crack it,
but all of them failed. In the year 2000 
 the Italian mathematician,
Piergiorgio Odifreddi, listed it among four of the
most pressing open problems at the time. Solving this problem could be as simple as finding a single number. 
 So mathematicians have used computers and checked numbers up to
10 to the power of 2,200, but so far they've come up empty handed. Why do you think this problem
has captured the imaginations of so many mathematicians? 
 - It's old, it's simple, it's beautiful. - What else could you want? So the problem is this. Do any odd perfect numbers exist? 
 So what is a perfect number? Well take the number six for example. You can divide it by 1, 2,
3, and 6, but let's ignore 6 because that's the number itself, and now we're left with
just the proper divisors. 
 If you add them all up, you
find that they add to six, which is the number itself. So numbers like this are called perfect. You can also try this with
other numbers like 10. 10 has the proper divisors
one, two, and five. 
 If you add those up, you only get eight. So 10 is not a perfect number. Now you can repeat this
for all other numbers, and what you find is that
most numbers either overshoot or undershoot between 1 and a 100, 
 only 6 and 28 are perfect numbers. Go up to 10,000 and you find the next two
perfect numbers 496 and 8,128. These were the only perfect numbers known by the ancient Greeks, 
 and they would be the only known ones for over a thousand years. If only we could find a pattern
that makes these numbers, then we could use that
to predict more of them. So what do these numbers have in common? 
 Well, one thing to notice is that each next perfect
number is one digit longer than the number that came before it. Another thing they share is
that the ending digit alternates between 6 and 8, which also
means they are all even. 
 But here's where things get really weird. You can write 6 as the
sum of 1 plus 2 plus 3 and 28 as the sum of one, plus 2, plus 3, plus 4 plus 5 plus 6 plus 7, and so on for the others as well,
they're all just the sum 
 of consecutive numbers and you can think of
each additional number as adding a new layer. And so these create a triangle, which is why these numbers
are called triangular numbers. 
 Also, every number
except for six is the sum of consecutive odd cubes. So 28 is 1 cubed plus 3 cubed. 496 is equal to 1 cubed plus 3 cubed
plus 5 cubed plus 7 cubed. 
 And 8,128 is equal to 1 cubed plus 3 cubed
plus 5 cubed plus 7 cubed plus 9 cubed all the way up to 15 cubed. But here's the one that
really blows my mind. If you write these numbers in binary, 
 six becomes 110, and 28 becomes 11100. 496 becomes 111110000. And 8,128, you guessed it. 
 It is also a string of ones
followed by a series of zeros. So if you write them out, they are all just
consecutive powers of two. What now around 300 BC Euclid was actually
thinking along similar lines 
 when he discovered the pattern that makes these perfect numbers. Take the number one and double it, you get two now, keep doubling it. You get 4, 8, 16, 32, 64, and so on. 
 Now starting from one,
add the next number to it. So 1 plus 2 equals 3. If that adds up to a
prime, then you multiply it by the last number in the
sequence to get a perfect number. So two times three equals
six, the first perfect number. 
 Now let's keep doing this. Add 1 plus 2 plus 4, and you get 7, which is again prime. So multiply it by the last
number four, and you get 28. The next perfect number. 
 Next, add 1 plus 2 plus
4 plus 8 equals 15, but 15 isn't prime, so we
continue add 16 to get 31, this is prime. So you multiply it by 16 and you get 496. The third perfect number. 
 Now you can keep doing this to find bigger and bigger perfect numbers, and using this we can
rewrite the first three. So 6 equals 1 plus 2
times 2 to the power of 1 and 28 equals 1 plus 2
plus 4 times 2 squared 
 and 496 equals 1 plus 2 plus 4 plus 8 plus 16 times 2 to the power of 4 where the first term is prime. But there's a more convenient
way to write this still. Take any sum of consecutive powers of 2. 
 So 2 to the power of zero which is 1 plus 2 to the 1 plus 2 to the 2, all the way up to 2 to the n minus 1. And now because you don't
know n, you don't know what that is equal to, but it
will be equal to something. 
 So let's call that T. Now multiply this whole equation by two. So you get 2 to the 1 plus 2 to the 2, all the way up to 2 to the
n, and this is equal to 2T. If you now subtract the first
equation from the second, 
 almost all the terms will cancel out and you're left with T
equals 2 to the n minus 1. So you can replace this whole series with one less than the next power of 2. So six becomes 2 squared
minus 1 times 2 to the 1. 
 28 becomes 2 cubed
minus 1 times 2 squared, and 496 becomes 2 to the 5
minus 1 times 2 to the 4. Do you see the pattern? This number is always one more than this. So if we call this P, then Euclid formula 
 that gives a perfect number
is 2 to the P minus 1 times 2 to the P minus 1
whenever this is prime. Now, because you're multiplying
it by 2 to the P minus 1, which is even, this will
always give an even number. Euclid had found a way to
generate even perfect numbers, 
 but he didn't prove that
this was the only way. So there could be other
ways to get perfect numbers, including potentially ones that are odd. 400 years later, the Greek philosopher nicomchaus published 
 Introdutio Arithmetica, the
standard arithmetic text for the next thousand years. In it, he stated five conjectures
statements he believed to be true, but did not bother
actually trying to prove. His conjectures were one, 
 the nth perfect number has n digits. Two, all perfect numbers are even. Three, all perfect numbers
end in 6 and 8 alternately. Four, Euclid algorithm produces
every even perfect number. And five, there are infinitely
many perfect numbers. 
 For the next thousand years no one could prove or disprove
any of these conjectures, and they were considered facts. But in the 13th century, Egyptian mathematician Ibn Fallus 
 published a list with 10 perfect numbers and their values of P. Three of these perfect numbers turned out not to be perfect at all. But the remaining ones are. 
 The fifth perfect number
is eight digits long, which disproves Nicomachus's
first conjecture. And the next thing to notice
is that both the fifth and sixth perfect number end in a 6. So that disproves
Nicomachus's third conjecture 
 that all perfect numbers
end in a 6 or 8 alternately. Two conjectures were proven false. But what about the other three? Two centuries later, the problem
reached Renaissance Europe where they rediscovered the fifth, sixth, 
 and seventh perfect numbers. So far every perfect
number had Euclid's form. And the best way to find new
ones was by finding the values of P that make 2 to the P minus 1 prime. So French polymath Marin
Mersenne extensively studied 
 numbers of this form. In 1644, he published his in a book including a list of 11 values of P for which he claimed
they corresponded to primes. Numbers for which this is true 
 are now called Mersenne Primes. Of his list the first seven exponents of P do result in primes and they correspond to the
first seven perfect numbers. But for some of the larger numbers 
 like 2 to the 67 minus
1, Mersenne admitted to not even checking
whether they were prime. "To tell if a given number
of 15 to 20 digits is prime or not all time would not
suffice for the test." Mersenne discussed the
problem of perfect numbers 
 with other luminaries of the time, including Pierre de
Fermat and Rene Descartes. In 1638, Descartes wrote to
Mersenne, I think I can show that there are no even perfect numbers except those of Euclid. 
 He also believed that if an
odd perfect number does exist, it must have a special form. It must be the product of a prime and the square of a different number. If he was right, these
would easily have been 
 the biggest breakthroughs
on the problem since Euclid 2000 years earlier. But Descartes couldn't prove
either of those statements. Instead, he wrote "As for
me, I judge that one can find real odd perfect numbers. 
 But whatever method you
use, it takes a long time to look for these." Around a hundred years later
at the St. petersburg Academy, the Prussian mathematician
Christian Goldbach met a 20-year-old math prodigy. 
 The two stayed in touch
corresponding by mail, and in 1729, Goldbach
introduced this young man to the work of Fermat. At first, he seemed indifferent, but after a little more
prodding by Goldbach 
 he became passionate about number theory and he spent the next 40 years working on different problems in the field among them was the problem
of perfect numbers. This Prodigy's name was Leonhard Euler. 
 Euler picked up where
Descartes had left off, but with more success. In doing so, he made three
breakthroughs on this problem. First in 1732, he discovered the eighth perfect
number, which he had done 
 by verifying that 2 to
the 31 minus 1 is prime. Just as Mersenne had predicted. For his other two breakthroughs,
he invented a new weapon, the sigma function. All this function does is
it takes all the divisors 
 of a number, including the
number itself and adds them up. So take any number, say
six, sum up all its divisors and you get 12, which is twice
the number we started with. And this will be true
for all perfect numbers. The Sigma function of a perfect number 
 will always give twice the number itself because the sigma function
includes the number as one of its divisors. Now this may seem like a small change, but it ends up being extremely powerful. 
 So let's look at a few examples. Take a prime number like seven. Now, because it's prime, you can't rearrange it into a rectangle, therefore the only divisors
are one and the prime itself. 
 So Sigma seven is 1 plus
7, which is equal to 8. Now, to keep things easier to follow, we'll just stick to the numbers. But what if instead of
seven, you had seven cubed? Well, again, the sum of the
divisors is really simple. 
 It's just 1 plus 7 plus
7 squared plus 7 cubed. Now let's use it on a
different number, say 20. The sum of its divisors
is 1 plus 2 plus 4 plus 5 plus 10 plus 20, which equals 42. But you can also write this 
 as 1 plus 2 plus 4 times 1 plus 5. And this is what really makes the sigma function so powerful. If you have a number that
is made up of other numbers that don't share factors with each other, 
 then you can split up the sigma function into the sigma functions
of the prime powers that make it up. So sigma of 2 squared times sigma 5 is equal to sigma 20. 
 And since any number can
be written as the product of prime powers, you can
split up the sigma function of any composite number
into the sigma functions of its prime powers. With his new function in hand, 
 Euler achieved his second breakthrough and did what Descartes couldn't. He proved that every even
perfect number has Euclid's form. This Euclid-Euler theorem
solved a 1600-year-old problem and proved Nicomachus's fourth conjecture. 
 Math historian William Dunham called it the greatest mathematical
collaboration in history. But Euler wasn't finished yet. He also wanted to solve the
problem of odd perfect numbers. So for his third breakthrough, he set out 
 to prove Descartes other statement that every odd perfect number
must have a specific form. Because if an odd perfect
number does exist, you know two things first n is odd. And second sigma of n equals 2n. 
 Now any number n, you
can write as a product of different prime numbers and each prime can be to some power. So let's take that and put
it into Euler sigma function. So you get sigma of n equals
sigma of all of those primes 
 to their powers, which equals 2n. But since all of these factors are primes, you can actually split up the
sigma function into the sigmas of the individual prime powers. Now one thing to notice is 
 that if you have a prime
number raised to an odd power, for example seven to the power of 1, then the sigma function will be even because 1 plus 7 equals 8, you'll always get an even number 
 because odd plus odd is even if the prime number is instead raised to an even power like seven squared, then the sigma function
returns an odd number. Sigma of 7 squared equals
1 plus 7 plus 7 squared, 
 which equals 57. Because odd plus odd plus odd equals odd. So if you have the sigma
function of an odd prime raised to an odd power, it will
give an even number. If instead it's raised to an even power, 
 you get an odd number. And this is where Euler's
genius insight comes in because here on the right
side you've got 2 times n where n is an odd perfect
number, and 2 is even. Well, what that means is 
 that on the left side there
must only be one even number because if there were two even numbers, you could factor out four. But that means you should also be able to factor out four on the
right side, which you can't 
 because n is odd and there's
only a single 2 here. So only one of these sigmas
here can give an even number, which means that there
is exactly one prime that is to an odd power and all the others must
be to an even power 
 just as Descartes had predicted. Now, Euler refined the form a bit more and showed that an odd
perfect number must satisfy this condition, but even
Euler couldn't prove whether they existed or not. 
 He wrote "Whether there
are any odd perfect numbers is a most difficult question." For the next 150 years very little progress was made and no new perfect
numbers were discovered. 
 English mathematician Peter Barlow wrote that Euler eighth perfect
number "Is the greatest that ever will be discovered for as they are merely
curious without being useful, it is not likely that any
person will ever attempt 
 to find one beyond it." But Barlow was wrong. Mathematicians kept pursuing
these elusive perfect numbers and most started with Mersenne's
list of proposed primes. The next on his list
was 2 to the 67 minus 1. 
 So far, Mersenne had
done an excellent job. He had included Euler's
eighth perfect number while avoiding others like 29 that turned out not to
lead to a perfect number, but 230 years after
Mersenne published his list, 
 Edouard Lucas proved that 2 to
the 67 minus 1 was not prime, although he was unable
to find its factors. 27 years later, Frank
Nelson Cole gave a talk to the American mathematical
society without saying a word, he walked to one side of the blackboard 
 and wrote down 2 to the 67 minus 1 equals 147,573,952,589,676,412,927. He then walked to the other
side of the blackboard and multiplied 193,707,721 times 761,838,257,287 
 giving the same answer. He sat down without saying a word and the audience erupted in applause. He later admitted it took him three years working on Sundays to solve this. 
 A modern computer could solve
this in less than a second. From 500 BC until 1952 people had discovered
just 12 Mersenne primes and therefore only 12 perfect numbers. The main difficulty was checking whether 
 large Mersenne numbers
were actually prime. But in 1952, American mathematician
Raphael Robinson wrote a computer program to perform this task and he ran it on the fastest
computer at the time, the SWAC. 
 Within 10 months, he found
the next five Mersenne primes and so corresponding perfect numbers. And over the next 50 years, new Mersenne primes were
discovered in rapid succession, all using computers. 
 The largest Mersenne
prime at the end of 1952 was 2 to the power of 2,281 minus 1, which is 687 digits long. By the end of 1994, the
largest Mersenne prime was 2 to the power of 859,433 minus 1, 
 which is 258,716 digits long. Since these numbers were
getting so astronomically large, the task of finding
numerous end primes became more and more difficult
even for supercomputers. So in 1996, 
 computer scientist George Woltman launched the Great Internet Mersenne
Prime Search or GIMPS. GIMPS distributes the
work over many computers allowing anyone to volunteer
their computer power to help search for Mersenne primes. 
 The project has been
highly successful so far, having discovered 17 new Mersenne primes, 15 of which were the largest
known primes at that time. And the best part, if
your computer discovers a new Mersenne prime, 
 you'll be listed as its discoverer, adding yourself to a list that includes some of the best
mathematicians of all time. There's even a $250,000 prize for the first billion-digit prime. 
 In 2017 Church Deacon John Pace discovered the 50th Mersenne Prime by using GIMPS. The number 2 to the 77,232,917 minus 1 is more than 23 million digits long, and it was also the largest
known prime at the time. 
 To celebrate this achievement the Japanese publishing house, Nanairosha published this book, "The Largest Prime number of 2017." And all it is 
 is that number spread
over 719 glorious pages. It's wild. The size of this font is so tiny. The book quickly rose to the
number one spot on Amazon and sold out in four days. 
 A year later, the 51st
Mersenne Prime was discovered. It's 2 to the 82,589,933 minus 1, and this number has
24,000,860 2048 digits. But there's something I
enjoy about the absurdity, like there is knowledge in here, 
 but it's not the kind of knowledge that anyone's ever gonna
read out of a book. But in some way it's nice that there's this physical artifact that like has the number, 
 if ever we lost all the prime numbers. You know, someone could find this book be like, here's the big one. As of today, this is still
the largest known prime. And since numbers of this
form grow so rapidly, 
 the largest Mersenne Prime is almost always the largest known prime. Computers have been incredibly successful at finding new Mersenne primes and their corresponding perfect numbers, 
 but we've still only found 51 so far. So you might suspect that there are only a finite number of them, which would mean that
Nicomachus's fifth conjecture would be false, 
 that there aren't infinitely
many perfect numbers, but that might not be the case. The Lenstra and Pomerance
Wagstaff conjecture predicts how many Mersenne primes should appear based on how large P is. 
 Now this is the actual data the conjecture performs remarkably well. But more importantly, it predicts that there are infinitely
many Mersenne primes and so infinitely many
even perfect numbers. 
 The Mersenne primes are
just so large and rare that they take a lot of time
and computer resources to find. But a conjecture is not a proof. And up until this day, this problem shares the title of oldest
unsolved problem in math 
 with the other open problem. Do any odd perfect numbers exist? The easiest way to solve this problem is by finding an example. So maybe we could just
check different odd numbers 
 and see if one of them is perfect. That's exactly what
researchers tried in 1991. By using a smart algorithm
called a factor chain, they were able to show that
if an odd perfect number does exist, it must be larger than 10 
 to the power of 300. 21 years later, Pascal
Ochem and Michael Rao raised that lower bound to 10 to the 1,500 with recent progress
pushing that number up to 10 to the 2,200. 
 With numbers that large, it's unlikely that a computer
will find one anytime soon. So we'll need to get smart. What would a proof look like? Like how could we actually prove this? 
 - I think the main idea
that people have been trying to approach this problem
with is coming up with more and more conditions odd perfect numbers have to
satisfy, it's called this web of conditions where it has
to have 10 prime factors now 
 that we know and maybe thousands of non distinct prime factors and has to be bigger than 10 to the 3000. And it has to do all
these different things and we hope that eventually
there's just so many conditions 
 that can strain the numbers
so much that they can't exist. - Since Euler, mathematicians
have kept adding new conditions to this web. - But so far it hasn't worked. - But there might be another path. 
 When Descartes was looking
for odd perfect numbers, he came across 198,585,576,189, which you can factor as
3 squared times 7 squared times 11 squared times
13 squared times 22021. Put this into Euler sigma function 
 and you find it is equal to
two times the original number. In other words, it is perfect. That is if 22021 were prime, but it's not because it is equal to
19 squared times 61. And filling that in shows
that it is not perfect. 
 Numbers like this that are very close to being odd perfect
numbers are called spoofs. Spoofs are a larger group of numbers. So odd perfect numbers share
all properties of spoofs and then a few extra ones. 
 And the goal is to find
properties of spoofs that ultimately prevent them
from being odd perfect numbers. For example, one condition of odd perfect numbers is that
they can't be divided by 105. So if you find that spoofs
must be divisible by 105, 
 then this would prove that odd perfect numbers can't exist. In 2022 Pace Nielsen and a team at BYU found 21 spoof numbers
including Descartes number, and while they discovered
some new properties of spoofs, 
 they didn't find any that
rule out odd, perfect numbers. So how large would an odd
perfect number have to be? - They don't exist. - You don't think odd
perfect numbers exist? - No, they don't exist. 
 I wish they did. That'd be really cool if if there was just this one gigantic odd, perfect
number out in the universe. They don't exist. No. - How are you convinced
that they don't exist? 
 - There is something
called a heuristic argument where it's not a proof. So if we had a proof, we'd be done. It's just an argument from, okay, we think primes occur
this often of this type. 
 And you put that those pieces
of information together and you think, okay, on average how many numbers should be perfect. - This argument, which was
made by Carl Pomerance predicts that between 10 to the 2,200 
 and infinity, there are no more than 10 to the negative 540 perfect numbers of the form N equals pm squared - With odd perfect numbers the heuristic says we
shouldn't expect any. 
 We've searched high
enough now that we think we have enough evidence they
shouldn't exist anymore. - My understanding is
this heuristic argument. It also predicts that there are no large
perfect numbers even or odd. 
 So... That's true. So there's a downside. Yeah, there's a downside because it says there shouldn't be large, 
 even perfect numbers and
we actually expect there to be infinitely many. And so, okay, so... why do I believe the
heuristic in this case and not this case? 
 You're right. Am I being hypocritical about that? There are other aspects you can add on to the heuristic and make it stronger. Let me put it that way. 
 But you're right, it's not a proof. - For now this is still the
oldest unsolved problem in math. Euler was right when he
said whether there are any odd perfect numbers is
a most difficult question. So are there any
applications of this problem? 
 - I can say no. - Now, many people may think that if there are no
applications to the real world, then there's no point studying it. Why should anyone care about
some old unsolved problem? 
 But I think that's the wrong approach. For more than 2000 years, number theory had no
real world applications. It was just mathematicians
following their curiosity and solving problems they
found interesting proving 
 one result after another and building a foundation
of useless mathematics. But then in the 20th century, we realized that we could take this foundation and base our cryptography on it. 
 This is what protects
everything from text messages to government secrets. - Whenever you have a group of people put their
minds towards a problem, something good's gonna come out of it. 
 If it's only, if it's
only at the beginning, this doesn't work. Okay, well, as Edison
said, I learned 999 ways of not making a light bulb. Eventually I got a good way to do it. 
 It's the same with math. You have a problem and you throw your mind
at it and others do too. And you come up with new ideas and eventually something
good comes from that process. 
 - Einstein's general relativity was built on non-Euclidean geometries,
geometries that were developed as intellectual curiosities
without foresight of how they would one day change the way we understand the universe. 
 How many people do you think
are working on the problem of perfect numbers right now? - I'd guess around 10 people currently have papers in the area, 10 to 15. If you're a high schooler
and you just love mathematics 
 and you think, I want a
problem to think about, this one's a great problem to think about. And you can make progress.
You can figure out new things. Yeah, don't be scared. Hundreds of people have
thought about this problem 
 for thousands of years. What can I do? You can do something. - Why should you do math if you don't know that it will lead anywhere? Well, because doing the
math is the only way 
 to know for sure. You can't tell in advance
what the outcome will be. Like this problem might
turn out to be a dud. We might solve it and it might
not mean anything to anyone, or it could turn out to
be remarkably helpful. 
 The only way to know for sure is to try In today's world, it often
feels like you've gotta choose between following your curiosity
and building real skills you can apply. But the truth is it's
essential to do both. 
 Fortunately, there's one learning
platform which allows you to do just that. And it's this video sponsor, Brilliant. Brilliant will make you a better thinker and problem solver by
helping you build real skills 
 and everything from math and data science to
programming technology. You name it, Brilliant has
thousands of lessons for you to explore so you can
follow your curiosity wherever it leads you, 
 and you won't just learn key concepts.