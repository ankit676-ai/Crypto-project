# Crypto Time Series Analysis & Prediction

## Overview
A comparative study of ML models (Baseline, CNN, LSTM, GRU, GAN) for forecasting cryptocurrency trends using historical price data.

## Project Structure
- `notebooks/` – exploratory analysis and model training notebooks  
- `src/` – reusable scripts for data processing and prediction  
- `plots/` – generated charts for model evaluation  

## Data
Description of dataset source and features used (e.g., open, close, volume).

## Models & Performance
| Model     | Metric (e.g. MSE) |
|-----------|------------------:|
| Baseline  | 0.0123            |
| LSTM      | 0.0087            |
| CNN       | ...               |
...  
Include brief commentary.

## Setup & Reproduction
```bash
git clone <repo-url>
cd Crypto-project
pip install -r requirements.txt
jupyter notebook notebooks/Baseline.ipynb
