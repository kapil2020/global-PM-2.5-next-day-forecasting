# 🌍 Global PM2.5 Next-Day Forecasting

**Predicting next-day fine particulate matter (PM₂.₅) concentrations using Machine Learning techniques.**

This repository contains code, data workflow, and visualizations from the Kaggle-based notebook for global air quality prediction.  
It leverages meteorological and environmental datasets to build high-performance models that forecast PM₂.₅ concentration levels across multiple regions worldwide.

---

## 🚀 Project Overview

Air pollution remains one of the most critical global challenges.  
This project develops a **data-driven machine learning framework** for next-day PM₂.₅ forecasting using publicly available datasets.

**Key Features:**
- Data preprocessing and feature engineering from multi-source air quality datasets  
- Model training using tree-based ensemble methods (e.g., XGBoost, LightGBM)  
- Performance evaluation with RMSE and R² metrics  
- SHAP interpretability for feature impact analysis  
- Visual dashboards and plots for spatial-temporal understanding  

---

## 🧠 Methodology

1. **Data Aggregation:**  
   Merging global PM₂.₅ datasets with weather parameters such as temperature, wind speed, humidity, and pressure.

2. **Preprocessing & Cleaning:**  
   Handling missing values, scaling features, and temporal alignment.

3. **Model Development:**  
   Training machine learning regressors like:
   - XGBoost  
   - Random Forest  
   - LightGBM  
   - Linear Regression  

4. **Evaluation:**  
   - RMSE, MAE, and R²  
   - SHAP-based feature importance visualization  

5. **Forecast Generation:**  
   Produces next-day PM₂.₅ predictions for multiple global locations.

---

## 📊 Results & Visualization

You can explore the interactive visualizations and full notebook here:  
🔗 **[View the Project Dashboard](https://kapil2020.github.io/global-PM-2.5-next-day-forecasting/)**

---

## 🧩 Repository Structure

global-PM-2.5-next-day-forecasting/
│
├── data/ # Raw and processed datasets (not pushed due to size)
├── docs/ # HTML outputs for GitHub Pages
│ ├── index.html
│ └── notebook.html
│
├── global-analysis-next-day-pm2-5-ml.ipynb # Kaggle notebook
├── requirements.txt # Environment dependencies
└── README.md # Project documentation


---

## ⚙️ Setup Instructions

To run locally:

```bash
git clone https://github.com/kapil2020/global-PM-2.5-next-day-forecasting.git
cd global-PM-2.5-next-day-forecasting
pip install -r requirements.txt
jupyter notebook global-analysis-next-day-pm2-5-ml.ipynb


🧾 License

This project is released under the MIT License
.
