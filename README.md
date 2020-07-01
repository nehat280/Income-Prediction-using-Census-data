# Income-Prediction-using-Census-data

In this Notebook, I am working through the Income Prediction problem associated with the Adult Income Census dataset. The goal is to accurately predict whether or not someone is making more or less than $50,000 a year.Details of Survey and final_weight parameter and other basic information can be found on : (https://www.bls.gov/opub/hom/cps/pdf/cps.htm)

The Repository can be divided in to two parts:
1. [Data Cleaning and  Exploratory Data Analysis](https://github.com/nehat280/Income-Prediction-using-Census-data/blob/master/census%20(Data%20Cleaning%20and%20EDA).ipynb)

2. [Feature Selection and  Modelling](https://github.com/nehat280/Income-Prediction-using-Census-data/blob/master/census-%20modelling.ipynb) 

    Models used for prediction are 
      1. Logistic Regression
      2. Random Forest
      3. K-Nearest Neighbour
    
    from all the Three **Random Forest showed highest accuracy of about 86.6 %**. I used **Classification Report** and Accuracy to find the best model from all the three.
    
 ## Findings:
 
1. In U.S Low income group make up majoirty of the population
2. People with income of >$50k has studied more than 12.5 yrs
3. people with income < $50k have studied on an average 8-10 yrs
4. There are more number of Males who are earning compared to females.
