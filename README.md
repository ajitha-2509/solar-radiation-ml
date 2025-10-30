# ☀️ Global Horizontal Irradiance (GHI) Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Viz-brightgreen)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🧠 Project Overview

This project focuses on **predicting Global Horizontal Irradiance (GHI)** — a key parameter in solar energy studies — using **machine learning techniques**.  
It applies **data science** methods to meteorological data for forecasting solar radiation patterns, helping in **solar energy management and research**.

---

## 🎯 Objectives

- Develop a predictive model for **solar radiation (GHI)**  
- Use input features such as:
  - ☀️ Maximum Temperature  
  - 🌡️ Minimum Temperature  
  - ☁️ Cloud Cover  
- Compare multiple regression algorithms to determine the most accurate one  

---

## 🧪 Methodology

### 1️⃣ Data Collection & Preprocessing
- Dataset of **125 days** with **10-minute intervals**  
- Cleaned, merged, and normalized features  
- Derived **extraterrestrial radiation** using **Hargreaves & Samani (1985)** equation  

### 2️⃣ Model Development
Implemented and evaluated the following ML models:
- **Linear Regression**
- **Decision Tree Regressor**
- **Support Vector Regressor (SVR)**
- **Random Forest Regressor** ✅ *(best performer)*

### 3️⃣ Model Evaluation
Evaluated with:
- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)

| Model | R² Score | Remarks |
|:------|:---------:|:--------|
| Random Forest | **Highest Accuracy** | Most robust & generalizable |
| Decision Tree | Moderate | Prone to overfitting |
| Linear Regression | Fair | Simple baseline |
| SVR | Lower | Sensitive to scaling |

*(Insert your actual R² / MAE / MSE values once finalized)*

---

## 📊 Visual Results

| Example Output | Description |
|:---------------:|:------------|
| ![Sample Plot](https://github.com/ajithakumaravel/ghi-prediction/assets/sample_plot.png) | Sample visualization of predicted vs actual GHI values |
| ![Feature Importance](https://github.com/ajithakumaravel/ghi-prediction/assets/feature_importance.png) | Feature importance plot from Random Forest |

*(Upload your actual plots in the repository and update the image links above.)*

---

## 🧰 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python |
| Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| ML Algorithms | Scikit-learn |
| Environment | Jupyter Notebook |
| Domain | Meteorology, Solar Energy Prediction |

---
## 🌦️ Domain Relevance

This project was conducted during my Meteorology Internship (May–Jun 2025) at the
India Meteorological Department (IMD), where the objective was to:

Develop a reliable solar radiation prediction model

Support renewable energy planning and atmospheric research


## 📚 References

Hargreaves, G. H., & Samani, Z. A. (1985). Reference crop evapotranspiration from temperature. Applied Engineering in Agriculture.

India Meteorological Department data archives

## 👩‍💻 Author

Ajitha Kumaravel
🎓 M.Sc. Physics | Data Science & Meteorology Enthusiast
📍 VIT Chennai
🔗 LinkedIn

📧 ajithakumaravel200@gmail.com

