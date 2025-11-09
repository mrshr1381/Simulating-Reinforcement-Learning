# Simulating Reinforcement Learning

Q-learning on Gymnasium FrozenLake. Reproducible and easy to run.

## Quick start
python -m venv .venv
. .\.venv\Scripts\Activate.ps1
pip install -U pip
pip install -r requirements.txt
python run.py --train_episodes 5000 --eval_episodes 200

## Structure
src/          source code
assets/       figures and saved artifacts
notebooks/    exploratory notebooks
tests/        minimal tests

## Expected outputs
Q-table file in assets
Success rate printed at the end

## License
MIT
