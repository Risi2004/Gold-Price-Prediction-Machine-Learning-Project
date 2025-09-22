# Gold-Price-Prediction-Machine-Learning-Project

This project applies **machine learning techniques** to predict gold prices. By analyzing historical gold price data along with related economic indicators, the goal is to build a predictive model that can forecast future gold price movements.

---

## 📌 Introduction
Gold is a significant commodity influenced by various **economic and geopolitical factors**. Predicting its price can be valuable for investors and analysts.  
This project demonstrates how to use a **Random Forest Regressor** to predict the price of gold based on historical and financial data.

---

## 🚀 Features
- **Data Collection & Processing**: Reads and prepares the historical gold price dataset.
- **Exploratory Data Analysis (EDA)**: Visualizes trends and relationships in the data.
- **Model Training**: Uses a **Random Forest Regressor** model.
- **Model Evaluation**: Assesses performance using accuracy metrics.
- **Prediction**: Forecasts gold prices with the trained model.

---

## 📊 Methodology
The project follows a standard **machine learning pipeline** implemented in Jupyter Notebook:

1. **Data Collection**  
   - Uses a CSV file `gold.csv` containing historical gold prices and related financial indicators.

2. **Data Preprocessing**  
   - Cleans the dataset, handles missing values, and performs feature selection.

3. **Train-Test Split**  
   - Splits the dataset into **training** and **testing** sets for unbiased evaluation.

4. **Model Training**  
   - Trains a **Random Forest Regressor** to capture complex relationships with good bias-variance balance.

5. **Evaluation**  
   - Evaluates performance using:
     - R² (R-squared)
