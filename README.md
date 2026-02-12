# Lab 04 - SOP/POS and KMaps
Ivan Ha & Abigail Ames
In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
Because they represent active links between end points.
### Why are the names Sum of Products and Products of Sums?
The names "Sum of Products" (SOP) and "Product of Sums" (POS) come directly from their logical structure in Boolean algebra: SOP sums (ORs) together several products (ANDs) of variables, while POS takes the product (AND) of several sums (ORs). 
### Open the test.v file – how are we able to check that the signals match using XOR?
We are looking at the signals if they are true, that means there diffrent.
