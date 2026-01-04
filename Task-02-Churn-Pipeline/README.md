# Task 02: Customer Churn Prediction Pipeline

## Overview
This project builds an **end-to-end machine learning pipeline** to predict customer churn
using the **Telco Customer Churn dataset**.

The goal is to demonstrate how a production-ready ML workflow can be created using
**Scikit-learn Pipelines**, including preprocessing, model training, hyperparameter tuning,
and model export.

---

## Dataset
- **Name:** Telco Customer Churn Dataset
- **Source:** Kaggle
- **Target Variable:** `Churn` (Yes / No)

The dataset contains customer demographics, services subscribed, and billing information.

---

## Pipeline Design
The ML pipeline includes:

### 1. Data Preprocessing
- Numerical features: Standard Scaling
- Categorical features: One-Hot Encoding
- Handling missing values

### 2. Models Used
- Logistic Regression
- Random Forest Classifier

### 3. Hyperparameter Tuning
- GridSearchCV used to find best parameters
- Cross-validation for robust evaluation

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score

---

## Model Export
- The complete trained pipeline is exported using **joblib**
- This allows easy reuse in production or deployment

---

## How to Run
1. Open `TASK_02.ipynb`
2. Run all cells sequentially
3. The final pipeline will be trained and evaluated
4. The model will be saved locally using joblib

---

## Skills Demonstrated
- Scikit-learn Pipeline API
- Feature engineering
- Hyperparameter tuning with GridSearchCV
- Model evaluation
- Production-ready ML workflow

---

## Notes
This notebook is designed to be **beginner-friendly** and can be run entirely in
**Google Colab or local Jupyter Notebook** without additional configuration.
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "# Task 2: End-to-End ML Pipeline with Scikit-learn\n",
        "\n",
        "## Objective\n",
        "Build a reusable and production-ready machine learning pipeline to predict customer churn.\n",
        "\n",
        "## Dataset\n",
        "- **Telco Customer Churn Dataset**\n",
        "- Contains customer information and churn labels\n",
        "- Some columns are numeric, others are categorical\n",
        "\n",
        "## Steps Implemented\n",
        "\n",
        "1. **Data Preprocessing**\n",
        "   - Handled categorical columns using `OneHotEncoder`\n",
        "   - Scaled numeric columns using `StandardScaler`\n",
        "   - Combined preprocessing using `ColumnTransformer`\n",
        "\n",
        "2. **Pipeline Construction**\n",
        "   - Built a complete pipeline using `sklearn.pipeline.Pipeline`\n",
        "   - Pipeline includes preprocessing + model\n",
        "\n",
        "3. **Models Used**\n",
        "   - Logistic Regression\n",
        "   - Random Forest Classifier\n",
        "\n",
        "4. **Hyperparameter Tuning**\n",
        "   - Used `GridSearchCV` to find the best parameters for models\n",
        "\n",
        "5. **Model Export**\n",
        "   - Saved the final pipeline using `joblib` for reusability\n",
        "\n",
        "\n",
        "## Skills Gained\n",
        "- Building ML pipelines with `sklearn`\n",
        "- Preprocessing and encoding data\n",
        "- Hyperparameter tuning with `GridSearchCV`\n",
        "- Exporting and reusing models\n",
        "- Production-ready ML workflow\n"
      ],
      "metadata": {
        "id": "iNiP7sxTlBby"
      }
    }
  ]
}
