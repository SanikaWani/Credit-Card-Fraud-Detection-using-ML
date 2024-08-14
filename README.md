# Credit Fraud Detection

This project aims to build a model that detects fraudulent credit card transactions using various machine learning algorithms. The model helps classify transactions as either legitimate or fraudulent, aiding in the prevention of financial losses due to fraud.

## Project Overview

- **Project Name:** Credit Fraud Detection
- **Dataset:** The project uses the `creditcard` dataset, which contains features related to credit card transactions.
- **Objective:** To classify transactions as normal or fraudulent.
- **Main File:** `credit_fraud_detection.ipynb`
- **Model Output:** The trained model is saved as `credit_card_model.pkl`.

## Methodology

1. **Data Preprocessing:**
   - The dataset was loaded and preprocessed to handle missing values, feature scaling, and class imbalance.
   - Feature selection was done to identify the most relevant features for fraud detection.

2. **Modeling:**
   - Multiple machine learning algorithms were experimented with, including:
     - Logistic Regression
     - Decision Trees
     - Random Forests
   - The models were evaluated based on precision score, accuracy score, F1 score, and recall.

3. **Model Evaluation:**
   - The best-performing model was selected based on evaluation metrics.
   - The final model was saved as `credit_card_model.pkl` for future use.

4. **Prediction:**
   - The model is capable of predicting whether a transaction is normal or fraudulent.
   - The results are provided at the end of the notebook.

## Files in the Repository

- `credit_fraud_detection.ipynb`: Jupyter Notebook containing the entire code implementation.
- `credit_card_model.pkl`: Trained model file.
- `README.md`: Project documentation (this file).

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/credit-fraud-detection.git

##  Install Dependencies
 
pip install -r requirements.txt

## Run the Notebook

Open the credit_fraud_detection.ipynb notebook in Jupyter Notebook and execute the cells to understand the process and generate predictions

## Load and Use the Model

You can load the trained model from credit_card_model.pkl to make predictions on new transaction data.
