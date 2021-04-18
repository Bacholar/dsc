## DSC Assignment - classification

### Task 1 - Bayes' theorem

**[Bayes Example Link](https://www.mathsisfun.com/data/bayes-theorem.html)**

***
**Naive Bayes equation**

<img src="https://latex.codecogs.com/gif.latex?\bg_white&space;P(A|B)&space;=&space;\frac{P(B|A)P(A))}{P(B))}" title="P(A|B) = \frac{P(B|A)P(A))}{P(B))}" />

**Translation of Bayes theorem**

- P(A|B): probability of A, given B is true
- P(B|A): probability of B, given A is true
- P(A): probability that A is true (prior probability)
- P(B): probability that B is true (prior probability)
- A and B must be different events
- P(B) ≠ 0

***

*" ... Bayes' theorem ... describes the probability
of an event, based on prior knowledge of
conditions that might be related to the event."
(wikipedia)*

***

**A.**

60% of the kids play football, and 36% of the kids play ice hockey. 40% of the kids who play football also play ice hockey. What percent of those that play ice hockey also play football?

* 60% play football (0.6%)
* 36% play ice hockey (0.36%)
* 40% play football | play ice hockey (0.4%)
* ??? play ice hockey | play football

<img src="https://latex.codecogs.com/gif.latex?\bg_white&space;P(Ice|Foot)&space;=&space;\frac{P(Foot|Ice)P(Ice))}{P(Foot))}" title="P(Ice|Foot) = \frac{P(Foot|Ice)P(Ice))}{P(Foot))}" />

<img src="https://latex.codecogs.com/gif.latex?\bg_white&space;P(Ice|Foot)&space;=&space;\frac{0.4%&space;\cdot&space;0.36%}{P(0.6%))}&space;=&space;0.24%" title="P(Ice|Foot) = \frac{0.4% \cdot 0.36%}{P(0.6%))} = 0.24%" />

**24 % of the kids playing ice hockey, are also playing football.**

**B.** 

40% of the kids like music, and 24% of the kids like to dance. Given that 30% of those that like music also likes to dance, what percent of those that like to dance also likes music?

* 40% like music (0.4%)
* 24% like dancing (0.24%)
* 30% like music | like dancing (0.3%)
* ??? like dancing | like music

<img src="https://latex.codecogs.com/gif.latex?\bg_white&space;P(Dance|Music)&space;=&space;\frac{P(Music|Dance)P(Dance)}{P(Music)}" title="P(Dance|Music) = \frac{P(Music|Dance)P(Dance)}{P(Music)}" />

<img src="https://latex.codecogs.com/gif.latex?\bg_white&space;P(Dance|Music)&space;=&space;\frac{0.3%&space;\cdot&space;0.24%}{0.4%}&space;=&space;0.18%" title="P(Dance|Music) = \frac{0.3% \cdot 0.24%}{0.4%} = 0.18%" />

**18% of the kids who likes to dance also likes to listening to music.** 

**C.**

**[Example Link 1](https://www.bartleby.com/questions-and-answers/a-bag-contains-total-30-balls-out-of-which-9-are-red-12-are-white-and-9-are-blue.-two-balls-are-draw/9d39bb8b-e41a-4804-a647-6a1e71cae64a)**

**[Example Link 2](https://www.toppr.com/ask/question/assume-that-a-factory-has-two-machines-a-and-b-past-records-shows-that-machine/)**

In a factory, machine X produces 60% of the daily output and machine Y produces 40% of the daily output. 2% of machine X’s output is defective, and 1.5% of machine Y’s output is defective. One day, an item is inspected at random, and found to be defective. What is the probability that it was produced by machine X ?

* 60% machine X
* 40% machine Y
* 2% machine X is defective.
* 1.5% machine Y is defective.

A = is the event that the item are produced by machine X 

B = is the event that the item are produced by machine Y

x = is the event of drawing a defective item.

Probability of items produced by machine A, **P(E1​)**

P(A1) = 60/100

Probability of items produced by machine B, **P(E2​)**

Probability that machine A produced defective items, **P(x/E1)**

P(A2) = 40/100

Probability that machine B produced defective items, **P(x/E2)**

P(B/A2) = 1.5/100

The probability that randomly selected items was from machine A is given by **P(E1/x)**

<img src="https://latex.codecogs.com/gif.latex?\bg_white&space;P\frac{E1}{x}=\frac{P(E1)P(\frac{x}{E1})}{P(E1)P(\frac{x}{E1})&plus;P(E2)P(\frac{x}{E2})}" title="P\frac{E1}{x}=\frac{P(E1)P(\frac{x}{E1})}{P(E1)P(\frac{x}{E1})+P(E2)P(\frac{x}{E2})}" />

***

<img src="https://latex.codecogs.com/gif.latex?\bg_white&space;=&space;\frac{\frac{3}{5}\cdot&space;\frac{2}{100}}{\frac{2}{5}\cdot&space;\frac{1.5}{100}&plus;\frac{3}{5}\cdot&space;\frac{2}{100}}" title="= \frac{\frac{3}{5}\cdot \frac{2}{100}}{\frac{2}{5}\cdot \frac{1.5}{100}+\frac{3}{5}\cdot \frac{2}{100}}" />

***
**= 0.67**

**The chance that it was produced by machine X is 0.67%**

