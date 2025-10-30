**Heart Disease Prediction —
Project Overview**:
This project focuses on analyzing cardiovascular disease (CVD) data to uncover key factors influencing heart attack risk, such as age, cholesterol, and blood pressure.
After performing data cleaning and exploratory data analysis (EDA), a logistic regression model is built to predict the likelihood of CVD.
The model serves as a baseline for future enhancements with more advanced machine learning techniques.
Cardiovascular disease is the leading cause of death worldwide, and early risk detection is vital for prevention and timely intervention.
Through this project, we aim to identify significant predictors of heart disease and develop a foundation for accurate, data-driven diagnosis.

**Overview about data set**:
The dataset includes medical records of patients with various clinical measurements relevant to heart health.
Each record consists of features that may influence the presence of cardiovascular disease.

**Key Attributes Include**:
age: Age of the patient
sex: Gender (1 = male, 0 = female)
trestbps: Resting blood pressure (in mm Hg)
chol: Serum cholesterol (mg/dl)
fbs: Fasting blood sugar (>120 mg/dl → 1, else 0)
restecg: Resting electrocardiographic results
thalach: Maximum heart rate achieved
exang: Exercise-induced angina (1 = yes, 0 = no)
oldpeak: ST depression induced by exercise
ca: Number of major vessels (0–3) colored by fluoroscopy
thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)
target: Presence of CVD (1 = yes, 0 = no)

**Objectives**:
Perform data inspection and cleaning to ensure dataset quality.
Conduct exploratory data analysis (EDA) to identify relationships between variables.
Build and evaluate a baseline Logistic Regression model for CVD prediction.
Visualize key insights through statistical and graphical methods.

**Workflow of project**:
1. **Initial Data Analysis**:
Data Inspection:
Checked structure, missing values, and duplicates.
Data Cleaning:
Replaced missing numerical values using mean/median imputation.
Treated missing categorical values using mode.
Removed duplicates and corrected inconsistencies.
Checked for and handled outliers that could bias results.

3. **Exploratory Data Analysis (EDA)**:
Generated summary statistics (mean, median, variance, standard deviation).
Created count plots to analyze categorical distributions (e.g., gender, chest pain type).
Examined CVD distribution across age groups and between genders.
Explored relationships among key factors like blood pressure, cholesterol, and heart rate.
Visualized pairwise correlations using pair plots and heatmaps.

3. **Baseline Model — Logistic Regression**:
Built a Logistic Regression model to predict heart disease presence.
Evaluated model using metrics like:
Accuracy
Visualized performance with a confusion matrix.

**Factor Analysis**:
Identified correlations among all features to understand their combined effect on heart disease risk.
Strong positive relationships were found between age, cholesterol, blood pressure, and CVD likelihood.

Pair Plot Visualization
Generated pair plots for continuous variables such as age, cholesterol, thalach, oldpeak, and trestbps.
These plots reveal how individual attributes interact and distinguish CVD from non-CVD cases.


**Conclusion**:
The exploratory data analysis revealed that factors such as age, gender, cholesterol, resting blood pressure, 
and exercise play a crucial role in determining heart disease risk.
The logistic regression model serves as an initial predictive framework, 
which can be further enhanced by refining features and experimenting with more advanced machine learning algorithms.



