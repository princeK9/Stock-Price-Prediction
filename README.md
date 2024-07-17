# Stock-Price-Prediction
This project aims to develop a predictive model that can accurately forecast stock prices based on historical data and relevant market indicators. The model will leverage machine-learning techniques to analyze past price movements, trading volumes, economic indicators, and other financial data to predict future stock prices. 


## Key Features

- **Data**: Historical stock data including Open, High, Low prices, and Volume.
- **Model**: RandomForestRegressor trained to predict Adjusted Close prices.
- **Evaluation Metrics**: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R-squared (R²).

## Steps

1. **Data Preparation**: 
   
2. **Model Training**: 

3. **Prediction**:

4. **Evaluation**: Optionally evaluate predictions using MAE, RMSE, and R² metrics.

## Files

- `proj1.ipynb`: Jupyter notebook containing the project code.
- `stocks.csv`: Sample dataset containing historical stock data.

## Requirements

- Python 3.x
- Libraries: pandas, scikit-learn, matplotlib, seaborn

## Usage

1. Cloned the repository.
2. Installed required libraries 
3. Run the `proj1.ipynb` notebook to train the model and make predictions.

### Points of Improvement
1. Data Scaling and normalisation

2. Proper Visualisations : Better plots like predicted vs actual prices with less discrepancies.
   
3. Ensemble Methods: Experiment with ensemble methods beyond Random Forest, such as Gradient Boosting or Stacking, to potentially improve prediction accuracy.

4. Error Analysis: Conduct thorough error analysis to understand and mitigate systematic biases or sources of prediction errors in the model.


