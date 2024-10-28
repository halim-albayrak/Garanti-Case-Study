# Garanti-Case-Study

## Description
For the Data-Day event organized by Garanti Bank, I developed a project to predict the additional contributions of Garanti Bank's individual retirement plan customers.

## Project Files
Halim_Albayrak.ipynb = The file containing the entire project, including the EDA, visualizations and modeling phases.

## Details
Tools = Pandas, Numpy, Seaborn, Catboost
Feature Engineering = When I began analyzing the data, I noticed that many columns contained 0s and null values. I assumed that most of these null and zero values were present for a reason. For instance, I observed that if the LASTAUTOPAYTIME value was null for a customer, it likely meant that they hadn’t set up an automatic payment instruction. I applied this detailed analysis across multiple columns. Additionally, I merged columns with high correlation. For the CONTPAID columns, I calculated the averages, standard deviations, and maximum values to create a new column.
Data = I am unable to share the data due to privacy concerns.
Performance = Public = RMSE 8973.56 with Catboost  Private = RMSE 14850.80 with Catboost

### Link = https://www.kaggle.com/competitions/garanti-bbva-data-day-case-study/overview
