# Chaotic Systems and Code Stability

This repository contains a compact set of Python experiments that illustrate chaotic dynamics and the impact of small changes in code and initial conditions. It includes a Lorenz attractor simulation, a stability comparison between clean and faulty implementations, and supporting analysis scripts.

## Highlights
- Lorenz attractor simulation with 3D visualization
- Side-by-side comparison of clean vs. buggy implementations
- Error propagation metrics and diagnostics

## Requirements
- Python 3.9+
- numpy, matplotlib, scipy, python-docx

Install dependencies:
```
pip install numpy matplotlib scipy python-docx
```

## Usage

Run the main entry point:
```
python main.py
```

Or run individual scripts:
```
python lorenz_attractor.py
python clean_code.py
python buggy_code.py
python epm_metric.py
```

## Project structure
```
lorenz_attractor.py          # Lorenz system simulation
clean_code.py                # Stable reference implementation
buggy_code.py                # Faulty implementation for comparison
epm_metric.py                # Error propagation metric
fragmentation_simulation.py  # Additional stability experiment
main.py                      # Runner
```

## License
MIT
