# Credit Card Approval 

This project explores the factors that influence customer attrition in the banking industry using the BankChurners dataset. The dataset contains information about customer demographics, credit history, and banking activity.

The project includes data preprocessing, exploratory data analysis, machine learning model building, and evaluation.

## Data Preprocessing

The data is preprocessed to handle missing values, convert categorical variables to numerical representations, and remove irrelevant columns.

## Exploratory Data Analysis

Exploratory data analysis is performed to gain insights into the data and identify patterns and relationships between variables. This includes visualizations such as scatter plots, bar charts, and heatmaps, as well as univariate and bivariate analysis.

![Image](https://github.com/shahjahnavi/Predicting_Credit_Card_Approvals/assets/138523298/25769185-9a3b-4ff4-96ec-dbea4fef4021)

![Image](https://github.com/shahjahnavi/Predicting_Credit_Card_Approvals/assets/138523298/261d4399-3dd2-4cdf-907e-58b7e3d71be2)

![Image](https://github.com/shahjahnavi/Predicting_Credit_Card_Approvals/assets/138523298/0d1fb1d1-edbb-40f0-aae6-7280f85b3328)

![Image](https://github.com/shahjahnavi/Predicting_Credit_Card_Approvals/assets/138523298/40b9a7cd-1b11-4667-b010-a9ba029d7d27)



## Machine Learning Model Building

Three machine learning algorithms - logistic regression, ridge regression, and lasso regression - are applied to predict customer attrition based on the demographic and banking activity data. The models are evaluated using cross-validation to select the optimal parameters and assess their performance.

## Evaluation

The performance of the machine learning models is evaluated using accuracy, precision, recall, and F1-score. The results indicate that ridge regression and lasso regression achieve higher accuracy than logistic regression.

![Image](https://github.com/shahjahnavi/Predicting_Credit_Card_Approvals/assets/138523298/f4bd59cd-6e01-4491-aac6-a9e30603fb01)

![Image](https://github.com/shahjahnavi/Predicting_Credit_Card_Approvals/assets/138523298/490adb63-d7ab-4ec8-a2a7-b58977d5cc49)


## Findings

The analysis reveals that several factors influence customer attrition, including age, income level, education level, number of contacts, number of inactive months, total relationship count, and dependent count.

![Image](https://github.com/shahjahnavi/Predicting_Credit_Card_Approvals/assets/138523298/751f9319-6e91-4a89-9bef-7047ba7f4773)

![Image](https://github.com/shahjahnavi/Predicting_Credit_Card_Approvals/assets/138523298/44f88c69-0032-4b09-8fd6-ccb9ae8ed0d9)



## Conclusions

The findings of this project can be used by banks to identify customers at risk of attrition and implement strategies to retain them. This can lead to increased customer satisfaction, reduced customer churn, and improved profitability.

## Code Structure

The code is structured into sections for data preprocessing, exploratory data analysis, machine learning model building, and evaluation. Each section contains comments to explain the code and its purpose.

## Dependencies

The code requires the following R packages:

* tidyverse
* glmnet
* ggplot2
* DataExplorer
* hrbrthemes
* viridis
* ggstatsplot
* skimr
* Hmisc
* ggsci
* caret
* ggpubr
* gridExtra
* corrplot
* rpart
* rpart.plot
* rattle
* pscl
* pROC
* readr
* dplyr
* caret
* repr

## Additional Notes

* The code is written in R and uses the tidyverse package for data manipulation and visualization.
* The code is well-documented and easy to understand.
* The code is reproducible and can be used to replicate the analysis.
* The code is efficient and uses vectorized operations to improve performance.

## Future Work

* Collect additional data to provide a more comprehensive analysis of customer attrition.
* Develop more complex machine learning models to improve prediction accuracy.
* Implement the findings of this project to develop a customer retention strategy for a bank.
