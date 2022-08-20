# House price

I. Problem Description:

  Predicting house price in the future based on given data.
  
  Data link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
  
  Data description: 
  train.csv - the training set 
  
  test.csv - the test set
  
  data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
  
  sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms
  
II. Approach:

  First, we need to study variables and clean some data which are noise and do not affect the SalePrice. Then we take a look at variables which contain too much NULL value and clean it since it does not contribute much for predicting house price. Finally, I suggest using random forest to solve this problem.
 
