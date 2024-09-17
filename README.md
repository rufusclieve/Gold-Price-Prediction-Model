
# Gold Price Prediction Model

## Project Overview

This project predicts the price of gold using machine learning models, specifically **Random Forest Regressor**. By analyzing historical gold prices and key economic factors, the model provides accurate predictions for future gold prices. This can be helpful for investors and analysts making data-driven decisions.

## Dataset

The dataset includes the following columns:

- **SPX**: S&P 500 Index, which represents the stock market performance of 500 large companies in the U.S.
- **GLD**: Gold ETF, which tracks the price of gold.
- **USO**: United States Oil Fund, which tracks the price movements of oil.
- **SLV**: Silver ETF, which tracks the price of silver.
- **EUR/USD**: The exchange rate between the Euro and U.S. Dollar.

## Data Preprocessing

1. **Handling Missing Values**: Missing values were carefully handled to ensure data quality.
2. **Feature Scaling**: The features were scaled appropriately to improve model performance.
3. **Train-Test Split**: The dataset was split into training and testing sets, with 80% for training and 20% for testing to evaluate model generalization.

## Model

The **Random Forest Regressor** was used to predict gold prices. This ensemble learning method builds multiple decision trees to enhance prediction accuracy and reduce overfitting.

### Model Training

- **Features (X)**: The features used were SPX, GLD, USO, SLV, and EUR/USD.
- **Target (y)**: The target was the gold prices (tracked by GLD).
- **Random Forest Regressor** was selected for its accuracy and robustness in handling structured data.

## Evaluation

The model’s performance was evaluated using the following metrics:

- **R-squared**: Indicates how well the model’s predictions match the actual values.
- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values, providing insight into the model's prediction accuracy.

### Results

The **Random Forest Regressor** provided high accuracy in predicting gold prices, outperforming simpler regression models by reducing overfitting and improving generalization.

## Conclusion

This **Gold Price Prediction** project demonstrates the effectiveness of machine learning, particularly the **Random Forest Regressor**, in forecasting gold prices. The model’s strong performance makes it a valuable tool for analyzing market trends and predicting future price movements based on economic factors.

## Usage

1. **Clone the repository**:
   ```bash
   git clone <repository-link>
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the notebook**:
   Open `gold_price_prediction.ipynb` to preprocess the data, train the model, and evaluate predictions.

## Technologies Used

- **Python**: Programming language used for analysis and modeling.
- **Pandas & NumPy**: For data handling and preprocessing.
- **Random Forest Regressor**: Main machine learning algorithm used.
- **Matplotlib & Seaborn**: For visualization of results.
- **Scikit-learn**: For evaluation metrics like R-squared and MSE.
