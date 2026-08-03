---
title: "Credit Card Fraud Detection Using Apache Spark and Machine Learning"
excerpt: "Scalable fraud detection on 555,000+ credit card transactions using Apache Spark MLlib"
collection: portfolio
category: technical
permalink: /technical-projects/credit-card-fraud-detection-spark
date: 2024-04-08
---

## Overview
Developed a scalable fraud detection solution using Apache Spark and machine learning to analyze over 555,000 credit card transactions. The project combined big data processing, exploratory analysis, time series analysis, geospatial analysis, and predictive modeling to identify fraudulent transactions and evaluate the effectiveness of multiple machine learning algorithms.

## My Contributions
- Performed data preprocessing and feature engineering for time-series analysis
- Conducted exploratory analysis to identify temporal transaction patterns
- Developed predictive models for fraud detection using Apache Spark MLlib
- Evaluated machine learning model performance using multiple metrics
- Contributed to documenting the methodology, analysis, results, and project conclusions

## Dataset
- Analyzed 555,000+ credit card transactions collected from a publicly available Kaggle dataset
- Processed 22 numerical and categorical features including transaction amount, merchant, customer demographics, location, timestamps, and fraud labels
- Worked with a highly imbalanced dataset containing both fraudulent and legitimate transactions

## Exploratory Data Analysis
Performed extensive analysis to understand fraud patterns by examining:
- Gender-based fraud rates
- Geographic distribution by state
- Transaction categories
- Transaction amount distributions
- Correlation analysis
- Weekly, monthly, and hourly fraud trends
- Geospatial clustering of fraudulent transactions

## Machine Learning Models
Developed and evaluated multiple predictive models using Apache Spark MLlib.

**Classification Models**
- Logistic Regression
- Random Forest
- Gradient Boosting Trees

**Regression Models**
- Linear Regression
- Random Forest Regressor
- Gradient Boosted Trees Regressor

**Model optimization included:**
- Cross validation
- ParamGridBuilder for hyperparameter tuning
- Pipeline-based preprocessing
- Feature importance analysis

## Key Results
- Successfully built fraud detection models capable of identifying fraudulent credit card transactions
- Gradient Boosting achieved the highest predictive performance in time-series fraud prediction
- Logistic Regression demonstrated the strongest recall for fraud detection after balancing the dataset
- Achieved approximately: **90% average accuracy, 86% precision, 82% recall**
- Identified transaction amount, transaction hour, and city population as influential predictive features

## Project Outcome
Designed and evaluated a scalable machine learning pipeline for credit card fraud detection using Apache Spark. The project demonstrated how distributed data processing, feature engineering, and predictive modeling can improve fraud detection accuracy while handling large-scale transactional datasets. The work also highlighted opportunities for future improvements through deep learning models, real-time analytics, and advanced resampling techniques.

## Skills Demonstrated
- Apache Spark & Spark MLlib
- Big data processing and distributed computing
- Feature engineering and preprocessing pipelines
- Time series and geospatial analysis
- Classification and regression modeling
- Hyperparameter tuning and cross-validation
- Model evaluation (accuracy, precision, recall)
- Handling imbalanced datasets

<details>
<summary><strong>📷 Images</strong></summary>
<div style="display: flex; flex-wrap: wrap; gap: 15px; margin-top: 15px;">
  <div style="flex: 1 1 30%;">
    <a href="/images/Analysis_of_transactions.png" target="_blank">
      <img src="/images/Analysis_of_transactions.png" style="width: 100%; border-radius: 6px; cursor: pointer;">
    </a>
    <p style="text-align: center; font-style: italic; font-size: 0.9em;">Analysis of transactions</p>
  </div>
  <div style="flex: 1 1 30%;">
    <a href="/images/Clustering_analysis_of_transaction_data.png" target="_blank">
      <img src="/images/Clustering_analysis_of_transaction_data.png" style="width: 100%; border-radius: 6px; cursor: pointer;">
    </a>
    <p style="text-align: center; font-style: italic; font-size: 0.9em;">Clustering analysis</p>
  </div>
  <div style="flex: 1 1 30%;">
    <a href="/images/Comparison_of_fraudulent_&amp;_non-fraudulent_transactions.png" target="_blank">
      <img src="/images/Comparison_of_fraudulent_&amp;_non-fraudulent_transactions.png" style="width: 100%; border-radius: 6px; cursor: pointer;">
    </a>
    <p style="text-align: center; font-style: italic; font-size: 0.9em;">Comparison of transactions</p>
  </div>
  <div style="flex: 1 1 30%;">
    <a href="/images/fraud_rate_based_on_gender_state.png" target="_blank">
      <img src="/images/fraud_rate_based_on_gender_state.png" style="width: 100%; border-radius: 6px; cursor: pointer;">
    </a>
    <p style="text-align: center; font-style: italic; font-size: 0.9em;">Fraud rate </p>
  </div>
  <div style="flex: 1 1 30%;">
    <a href="/images/Histogram_of_data.png" target="_blank">
      <img src="/images/Histogram_of_data.png" style="width: 100%; border-radius: 6px; cursor: pointer;">
    </a>
    <p style="text-align: center; font-style: italic; font-size: 0.9em;">Histogram of data</p>
  </div>
  <div style="flex: 1 1 30%;">
    <a href="/images/results_of_fraud_prediction_models.png" target="_blank">
      <img src="/images/results_of_fraud_prediction_models.png" style="width: 100%; border-radius: 6px; cursor: pointer;">
    </a>
    <p style="text-align: center; font-style: italic; font-size: 0.9em;">Results of fraud prediction models</p>
  </div>
</div>
</details>
