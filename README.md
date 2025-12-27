# DevelopersHub-AI-and-ML-Advanced-Tasks

# Customer Churn Prediction Pipeline

This project builds a production-ready ML pipeline to predict customer churn using the Telco dataset.

## Dataset
- Telco Customer Churn Dataset
- Features: Customer info, account info, services subscribed
- Target: Churn (Yes/No)

## How to Run
- Open `churn_pipeline.ipynb` in Google Colab
- Upload the dataset or use the provided one
- Run all cells to train models and save `churn_pipeline.pkl`
- Load and predict on new data:
```python
import joblib
model = joblib.load("churn_pipeline.pkl")
predictions = model.predict(new_data)
