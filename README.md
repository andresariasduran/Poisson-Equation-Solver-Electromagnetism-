# Poisson-Equation-Solver-Electromagnetism

This project numerically solves Poisson’s equation in 2D for a non-uniform charge distribution using finite difference methods.

## Problem

Solve:

∇²V(x,y) = -ρ(x,y)

with:

ρ(x,y) = exp(-5(x² + y²)) + 0.5 sin(3πx) sin(3πy)

## Method

- Finite Difference Method (FDM)
- Jacobi iterative solver
- Dirichlet boundary conditions (V = 0)

## Features

- Numerical solution of PDE
- Electric field computation: E = -∇V
- Visualization of scalar and vector fields
