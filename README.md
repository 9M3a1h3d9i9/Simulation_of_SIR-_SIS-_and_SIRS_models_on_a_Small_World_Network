# SIR / SIS / SIRS Simulation on a Small-World Network

> Simulation study of epidemic-spread models on a synthetic small-world network.

## Overview

This project explores how different epidemic models behave when infections propagate through a network with small-world structure.

The repository focuses on simulation and interpretation rather than claiming a production epidemiological model.

## Models

- **SIR** — Susceptible, Infected, Recovered
- **SIS** — Susceptible, Infected, Susceptible
- **SIRS** — Susceptible, Infected, Recovered, Susceptible

## Core Pipeline

```text
Network Generation
      ↓
Initial Conditions
      ↓
Disease Dynamics
      ↓
Time-step Simulation
      ↓
Population Curves
      ↓
Comparison & Interpretation
```

## Concepts Demonstrated

- Graph-based simulation
- Network diffusion
- Discrete-time dynamics
- Parameter sensitivity
- Visualization of system behavior

## Technology

- Python
- NetworkX
- NumPy
- Matplotlib

## Development Status

**Status: Educational / research prototype**

The project is useful as a foundation for understanding the relationship between network topology and diffusion dynamics. It is not intended to provide clinical or public-health predictions.

## Future Roadmap

- Add configurable network topologies
- Run parameter sweeps
- Compare small-world, random, and scale-free networks
- Add reproducible experiment configuration
- Quantify outbreak-size and peak-infection statistics
- Connect diffusion analysis to broader complex-network research

## Reproducibility

All reported observations should be generated from the repository's current simulation code and documented with the corresponding parameters.
