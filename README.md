# Food Delivery Analysis 

## Team Members
* Tara Dehdari
* Nishok Narayanan
* Muris Saab

## Overview
In this project, we aim to enhance customer satisfaction in food delivery services by predicting whether a food order is satisfactory or not. We've explored various aspects of data analysis and machine learning models to achieve this goal.


### EDA and Data Preprocessing
We started by importing the dataset and performed exploratory data analysis (EDA) and preprocessing:

* Renamed columns for better readability.
* Dropped unnecessary columns.
* Handled missing values by converting "Not given" ratings to NaN and then dropping them.

We conducted exploratory data analysis to gain insights into the dataset, such as:

* Analyzing the distribution of cuisine types and days of the week.
* Identifying top restaurants based on order frequency.
* Investigating the relationships between numerical variables.

### Modeling and Evaluation
We built and evaluated three machine learning models:

* Random Forest Classifier: Achieved an accuracy of around 81%.
* Logistic Regression: Achieved an accuracy of approximately 83%.
* Support Vector Machine (SVM): Also achieved an accuracy of around 83%. This model performed best, showing promising results in classifying satisfactory and unsatisfactory orders.

### Conclusion 

To enhance customer satisfaction in food delivery services, we recommend using the Support Vector Machine (SVM) model for binary classification. It offers a balance between precision and recall, making it a valuable tool for improving service quality and the overall customer experience. Since the dataset is imbalanced we also recommend grabbing data with lower ratings as well. 

## Data Source

The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/ahsan81/food-ordering-and-delivery-app-dataset). This dataset provides information about food orders and delivery from various restaurants. It is a valuable resource for analyzing customer preferences, restaurant performance, and delivery times in the context of a food delivery application.


