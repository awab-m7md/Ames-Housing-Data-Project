# Project 2 - Ames Housing Data and Kaggle Challenge
---

**Table of Contents**

  num | File
----- | ------------
**1** | _Datasets_
**2** | _Project 2 Notebook_
**3** | _readme.md_

Project 2 Notebook contains all the code for this project.

- All the data cleaning and EDA assumssions in this project based on the data description from Kaggle, most of the null values  in numerical columns refers to 0, the null values in the caterogorical columns refers to `None`. I did a very thorough data cleaning column by column.

- The predictors contain all the numerical columns except for the `Id` and `PID` columns because they are index columns which means they are irrelevant, from the categorical columns I included the column with the biggest impact which is the `Neighborhood` column.

- The modeling proccess contains **Linear Regression**, **Lasso**, **Ridge** and **Elastic Net**. I tried all of them in order to get the best model, I applied regularization in order to remove the effect of overfitting in my model because it contains a lot of features.





