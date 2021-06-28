https://www.kaggle.com/c/house-prices-advanced-regression-techniques


Start here if...
You have some experience with R or Python and machine learning basics. This is a perfect competition for data science students who have completed an online course in machine learning and are looking to expand their skill set before trying a featured competition. 

Competition Description
<img src="https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png" />

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

Practice Skills
Creative feature engineering 
Advanced regression techniques like random forest and gradient boosting
Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

Photo by Tom Thain on Unsplash.


Goal
It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

Submission File Format
The file should contain a header and have the following format:

Id,SalePrice
1461,169000.1
1462,187724.1233
1463,175221
etc.
You can download an example submission file (sample_submission.csv) on the Data page.


Other Python Tutorials
Comprehensive Data Exploration with Python

Understand how variables are distributed and how they interact
Apply different transformations before training machine learning models
House Prices EDA

Learn to use visualization techniques to study missing data and distributions
Includes correlation heatmaps, pairplots, and t-SNE to help inform appropriate inputs to a linear model
A Study on Regression Applied to the Ames Dataset

Demonstrate effective tactics for feature engineering
Explore linear regression with different regularization methods including ridge, LASSO, and ElasticNet using scikit-learn
Regularized Linear Models

Build a basic linear model
Try more advanced algorithms including XGBoost and neural nets using Keras