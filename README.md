# Hospital Treatment Pricing Prediction

## Project Overview
This project aims to predict healthcare treatment costs using a publicly available medical insurance dataset. The goal is to estimate patient-specific treatment charges, which can be useful for insurance companies, hospitals, and patients for cost transparency and budgeting.

## Dataset
The dataset used is the "Medical Cost Personal Dataset" from Kaggle. It contains patient demographics and health-related features:
- Age
- Sex
- BMI (Body Mass Index)
- Number of children covered under insurance
- Smoking status
- Region
- Charges (target variable representing medical insurance costs)

## Project Workflow
1. **Data Loading and Cleaning**  
   Loaded data, checked for missing values, and performed basic cleaning.

2. **Exploratory Data Analysis (EDA)**  
   Explored feature distributions and relationships with medical charges to understand key drivers of cost.

3. **Data Preprocessing and Feature Engineering**  
   Encoded categorical variables, scaled numerical features, and performed target transformation (log) to handle skewness in charges.

4. **Modeling**  
   Built regression models including Linear Regression and Random Forest. Performed hyperparameter tuning for best accuracy.

5. **Evaluation**  
   Evaluated models using RMSE, MAE, and R² metrics. Analyzed feature importance and model errors.


Run the Jupyter notebooks in the `/notebooks` directory for step-by-step workflow and model training.

## Key Findings
- Smoking status, age, and BMI are the most influential predictors of healthcare costs.
- Models show reasonable prediction accuracy with RMSE around [your model's RMSE].
- Log-transforming the target improved model stability and performance.

## Limitations & Future Work
- Dataset lacks detailed clinical information (e.g., diagnosis codes) which could improve predictions.
- Deployment and real-time prediction service are not included in this version.
- Future work can include adding deployment, more complex models, and integrating dynamic patient data.

## Author
[Maguvarshini M]  
[www.linkedin.com/in/maguvarshinim]
