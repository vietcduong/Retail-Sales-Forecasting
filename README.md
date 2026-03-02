# Retail Sales Forecasting with Machine Learning

## Project Overview

This project analyses historical retail sales data to understand key drivers of store performance and to build predictive models capable of forecasting future sales. The work was completed as part of my MSc in Business Analytics at the University of Manchester.

The objective was to combine exploratory data analysis, statistical modelling, and machine learning to generate insights that could support operational and strategic retail decisions.

---

# Business Problem

Retail chains rely on accurate sales forecasts to plan inventory, staffing, promotions, and supply chain operations.

However, sales are influenced by multiple factors including:

* promotions
* holidays
* store characteristics
* competition
* seasonal patterns

The goal of this project was to identify the most important drivers of sales and develop models that improve forecasting accuracy.

---

# Dataset

The analysis uses a retail dataset covering **1,115 stores** with daily sales observations.

Key variables include:

* Daily sales
* Promotions
* Store type and assortment
* Competition distance
* Holiday indicators
* Customer counts
* Date information

The dataset combines transactional sales data with store-level attributes to enable both behavioural and operational analysis.

---

# Project Workflow

## 1. Data Cleaning and Preparation

Key preprocessing steps included:

* Handling missing values
* Removing closed-store observations
* Merging store metadata with transactional data
* Creating time-based features
* Outlier inspection

Feature engineering was used to capture patterns such as:

* day of week
* seasonality
* promotion timing
* competition effects

---

# 2. Exploratory Data Analysis

EDA was used to uncover patterns in demand and store performance.

Key findings:

• Sales show strong weekly and seasonal patterns
• Promotions significantly increase revenue
• Holiday periods create large spikes in demand
• Store categories show different baseline sales levels

Visualisation techniques were used to understand variation across stores and time.

---

# 3. Store Segmentation

Clustering techniques were applied to group stores with similar behaviour.

This allowed:

* more tailored modelling
* improved understanding of demand drivers
* better forecasting accuracy

Four distinct store clusters were identified based on sales dynamics and operational characteristics.

---

# 4. Predictive Modelling

Two modelling approaches were developed and evaluated.

### Linear Regression

Used to estimate relationships between sales and explanatory variables such as promotions, holidays, and store characteristics.

### Neural Networks

Implemented to capture more complex nonlinear relationships in the data.

---

# Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R²

Results showed that combining engineered features with segmentation improved predictive performance.

---

# Key Insights

Important drivers of retail sales include:

* promotional campaigns
* seasonal effects
* holiday periods
* store format
* competitive environment

Segmenting stores before modelling improved forecasting accuracy and interpretability.

---

# Tools and Technologies

Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn
Machine Learning
Exploratory Data Analysis

---

# Repository Structure

```
retail-sales-forecasting
│
├── data                # dataset used for analysis
├── notebooks           # analysis and modelling notebooks
├── report              # full academic report
└── images              # visualisations used in this project
```

---

# Example Visualisations

(Add exported charts here)

Examples may include:

* sales trends
* promotion impact
* cluster visualisation
* model performance

---

# What This Project Demonstrates

• Data cleaning and feature engineering
• Exploratory data analysis
• Machine learning modelling
• Business insight generation
• Communicating analytical results clearly

---

# Future Improvements

Possible extensions of this work include:

* advanced time-series forecasting
* gradient boosting models
* hyperparameter optimisation
* deployment as an automated forecasting pipeline

---

# Author

Viet Cuong Duong
MSc Business Analytics – University of Manchester

Focus areas:
Data Analytics | Machine Learning | Financial & Business Analysis
