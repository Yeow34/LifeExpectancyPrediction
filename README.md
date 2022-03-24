# LifeExpectancyPrediction
In this project, the aim was to predict life expectancy based on various factors, such as countries, developing status, GDP, adult mortality, BMI and other measurable factors. The file for dataset was collected from the Global Health Observatory (GHO) data repository under World Health Organization (WHO) which keeps track of the health status as well as many other related factors for all countries.

For the dataset, feel free to download from here: https://www.kaggle.com/mrinath/starter-life-expectancy-who-9536c272-3/data

The first method applied in this project was the multiple linear regression as shown in the "Multiple Linear Regression" file. It was known that the dataset was indeed a 2938 x 19 matrix. The dataset was cleaned and normalized before the regression models were applied. Then, the dataset was split into 1/3 of testing data and the remaining as the training data. The data was linearised using Scikit-Learn libraries. Each portion was plotted and was found that they produced almost similar results with accuracy about 70%. 

The second method applied was the multivariate linear regression using Batch Gradient Descent as shown in the "Multivariate Linear Regression" file. Similar data engineering procedures were performed as in the multiple linear regression method. The gradient descent was performed at the learning rate of 0.05 and iterated for 20 times. However, due to the computational limitation, higher steps could not be tested out. The displayed results showed that for both original and predicted data were not compatible and could be said that this method needed further improvements such as tuning of learning rate and iteration steps.

# Reference
Sucky, R., N. (2020). Multivariate Linear Regression in Python Step by Step. Towards Data Science. Retrieved from https://towardsdatascience.com/multivariate-linear-regression-in-python-step-by-step-128c2b127171

Mishra, S. (2019). Implementing and Visualizing Linear Regression in Python with SciKit Learn. Towards Data Science. Retrieved from https://becominghuman.ai/implementing-and-visualizing-linear-regression-in-python-with-scikit-learn-a073768dc688


