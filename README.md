# 🔮🔮 Sales Prediction from Media Spend 🚀🚀
![Python version](https://img.shields.io/badge/Python%20version-3.10%2B-lightgrey)
![GitHub last commit](https://img.shields.io/github/last-commit/Taweilo/Red_Wine_Quality_Classification_Model)
![GitHub repo size](https://img.shields.io/github/repo-size/Taweilo/Red_Wine_Quality_Classification_Model)
![Type of ML](https://img.shields.io/badge/Type%20of%20ML-Regression%20-red)
![License](https://img.shields.io/badge/License-MIT-green)

Badge [source](https://shields.io/)
 <img src="https://ewm.swiss/application/files/3916/6365/7200/The_Future_of_Marketing_EWM_SA_Digital_Agency_Geneva.jpg" width="1100" height="450">

This project will follow the BA workflow to tackle red wine business issues using data mining techniques. A red wine retailer imports wine and sells it to customers. Thus, it needs to predict the wine quality for the business when importing. Via machine learning techniques, we can classify and predict the quality in advance. By evaluating the model performance, we can make better decisions and thus maximize profits in advance.
Overall, the Radom Forest classification model maximizes profits the most. Considering the non-ml and ml model, ml model always performs better than the non-ml model under different true positive rate conditions. 

## Repository structure
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

## 2. Data Understanding
The Wine Quality data was loaded via Jupyter Notebook. The dataset is from Kaggle: https://www.kaggle.com/datasets/harrimansaragih/dummy-advertising-and-sales-data (also please see Dummy Data HSS.csv attached). Basic data analysis was performed to identify the shape of data, get column names, find missing values, and generate descriptive statistics. The Pearson correlation matrix was calculated to find the pairwise correlation of the columns in the data. All columns in the data are visually represented as histograms. A correlation heatmap figure was generated to represent the correlation matrix.

| Name | Modeling Role | Measurement Level| Description|
| ---- | ------------- | ---------------- | ---------- |
| **TV** | input | float | TV promotion budget (in million) |
| **Radio** | input | float | Radio promotion budget (in million) |
| **Social Media** | input | float | Social Media promotion budget (in million) |
| **Influencer** | input | float | Type of Influencers |
| **Sales** | target | float | Sales in million |

## 3. Data Preparation

## 4. Modeling
* Linear Regression
* Polynomial Regression
* Decision Tree Regression
* Support Vector Regression
* K-Nearest Neighbors Regression
* Random Forest Regression
* Gradient Boosting Regression (e.g., XGBoost, LightGBM)
* Neural Network Regression
## 5. Evaluation

## 6. Recommendation
