# Reinforcement Learning for Stock Trading

This project tests whether a reinforcement-learning agent can learn stock-trading decisions from historical market data. It trains and evaluates the agent for a selected ticker, then saves plots for test performance and training stability.

## What I wanted to test

Instead of writing every trading rule by hand, I wanted to see what an agent could learn through repeated interaction with a market environment. This repository keeps the experiment, its feature-engineering code, and the final report together.

## Main files

- `RL_QL_test_v3.py`: main training and evaluation script
- `Agent_v3`: agent environment
- `collect_data.py`: feature-engineering functions
- `report.pdf`: final presentation and report

## Running the experiment

1. Install the required packages, including TensorFlow.
2. Open `RL_QL_test_v3.py`.
3. Set the output path and the stock ticker you want to test.
4. Use a ticker symbol such as `AAPL`, not a company name such as `APPLE`.
5. Run the script.

## Output

The experiment creates:

- One figure showing performance on the test data
- One error-bar plot showing the training process
- One `.npy` file containing the training record

This is an experimental research model, not a live trading system.
