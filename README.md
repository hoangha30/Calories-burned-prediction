# Calories-burned-prediction
- Takes some parameters such as age, gender, exercise duration, etc. to evaluate the amount of calories you would burn.
- This project is made up of a simple machine learning algorithm Linear Regression and Random Forest Regressor.
- Before training and testing, preprocessing data and applying StandardScaler for normalization. 
- Using PCA to select the minimum number of principal components that explain a desired percentage of the total variance, often 80 - 90%.
-> Using the first 2 principal components captures approximately 93.98% of the variance in the data. This implies that through several principal components, the components can still account for a significant amount of variability in the data.

- Train and test 2 models with and without PCA to predict the amount of calories you burned.
- Evaluate by Root Mean Squared Error score.