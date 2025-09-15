# Week1

# Air Quality Prediction and Analysis using Machine Learning

## 📌 Project Overview
This project focuses on **environmental monitoring and pollution control**, specifically predicting and analyzing **Air Quality Index (AQI)** using Machine Learning techniques. Poor air quality has direct impacts on human health and the environment, making it a crucial area for AI-driven insights.

## 🎯 Objectives
- Explore and analyze air quality data (PM2.5, PM10, SO2, NO2, CO, O3, etc.).
- Preprocess and clean the dataset.
- Train ML models to predict Air Quality Index (AQI).
- Compare performance of different algorithms.
- (Optional) Deploy as a simple web app for visualization and prediction.

## 📊 Dataset
- **Source**: [Air Quality Dataset - Kaggle](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)  
- **Description**: Historical air pollution data across multiple Indian cities (2015–2020) with AQI levels.

## 🛠 Project Plan (AI/ML Lifecycle)
1. **Data Exploration** – Load dataset, check shape, missing values, descriptive stats.
2. **Visualization** – Histograms, pollutant trends, correlation heatmap.
3. **Preprocessing** – Handle missing values, scaling, feature engineering.
4. **Model Training** – Train models (Linear Regression, Random Forest, XGBoost).
5. **Evaluation** – Compare accuracy, RMSE, R².
6. **Deployment (Optional)** – Build a Streamlit/Flask app for real-time predictions.

## 📅 Week 1 Deliverables
- ✅ Finalized project title  
- ✅ Chosen dataset  
- ✅ Initial plan documented  
- ✅ Dataset loaded & basic exploration in Jupyter Notebook  

## ✅ Week 2 Progress
- Completed data preprocessing (missing values handled, date converted, City & AQI_Bucket encoded).
- Feature selection finalized (pollutants + City as features; AQI_Bucket as target).
- Train–test split (80/20) applied.
- Trained & tested Logistic Regression, Decision Tree, Random Forest, SVM.
- Evaluated with accuracy & classification report; added comparison chart.
- Best performer this week: SVM (high accuracy).

## ✅ Week 3 Progress
Performed detailed model evaluation, confusion matrices, and hyperparameter tuning (GridSearchCV). Final tuned model: SVM (C=1, kernel=linear, gamma=scale), saved as final_best_model.pkl. Notebook: week3_air_quality.ipynb

---
