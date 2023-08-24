# Heart Disease Prediction
In this project we are checking a person is diseased or not

## Objective:
Do classification(Diseased or Not Diseased) on this data and choose the best model with highest accuracy.

## Indroduction:

Problem Description:

The goal of this project is to predict the binary output.Whether the patient has heart disease or not.Today, heart failure diseases affect more people worldwide than other autoimmune conditions.

It is well known that the libraries available in Python for data loading, management, and building models, such as Pandas, NumPy, and Scikit-Learn, help build robust data science applications. However, when dealing with medical data in data science, data privacy and protection are important parameters that cannot be ignored.With Python programming language, cybersecurity professionals can efficiently accomplish these aspects in healthcare projects. Beyond data science, Python is also widely used for decoding and sending packets, network scanning, accessing servers, analyzing web traffic, and port scanning.

 Best Machine learning approaches for Heart disease prediction are:
    
    1.Logistic Regression
   
    2.Random Forest
   
    3.Decision Tree
   
    4.K-Nearest Neighbours
   
    5.Support Vector Machine
    
    6.ADA boost classifier

By performing this 6 techniques we will choose the best model for predict Heart Disease.

### HEART DATA DICTIONARY:

age : age of persons

sex : gender of persons

cp : chest pain type (4 values)

trtbps : resting blood pressure

chol : serum cholestrol in mg/dl

fbs : fasting blood sugar > 120 mg/dl

restecg : resting electrocardio results(values 0,1,2)

thalach : maximum heart rate achieved

exng : exercise induced angina

oldpeak : ST depression induced by exercise relative to rest

slp : the slope of the peak exercise ST segment

caa : number of major vessels(0-3) colored by flourosopy

thall : 0=normal, 1=fixed defect, 2 = reversable defect

output : Target column, 1 = Diseased, 0 = Not Diseased

## Dataset Features:
- age
- sex
- chest pain type (4 values)
— Value 0: typical angina
— Value 1: atypical angina
— Value 2: non-anginal pain
— Value 3: asymptomatic
- trestbps: resting blood pressure (in mm Hg on admission to the hospital)
- chol: serum cholestoral in mg/dl
- fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- restecg: resting electrocardiographic results
— Value 0: normal
— Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
— Value 2: showing probable or definite left ventricular hypertrophy by Estes’ criteria
- thalach: maximum heart rate achieved
- exang: exercise induced angina (1 = yes; 0 = no)
- oldpeak = ST depression induced by exercise relative to rest
- slope: the slope of the peak exercise ST segment
— Value 1: up-sloping
— Value 2: flat
— Value 3: down-sloping
- ca: number of major vessels (0–3) colored by fluoroscope
- thal: 3 = normal; 6 = fixed defect; 7 = reversible defect
- target : 0=low risk of heart attack, 1=high risk of heart attack

## Model Training and Prediction :

We can train our prediction model by analyzing existing data because we already know whether each patient has heart disease. This process is also known as supervision and learning. The trained model is then used to predict if users suffer from heart disease. The training and prediction process is described as follows:

## Splitting:

First, data is divided into two parts using component splitting. In this experiment, data is split based on a ratio of 80:20 for the training set and the prediction set. The training set data is used in the logistic regression component for model training, while the prediction set data is used in the prediction component.

The following classification models are used - Logistic Regression, Random Forest Classfier, SVM, Naive Bayes Classifier, Decision Tree Classifier, LightGBM, XGBoost

## Prediction:
The two inputs of the prediction component are the model and the prediction set. The prediction result shows the predicted data, actual data, and the probability of different results in each group.

## Evaluation:
The confusion matrix, also known as the error matrix, is used to evaluate the accuracy of the model.

