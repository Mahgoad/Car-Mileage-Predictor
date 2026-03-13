# Car Mileage Predictor

This project utilizes Machine Learning to predict vehicle fuel economy (km/L) based on physical and mechanical specifications.

## Objective
To predict a vehicle's raw mileage accurately and evaluate its actual engine workload.

## Dataset
The dataset contains specifications for 100 modern vehicles. Key features include:
- total_mass_kg (Vehicle Weight)
- horsepower & displacement_cc (Engine Specs)
- drag_coefficient & frontal_area_m2 (Aerodynamics)
- tire_pressure_psi & tire_width_mm (Wheel mechanics)
- est_km_per_l (Target Variable)

## Methods
1. Data Preprocessing: Cleaning missing text and mapping categorical variables2.
2. Exploratory Data Analysis (EDA): Correlation mapping to identify non-linear relationships between mass, horsepower, and fuel consumption
3. Feature Engineering: Development of the FEI Formula to normalize efficiency across different weight classes.
4. Model Validation: 80/20 Train-Test split. 

## Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor (Final Model)

## Evaluation Metrics
- MAE
- RMSE
- R2 Score
- Cross-Validation

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
