# 🎥 YouTube Success Analysis  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-purple)
![NumPy](https://img.shields.io/badge/NumPy-1.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.x-orange)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Repo Size](https://img.shields.io/github/repo-size/jaouharjihan-oss/youtube-success-analysis)

---

## 👩‍💻 Author

**Jaouhar Jihan**  
🔗 GitHub: https://github.com/jaouharjihan-oss  

---

## 📌 Project Overview

In today’s digital economy, YouTube is one of the most powerful platforms for content creation and monetization.

This project analyzes the key factors driving **subscriber growth** and **estimated revenue** using a structured **Data Analytics workflow**.

The objective is to generate **actionable insights** for content creators, digital marketers, and business decision-makers.

---

## 🎯 Business Objectives

- Identify key drivers of channel growth  
- Understand revenue distribution across categories  
- Detect patterns in top-performing channels  
- Provide data-driven strategic recommendations  

---

## 📊 Dataset Description

Main variables include:

- Subscribers  
- Total Views  
- Total Videos  
- Channel Category  
- Estimated Revenue  
- Channel Creation Date  

---

## 🧹 Data Preparation

- Duplicate removal  
- Missing value handling  
- Outlier detection  
- Feature transformation  
- Data type standardization  

---

## 🔍 Exploratory Data Analysis (EDA)

- Subscriber distribution analysis  
- Revenue comparison across categories  
- Correlation heatmaps  
- Scatter analysis (Subscribers vs Views / Revenue)  
- Top 1% channel performance analysis  

---

## 📊 Results & Visualizations

Key findings supported by visual analysis:

- 📈 Strong positive correlation between total views and estimated revenue  
- 🎯 High upload frequency contributes to subscriber growth  
- 🏆 Certain categories dominate both views and revenue  
- 📊 Top 1% channels follow consistent publishing strategies  

(Visual outputs available in `/reports/figures/`)

---

## 🧠 Machine Learning (Optional Extension)

To extend the analysis, a predictive model can be implemented:

- 🎯 Target Variable: Estimated Revenue  
- 📌 Features: Subscribers, Views, Total Videos, Category  
- 🤖 Models: Linear Regression, Random Forest Regressor  
- 📊 Evaluation Metrics: R² Score, MAE, RMSE  

This allows revenue prediction based on channel performance metrics.

---

## 💡 Business Recommendations

- Increase content publishing consistency  
- Focus on high-performing categories  
- Optimize video production frequency  
- Benchmark strategy against top-performing channels  

---

## 🏆 Project Structure

```bash
youtube-success-analysis/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_modeling.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── visualization.py
│   ├── feature_engineering.py
│   ├── modeling.py
│
├── reports/
│   ├── figures/
│   ├── final_report.pdf
│
├── requirements.txt
├── README.md
└── LICENSE
