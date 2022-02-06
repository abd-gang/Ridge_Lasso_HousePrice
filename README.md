# Ridge and Lasso on house sale price prediction
> The purposen of this assignment is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

- The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- The company wants to know:

- - -Which variables are significant in predicting the price of a house, and

- - -How well those variables describe the price of a house.

-Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### After building the model, the 3 main driving factors are-
- The model was overfitting without doing the regularization. 
- Once we used the ridge and lasso, the models fits well and the overfitting is avoided. The lambda values are 10 and .001 for ridge and lasso respectively. 
- Some of the important predictors are OverallQual, Neighborhood_Somerst, Neighborhood_Edwards, GrLivArea, MSSubClass_30.0

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.9
- Jupyter Notebook - version 6.3.0
- Numpy - version 1.20.1
- Pandas - version 1.2.4
- Matplotlib - version 3.3.4
- Seaborn - version 0.11.1
- statsmodels - version  0.12.2
- scikit-learn - version 0.24.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
#### Created by:
- Akhilesh Gangwar (akhi.gangwar@gmail.com)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->