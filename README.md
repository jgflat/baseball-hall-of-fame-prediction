# Baseball Hall of Fame Prediction Project

## Overview
This project uses machine learning and predictive analytics to predict potential Major League Baseball Hall of Fame players based on career statistics, awards, All-Star appearances, batting performance, pitching performance, and fielding statistics.

The project combines multiple baseball datasets and applies several machine learning models to compare prediction performance across player positions.

Models used include:

- Logistic Regression
- Random Forest
- Neural Networks (MLPClassifier)

The project also identifies current players with strong Hall of Fame potential based on model predictions.

---

## Features

- Data cleaning and preprocessing
- Career statistic aggregation
- Feature engineering
- Hall of Fame voting analysis
- Position-specific machine learning models
- Feature importance analysis
- ROC curve visualizations
- Prediction of future Hall of Fame candidates

---

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

---

## Machine Learning Models

### Logistic Regression
Used for baseline Hall of Fame classification and probability prediction.

### Random Forest
Used to identify important player statistics and improve prediction accuracy.

### Neural Network
Used to compare deep learning style classification performance against traditional machine learning models.

---

## Dataset Information

The project uses multiple baseball datasets including:

- Hall of Fame voting data
- Batting statistics
- Pitching statistics
- Fielding statistics
- Player information
- Awards data
- All-Star appearance data

---

## Example Analysis

The project analyzes:

- Induction rates over time
- Inducted vs non-inducted players
- Position-based Hall of Fame trends
- Feature importance by position
- Predicted Hall of Fame candidates

---

## Project Structure

```text
baseball-hall-of-fame-prediction/
│
├── data/
├── hall_of_fame_prediction.py
├── README.md
├── requirements.txt
└── .gitignore

```bash
pip install -r requirements.txt

## Author Jeremy Granflaten
