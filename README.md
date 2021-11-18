# approve a credit card 

Abstract
This project aimed to understand people's emotions about approve a credit card using machine learning models to , who would be good to approve a credit card request?. The used data in this project is provided by Kaggle, the data is labeled using, status with sklearn library XGboost and KNN was trained and get 95% accuracy.

Design
This project is one of the T5 Data Science BootCamp requirements. Data provided by Kaggle has been used in this project. The included approve a credit card in the data ID. Classifying how client  approve a credit card using machine learning algorithms .

Data
The dataset is provided in .csv format. the Dataset provided in .csv  format from Kaggle  it is 2 table .
1- application_record.csv,.it contains 438557  ID, each ID has 18 Features .
2- credit_record.csv .it contains  1048575 ID, each ID has 3 Features.

Algorithms
Feature Engineering
•	Cleaning the text feature by converting  to numeric  
•	Duplicate rows by drop . 




Models
•	 because binary classification (metric) uses two model.
A – XGBoost
 is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable by training .
•	Accuracy : 93%
•	Precision : 99%
•	Recall: 87%
•	F1: 93%

B - (KNN) K-Nearest Neighbors Algorithm for Regression
•	Accuracy : 68%
•	Precision : 99%
•	Recall: 36%
•	F1: 53%


Tools
•	Pandas for data manipulation.
•	sklearn for modeling.
•	Matplotlib for plotting.
•	Xgboost for classifier.
•	Seaborn for statistical data visualization.


