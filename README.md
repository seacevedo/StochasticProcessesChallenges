# StochasticProcessesChallenges
Repo Containing Coding Challenges For The Course "Stochastic Processes in Biology"

## Coding Challenge 0

Challenge: As discussed in class, write a short Python program that takes a sequence of 19 numbers, and
generates 4 groups randomly. There should be 3 groups of 5, and one group of 4 numbers.

Solution: This solution uses the numpy library. The program creates a sequential array of numbers using a specified length, shuffles that array, and splits them into sub-arrays that are of equal size. If the array cannot be equally split, then one sub-array will be shorter than the rest. 
