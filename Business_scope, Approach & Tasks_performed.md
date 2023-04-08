# Business Scope of the project:
This project will be helpful for  app developers and marketing teams to predict the number of downloads for an app on the Google Play Store. 
This can help them to optimizetheir app development and marketing strategies to improve the visibility and popularity of theirapps, 
which can ultimately lead to more downloads and revenue.

# Approach:
Based on the available dataset and problem statement, we can use regression models such as Linear Regression, Ridge Regression, Lasso Regression, 
Decision Tree Regression, Random Forest Regression, Gradient, Extreme Gradient and Ada Boost Regression to predict the total number of downloads 
of an app on the Google Play Store. Alsosince the target variable has limited unique data and is in the form of discrete classes, we will bin the data of the
target variable into classes and use classification models like Decision Tree Clasifier, Random Forest Classifier, Gradient Boost classifier to check its accuracy.

# Tasks Performed and Outcome:
1) First the data is thoroughly analysed and EDA is performed. In this Data Preprocessing part, the null values are checked and treated, Box Plots created to find outliers. Extreme values are not dropped in this dataset as replacing them with mean, median for this particular data set made little sense.

2) To check for multicollinearity, we used heat map and variance inflation factor (VIF). If multicollinearity is present, we can remove one of the highly correlated features or use dimensionality reduction techniques such as Principal Component Analysis (PCA). In this dataset we removed the 'Rating' feature which showed a high VIF number. Removing it helped to prevent overfitting in the Regression Model Building part. The Classification Models however showed signs of over fitting.

3) The model requires scaling. We have used log transformation and also used Normalisation technique for scaling certain features.

4) The Regression models were built be evaluated using various evaluation parameters such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared (R2). The Classification Models were evaluated using parameters like Accuracy Score. Based on these parameters, we can select the best-performing model. The best performing models from Regression and Classification were chosen and further trained and tuned with hyper parameters to futher improve their performance.
