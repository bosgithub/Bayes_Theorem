# Bayes_Theorem

#### What is Bayes' Theorem?
Bayes' theorem describes the probability of an event, based on previous knowledge of conditions that are related to the event.

---

#### Derivation from conditional probability:

We have:

<a href="https://www.codecogs.com/eqnedit.php?latex=P(A|B)&space;=&space;\frac{P(A\bigcap&space;B)}{P(B)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P(A|B)&space;=&space;\frac{P(A\bigcap&space;B)}{P(B)}" title="P(A|B) = \frac{P(A\bigcap B)}{P(B)}" /></a>

and 

<a href="https://www.codecogs.com/eqnedit.php?latex=P(B|A)&space;=&space;\frac{P(B\bigcap&space;A)}{P(A)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P(B|A)&space;=&space;\frac{P(B\bigcap&space;A)}{P(A)}" title="P(B|A) = \frac{P(B\bigcap A)}{P(A)}" /></a>

knowing

<a href="https://www.codecogs.com/eqnedit.php?latex=P(B\bigcap&space;A)&space;=&space;P(A\bigcap&space;B)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P(B\bigcap&space;A)&space;=&space;P(A\bigcap&space;B)" title="P(B\bigcap A) = P(A\bigcap B)" /></a>

rewriting above equations:

<a href="https://www.codecogs.com/eqnedit.php?latex=P(A|B)&space;*&space;P(B)=&space;P(B|A)&space;*&space;P(A)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P(A|B)&space;*&space;P(B)=&space;P(B|A)&space;*&space;P(A)" title="P(A|B) * P(B)= P(B|A) * P(A)" /></a>

finally:

<a href="https://www.codecogs.com/eqnedit.php?latex=P(A|B)&space;=&space;\frac{P(B|A)&space;*&space;P(A)}{P(B)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P(A|B)&space;=&space;\frac{P(B|A)&space;*&space;P(A)}{P(B)}" title="P(A|B) = \frac{P(B|A) * P(A)}{P(B)}" /></a>

or

<a href="https://www.codecogs.com/eqnedit.php?latex=P(B|A)&space;=&space;\frac{P(A|B)&space;*&space;P(B)}{P(A)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P(B|A)&space;=&space;\frac{P(A|B)&space;*&space;P(B)}{P(A)}" title="P(B|A) = \frac{P(A|B) * P(B)}{P(A)}" /></a>
