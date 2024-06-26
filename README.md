# Algorithmic Trading System using Reinforcement Learning

## Overview

This project aims to develop an algorithmic trading system using reinforcement learning techniques. The system is designed to make buy/sell decisions based on market data, with the ultimate goal of achieving profitable trading strategies through automated decision-making.

## Project Structure

The project is organized into the following components:

1. **Data Collection and Preprocessing:** Market data is collected and preprocessed to prepare it for model training. Raw data is cleaned, normalized, and formatted for input into the trading system.

2. **Environment Setup:** A custom trading environment is created using the OpenAI Gym framework. This environment provides an interface for the reinforcement learning agent to interact with market data and make trading decisions.

3. **Model Training:** Reinforcement learning models, particularly Proximal Policy Optimization (PPO), are trained on historical market data. The models learn optimal trading strategies through trial and error, with rewards provided based on the profitability of trades.

4. **Evaluation and Backtesting:** Trained models are evaluated and backtested using validation and test datasets. Performance metrics such as average profit, reward, and win rate are analyzed to assess the effectiveness of the trading system.

## Technologies Used

The project utilizes the following technologies and libraries:

- Python: Programming language used for implementation.
- Pandas: Data manipulation and analysis library for preprocessing market data.
- Scikit-learn: Machine learning library for model training and evaluation.
- Gym: OpenAI Gym framework for creating custom trading environments.
- Stable Baselines3: Reinforcement learning library for implementing and training RL agents.

## Data

The project relies on market data for training and evaluation. You can access the data from the following link:

[Market Data](https://drive.google.com/drive/folders/1o_hilSBAXP4DugnycmVAtHrv6QkD0oXw?usp=sharing)

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Download the market data from the provided link and place it in the appropriate directory within the project.
3. Install the required dependencies listed in the `requirements.txt` file.
4. Run the training scripts to train the reinforcement learning models.
5. Evaluate the trained models using the provided evaluation scripts.
6. Experiment with different hyperparameters and algorithms to optimize the trading system's performance.
