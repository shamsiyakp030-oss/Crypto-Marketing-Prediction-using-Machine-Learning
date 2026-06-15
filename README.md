#  Crypto Marketing Prediction using Machine Learning

##  Project Overview

This project predicts whether a cryptocurrency's closing price will increase on the next day.

The model analyzes historical cryptocurrency market data, technical indicators, market sentiment indicators, and trading metrics to generate predictions.

The project demonstrates a complete Machine Learning workflow:

- Data Collection & Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing Pipeline
- Model Building
- Hyperparameter Tuning
- Model Evaluation
- Feature Importance Analysis
- Pipeline Saving for Deployment

---

##  Business Problem

Cryptocurrency markets are highly volatile.

The objective is to build a classification model that predicts:

- **1 = Price will increase tomorrow**
- **0 = Price will decrease tomorrow**

This helps traders and investors make data-driven decisions.

---

##  Dataset Features

The dataset contains:

### Market Features
- Open Price
- High Price
- Low Price
- Close Price
- Volume

### Technical Indicators
- SMA (Simple Moving Average)
- RSI (Relative Strength Index)
- Bollinger Bands
- ATR (Average True Range)

### Market Sentiment
- Fear & Greed Index

### Cryptocurrency Information
- Symbol
- Market Metrics

---

##  Machine Learning Pipeline

### Data Preprocessing

Numerical Features:
- Missing Value Imputation (Median)
- Standard Scaling

Categorical Features:
- Missing Value Imputation
- One-Hot Encoding

### Algorithms Used

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Gradient Boosting Classifier
5. Extra Trees Classifier

---

##  Hyperparameter Tuning

GridSearchCV was used to optimize the Random Forest model.

Parameters tuned:

- n_estimators
- max_depth
- min_samples_split

---

##  Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

##  Feature Importance

Feature importance analysis helps identify the most influential factors affecting cryptocurrency price movement.

Examples:

- RSI
- SMA
- ATR
- Volume
- Fear & Greed Index

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

##  Project Structure

Crypto-Marketing-Prediction/

│

├── crypto_daily.csv

├── Crypto Marketing.ipynb

├── requirements.txt

├── README.md

└── saved_pipeline.pkl

---

##  How to Run

### Clone Repository

git clone https://github.com/yourusername/crypto-marketing-prediction.git

cd crypto-marketing-prediction

### Install Dependencies

pip install -r requirements.txt

### Run Notebook

jupyter notebook

Open:

Crypto Marketing.ipynb

---

## Streamlit cloud community:
https://crypto-marketing-prediction-using-machine-learning-bwvqjcwnnhv.streamlit.app/

##  Results

The project compares multiple machine learning models and selects the best-performing model using GridSearchCV optimization.

The final model can be used for:

- Crypto trend prediction
- Trading signal generation
- Market analysis
- Investment research

---

## 👨‍💻 Author

Shamsiya KP

AI & Data Science Trainee

Machine Learning | Data Science | Python Developer
