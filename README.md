  # Investigating Thermal Noise and Decay Effects on Spin Qubit Coherence

This repository contains the **Final Project for TN3156**: A study on how thermal noise and decay rates influence the coherence of a spin qubit. The project models and simulates the interaction of a spin-1/2 qubit with a thermal bath, examining the effects of varying parameters like temperature and decay rates on qubit decoherence.

## Project Overview

- **Goal**: Model the dynamics of a spin-1/2 qubit in a thermal environment, investigate decoherence effects, and explore strategies to mitigate them.
- **Key Techniques**: Lindblad master equation, Bose-Einstein statistics, numerical simulations, and interactive visualizations.
- **Outcome**: Insights into how thermal noise and decay rates influence qubit behavior, providing groundwork for improving qubit performance in quantum systems.

## Features

- **Thermal Noise Simulation**:
  - Models the interaction between a qubit and a thermal bath using Bose-Einstein statistics.
  - Investigates the impact of varying temperatures on qubit coherence.

- **Decay Rate Analysis**:
  - Studies the effects of relaxation, excitation, and dephasing on qubit dynamics.
  - Explores how decay rates influence coherence times and steady-state populations.

- **Interactive Visualization**:
  - Visualizes qubit behavior over time using plots of population difference (⟨σ_z⟩) and coherence (⟨σ_x⟩, ⟨σ_y⟩).
  - Enables real-time parameter adjustment using sliders.

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: QuTiP (Quantum Toolbox in Python), NumPy, Matplotlib, ipywidgets

## How to Run

### Prerequisites

- Python 3.8 or higher
- Required libraries: QuTiP, NumPy, Matplotlib, ipywidgets

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quantum-project.git
   cd quantum-project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Final Project Template.ipynb"
   ```

4. Use the sliders in the notebook to adjust parameters like temperature and decay rates, and observe their effects on qubit behavior.

## Key Results

- **Thermal Noise**:
  - Higher temperatures accelerate qubit decoherence, reducing coherence times.
  - Steady-state population shifts toward equilibrium as temperature increases.

- **Decay Rates**:
  - Increasing decay rates results in faster relaxation to equilibrium.
  - Dephasing significantly impacts the coherence properties of the qubit.

- **Visualizations**:
  - Dynamic plots illustrate the effects of noise and decay on qubit population and coherence.

## Contributors

- **Maria Ruxanda Tudor**: Techniques and approach, Results, Code implementation
- **Luis Cabo**: Introduction, Physical problem description, Code implementation
