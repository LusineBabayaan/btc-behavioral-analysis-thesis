# btc-behavioral-analysis-thesis

# Neural Networks for Financial Market Behavioral Analysis
**Thesis Project | Binance BTCUSDT Trade Execution Analysis**

## Overview
This repository contains the full implementation of my thesis research on applying 
neural networks (LSTM, CNN, Transformer) to analyze behavioral patterns in 
Bitcoin trade execution data.

## Data Source
Binance Public Data API — BTCUSDT tick-by-tick trades (January 2024)

## Research Questions
1. How does Order Flow Imbalance predict short-term price movements?
2. Do large trades have disproportionate price impact?
3. How does trading intensity relate to volatility?
4. What do microstructure patterns reveal about liquidity?
5. Can neural networks detect market regimes automatically?
6. Which architecture (LSTM/CNN/Transformer) performs best?

## Results
| Model | Accuracy | F1 Score |
|-------|----------|----------|
| Transformer | 0.3979 | 0.3977 |
| CNN | 0.3941 | 0.3910 |
| LSTM | 0.3889 | 0.3824 |
| Random Baseline | 0.3333 | — |

**Key Finding:** Trading Intensity — Volatility correlation = 0.7925

## Notebooks
| Notebook | Description |
|----------|-------------|
| 01 | Data Collection (Binance API) |
| 02 | EDA & Behavioral Visualizations |
| 03 | Feature Engineering (44 features) |
| 04 | LSTM Model |
| 05 | CNN Model |
| 06 | Transformer Model |
| 07 | Final Comparison & Results |

## Tech Stack
Python 3.10 | TensorFlow 2.x | Pandas | Scikit-learn | Matplotlib
