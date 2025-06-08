# Sugarcane Production and Export Prediction

## Overview
This project uses machine learning models to predict sugarcane production and export based on historical data from Australia. The analysis is performed in two stages:
1. Predicting sugar production using land usage and sugarcane yield.
2. Predicting sugar export using land usage, sugarcane yield, and sugar production.

## Files
- `model_june_7.ipynb`: Contains the implementation of various machine learning models for predicting land usage.
- `sugar_pred.ipynb`: Implements machine learning models for predicting sugar production and export.

## Data
The dataset used is `Australia.xlsx`, which includes the following columns:
- Land_used(ha)
- Sugarcane_Yield(t/ha)
- Sugar_Prod(tons)
- Exported_sugar(tons)

## Setup
1. Ensure you have the required libraries installed:
   - pandas
   - numpy
   - scikit-learn
   - tensorflow
   - keras_tuner
   - matplotlib
   - xgboost

2. Run the notebooks in the following order:
   - `model_june_7.ipynb`
   - `sugar_pred.ipynb`

## Results
The results of the predictions are visualized using plots and tables, showing the performance of individual models and ensemble methods.

## License
[Specify your license here]

## Contributing
[Specify how others can contribute to your project] 