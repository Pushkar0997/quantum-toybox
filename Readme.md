# quantum-toybox

Quantum Toybox is a notebook-first Qiskit playground for learning core quantum computing ideas through small, focused experiments.

The project is organized as a sequence of numbered folders, each one exploring a single concept with executable notebooks and visual output. The emphasis is on clarity and hands-on inspection rather than building a packaged application.

## What's Inside

- Bell-state preparation and statevector inspection
- Uniform superposition experiments and qubit-scaling checks
- Quantum teleportation
- Deutsch's algorithm with constant and balanced oracles
- Bernstein-Vazirani secret-string recovery
- Grover search on 2-qubit and 3-qubit examples
- Standard and inverse Quantum Fourier Transform notebooks
- Quantum phase estimation with a T-gate example
- Variational Quantum Eigensolver experiments with multiple optimizers
- Basic quantum error-correction experiments

## Setup

1. Create and activate a Python virtual environment.
2. Install the notebook dependencies.
3. Open the repository in VS Code or Jupyter and run the notebooks you want to explore.

```bash
pip install -r requirements.txt
```

The notebooks depend on `qiskit`, `qiskit-aer`, and `matplotlib`.

## Repository Guide

| Folder | Focus |
| --- | --- |
| [01_bell_state](01_bell_state/README.md) | Bell-state preparation and statevector visuals |
| [02_superposition_explorer](02_superposition_explorer/README.md) | Uniform superposition and qubit-scaling tests |
| [03_quantum_teleportation](03_quantum_teleportation/README.md) | Quantum teleportation protocol |
| [04_deutschs_algorithm](04_deutschs_algorithm/README.md) | Deutsch’s algorithm with constant and balanced oracles |
| [05_bernstein_vazirani](05_bernstein_vazirani/README.md) | Secret-string recovery experiments |
| [06_grovers_search](06_grovers_search/README.md) | Grover search on 2-qubit and 3-qubit circuits |
| [07_quantum_fourier_transform](07_quantum_fourier_transform/README.md) | Standard and inverse QFT walkthroughs |
| [08_quantum_phase_estimation](08_quantum_phase_estimation/README.md) | Phase estimation with a T-gate example |
| [09_variational_quantum_eigensolver](09_variational_quantum_eigensolver/README.md) | VQE optimizer comparisons |
| [10_error_correction](10_error_correction/README.md) | Bit-flip and phase-flip error correction |

## Working With the Notebooks

- Each notebook is self-contained and can be run independently.
- Markdown cells document the intent of the circuit or analysis step.
- Code cells generally build circuits, execute samplers or estimators, and visualize the result.
- If you want to compare approaches, run the paired notebooks in the same folder side by side.

## Notes

- This repository intentionally uses notebooks instead of `.py` scripts.
- The examples are designed as learning artifacts and experimentation starting points.
- Some notebooks use newer Qiskit primitives such as `StatevectorSampler` and `StatevectorEstimator`.
