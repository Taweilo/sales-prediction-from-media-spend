# 🔮🔮 Sales Prediction from Media Spend 🚀🚀
![Python version](https://img.shields.io/badge/Python%20version-3.10%2B-lightgrey)
![GitHub last commit](https://img.shields.io/github/last-commit/Taweilo/Red_Wine_Quality_Classification_Model)
![GitHub repo size](https://img.shields.io/github/repo-size/Taweilo/Red_Wine_Quality_Classification_Model)
![Type of ML](https://img.shields.io/badge/Type%20of%20ML-Regression%20-red)
![License](https://img.shields.io/badge/License-MIT-green)

Badge [source](https://shields.io/)
 <img src="https://ewm.swiss/application/files/3916/6365/7200/The_Future_of_Marketing_EWM_SA_Digital_Agency_Geneva.jpg" width="1100" height="450">

In this project, we aim to optimize media spending for a business by leveraging data mining techniques to analyze the relationship between media spend and revenue. The company has been running multiple media channels to promote its products/services, and while it has ROI metrics to evaluate Key Performance Indicators (KPIs), it is more interested in understanding how media spend influences revenue. Through machine learning and inferencing techniques, we seek to predict sales based on media spend, enabling the company to allocate resources effectively and optimize its media channel management.

## Repository structure (Not yet)
```
├── Image
│   ├── business value.jpg                        <- image used in the README.
│   ├── data statistics.jpg                       <- data statistics summary used in the README.
│   ├── evaluation.jpg                            <- model summary table used in the README.
│   ├── heatmap.jpg                               <- heatmap image used in the README.
│   ├── quality distribution.jpg                  <- quality distribution image used in the README.                             
│
├── Red Wine Classification Project.ipynb         <- code
├── Dummy Data HSS.csv                            <- dataset
```
## 1. Business Understanding
Via the regression, we can predict the sales from media spending. Therefore, the company would manage its media channel effectively. Several machine learning techniques were applied and the best predictor would be suggested. 

## 2. Data Understanding (Not yet)
The Sales & Media Spend data was loaded via Colab. The dataset is from Kaggle: https://www.kaggle.com/datasets/harrimansaragih/dummy-advertising-and-sales-data (also please see Dummy Data HSS.csv attached). Basic data analysis was performed to identify the shape of data, get column names, find missing values, and generate descriptive statistics. The Pearson correlation matrix was calculated to find the pairwise correlation of the columns in the data. All columns in the data are visually represented as histograms. A correlation heatmap figure was generated to represent the correlation matrix.

* Original Dataset
 <img src="https://ewm.swiss/application/files/3916/6365/7200/The_Future_of_Marketing_EWM_SA_Digital_Agency_Geneva.jpg" width="1100" height="450">
 
| Name | Modeling Role | Measurement Level| Description|
| ---- | ------------- | ---------------- | ---------- |
| **TV** | input | float | TV promotion budget (in million) |
| **Radio** | input | float | Radio promotion budget (in million) |
| **Social Media** | input | float | Social Media promotion budget (in million) |
| **Influencer** | input | Object | Type of Influencers |
| **Sales** | target | float | Sales in million |

* Statistics
 <img src="https://ewm.swiss/application/files/3916/6365/7200/The_Future_of_Marketing_EWM_SA_Digital_Agency_Geneva.jpg" width="1100" height="450"> 
* heatmap
 <img src="https://ewm.swiss/application/files/3916/6365/7200/The_Future_of_Marketing_EWM_SA_Digital_Agency_Geneva.jpg" width="1100" height="450">
* Scatter plot
 <img src="https://ewm.swiss/application/files/3916/6365/7200/The_Future_of_Marketing_EWM_SA_Digital_Agency_Geneva.jpg" width="1100" height="450">
 
## 3. Data Preparation 
1. Define variables
2. Get dummy variables
3. Split the data into train and test dataset
  
## 4. Modeling (Not yet)
* Linear Regression
* LASSO Regression
* Ridge Regression
* Elastic Net
* Decision Tree Regression
* Support Vector Regression
* K-Nearest Neighbors Regression
* Random Forest Regression
* Gradient Boosting Regression (e.g., XGBoost)
* Neural Network Regression
  
## 5. Evaluation
 <img src="https://ewm.swiss/application/files/3916/6365/7200/The_Future_of_Marketing_EWM_SA_Digital_Agency_Geneva.jpg" width="1100" height="450">
## 6. Recommendation
