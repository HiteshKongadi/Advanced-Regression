# Advanced Regression using Ridge and Lasso Regularization
> The model is expected to help the management understand the key factors affecting the prices of house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based Housing company wants to understand the variables affecting the sale of houses.
- The company wants to enter into Australian Housing market.
- Trying to understand the contributing factors which can give us insights in to the Australian housing market when the company starts to operate in Australian market.
- Data set used is the Housing market data from US which has the features which may or may not be affect the prices of the houses.(train.csv)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Ridge and Lasso Regression Model are built with optimum alpha calculated in GridSearchCV method.
Optimum alpha = 9.0 for ridge and 0.0001 for lasso model.
- Model evaluation is done with R2 score and Root Mean Square Error.
- Lasso Regression is chosen as final model for having slightly better R-square value on test data.
- Out of 50 features in the final model, top 10 features in order of descending importance are ['1stFlrSF', '2ndFlrSF', 'OverallQual', 'OverallCond', 'SaleCondition_Partial', 'LotArea', 'BsmtFinSF1','SaleCondition_Normal', 'MSZoning_RL', 'Neighborhood_Somerst']

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
### Python
- library - Pandas
- library - NumPy
- library - matplotlib
- library - Seaborn
- library - sklearn
- library - statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was completed as part of Advanced Regression Assignment...
- This project was based on [Ridge Regression](https://learn.upgrad.com/course/1990/segment/23652/142198/435020/2251628) and [Lasso Regression](https://learn.upgrad.com/course/1990/segment/23652/142198/435020/2251630).


## Contact
Created by [@HiteshKongadi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->