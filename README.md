# Simulating Reinforcement Learning in a Neuroscience-Inspired Environment

This repository contains an implementation of a **Q-learning** agent trained on the **Gymnasium FrozenLake environment**, designed to explore reinforcement learning dynamics from a neuroscience-inspired perspective.  
The project focuses on how an agent forms associations between environmental states and actions through iterative reward-based updates, analogous to neural adaptation and behavioral learning processes.

## Objective
To simulate reinforcement learning mechanisms that parallel key aspects of decision-making and adaptation in biological neural systems, using a simple but interpretable environment.

## Implementation
- **Language:** Python  
- **Libraries:** Gymnasium, NumPy, Matplotlib  
- **Method:** Tabular Q-learning with epsilon-greedy exploration  
- **Environment:** FrozenLake (discrete grid-based environment)  

## Key Features
- Trainable Q-learning agent with adjustable learning and discount parameters  
- Visualization of convergence and policy stability  
- Evaluation of performance metrics (success rate, cumulative reward)  
- Reproducible results with configurable hyperparameters  

## Quick Start
`ash
python -m venv .venv
. .\.venv\Scripts\Activate.ps1
pip install -U pip
pip install -r requirements.txt
python run.py --train_episodes 5000 --eval_episodes 200
## Repository Structure
- **src/** — Core source code (training, evaluation, and utility modules)  
- **assets/** — Saved Q-tables, plots, and learning curves  
- **notebooks/** — Exploratory analysis and visualizations  
- **tests/** — Minimal reproducibility and verification scripts  

## Expected Outputs
- Trained Q-table stored in ssets/  
- Learning curve and policy visualization in ssets/plots/  
- Evaluation report printed in console  

## License
MIT License © 2025 Shayan Rezaei
