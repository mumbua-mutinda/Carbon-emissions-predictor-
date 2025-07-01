# SDG13: Carbon Emissions Forecasting using Machine Learning

##  Overview
This project aligns with **UN SDG 13 – Climate Action**, focusing on forecasting carbon emissions globally using historical energy and economic indicators. Using supervised learning, we predict annual CO₂ emissions for countries over time to aid in sustainability planning.

## Dataset
- Source: Kaggle CO₂ Emissions dataset
- Features: `Year`, `Country (Entity)`
- Target: `Annual CO₂ Emissions (tonnes)`

## Model
- Algorithm: Random Forest Regressor
- MAE: ~6.6M
- R² Score: 1.00 
- Tools: Python, Pandas, Scikit-learn, Seaborn, Matplotlib

## Ethical Reflection
- **Bias**: Some countries might report more accurately than others.
- **Sustainability**: Forecasting helps governments make data-driven green energy policies.
- **Overfitting**: R² = 1.00 might indicate the model is memorizing, not generalizing — further tuning or validation needed.

## Contribution to SDG
This tool demonstrates how AI can help:
- Track progress of climate goals
- Predict and prepare for emissions trends
- Support climate-conscious policy design

## Visualizations

### 1. Actual vs Predicted CO₂ Emissions
This scatter plot shows how close the model’s predictions are to actual CO₂ emissions across countries and years.

![Actual vs Predicted](screenshots/actual-vs-predicted.png)

---

### 2. CO₂ Emissions Over Time – Kenya
A line graph showing how emissions in Kenya have evolved from 1949 onwards.

![Kenya Emissions](screenshots/kenya-emissions-trend.png)

---

### 3. Feature Importance
The model relies more heavily on the `Year` variable than on `Entity` (country), as shown below.

![Feature Importance](screenshots/feature-importance.png)
