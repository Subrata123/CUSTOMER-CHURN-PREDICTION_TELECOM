Customer Churn Prediction_Telecome Sector

Objective:
The cost of retaining a customer is always less than acquiring a new customer. Customer churn is one of the great challenges for the telecom industry.
The dataset shared contains the customer information’s to whom company are provided the services for certain period of time. The objective is to look for general patterns in the provided data that would help to identify customers that are more likely to churn so that company can address those customer and prevent them from churn by addressing the right concerned areas.
Dataset:
The dataset contains 21 columns and 7043 rows. 

Data dictionary:

Variable name	Variable description
customerID :	a unique number for identifying a customer
gender :	Gender is female or male
SeniorCitizen :	whether the customer is a senior citizen or not (available values: 1/0, where 1 means ‘Yes’ and 0 means ‘No’)
Partner :	whether the customer has a partner or not (available values: Yes/No)
Dependents :	whether the customer has dependents or not (available values: Yes/No)
tenure :	number of months the customer has stayed with the company
PhoneService :	whether the customer has a phone service or not (available values: Yes/No)
MultipleLines :	whether the customer has multiple lines or not (available values: Yes/No/No phone service)
InternetService :	customer’s internet service provider (available values: DSL/Fiber optic/No)
OnlineSecurity :	whether the customer has online security or not (available values: Yes/No/No internet service)
OnlineBackup :	whether the customer has online backup or not (available values: Yes/No/No internet service)
DeviceProtection :	whether the customer has device protection or not (available values: Yes/No/No internet service)
TechSupport :	whether the customer has tech support or not (available values: Yes/No/No internet service)
streamingTV :	whether the customer has streaming TV or not (available values: Yes/No/No internet service)
streamingMovies :	whether the customer has streaming movies or not (available values: Yes/No/No internet service)
Contract :	the contract term of the customer (available values: Month-to-month/One year/Two year)
PaperlessBilling :	whether the customer has paperless billing or not (available values: Yes/No)
PaymentMethod :	the customer’s payment method (available values: Electronic check/Mailed check/Bank transfer (automatic)/Credit card (automatic))
MonthlyCharges :	the amount charged to the customer monthly(numeric variable)
TotalCharges :	the total amount charged to the customer(numeric variable)


Approach considered:

As a part of machine learning exercise, following activities performed to build predictive model & assess the performance.
i.	Importing dataset and libraries
ii.	Data cleaning and preparation
iii.	Exploratory data Analysis (EDA)
iv.	Feature engineering and dataset preparation
v.	Training and test data preparation
vi.	Model development and evaluation

Algorithm used:

‘MLR’ packaged has been used to develop and assess the model performance. Performance tuning done selecting the best hyperparameter and Gridsearch /Random search control parameter has been used. Here the list of algorithms considered –
•	Logistic regression
•	Decision tree
•	Random Forest
•	Support vector machine
•	K nearest neighbor (KNN)

