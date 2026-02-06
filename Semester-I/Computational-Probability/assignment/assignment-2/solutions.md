### 1. A cartoon contains 6 Dell Laptops , 9 Lenovo Laptops and 5 Acer Laptops. Two Laptops are selected at random, find the probability that (i) both Laptops are Lenovo (ii) Dell and Acer Laptops.
Here, \
Total laptops = 6 + 9 + 5 = 10 \

Now, \
Combination formula for choosing r items ($\binom{n}{r}$) = $\frac{n!}{r!(n-r)}!$ \
Combination formula for choosing 2 items ($nC2$) = $\frac{n(n-1)}{2}$


**i) both Laptos are lenovo:** \
Favourable outcomes ($9C2$) = $\frac{9(9-1)}{2} = 36$  
Total outcomes ($20C2$) = $\frac{20(20-1)}{2} = 190$  
$$
P(\text{both lenovo}) = \frac{9C2}{20C2} 
= \frac{36}{190}
= 0.18
$$

**ii) Dell and Aece Laptops** \
Favourable outcome = $6C1*5C1$ = $6*5$ = 20
Total outcomes ($20C2$) = $\frac{20(20-1)}{2} = 190$  
$$
P(\text{dell and acer laptop}) = \frac{20}{190} 
= 0.22
$$
___

### 2. The staff body of a IT company is composed of 60% male and 40% female. 40% of male and 60% of female shows interest in sports. What is the probability that a staff selected at random shows interest in sports given that the staff is female? 
Given, \
$P(male) = 0.6$ \
$P(female) = 0.4$ \
$P(sports | male ) = 0.4$ \
$P(sports | female) = 0.6$

Now,
$$
    Conditional Probability: P(A|B) =  \frac{P(A\cap B)}{P(B)} 
$$

Probability of staff shows interest given the staff is female is:
$$
P(sports|female) = 0.6
$$
___

### 3. There are three machines A, B, and C producing 500, 1000 and 1500 articles per week respectively. These machines are known to be producing 1%, 2% and 3% defects respectively. One article is selected at random from a week's production of three machines and found to be defective. What is the probability that the article is produced from Machine A? 

Given,
Machine outputs: A=500, B=1000, C=1500
Defective rates: 1%, 2%, 3% respectively

Here, \
Total number of articles = 500 + 1000 + 1500 = 3000

Probability of artical being from machine A = $P(M_A) = \frac{500}{3000} = 0.167$ \
Probability of artical being from machine B = $P(M_B) = \frac{1000}{3000} = 0.333$ \
Probability of artical being from machine C = $P(M_C) = \frac{1500}{3000} = 0.5$ 

Probability of defect given machine A = $P(D|M_A) = 0.01$ \
Probability of defect given machine B = $P(D|M_B) = 0.02$ \
Probability of defect given machine C = $P(D|M_C) = 0.03$

According to total probability theorem, probability of defect is:
$$
P(D)= P(D|M_A)P(M_A) + P(D|M_B)P(M_B) + P(D|M_C)P(M_C)
= 0.01*0.167 + 0.02*0.333 + 0.3*0.5
= 0.023 
$$

Now, Probability of artifact being from machine A given defect is: 
$$
P(M_A|D) = \frac{P(D|M_A)|(M_A)}{P(D)}
= \frac{0.01*0.167}{0.023}
= 0.073
$$
___

### 4. In an examination of MTech level, 40% failed in AI, 25% failed in statistics and 10% failed in both AI and statistics. A student is selected at random.
**a.  What is the probability that the selected students have failed in statistics or AI?** \
**b.  What is the probability that the selected student has failed in statistics given that he has failed in AI?** \
**c.  What is the probability that the selected student has failed in AI given that he has failed in statistics?** 

Given, \
Probability of student failing AI ($P(AI)$) = 40% = 0.4 \
Probability of student failing Statistics ($P(S)$) = 25% = 0.25 \
Probability of student failing AI and statistics ($P(AI\cap S)$) = 10% = 0.1

Probability that the selected student failed in statistics or AI is, 
$$
P(AI\cup S) = P(AI) + P(S) - P(AI\cap S)
= 0.4 + 0.25 - 0.1
= 0.55
$$

Probability that the selected student failed in stats given student has failed in AI is, 
$$
P(S|AI) = \frac{P(AI\cap S)}{P(AI)}
= \frac{0.1}{0.4}
= 0.25
$$

