# Market Anomaly Detection System

A machine learning-based system that detects market anomalies and proposes investment strategies to protect against market crashes.

## Project Overview
This project implements a comprehensive market monitoring system that:
- Detects potential market crashes using machine learning
- Uses multiple market indicators (VIX, bonds, currencies, commodities) for validation
- Provides data-driven investment strategies to minimize losses
- Generates clear, actionable trading recommendations

## Technical Implementation
- Anomaly detection using Isolation Forest algorithm
- Feature engineering incorporating financial domain knowledge
- Multi-factor market stress signals
- Dynamic portfolio allocation strategy
- Performance visualization and analysis

## Dataset
The system uses historical financial market data including:
- Volatility Index (VIX)
- Treasury yields
- Currency pairs
- Commodity indices

## Results
The model achieved:
- F1 score of 0.49 on test data
- 83% recall rate for market crash detection
- Strategy outperformance during high-stress periods
