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

Predicting heart disease using machine learning is a common and valuable healthcare application. Here are the steps you can follow to build a heart disease prediction model:

## 1. Data Collection:

Gather a dataset containing various health-related features such as age, gender, blood pressure, cholesterol levels, heart rate, exercise habits, smoking status, and medical history.
Include the target variable indicating the presence or absence of heart disease (often binary: 0 for no heart disease, 1 for heart disease).

## 2. Data Preprocessing:

Clean the dataset by handling missing values and outliers.
Normalize or standardize numerical features to ensure they have similar scales.
Encode categorical features if necessary.

## 3. Exploratory Data Analysis (EDA):

Perform exploratory data analysis to understand the relationships between different features and the target variable. Visualization can be useful for this step.

## 4. Feature Selection/Engineering:

Identify important features for heart disease prediction. You can use techniques like feature importance scores, correlation analysis, or domain knowledge.
Create new features if they could provide valuable information, such as the body mass index (BMI).

## 5. Data Splitting:

Split the dataset into training, validation, and test sets (e.g., 70% for training, 15% for validation, and 15% for testing).

## 6. Model Selection:

Choose a machine learning algorithm for classification tasks. Common algorithms include Logistic Regression, Decision Trees, Random Forest, Support Vector Machines (SVM), k-Nearest Neighbors (k-NN), and Neural Networks.

## 7. Model Training:

Train the selected model on the training data.
Tune hyperparameters using techniques like cross-validation to optimize model performance.

## 8. Model Evaluation:

Evaluate your model on the validation set using classification metrics such as accuracy, precision, recall, F1-score, and the area under the Receiver Operating Characteristic (ROC-AUC) curve.
Adjust your model or try different algorithms if the performance is not satisfactory.

## 9. Testing:

Assess the final model's performance on the test set to obtain an unbiased estimate of its accuracy and generalization ability.

## 10. Interpretability:

Depending on the model used, consider methods for interpreting the model's decisions to provide insights into why a person is predicted to have heart disease or not. Interpretability can be crucial in healthcare applications.

## 11. Deployment:

Deploy the trained model in a healthcare setting where it can make predictions on new patient data.

## 12. Monitoring and Maintenance:

Continuously monitor the model's performance in the production environment and retrain it periodically with new data to keep it up-to-date.

## 13. Ethical Considerations:

Ensure that data privacy and ethical considerations are adhered to when working with healthcare data.
Remember that model performance and interpretability are essential, especially in healthcare applications. It's important to involve healthcare professionals to validate the model's predictions and ensure its clinical relevance and safety. Additionally, adhere to regulatory guidelines and data privacy laws when working with medical data.

## Evaluation:
The confusion matrix, also known as the error matrix, is used to evaluate the accuracy of the model.

