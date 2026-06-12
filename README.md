# S&P 500 Stock Price Prediction using Machine Learning

## 📌 Overview

This project uses Machine Learning to predict whether the S&P 500 index will move up or down on the next trading day based on historical market data.

## 🎯 Objective

Build a classification model that predicts if tomorrow's closing price will be higher than today's closing price.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* yfinance
* Scikit-learn
* Matplotlib

## 📊 Dataset

Historical S&P 500 market data was collected using the `yfinance` library, including:

* Open Price
* High Price
* Low Price
* Close Price
* Volume

## 🚀 Workflow

1. Collect historical stock market data.
2. Preprocess and clean the dataset.
3. Create target and prediction features.
4. Train a Random Forest Classifier.
5. Evaluate the model using backtesting.
6. Predict future market movement.

## 🤖 Machine Learning Model

* Random Forest Classifier

## 📈 Results

The model achieved a precision score of approximately **54.46%** in predicting upward market movements.

## ▶️ How to Run

1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook.

```bash
pip install pandas numpy yfinance scikit-learn matplotlib
```

## 📂 Project Structure

```text
S&P500-Stock-Prediction/
│
├── stock_prediction.ipynb
├── README.md
└── requirements.txt
```

## 🔮 Future Improvements

* Hyperparameter tuning
* Additional technical indicators
* Testing advanced ML models
* Improving prediction accuracy

