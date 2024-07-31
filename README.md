# Airline Customer Satisfaction Analysis
## 1. Introduction
This project is based on the "Invistico Airline" dataset, which contains customer satisfaction ratings for flights based on various criteria. The dataset was uploaded on Kaggle by Sayantan Jana and can be accessed [here](https://www.kaggle.com/datasets/sjleshrac/airlines-customer-satisfaction). The dataset is labeled, with the target variable being Satisfaction (whether customers are satisfied or dissatisfied with their flight). In this project, we will:

- Examine the dataset
- Preprocess the dataset
- Visualize the data to identify trends and key features
- Perform classification: Split the dataset into training and test sets, apply various supervised learning methods to predict whether customers in the test set are satisfied or dissatisfied with their flight, and determine the most suitable classification method for this dataset.
- Perform clustering: Ignore the Satisfaction label, treat the dataset as unlabeled, apply clustering methods to label the data, and then compare the results with the original labels to measure the accuracy of clustering methods for this dataset.
## 2. Dataset Overview
The dataset provides detailed information about flights and customer ratings (on a scale of 1-5) on various flight-related criteria. The dataset contains 129,880 records and 23 variables, detailed as follows:
| Variable Name | Values |
|---------------|--------|
| Satisfaction | satisfied / dissatisfied	|
| Gender | Male / Female |	
| Customer Type | Loyal Customer / Disloyal Customer |
| Age | Min: 7 / Max: 85 |
| Type of Travel | Personal Travel / Business Travel |	
| Class | Business / Eco / Eco Plus	|
| Flight Distance | Min: 50 km / Max: 6951 km |	
| Seat comfort |	Scale: 1 (Very Dissatisfied) to 5 (Very Satisfied)	|
| Departure/Arrival time convenient |	Scale: 1 to 5	|
| Food and drink |	Scale: 1 to 5 / 0: Not Rated	|
| Gate location	| Scale: 1 to 5	|
| Inflight wifi service	| Scale: 1 to 5	|
| Inflight entertainment	| Scale: 1 to 5	|
| Online support	| Scale: 1 to 5	|
| Ease of Online booking	| Scale: 1 to 5	|
| On-board service |	Scale: 1 to 5	|
| Leg room service	| Scale: 1 to 5	|
| Baggage handling	| Scale: 1 to 5 |
| Check-in service	| Scale: 1 to 5	|
| Cleanliness	| Scale: 1 to 5 |	
| Online boarding	| Scale: 1 to 5 |	
| Departure Delay in Minutes	| Min: 0 min / Max: 1592 min	|
| Arrival Delay in Minutes	| Min: 0 min / Max: 1584 min	|

## 3. Objectives
In this project, we aim to:

1. Dataset Examination: Review and understand the structure and content of the dataset.
2. Data Preprocessing: Clean and preprocess the data to handle missing values, outliers, and categorical variables.
3. Data Visualization: Use various visualization techniques to identify trends, correlations, and key insights from the data.
4. Classification: Apply different supervised learning algorithms to classify customer satisfaction and evaluate their performance.
5. Clustering: Perform clustering on the dataset, treating it as unlabeled data, and assess the clustering accuracy by comparing it to the original labels.
