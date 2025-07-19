# LSTM Deep Learning for Bicing Bike Sharing Prediction

## Project Overview
This repository contains a deep learning time series analysis project focused on predicting bike usage patterns for Barcelona's Bicing bike sharing service. The project uses Long Short-Term Memory (LSTM) neural networks to forecast bike demand and availability across the city.

## Problem Statement
Barcelona's Bicing service faces challenges in maintaining optimal bike distribution across stations. This project aims to develop time series forecasting models that can predict future bike usage patterns, helping to optimize bike redistribution strategies and improve service efficiency.

## Data
The analysis uses preprocessed time series data from the Bicing service:
- **Source**: Preprocessed Bicing service data
- **Timeframe**: 15-minute intervals
- **Features**: Include bikes in usage, electrical and mechanical bike counts, temporal features
- **Location**: `/data/preprocessed/ts_data_15min.csv`

## Methodology

### Data Preparation
- Temporal feature engineering (time of day, day of week, seasonality)
- Train/test split for time series validation
- Feature scaling and normalization

### Modeling Approaches
The project implements two main modeling approaches:

1. **LSTM Deep Learning Model** (`Model-LSTM.ipynb`)
   - Long Short-Term Memory neural networks
   - Specialized for sequence data and time series forecasting
   - Capable of capturing long-term dependencies in the data

2. **Time Series Analysis** (`Model_TS.ipynb`)
   - Traditional time series modeling techniques
   - Comparative analysis with deep learning approach

## Key Files
- `Model-LSTM.ipynb`: Main notebook with LSTM implementation
- `Model_TS.ipynb`: Time series analysis notebook
- `AdvPython_Final Presentation_Bicing_Team 3.pdf`: Project presentation with results and conclusions
- `data/preprocessed/ts_data_15min.csv`: Preprocessed time series data

## Results & Conclusions
The LSTM deep learning models demonstrate effective prediction of bike usage patterns. Key findings include:
- Ability to capture complex temporal patterns in bike usage
- Identification of important factors influencing bike demand
- Potential applications for service optimization and resource allocation

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required libraries (TensorFlow, Keras, NumPy, Pandas, Matplotlib)

### Running the Notebooks
1. Clone this repository
2. Install required dependencies
3. Open the Jupyter notebooks in your preferred environment
4. Execute the cells in sequence

## Team
- Team 3 - Advanced Python Course
- ESADE Business School

## License
This project is available for academic and research purposes.

---
*Note: This README was generated based on the project files and is subject to updates as the project evolves.*
