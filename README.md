# microwave-quantum-transduction-simulation
# Microwave–Quantum Transduction Simulation

A Python-based educational project exploring microwave–optical quantum transduction through coupled-mode dynamics and an analytical conversion-efficiency model.

## Objectives

- Simulate coupled microwave and optical mode populations using QuTiP.
- Explore the effect of thermal-bath occupation.
- Compare numerical steady-state populations with an analytical benchmark.
- Implement an analytical transduction-efficiency equation.
- Compare finite and ideal Stokes-process suppression.

## Repository contents

- `microwave_quantum_transduction_simulation.ipynb` — simulation notebook and analysis.
- `transduction_efficiency_results.csv` — generated efficiency sweep.
- `transduction_efficiency_comparison.png` — comparison plot.

## Requirements

Python 3, NumPy, SciPy, Matplotlib, pandas, and QuTiP.

## How to run

1. Open the notebook in Google Colab.
2. Run the setup and import cells in order.
3. Run the simulation, analytical-model, and validation cells.
4. Execute the export cells to regenerate the results and plot.

## Validation and limitations

The notebook includes numerical checks for finite values, physical bounds, zero cooperativity, and the ideal-suppression limit.

These tests check numerical consistency; they do not establish agreement with experimental measurements. The coupled-mode dynamics and analytical efficiency equation are distinct model components. Full experimental reproduction requires further comparison against the reference paper's data, assumptions, and reported figures.

## Reference

Sahu et al., “Quantum-enabled operation of a microwave-optical interface,” *Nature Communications* (2022).

https://doi.org/10.1038/s41467-022-28924-2
