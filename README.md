
# Program Outcomes Prediction Using Machine Learning

This project demonstrates how machine learning can be used to predict program completion and identify key factors influencing treatment outcomes in a behavioral health setting.

## Business Problem
Understanding which clients are likely to complete treatment programs is critical for improving outcomes and optimizing resource allocation. This project aims to identify patterns associated with program completion and highlight opportunities for early intervention.

## Dataset
The dataset includes:
- Client demographics  
- Program type  
- Attendance patterns  
- Care gaps  
- Medication adherence  
- Social and environmental factors  

## Methods
- Exploratory Data Analysis (EDA)  
- Logistic Regression (baseline model)  
- Random Forest (improved model)  
- Class imbalance handling using class weighting  

## Results
The initial model showed high accuracy but performed poorly at identifying non-completers due to class imbalance. After applying class weighting, model performance improved, particularly in identifying at-risk clients.

Key drivers of program completion included:
- Session attendance  
- Care gaps  
- Medication adherence  
- Social support  
- Transportation barriers  

## Business Impact
These insights can help organizations:
- Identify clients at risk of not completing treatment  
- Improve intervention strategies  
- Optimize care planning and resource allocation  

## Tools Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
