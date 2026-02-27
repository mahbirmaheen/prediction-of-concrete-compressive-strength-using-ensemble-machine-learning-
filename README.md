# Data-Driven Prediction of Concrete Strength (Materials Informatics)

## Project Goal

This project predicts the compressive strength of concrete using machine learning and interprets the results using materials science principles.

Concrete strength depends on curing age, cement hydration, water-cement ratio, and microstructure development. Instead of empirical equations, this work applies data-driven modeling to capture nonlinear relationships.

## Dataset

UCI Concrete Compressive Strength Dataset
1030 experimental samples
8 compositional/process parameters
Target: Compressive Strength (MPa)

## Models Used

* Linear Regression
* Random Forest
* Gradient Boosting
* XGBoost

## Model Performance (R²)

Linear Regression: 0.6275
Random Forest: 0.8791
Gradient Boosting: 0.9155
XGBoost: 0.9282

## Scientific Insight

Feature importance shows:

* Strength increases with curing age
* Cement increases strength
* Excess water reduces strength due to porosity

The model captures the processing → structure → property relationship in materials science.

## Project Structure

data → dataset
notebooks → analysis notebook
results → plots and figures

## Author

Mahbir Ahmed Maheen
Materials & Metallurgical Engineering
 
