### The Frog Problem
#### Presented by Timandra Harkness and Matt Parker in [Can you solve The Frog Problem?](https://www.youtube.com/watch?v=ZLTyX4zL2Fc)
Imagine some number of lilypads span a river, and a frog is at one bank. To get across, it randomly selects one of the lilypads ahead of it with equal probability (or the far bank), jumps there, and repeats this process until it has crossed.

For a given number of lilypads *n*, what is the expected number of jumps for the frog to make it across?

[My solution in Google Colab](https://colab.research.google.com/drive/1vMQ81rhLTEz48cXQ6XUiBcQ0KKtZb5JA)

####  Example queries
`lengthProb(n,k)` returns the probability of the frog taking a path of length *k* given *n* lilypads.
```python
>>> lengthProb(4,1)
0.2
```
`expectedSteps(n)` returns the expected number of steps given *n* lilypads.
```python
>>> expectedSteps(1)
1.5
```
#### Expected number of steps for several values of *n*
<p align="center">
  <img src="https://github.com/brayvid/FrogProblem/blob/master/FrogProblem.png">
</p>
