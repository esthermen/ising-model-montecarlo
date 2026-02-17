# 2D Ising Model – Monte Carlo Simulation

## Overview

This project implements a 2D Ising model simulation using the Metropolis Monte Carlo algorithm.

The system models a ferromagnetic lattice under thermal fluctuations and external magnetic field.

The simulation computes:

- Magnetization as a function of temperature
- Energy evolution
- Dependence on external magnetic field

---

## Physical Model

The Hamiltonian of the system is:

H = -J Σ s_i s_j - H Σ s_i

where:
- s_i = ±1 spin variable
- J = interaction strength
- H = external magnetic field

Periodic boundary conditions are applied.

---

## Numerical Method

- Random initial spin configuration
- Spin updates via Metropolis algorithm
- Thermal averaging over time steps
- Temperature sweep to analyze phase behavior

---

## Results

The simulation reproduces expected qualitative behavior:

- Decrease of magnetization with increasing temperature
- Dependence on external magnetic field
- Thermal fluctuations near critical region

---

## Requirements

- Python 3.x
- NumPy
- Matplotlib

---

## Author

Esther Menéndez
BSc Physics
