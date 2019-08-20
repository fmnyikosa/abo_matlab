# ABO: Adaptive Bayesian Optimization for MATLAB

This is Adaptive Bayesian Optimization (ABO )for time-varying objective functions in MATLAB. It relies on using [BayesOptMat](https://www.github.com/fmnyikosa/bayes_opt_mat). ABO performs Bayesian global optimization with the same acquisition functions as standard BO. This code has the following additional features:

- ABO diagnostic and logging tools to test optimization speed and efficiency; 
- ABO visualization and animation utilities for low dimensional data and test objective functions, and for performance metrics' graphs. 

## Setup

The root folder contains the file `start.m` which adds the relevent dependencies to the current path. Make sure you run this file before executing anything. 

The root folder also contains demo files for how to use the various features, and the methods have comments about their inputs and outputs.   