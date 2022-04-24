# Vivino wine analysis repository

## About
This SC1015 Introduction to Data Science and Artificial Intelligence Mini-Project analyses data from [Vivino Wine Dataset](https://www.kaggle.com/datasets/budnyak/wine-rating-and-price). For the best walkthrough experience, we recommend viewing the notebooks in the following order:
1. [Data Preparation and EDA](https://github.com/KuroZenon/Data-Analysis-of-Wine-Quality/blob/main/Data%20Preparation%20and%20EDA.ipynb)
2. [Machine Learning](https://github.com/KuroZenon/Data-Analysis-of-Wine-Quality/blob/main/Machine%20Learning.ipynb)


## Problem Definition
How do different variables affect the price of wine (red, white, rosé, sparkling)?
Which model most accurately predicts the price of wine?


## Models used
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Neural Networks


### Notebook 1 Data Preparation and EDA

In this notebook, we combined the wine data from our datasets and proceeded to clean the data. Subsequently, we conducted an Exploratory Data Analysis and discovered that Rating was the factor with the strongest correlation with Price.  We decided to perform np.log() on the Prices as Price was heavily skewed to the right, which improved the correlation of price with our predictors. One-hot Encoding was used to encode Country data as Country is a categorical variable.

### Notebook 2 Machine Learning

The 4 above-mentioned models were utilised for univariate and multivariate analysis. We found that Random Forest Regressor yielded the best Explained Variance (R^2) of 0.8 and that is the model we recommend our users for prediction.

## Conclusion
- Rating is the main feature as it has the strongest correlation with Price
- Misconception that red wines taste better with age
- More predictors included, generally more accurate prediction


## Acknowledgements
https://www.kaggle.com/datasets/budnyak/wine-rating-and-price
https://www.linkedin.com/pulse/wine-rating-price-patterns-trends-insights-sebastiano-denegri/
https://medium.com/rants-on-machine-learning/the-unreasonable-effectiveness-of-random-forests-f33c3ce28883
https://www.eatthis.com/news-best-wine-in-the-world/ 
https://cellaraiders.com/blogs/news/why-wine-tastes-better-with-age 
https://machinelearningmastery.com/how-to-improve-neural-network-stability-and-modeling-performance-with-data-scaling/ 



