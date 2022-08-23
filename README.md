# LifeExpectancyPrediction
In this project, the aim was to predict life expectancy based on various factors, such as countries, developing status, GDP, adult mortality, BMI and other measurable factors. The file for dataset was collected from the Global Health Observatory (GHO) data repository under World Health Organization (WHO) which keeps track of the health status as well as many other related factors for all countries.

For the dataset, feel free to download from here: https://www.kaggle.com/mrinath/starter-life-expectancy-who-9536c272-3/data

The first method applied in this project was the multivariate linear regression as shown in the "Linear Regression" file. It was known that the dataset was indeed a 2938 x 19 matrix. The dataset was cleaned and normalized before the regression models were applied. Then, the dataset was split into 30% of testing data and the remaining as the training data. The data was linearised using Scikit-Learn libraries and produced the accuracy of about 79%.

The second method applied was the multivariate linear regression using Batch Gradient Descent as shown in the "Batch gradient descent" file. Similar data engineering procedures were performed as in the multiple linear regression method. The gradient descent was performed at the learning rate of 0.01 and iterated for up to 10000000 times until the value of subsequent cost function had been reduced to below 10^-12. However, the r^2 score computed for the model was -52 indicating irrelavant model fitting. Thus, batch gradient descent might not be the suitable algorithm to compute prediction for this dataset using linear regression. 

# Reference
Sucky, R., N. (2020). Multivariate Linear Regression in Python Step by Step. Towards Data Science. Retrieved from https://towardsdatascience.com/multivariate-linear-regression-in-python-step-by-step-128c2b127171

Mishra, S. (2019). Implementing and Visualizing Linear Regression in Python with SciKit Learn. Towards Data Science. Retrieved from https://becominghuman.ai/implementing-and-visualizing-linear-regression-in-python-with-scikit-learn-a073768dc688


