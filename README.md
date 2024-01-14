# Heart Disease Classification

In this project, I have used the following classification techniques for heart disease classification -
1) Linear Regression
2) Artificial Neural Networks
3) Decision Tree Classifier
4) Bagging Classifier
5) Random Forest Classifier
6) AdaBoost Classifier
7) GradientBoost Classifier

Dataset used - (https://archive.ics.uci.edu/dataset/45/heart+disease)

<b>Description of attributes</b>
1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type
   - Value 1: typical angina
   - Value 2: atypical angina
   - Value 3: non-anginal pain
   - Value 4: asymptom
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl)  (1 = true; 0 = false)
7. restecg: resting electrocardiographic results
   - Value 0: normal
   - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
   - Value 2: showing probable or definite left ventricular hypertrophy by Estes' crite
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment
    - Value 1: upsloping
    - Value 2: flat
    - Value 3: downslop
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
14. num (<b>Target</b>): diagnosis of heart disease (angiographic disease status) 
    - Value 0: < 50% diameter narrowing
    - Value 1: > 50% diameter narrowingingriaatic

## Content
- Heart_Disease_Classification.ipynb - The main jupyter notebook
- DT_framework.py - decision tree and ensemble framework (as written in https://github.com/shashwatgupta42/tree_ensemble_framework)
- NN_Framework.py - feed forward neural net framework (as written in https://github.com/shashwatgupta42/neural_net)
- datasets - folder containing the dataset
