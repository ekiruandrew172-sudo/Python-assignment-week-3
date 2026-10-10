# PLP Python Week 3 Assignment

## Assignment Overview

This repository contains my Python Week 3 assignment. It demonstrates the use of loops, conditional statements, calculations, and debugging in Python.

## Files

* **grade_reporter.py:** Uses a `for` loop and `if/elif/else` statements to assign grades to five learners, calculate the number who passed and failed, and find the average score.
* **bug_hunt.py:** Demonstrates debugging by fixing three bugs in a program that calculates the sum of numbers from 1 to 5.

## Reflection

The hardest bug to find was the incorrect loop condition because the program could run without displaying an error but still produce the wrong answer. I knew something was wrong because the program was supposed to calculate the sum of the numbers from 1 to 5 and produce 15. I fixed the loop condition by changing `count < 5` to `count <= 5` so that the number 5 would also be included.
