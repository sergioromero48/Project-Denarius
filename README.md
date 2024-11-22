# Project Denarius: Comparative Analysis of Machine Learning Techniques in Market Forecasting

## Overview

**Project Denarius** explores the application of machine learning techniques to predict stock market trends using historical stock data. The project evaluates and compares the performance of several approaches, including:

- **Linear Regression**: A baseline method for stock price prediction using historical data.
- **Q-Learning**: A model-free reinforcement learning algorithm for trading strategy optimization.
- **Deep Q-Learning**: An extension of Q-Learning that uses neural networks for large state-space handling.
- **LSTM (Long Short-Term Memory)**: A recurrent neural network designed to capture both short-term and long-term temporal dependencies.

The project aims to understand the trade-offs between simplicity, computational requirements, and prediction accuracy in financial market forecasting.

---

## Dataset

The dataset contains 10 years of daily stock data (2013–2023) for 10 NASDAQ companies. It includes:
- **Features**: Open price, close price, high price, low price, trading volume, and derived indicators (e.g., SMA, MACD, volatility).
- **Structure**: Sequential data organized for time-series forecasting and trading strategy development.

---

## Key Insights

1. **Linear Regression**:
   - Provides a simple and computationally efficient baseline.
   - Performs well for short-term predictions but lacks the flexibility for modeling non-linear relationships.

2. **Q-Learning**:
   - Adapts to dynamic environments by learning from historical data.
   - Effective for short-term trading strategies but struggles with long-term generalization due to delayed rewards and high variance.

3. **Deep Q-Learning**:
   - Addresses the limitations of Q-Learning by leveraging neural networks for state-action mapping.
   - Training was computationally intensive, and system crashes limited its effectiveness in this project.

4. **LSTM**:
   - Captures complex temporal patterns and trends in stock data.
   - Achieved the best predictive accuracy but required careful tuning and significant computational resources.

---

## Challenges

- **Time Management**: Limited time for optimizing and testing all methods.
- **Computational Complexity**: Deep Q-Learning required resources beyond what was available, leading to incomplete training.
- **Scalability**: Reinforcement learning models struggled with the complexity of financial markets.

---

## Lessons Learned

- Simplifying project goals and focusing on fewer methods could improve overall outcomes.
- Efficient use of computational resources is critical for training complex models.
- Future iterations should consider more robust architectures and additional domain-specific features.

---

## How to Run

1. Install Python 3.9+ and required libraries: `numpy`, `pandas`, `tensorflow`, kagglehub.
2. Execute the Jupyter notebooks provided for each machine learning method:
   - `linear_reg.ipynb`
   - `q_learning.ipynb`
   - `deep_q_learning.ipynb`
   - `rnn.ipynb`

---

## Contributors

- **Gabriel Estevez Espinal**
- **Thomas Elie Free**
- **Sergio Romero Jr.**
