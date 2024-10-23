# PINNs-framework

## Overview
This repository contains ongoing development of a framework that utilizes PINNs (Physics Informed Neural Networks) to solve both forward and inverse problems. The idea of PINNs was introduced by [Raissi et al.](https://www.sciencedirect.com/science/article/pii/S0021999118307125) in 2019 as a method of embedding knowledge of a physical system and its governing laws into a neural network such that it was possble to learn the unknown analytical solution or coefficients of a PDE given data sparsity. More information will be added to this page as the framework scales.

### Benchmark
For the application of environmental forensics, pollutant tracking or source identification is particularly of interest. As a benchmark case, this study will look at the advection diffusion PDE in 1D, which can be described with
```math
u_t = c^2 u_{xx} - \beta u_x 
```

### PINNs for Forward Problems 
The forward problem formulation for PINNs involves solving for the solution $u$ given a PDE with some intial and boundary conditions. 

### PINNs for Inverse Problems
On the other hand, the backward problem formulation for PINNs involves finding the unknown coefficients or parameter values of a PDE given observational data. As a byproduct of solving the inverse problem, we are also essentially given the extrapolated solution.