Probability that the selected student failed in AI given student has failed in stats is, 
$$
P(AI|S) = \frac{P(AI\cap S)}{P(S)}
= \frac{0.1}{0.25}
= 0.4
$$

___

### 5. The probability that an integrated circuit chip will have defective etching is 0.12, the probability that it will have a crack defect is 0.29, and the probability that is has both defects is 0.07. What is the probability that a newly manufactured chip will have either an etching or a crack defects.

Given,\
Probability that an IC chip having defective etching $P(etch) = 0.12$  \
Probability that an IC chip having crack defect $P(crack) = 0.29$ \
Probability that an IC chip having both defect $P(etch\cap crack) = 0.07$

Probability that an IC chip having either an etching or crack defects is, 
$$
P(etch\cup crack) = P(etch) + P(crack) - P(etch\cap crack)
= 0.12 + 0.29 - 0.07
= 0.34
$$ 

___

### 6. Two sets of candidates are competing for the position on the Board of Directors of a company. The probabilities that the first and second sets will win are 0.6 and 0.4 respectively. If the first set wins, the probability of introducing a new product is 0.9 and the corresponding probability if the second set win is 0.4. What is the probability that new product will be introduced.

Given, \
Probability of Candidate One winning, $P(A) = 0.6$ \
Probability of Candidate Two winning, $P(B) = 0.4$ \
Probability of product being introduced given candidate one wins, $P(product|A)=0.9$ \
Probability of product being introduced given candidate two wins, $P(product|B)=0.4$ 

Using total probability theorem, probability of the new product being introduced is,
$$
P(product) = P(product|A)P(A) + P(product|B)P(B)
= 0.9*0.6 + 0.4*0.4
= 0.7
$$

___

### 7. Two parties congress and communist are competing for leading the government of Nepal. The chance of winning is 0.55 and 0.45 for both parties respectively. If the congress wins, the probability for presenting deficit budget is 0.75 and the corresponding probability if the communist win is 0.35.
**a.What is the probability that the deficit budget is presented?** \
**b.What is the probability the congress will lead the government for presenting the deficit budget?** \
**c.What is the probability the communist will lead the government for presenting the deficit budget?**
###

Given, \
Probability of congress winning, $P(congress) = 0.55$ \
Probability of communist winning, $P(communist) = 0.45$ \
Probability of presenting deficit budget given congress wins, $P(deficit|congress)=0.75$ \
Probability of presenting deficit budget given communist wins, $P(deficit|communist)=0.35$ 

Using total probability theorem, probability of the presenting deficit budget is,
$$
P(deficit) = P(deficit|congress)P(congress) + P(deficit|communist)P(communist)
= 0.55*0.75 + 0.45*0.35
= 0.57
$$

Probability that congress will lead the government for presenting defecit budget is,
$$
P(congress|deficit) = \frac{P(deficit|congress)|(congress)}{P(deficit)}
= \frac{0.55*0.75}{0.57}
\approx 0.723
$$

Probability that communist will lead the government for presenting defecit budget is,
$$
P(communist|deficit) = \frac{P(deficit|communist)|(communist)}{P(deficit)}
= \frac{0.45*0.35}{0.57}
\approx 0.276
$$

___

### 8. It is known from experience that in a certain industry 60% of all labor management disputes are over wages, 15% are over working conditions, and 25% are over fringe issues. Also 45% of the disputes over wages are resolved without strikes, 70% of the disputes over working conditions are resolved without strikes, and 40% of the disputes over fringe issues are resolved without strikes. What is the probability that if a labor-management disputes in this industry is resolved without a strike, it was over wages? 

Given, \
Probability of disputes over wages $P(wages) =60% = 0.6$ \
Probability of disputes over working conditions $P(conditions) =15% = 0.15$ \
Probability of disputes over fringe issues $P(fringe) =25% = 0.25$ 

45% of disputes over wages are resolved without strikes. Therefore, 
$P(resolved|wage) = 0.45$ \
70% of disputes over working conditions are resolved without strikes. Therefore, 
$P(resolved|conditions) = 0.7$ \
40% of disputes over fringe issues are resolved without strikes. Therefore, 
$P(resolved|fringe) = 0.40$

Probability that a dispute resolved without a strike being over wages,
$$
P(wages|resolved) = \frac{P(resolved|wages)P(wages)}{P(resolved|wages)P(wages)+P(resolved|conditions)P(conditions)+P(resolved|fringe)P(fringe)}
$$
$$
= \frac{0.45*0.6}{0.45*0.6+0.7*0.15+0.4*0.25}
\approx 0.568
\approx 0.57
$$

