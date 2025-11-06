# RL-Based Log Filtering for Process Mining

This repository contains the implementation of a reinforcement learning framework for optimizing filtering thresholds in event logs. The agent uses Q-learning guided by alignment-based fitness, precision, and predictive accuracy to discover thresholds that balance conformance and generalization.

## 📂 Project Structure
├── data/ │   └── sepsis_cases.csv              # Preprocessed event log ├── src/ │   ├── q_learning_agent.py           # Core Q-learning logic │   ├── reward_function.py            # Computes fitness, precision, accuracy │   ├── alignment_evaluator.py        # PM4Py-based conformance checking │   ├── sampling.py                   # Dynamic trace sampling │   └── visualization.py              # Plots and metrics ├── results/ │   ├── metrics.csv                   # Logged metrics per threshold │   └── plots/                        # Generated visualizations ├── README.md └── requirements.txt

