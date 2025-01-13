# Financial Market Anomaly Detection Using ARIMA and LSTM Models
This project analyzes financial market data to detect anomalies using statistical and machine learning methods. It includes exploratory data analysis, feature selection, and predictive modeling techniques for anomaly detection, with a primary focus on ARIMA and LSTM models. 

# Load datasets into the same workspace
![image](https://github.com/user-attachments/assets/b03004b2-927f-4534-934f-b6d7ec621f67)

---

## Key Features

### Data Analysis and Visualization:
- Analyze financial market data from `FinancialMarketData.xlsx`.
- Visualize the distribution of anomalies and trends in VIX over time.
- Generate heatmaps to assess correlations among financial indicators.

### Statistical Methods:
- Apply ARIMA for univariate time-series analysis of VIX.
- Identify anomalies using residual thresholds from ARIMA predictions.
- Evaluate model performance with metrics like MSE, MAE, and classification reports.

### Machine Learning Models:
- Feature selection based on correlation analysis to avoid multicollinearity.
- Develop multivariate models incorporating selected financial indicators.

### Deep Learning with LSTM:
- Implement Long Short-Term Memory (LSTM) networks for multivariate time-series prediction and anomaly detection.
- Prepare data with time-steps for LSTM input and scale features appropriately.

---

## Tools and Libraries

### Python Libraries:
- `pandas` and `numpy` for data manipulation.
- `matplotlib` and `seaborn` for data visualization.
- `statsmodels` for ARIMA modeling and statistical analysis.
- `scikit-learn` for data preprocessing and evaluation metrics.
- `tensorflow` or `keras` for building LSTM models.

---

## Workflow

### Exploratory Data Analysis:
1. Load and inspect the dataset.
2. Plot distributions and time-series trends.

### Correlation Analysis:
1. Identify highly correlated features.
2. Select features with high predictive potential for anomalies.
![download](https://github.com/user-attachments/assets/1aaddac3-b03e-4eaf-b3fa-920e112a49f1)


### ARIMA Modeling:
1. Determine optimal parameters `(p, d, q)` for ARIMA.
2. Train and test models using a rolling window approach.
3. Highlight anomalies on the VIX time-series plot.
![download](https://github.com/user-attachments/assets/4e15c441-3614-4fc8-8d3a-88b1c0f1f228)


### LSTM Implementation:
1. Split data into training and testing sets using a time-series split.
2. Scale and reshape data for LSTM input.
3. Train the LSTM model and analyze its performance with data from 2021 to 2024 in detecting anomalies.
![download](https://github.com/user-attachments/assets/ea2bddcf-8e3c-4ac8-9e6b-3066270d9f63)


### Evaluation:
1. Compare statistical methods and machine learning models.
2. Assess prediction accuracy and anomaly detection effectiveness.

---

## Results and Insights

The project demonstrates the effectiveness of statistical methods like ARIMA for univariate analysis and deep learning techniques like LSTM for multivariate anomaly detection. Insights from VIX trends and anomalies provide valuable signals for market analysis.

---

## Future Work
- Experiment with other time-series models like Prophet or neural network architectures.
- Extend the analysis to additional financial indicators.
- Develop a real-time anomaly detection pipeline.
