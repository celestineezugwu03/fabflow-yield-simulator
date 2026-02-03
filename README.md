# Fab Process Simulator

## Project Overview
This project implements a configuration-driven semiconductor fabrication process simulator that models wafer-level defect accumulation, process variability, and yield loss across a simplified multi-step fab workflow. The simulator represents key manufacturing steps using probabilistic defect generation and computes die yield using a Poisson-based yield model. The goal is to provide an educational yet engineering-grounded framework for analyzing yield degradation, process sensitivity, and manufacturing trade-offs in semiconductor fabrication.

## Features
- Simulates basic fab process steps
- Models process variability and defects
- Visualizes yield and process performance metrics

## How to Run (Placeholder)
1. Open the notebook in Google Colab.
2. Run the first cell to install dependencies:
   ```python
   !pip install numpy pandas matplotlib scipy

## Tech Stack
- Python
- NumPy
- Matplotlib
- Pandas (optional)

## Future Improvements
- Add equipment-level modeling
- Introduce statistical process control (SPC)
- Expand to multi-step fab workflows
