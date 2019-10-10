### The Frog Problem
#### Presented by Timandra Harkness and Matt Parker in [Can you solve The Frog Problem?](https://www.youtube.com/watch?v=ZLTyX4zL2Fc)
Imagine some number of lillypads spanning a river, and a frog at one bank. The frog wants to cross the river. To jump forward, it randomly selects a lillypad (or the far bank) from the available ones ahead of it with equal probability, jumps there, and repeats this process until it has reached the opposite bank.

For a given number of initially available positions *n* (the lillypads plus the far bank), what is the expected number of jumps for the frog to make it across?

[My solution in Google Colab](https://colab.research.google.com/drive/1SpVCQgN3CcJgsBXm8UwBuC68gV8EKctP)

####  Example queries
`lengthProb(n,k)` returns the probability of the frog taking a path of length *k* given there are *n* initial positions.
```python
>>> lengthProb(5,1)
0.2
```
`expectedSteps(n)` returns the expected number of steps given *n* initial positions.
```python
>>> expectedSteps(10)
2.9289682539682538
```
#### Expected number of steps for several values of *n*
<p align="left">
  <img src="https://github.com/brayvid/FrogProblem/blob/master/frogproblem.png">
</p>
