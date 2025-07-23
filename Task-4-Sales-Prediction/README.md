# Sales Prediction Project

# 📈 Sales Prediction with Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3.0-orange)
![License](https://img.shields.io/badge/License-MIT-green)

Predict sales based on advertising budgets (TV, Radio, Newspaper) using machine learning algorithms.

## 📌 Table of Contents
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Data Description](#-data-description)
- [Methodology](#-methodology)
- [Results](#-results)
- [Visualizations](#-visualizations)
- [License](#-license)

## 🌟 Features
- **Data Flexibility**: Works with real or synthetic data
- **Comprehensive EDA**: Statistical analysis + 3 visualization types
- **Multiple Models**: 
  - Linear Regression
  - Ridge Regression
  - Random Forest Regressor
- **Production-Ready**: Includes data scaling and model persistence

## 💻 Installation

# Clone repository
git clone https://github.com/Sananda-Dutta/sales-prediction.git
cd sales-prediction

Install dependencies
pip install -r requirements.txt

# Download dataset (optional)
wget -P data/ https://raw.githubusercontent.com/Sananda-Dutta/CODSOFT/main/Task-4-Sales-Prediction/advertising.csv

## 📸 Output Screenshots

### 1. Model Performance Results
![Model Comparison](images/sales_chart.png)  
Output showing R² scores and MSE metrics for all tested models

### 2. Prediction Example
![Sample Prediction](images/correlaton_matrix.png)  
Example prediction for ad budgets: TV=$200k, Radio=$40k, Newspaper=$30k
