# OIBSIP
# Machine Learning Projects Collection

## Overview

This repository contains three Machine Learning and Data Analysis projects developed using Python. These projects demonstrate data preprocessing, visualization, machine learning model development, and performance evaluation techniques.

### Projects Included

1. Iris Flower Classification
2. Unemployment Analysis with Python
3. Car Price Prediction using Machine Learning

---

# 1. Iris Flower Classification

## Project Description

The Iris Flower Classification project predicts the species of an iris flower based on its measurements.

### Species

- Iris-setosa
- Iris-versicolor
- Iris-virginica

### Features Used

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

### Algorithm

K-Nearest Neighbors (KNN)

### Workflow

1. Load Dataset
2. Data Exploration
3. Feature Selection
4. Train-Test Split
5. Feature Scaling
6. Model Training
7. Prediction
8. Performance Evaluation
9. Confusion Matrix Visualization
10. Sample Prediction

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Outcome

The model classifies iris flowers with high accuracy and demonstrates the use of supervised learning for classification problems.

---

# 2. Unemployment Analysis with Python

## Project Description

This project analyzes unemployment trends using data analysis and visualization techniques. The goal is to understand unemployment patterns across regions and study the impact of economic events such as Covid-19.

### Dataset Features

- Region
- Date
- Estimated Unemployment Rate (%)
- Estimated Employed
- Labour Participation Rate (%)

### Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

### Workflow

1. Load Dataset
2. Data Cleaning
3. Date Formatting
4. Exploratory Data Analysis
5. State-wise Analysis
6. Trend Analysis
7. Data Visualization
8. Result Interpretation

### Visualizations

- Line Chart for Unemployment Trends
- Bar Chart for State-wise Comparison

### Outcome

The analysis helps identify unemployment patterns, compare regions, and understand changes in unemployment over time.

---

# 3. Car Price Prediction using Machine Learning

## Project Description

This project predicts the selling price of a car using machine learning techniques based on vehicle specifications and market-related factors.

### Features Used

- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner
- Car Age

### Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

### Algorithm

Random Forest Regressor

### Workflow

1. Load Dataset
2. Data Cleaning
3. Feature Engineering
4. Encoding Categorical Data
5. Train-Test Split
6. Model Training
7. Price Prediction
8. Model Evaluation
9. Feature Importance Analysis

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### Outcome

The model accurately predicts car selling prices and identifies the most influential factors affecting vehicle value.

---

# Repository Structure

```text
Machine-Learning-Projects/
│
├── Iris-Flower-Classification/
│   ├── Iris.csv
│   ├── iris_classification.py
│   └── README.md
│
├── Unemployment-Analysis/
│   ├── Unemployment_Rate_upto_11_2020.csv
│   ├── unemployment_analysis.py
│   └── README.md
│
├── Car-Price-Prediction/
│   ├── car_data.csv
│   ├── car_price_prediction.py
│   └── README.md
│
└── requirements.txt
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Machine-Learning-Projects.git
```

Move to the project directory:

```bash
cd Machine-Learning-Projects
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

# Conclusion

These projects demonstrate practical applications of Machine Learning and Data Analysis techniques. The repository covers both classification and regression problems, along with exploratory data analysis and visualization, providing a strong foundation for beginners and intermediate learners interested in Data Science and Machine Learning.
