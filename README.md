# StochasticProcessesChallenges
Repo Containing Coding Challenges For The Course "Stochastic Processes in Biology"

## Coding Challenge 0

Challenge: As discussed in class, write a short Python program that takes a sequence of 19 numbers, and
generates 4 groups randomly. There should be 3 groups of 5, and one group of 4 numbers.

Solution: This solution uses the numpy library. The program creates a sequential array of numbers using a specified length, shuffles that array, and splits them into N sub-arrays that are of equal size. If the array cannot be equally split, then one sub-array will be shorter than the rest. 

## Coding Challenge 1

Challenge: Rejection sampling is a useful method for generating random samples from a distribution f(x) that may be hard to sample from. The idea is to generate samples from a known distribution g(x), and then either to accept or reject the samples. Use the uniform density on the unit interval as a candidate density to generate samples from the beta distribution.

Solution: The code uses the uniform distribution as our candidate g(x) to sample from the distribution of interest f(x). This code uses a variant of rejection sampling known as "Empirical Supremum Rejection Sampling", which interatively updates the constant C based on the ratio of f(x) and g(x).

