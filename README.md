# Titanic EDA – Exploratory Data Analysis on Titanic Dataset 🚢

This repository contains an exploratory data analysis (EDA) project on the famous Titanic dataset. The goal is to uncover hidden patterns and insights related to passenger survival, demographics, and other influencing factors.

## 📌 Project Overview

The Titanic dataset is one of the most well-known datasets in machine learning and data science education. In this project, we:

- Perform data cleaning and preprocessing.
- Analyze survival rates across different groups (gender, class, age, etc.).
- Visualize key statistics and distributions.
- Prepare data for potential predictive modeling.

## 📊 Dataset

**Source**: [Titanic - Machine Learning from Disaster | Kaggle](https://www.kaggle.com/competitions/titanic/data)

**Description**: The dataset contains details about passengers aboard the Titanic, including:

- `PassengerId`, `Name`, `Sex`, `Age`
- `Pclass`, `SibSp`, `Parch`
- `Fare`, `Cabin`, `Embarked`
- `Survived` (target variable)

## 🔍 Key Analysis Steps

- Handling missing data (`Age`, `Cabin`, `Embarked`)
- Feature engineering (e.g., extracting title from names)
- Grouped analysis by `Sex`, `Pclass`, `Age`, and `Family Size`
- Visualization using `matplotlib`, `seaborn`, and `plotly`
- Correlation heatmap of numerical features

## 📁 Files

- `titanic-eda.ipynb`: Main Jupyter notebook containing code, analysis, and plots
- `README.md`: Project overview and guide

## 🛠️ Tools & Libraries

- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn`, `plotly` – visualization
- `missingno` – missing data visualization

## 📌 How to Run

1. Clone the repository.
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly missingno
