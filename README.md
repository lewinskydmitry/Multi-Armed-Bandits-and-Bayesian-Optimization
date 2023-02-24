# Multi Armed Bandits and Bayesian Optimization
This repository contains code for comparing the performance of three different methods for conducting A/B testing:
E-greedy algorithm, Thompson sampling, and traditional A/B testing.

The E-greedy algorithm and Thompson sampling are two alternative methods for conducting A/B testing that have been shown
to be more efficient and effective than traditional A/B testing. The E-greedy algorithm involves randomly choosing between
the control group and the treatment group, with a certain probability of choosing the treatment group, while Thompson sampling
involves choosing the treatment group based on a probability distribution that is updated after each round of testing.

This repository includes code for implementing these three methods and comparing their performance in finding the optimal banner.
The code is written in Python and includes libraries for simulation and visualization of the results.
