# Rossmann Store Sales Prediction

![Status](https://i.imgur.com/6MYc56a.png)
---

Rossmann operates over 3,000 drug stores across 7 European countries. Store managers are tasked with predicting daily sales up to six weeks in advance. These sales are influenced by factors including promotions, competition, school and state holidays, seasonality, and locality. Because each manager predicts sales based on unique circumstances, prediction accuracy can vary widely.

---

## Project Overview

This project addresses Rossmann’s first Kaggle competition, challenging participants to predict daily sales for 6 weeks for 1,115 stores located across Germany. Accurate sales forecasts help store managers create effective staff schedules, boosting productivity and motivation.

By developing a robust prediction model, this project aims to support store managers in focusing on what matters most: their customers and their teams.

---

## Evaluation Metric

Submissions are evaluated using the **Root Mean Square Percentage Error (RMSPE)**

The submission file should be a CSV with the following format:
```
Id,Sales
1,0
2,0
3,0
```
where each `Id` corresponds to a unique store-date combination and `Sales` is the predicted daily sales.

---

## Modeling Approach

This project leverages **XGBoost**, a powerful gradient boosting framework, to build the sales prediction model. The model uses a variety of engineered features reflecting promotions, holidays, seasonality, and other relevant factors influencing sales performance.

XGBoost was chosen for its efficiency and accuracy in handling tabular data and its ability to model complex relationships between features and sales outcomes.

---

Feel free to explore the code to see how the dataset is preprocessed, features are engineered, and the XGBoost model is trained and evaluated.
