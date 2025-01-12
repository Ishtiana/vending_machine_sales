# 🥤 Vending Machine Sales Analysis Using Machine Learning

This repository contains an in-depth analysis of vending machine sales data. The study leverages machine learning techniques to uncover patterns, optimize sales, and enhance operational efficiency.

## 📜 Abstract
Modern vending machines cater to diverse customer needs by offering a wide range of products. This project analyzes sales data collected from vending machines across multiple locations and employs machine learning models to predict sales trends and identify key factors influencing performance. The analysis uses algorithms like **XGBRegressor**, **Linear Regression**, **k-Nearest Neighbors (kNN)**, and **Decision Trees**.

## 🚀 Project Objectives
1. Optimize sales performance and revenue generation in vending machines.
2. Identify key factors influencing sales and customer preferences.
3. Evaluate the effectiveness of machine learning algorithms in predicting sales volume.

## 📊 Key Features of the Analysis
- **Data Collection**:
  - Sales data from vending machines located in a mall, library, corporate office, and manufacturing plant.
  - Includes details such as product type, location, pricing, and transaction methods.

- **Machine Learning Models**:
  - **XGBRegressor**: Best performance with a high R-squared value and low Mean Squared Error.
  - **Linear Regression**: Captures linear relationships between sales and influencing factors.
  - **k-Nearest Neighbors (kNN)**: Predicts sales based on patterns in neighboring data points.
  - **Decision Trees**: Visualizes decision-making processes for sales predictions.

- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1 Score, R-squared value, and Mean Squared Error.

- **Insights**:
  - High-performing vending machine locations include malls and offices.
  - Product preferences vary by location (e.g., healthier snacks in libraries).
  - Technology advancements, such as cashless payments, enhance user experience.

## 🛠 Tools and Technologies
- **Programming Language**: Python (Pandas, NumPy, Scikit-learn)
- **Visualization Tools**: Matplotlib, Seaborn
- **Data Source**: Real-world sales data collected over 8 months.

## Graph
![Screenshot 2025-01-12 203832](https://github.com/user-attachments/assets/e2c08deb-bc55-4168-b07d-d61e6a6380fe)

![heat](https://github.com/user-attachments/assets/fc651477-ec7a-4aee-b6c2-e74a048f6219)


## 📈 Key Results
- **XGBRegressor** emerged as the most effective model, explaining 87.87% of sales data variance.
- Decision Trees provided actionable insights into inventory management and product preferences.
- Identified correlations between pricing strategies and sales volume.

## 📂 Repository Structure
```plaintext
.
├── data/
│   ├── vending_sales_data.csv      # Raw and processed datasets
├── models/
│   ├── xgb_model.pkl               # Trained XGBoost model
│   ├── knn_model.pkl               # Trained kNN model
├── notebooks/
│   ├── analysis.ipynb              # Jupyter Notebook with analysis and visualizations
├── visuals/
│   ├── feature_importance.png      # XGBRegressor feature importance chart
│   ├── sales_heatmap.png           # Correlation heatmap
├── README.md                       # Project overview
