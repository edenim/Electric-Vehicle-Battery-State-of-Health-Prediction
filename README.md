# Electric Vehicle Battery State-of-Health Prediction

## Project Overview
This project develops a machine learning model to predict the State-of-Health (SoH) of lithium-ion batteries used in electric vehicles. 

As EV adoption increases, accurate battery health estimation is essential for predictive maintenance, warranty cost management, and connected vehicle analytics platforms. This project simulates a real-world EV battery analytics workflow using publicly available degradation datasets.

---

## Objective
Build a regression model to estimate:

- Battery State-of-Health (SoH %), or
- Remaining Useful Life (RUL)

based on charge/discharge cycle data and battery operating conditions.

---

## Dataset
Primary dataset sources include:

- NASA Lithium-Ion Battery Aging Dataset
- Public EV battery degradation datasets from Kaggle

Key variables:
- Charge/discharge cycle number
- Voltage
- Current
- Temperature
- Capacity degradation
- Internal resistance

---

## Methodology

### Data Processing
- Data cleaning and normalization
- Handling missing values
- Exploratory Data Analysis (EDA)

### Feature Engineering
- Capacity degradation rate
- Rolling temperature averages
- Cycle-based degradation trends

### Modeling
Baseline model:
- Linear Regression

Advanced models:
- Random Forest Regressor
- XGBoost Regressor

Evaluation metrics:
- RMSE
- MAE
- R² score

---

## Project Roadmap

- Data preprocessing
- Exploratory analysis and visualization
- Feature engineering
- Model training and evaluation
- Model comparison
- Visualization of degradation prediction performance

---

## Industry Relevance

Battery health prediction plays a critical role in:

- Predictive maintenance for EV fleets
- Battery warranty cost optimization
- Over-the-air (OTA) battery monitoring systems
- Connected vehicle data analytics platforms

This project reflects real-world automotive data science applications in EV environments.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn

---
