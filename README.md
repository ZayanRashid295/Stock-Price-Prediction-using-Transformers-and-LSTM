# Stock Price Prediction using Transformers and LSTM
Welcome to the **IAI-Project** repository! This project focuses on analyzing historical stock market data and developing advanced machine learning models, including **Stock Transformer** and **LSTM**, to predict future stock trends.

---

## Objective

The primary goal of this project was to leverage deep learning models to predict stock price trends using historical S&P 500 data. By implementing state-of-the-art methods like Transformers and LSTMs, the project aimed to improve predictive accuracy and derive actionable insights.

---

## What We Did in This Project

### 1. **Data Collection and Preprocessing**
   - Utilized the dataset `sp500_historical_data_2.csv`, which contains historical S&P 500 stock data.
   - Performed preprocessing steps:
     - Cleaned data by handling missing values and outliers.
     - Scaled features using MinMaxScaler for compatibility with deep learning models.
     - Engineered features such as moving averages, volatility indices, and lag features.

### 2. **Exploratory Data Analysis (EDA)**
   - Conducted an in-depth analysis to uncover:
     - Key trends in historical stock prices.
     - Seasonal patterns and volatility.
     - Correlations among key financial indicators.
   - Visualized insights using Python libraries like **Matplotlib** and **Seaborn**.

### 3. **Model Development**
   - **Stock Transformer**:
     - Implemented a Transformer-based architecture for time-series forecasting.
     - Applied attention mechanisms to focus on key temporal patterns in stock data.
   - **LSTM (Long Short-Term Memory)**:
     - Built an LSTM model to capture sequential dependencies in stock prices.
     - Fine-tuned hyperparameters using grid search for optimal performance.
   - Both models were trained and evaluated to compare their accuracy and robustness.

### 4. **Model Evaluation**
   - Used evaluation metrics to measure performance:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
   - The Stock Transformer model outperformed LSTM in terms of capturing long-term dependencies, while LSTM showed competitive results for short-term predictions.

### 5. **Visualization and Deployment**
   - Visualized predictions against actual stock prices to evaluate model performance.
   - Integrated prediction results into an interactive **Power BI** dashboard (`IAI project 2.pbix`) for intuitive stakeholder communication.

---

## Tools & Technologies Used

- **Programming Languages**: Python
- **Deep Learning Frameworks**: PyTorch, TensorFlow/Keras
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Visualization**: Power BI
- **Models**: Stock Transformer, LSTM
- **Dataset**: `sp500_historical_data_2.csv`

---

## Key Insights

- The Stock Transformer effectively captured long-term temporal patterns in financial data.
- LSTM demonstrated strong performance for short-term sequential forecasting.
- Predictive insights were visualized in an interactive dashboard, enabling better decision-making for stakeholders.

---
