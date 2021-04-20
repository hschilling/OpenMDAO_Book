# Working with Derivatives

## Using Finite Difference or Complex Step
---
- [Approximating Partial Derivatives](approximating_partial_derivatives.ipynb)
- [Approximating Semi-Total Derivatives](approximating_totals.ipynb)
- [Speeding up Derivative Approximations with Parallel Finite Difference and Parallel Complex Step](parallel_fd.ipynb)

## Providing Analytic Partial Derivatives
- [Declaring Partial Derivatives](approximating_partial_derivatives.ipynb)
- [Sparse Partial Derivatives](approximating_partial_derivatives.ipynb)

## Verifying Partial Derivatives are Correct
- [Checking Partial Derivatives with Finite Difference](approximating_partial_derivatives.ipynb)
- [Changing Check Settings for FD or CS](approximating_partial_derivatives.ipynb)
- [Checking Partial Derivatives on a Subset of a Model](approximating_partial_derivatives.ipynb)
- [Visually Checking Partial Derivatives with Matrix Diagrams](approximating_partial_derivatives.ipynb)
- [Unit Testing Partial Derivatives](approximating_partial_derivatives.ipynb)

## Computing Total Derivatives Across a Model
- [Picking Forward or Reverse Total Derivative Solve](approximating_partial_derivatives.ipynb)
- [Computing Total Derivatives](approximating_partial_derivatives.ipynb)
- [Checking Total Derivatives](approximating_partial_derivatives.ipynb)
- [Matrix Free Total Derivatives](approximating_partial_derivatives.ipynb)

## Reducing the Cost of Total Derivative Solves Using Advanced Features

There are a number of special cases where a model has a particular structure that can be exploited to reduce the cost of linear solves used to compute total derivatives. You can learn details of how to determine if your problem has the necessary structure to use one of these features, or how to restructure your problem to make use of them in the :ref:`Theory Manual entry on how OpenMDAO computes total derivatives<total_derivs_theory>`

- [In-Memory Assembly of Jacobians](approximating_partial_derivatives.ipynb)
- [Simultaneous Total Derivative Coloring For Separable Problems](approximating_partial_derivatives.ipynb)
- [Parallel Coloring for Multipoint or Fan-Out Problems](approximating_partial_derivatives.ipynb)
- [Vectorizing Linear Solves for Feed-Forward Models](approximating_partial_derivatives.ipynb)
- [Restarting Linear Solutions for Expensive Linear Solves](approximating_partial_derivatives.ipynb)


```python

```
