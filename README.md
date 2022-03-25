# sales-prediction
# Problem Description
Note: All information found here is fictitious. The company is planning to renovate all of its stores and needs an estimate of each store's budget to make the best possible decisions in the renovation process. That's why we got the job done by the CFO to predict how much their stores will have sold by the end of the next six weeks. We received data on each of the 1,115 stores and their characteristics, along with the daily sales volume over a two-and-a-half year interval.

# Business Problem Question
How much will each store sell in the next six weeks?
# Solution Planning
Let's build a machine learning model that predicts the sales volume for each of the stores over a period of 6 weeks. The solution will be accessed remotely through the Telegram Messenger app, as soon as a message containing a valid store number is sent, a chatbot will respond with the corresponding forecast.

# Project Walkthrough
- Loading Data - all data is stored in csv files ( source of files: https://www.kaggle.com/c/rossmann-store-sales/data)
- Data Description - check datatypes, null values and initial statistics.
- Feature Engineering - create business hypotheses and new features based on the original features.
- Filtering Variables - drop any non-helpful information.
- Exploratory Data Analysis - dig deep into data to gather all possible information and attempt to validate our hypotheses
- Data Preparation - get our data ready for machine learning models.
- Feature Selection - choose the most relevant features.
- Machine Learning Modeling - train and compare several models and select the best performing ones.
- Hyperparameter Fine Tuning - find optimal parameters for selected models and settle on the best one.
- Metrics Comprehension - translating the results obtained by the model into business performance.
- Model Deploy - make our model available to the company.
 # **Results Preview:**
<p align="center">
<img src="https://user-images.githubusercontent.com/76906524/132606612-2836ee9f-b6bf-44de-ace9-aa9e29b3b9c4.png">
<br>
Sales vs Predictions
</p>

<br>

<p align="center">
<img src="https://user-images.githubusercontent.com/76906524/132606354-728c41a7-8a5e-4bf6-9115-39afc3b23289.gif">
<br>
Telegram Chatbot
</p>


Validating our model with the last 6 weeks of available data showed:
- the difference between real values and predicted values are - on average - around $678 per day per store, what stands for an 10% error.
