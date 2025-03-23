                                           ** Heart Disease Prediction System**
  Thus preventing Heart diseases has become more than necessary. Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives. This is where Machine Learning comes into play. Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.

**Steps to predict the Heart Disease**
  1. Understanding the Problem
  2.Reading and understanding the data
  3.Exploratory Data Analysis and visualisation
  4.Modeling
  5.Generate Insight

**Objective**
In this project we are going to perform some analysis to discover different insights about the Heart disease and develop different ML models(Naive Bayes,Logistic Regression,Decision Tree,Random Forest) to predict the chances of Heart Disease based on some relevant features.

**Dataset**
There are 14 features in the dataset, which are described as:
1. age: age in years
2.sex: sex (1 = male; 0 = female)
3.cp: chest pain type
   Value 0: typical angina
   Value 1: atypical angina
   Value 2: non-anginal pain
   Value 3: asymptomatic
4.trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5.chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7.restecg: resting electrocardiographic results
   Value 0: normal
   Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
   Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8.thalach: maximum heart rate achieved

**Result**
After training all the models random forest is selected as best model with an accuracy of 96.18%
9.exang: exercise induced angina (1 = yes; 0 = no)
10.oldpeak = ST depression induced by exercise relative to rest
11.slope: the slope of the peak exercise ST segment
  Value 0: upsloping
  Value 1: flat
  Value 2: downsloping
12.ca: number of major vessels (0-3) colored by flourosopy
13.thal: Thalessemia
   0 = normal
  1 = fixed defect
  2 = reversable defect
14.condition: 0 = no disease, 1 = disease