___

### 9. The chances of X, Y, Z becoming manager of a certain company are 4:2:3. The probabilities that bonus scheme will be introduced if X, Y, Z becomes manager are 0.3, 0.5 and 0.8 respectively. If the bonus scheme has been introduced, what is the probability that X is appointed as the manager? 

Given, \
Total = 4+2+3 = 9
Chance of X becoming manager $P(X)= \frac{4}{9}$ \
Chance of Y becoming manager $P(Y)= \frac{2}{9}$ \
Chance of Z becoming manager $P(Z)= \frac{3}{9}$

Probability that bonus scheme being introduced if X wins, $P(bonus|X) = 0.3$ \
Probability that bonus scheme being introduced if Y wins, $P(bonus|Y) = 0.5$ \
Probability that bonus scheme being introduced if Z wins, $P(bonus|Z) = 0.8$

If bonus scheme has been introduced, the probability that X is appointed is, 
$$
P(X|bonus) = \frac{P(bonus|X)P(X)}{P(bonus|X)P(X)+P(bonus|Y)P(Y)+P(bonus|Z)P(Z)}
$$
$$
= \frac{0.3*\frac{4}{9}}{0.3*\frac{4}{9}+0.5*\frac{2}{9}+0.8*\frac{3}{9}}
\approx 0.261
$$

___

### 10. One bag contains 5 white and 4 black balls. Another bag contains 7 white and 9 black balls. A ball is transferred from the first bag to the second bag and then a ball is drawn from the second bag. Find the probability that the ball is white.

Initialy, \
Bag 1: 5 W, 4 B, Total = 9 \
Bag 2: 7 W, 9 B, Total = 16

**Case 1: White being transfered from fist bag to second bag**
$$P(\text{white transfered}) = 5/9$$ 
Now, bag 2 becomes: 8 W, 9 B, Total = 17
$$P(\text{white drawn}|\text{white transfered}) = 8/17$$

**Case 2: Black being transfered from first bag to second bag**
$$P(\text{black transfered}) = 4/9$$ 
Now, bag 2 becomes: 7 W, 10 B, Total = 17
$$P(\text{white drawn}|\text{black transfered}) = 7/17$$

Probability that the white ball is drawn,
$$
P(\text{white drawn}) =P(\text{white drawn}|\text{white transfered})P(\text{white transfered}) + P(\text{white drawn}|\text{black transfered})P(\text{black transfered})
$$
$$
=\frac{8}{17}*\frac{5}{9} + \frac{7}{17} * \frac{4}{9}
= \frac{68}{153}
= 0.44
$$

___

### 11. There is a 1% probability for a hard drive to crash. Therefore, it has two backups, each having a 2% probability to crash, and all three components are independent of each other. The stored information is lost only in an unfortunate situation when all three devices crash. What is the probability that the information is saved? 

Here, \
Probability that hard drive crashes = 1% = 0.01 \
Probability that backup 1 crashes = 2% = 0.02 \
Probability that backup 2 crashes = 2% = 0.02

Every event is independent to each other and information is lost if all three device crashes. \
Now, probability that all three device crashes, $P(\text{all crashes})=0.01*0.02*0.03 = 0.000004$  \
Hence, probability that information is saved = $1 - P(\text{all crashes}) = 1 - 0.000004 = 0.999996 = 99.9996\%$ 
___

### 12. Suppose that a shuttle’s launch depends on three key devices that operate independently of each other and malfunction with probabilities 0.01, 0.02, and 0.02,respectively. If any of the key devices malfunctions, the launch will be postponed. Compute the probability for the shuttle to be launched on time, according to its schedule.

Here, \
Probability of device one malfunction = 0.01  \
Therefore, probability that device one works = $P(D_1)  = 1 - 0.01 = 0.99$\
Probability of device two malfunction = 0.02 \
Therefore, probability that device two works = $P(D_2)  = 1 - 0.02 = 0.98$ \
Probability of device three malfunction = 0.02 \
Therefore, probability that device three works = $P(D_3)  = 1 - 0.02 = 0.98$

For the shuttle to launch on time, all of the devices should work independently, if any one device fails launch is postponed. Hence, \
Probability that the shuttle will be launched on time = $P(D_1)P(D_2)P(D_3) = 0.99*0.98*0.98 \approx 0.095$
___

