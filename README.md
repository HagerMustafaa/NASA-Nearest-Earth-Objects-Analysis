# NASA Nearest Earth Objects (NEO) Analysis

![NEO Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTS7MGeTtUIacMoMQC4tJ8vJtO5WLhm6DN_dP6TWVzGdYdFpBJZwHhFSPgplKoChARyU_o&usqp=CAU)

## Project Overview
This project analyzes the NASA Nearest Earth Objects (NEO) dataset from 1910 to 2024 to predict whether an object is hazardous using supervised machine learning models. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024/data).

## Objectives
1. Perform exploratory data analysis (EDA) and visualization.
2. Preprocess the data with outlier removal, feature engineering, and scaling.
3. Train and evaluate machine learning models (Logistic Regression, Random Forest, XGBoost) to classify hazardous NEOs.
4. Provide detailed insights into factors influencing hazardousness.

## Dataset
- Source: Kaggle (`neo_v2.csv`)
- Features: est_diameter_min, est_diameter_max, relative_velocity, miss_distance, absolute_magnitude, hazardous (target), etc.
- Size: ~90k rows

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, imblearn
