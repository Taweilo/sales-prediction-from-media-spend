# 🔮🔮 Sales Prediction from Media Spend 🚀🚀
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
| **Fixed Acidity** | input | float | The amount of non-volatile acids (such as tartaric, malic, and succinic acid). These acids are important for flavor and stability, and can contribute to the wine's tartness or sourness. However, too much acidity can also make the wine taste sour or unbalanced. On the other hand, low levels of fixed acidity can make the wine taste flat or dull. |
| **Volatile Acidity** | input | float | Taste measure, sign of winemaking quality. Higher – less control over taste. |
| **Citric Acid** | input | float | Not typically present in significant amounts in wine, but it can be added during winemaking to adjust the wine's acidity or enhance its flavor profile. Citric acid can contribute a bright, citrusy note to the wine, which can be desirable in some styles of white wine, rosé, or sparkling wine. |
| **Residual Sugar** | input | float | The amount of the natural grape sugars that remain in the wine after fermentation is complete. |

## 3. Data Preparation

## 4. Modeling

## 5. Evaluation

## 6. Recommendation
