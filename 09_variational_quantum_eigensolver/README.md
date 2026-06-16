# Variational Quantum Eigensolver

This folder compares two optimization strategies for a small VQE-style energy minimization workflow.

## Notebooks

- [gradient_descent_optimizer.ipynb](gradient_descent_optimizer.ipynb) uses a gradient-based optimizer to minimize the energy estimate.
- [cobyla_optimizer.ipynb](cobyla_optimizer.ipynb) uses COBYLA for the same general objective so the approaches can be compared.

## What to Expect

- A parameterized ansatz built with `EfficientSU2`
- Hamiltonian evaluation with `StatevectorEstimator`
- Energy-history tracking across optimizer steps
- Comparison of optimizer behavior and convergence

## Suggested Use

Run both notebooks with the same Hamiltonian and compare their energy traces to see how the optimizer choice affects convergence.
