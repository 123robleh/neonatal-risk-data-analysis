# neonatal-risk-data-analysis
Exploratory and predictive analysis of neonatal medical risk using clinical indicators.

# Neonatal Risk Data Analysis Project

## Project Overview
This project explores and predicts medical risk levels in newborns using clinical and demographic indicators.  
The objective is to identify early risk factors and build a predictive model that could support clinical decision-making.

## Research Question
Which clinical indicators in newborns are associated with higher medical risk, and to what extent can these indicators be used to predict neonatal complications?

## Dataset
The dataset contains approximately 3000 simulated clinical records of newborns, including:
- Birth weight  
- Gestational age  
- Body temperature  
- Heart rate  
- Jaundice level  
- Feeding type  
- Risk classification (Healthy / At Risk)

## Methodology

### Data Cleaning
- Removed duplicate records  
- Handled missing values using median imputation  
- Detected and treated outliers  
- Encoded categorical variables  
- Normalized numerical features  

### Exploratory Data Analysis
- Univariate distributions using histograms  
- Correlation matrix  
- Boxplots comparing risk groups  

### Hypothesis Testing
- Weight vs Risk  
- Temperature vs Risk  
- Heart Rate vs Risk  
- Feeding Type vs Weight (ANOVA)  
- Jaundice vs Risk  

### Predictive Modeling
A logistic regression model was developed to predict neonatal risk.

Key findings:
- Low birth weight is associated with higher medical risk  
- Jaundice level is the strongest predictive variable  
- Temperature and heart rate variability indicate physiological instability  
- Feeding type showed no significant short-term effect on weight  

## Example Prediction
For a newborn with:
- Age: 5 days  
- Temperature: 37.5°C  
- Jaundice level: 8.2 mg/dL  

The model predicts a **40.7% probability of being classified as At Risk**.

## Limitations
- The dataset is simulated  
- Maternal and delivery clinical variables were not available  
- Observational study design limits causal interpretation  

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Statistical hypothesis testing  

## Future Work
- Use real-world clinical datasets  
- Apply advanced machine learning models (Random Forest, XGBoost)  
- Develop an interactive clinical dashboard for risk monitoring  

## Academic Context
This project was developed as part of a data analysis course to demonstrate skills in data preprocessing, exploratory analysis, statistical testing, and predictive modeling.

## Author
Robleh Abdillahi Omar  
Computer Science Student  

