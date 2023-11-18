# Prediction-of-diabetes-using-machine-learning-algorithms

This is a project on the prediction of diabetes using machine learning algorithms. 
**Problem Description**
Diabetes is a medical condition that causes a person`s blood sugar level to become high. It has two major types, and they are Type 1 diabetes and Type 2 diabetes. Type 1 diabetes is a lifelong condition where the body`s immune system attacks and destroys the cells producing insulin.  While type 2 diabetes occurs when the body does not produce enough insulin or the body`s cells do not react to insulin properly, Type 2 diabetes is more prevalent than type 1, and according to the NHS UK, more than 90% of the adult population with diabetes has type 2. There are other types, such as gestational diabetes that occur when high blood sugar develops during pregnancy. Machine learning algorithms are veritable options for prediction, and some will be deployed for predicting diabetes. 



**Data**
Data used in this repository was obtained from Kaggle and originally from the National Institute of Diabetes, Digestive, and Kidney Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes based on certain diagnostic indices contained in the dataset. The data is a csv file and there are several variables in it. 



**Approach to analysis**
For the analysis, I had to first install all the libraries that would be needed, and they are Pandas. Pandas is a library applicable for data manipulation and analysis in Python.
NumPy- it’s applicable for adding support for large, multi-dimensional arrays and matrices, and it can be used for a high-level mathematical operation.
Matplotlib-Matplotlib is applicable for plotting in Python.
Seaborn- a library for making charts.
Scikit-learn- It is a free software machine learning library applicable to the Python programming language.
Exploratory data analysis
After the data were loaded into the Google Collab IDE using Panda's library, missing values were checked to ascertain if my data was clean or if I needed to clean the data. It was found that there are no missing values in the dataset which makes the analysis easy and straightforward. I also checked the head to have a quick glance at the dataset by checking the first five values from the head. The first five summary was done, and other exploratory analyses were done too. The data was also visualized using a chart, correlation was done, and some visualization. The dataset was standardized for uniformity before they were divided into train and test sets with a split ratio of 0.2. 




**Modeling**
I used the following as features and Outcome as the response:

Pregnancies

Glucose

Blood Pressure 

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age


Logistic regression and SVM were fitted into the algorithm on the training dataset, and predictions were made using the test data set. The accuracy score was 75.32% for logistic regression and 75.97% for SVM, which typifies that SVM was a better algorithm for predicting diabetes.

**Conclusion**
From the analysis, it was seen that the support vector machine was a better algorithm for predicting diabetes, and the features are good predictors. 

**References**
NHS. (2023). Diabetes. Available online: https://www.nhs.uk/conditions/diabetes/
