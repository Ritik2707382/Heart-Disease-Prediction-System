Heart Disease Prediction System

Heart disease is one of the leading causes of death worldwide. Early detection and prevention have become more crucial than ever. Data-driven systems for predicting heart disease can significantly enhance research and prevention strategies, ultimately helping more people lead healthier lives. This is where Machine Learning (ML) comes into play. ML models can accurately predict the likelihood of heart disease, enabling timely intervention.

🔍 Steps to Predict Heart Disease

Understanding the Problem – Define the objectives and requirements for heart disease prediction.

Reading and Understanding the Data – Load and analyze the dataset to extract meaningful insights.

Exploratory Data Analysis (EDA) & Visualization – Identify patterns, correlations, and relationships between features.

Modeling – Train different machine learning models to predict heart disease.

Generating Insights – Evaluate model performance and determine the most effective model.

🎯 Objective

The primary goal of this project is to analyze heart disease data and develop multiple machine learning models (Naïve Bayes, Logistic Regression, Decision Tree, Random Forest) to predict the likelihood of heart disease based on relevant medical features. After evaluation, the best-performing model is selected for deployment.

📊 Dataset

The dataset consists of 14 features, each contributing to the prediction of heart disease. Below is a brief description of these features:

age: Age in years

sex: Gender (1 = Male, 0 = Female)

cp (Chest Pain Type):

0: Typical Angina

1: Atypical Angina

2: Non-Anginal Pain

3: Asymptomatic

trestbps: Resting blood pressure (in mm Hg) on admission

chol: Serum cholesterol (mg/dl)

fbs: Fasting blood sugar (>120 mg/dl) (1 = True, 0 = False)

restecg (Resting ECG Results):

0: Normal

1: ST-T wave abnormality

2: Left ventricular hypertrophy by Estes’ criteria

thalach: Maximum heart rate achieved

exang: Exercise-induced angina (1 = Yes, 0 = No)

oldpeak: ST depression induced by exercise relative to rest

slope (ST Segment Slope):

0: Upsloping

1: Flat

2: Downsloping

ca: Number of major vessels (0-3) colored by fluoroscopy

thal (Thalassemia):

0: Normal

1: Fixed defect

2: Reversible defect

condition: Target variable (0 = No Disease, 1 = Disease)

🏆 Results

After training multiple models, Random Forest was selected as the best-performing model with an accuracy of 96.18%.
