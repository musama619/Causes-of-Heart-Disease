# Causes-of-Heart-Disease

![mildHeartAttack-866257238-770x553-650x428](https://user-images.githubusercontent.com/34093998/86289351-fd131a00-bc04-11ea-99f9-3160252142ec.jpg)

# Finding which attributes play vital role in heart disease

### The target values were 1 and 0. 1 means the person has heart disease, 0 mean person does not has a heart disease
### The whole data was in numerica form. So I replaced numerical values to understandable categories. E.g. 'Male':1, 'Female':0

-Replacing numerical data with nominal and ordinal values helped in visualization of data more easily

-Built two models: Random Forest Classifier and Decision Tree Classifier
-Random Forest Classifier performed better than Decision Tree Classifier

### From our analysis we can predict that the main causes of heart disease are:

- Major Heart Vessels(0-3). 
- The high chest pain
- High Cholestrol
- Thalassemia
- oldpeak
- slop


## Data: 
- age: The person's age in years
- sex: The person's sex (1 = male, 0 = female)
- cp: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
- trestbps: The person's resting blood pressure (mm Hg on admission to the hospital)
- chol: The person's cholesterol measurement in mg/dl
- fbs: The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
- restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or - definite left ventricular hypertrophy by Estes' criteria)
- thalach: The person's maximum heart rate achieved
- exang: Exercise induced angina (1 = yes; 0 = no)
- oldpeak: ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot. See more here)
- slope: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
- ca: The number of major vessels (0-3)
- thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)
- target: Heart disease (0 = no, 1 = yes)
