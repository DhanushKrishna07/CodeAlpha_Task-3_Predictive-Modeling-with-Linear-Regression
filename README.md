This is task 3 of CodeAlpha | Data Science Domain.

Build a predictive model using linear regression to
predict a numerical outcome based on one or more
features. Use a dataset with a continuous target
variable.

 🌆Predictive Modeling with Linear Regression🏠
 
A comprehensive project exploring the prediction of Boston housing prices using linear regression and random forest regressor, with a focus on data visualization, outlier detection, model training, and performance evaluation.

Project Highlights:

•Visualized distribution and relationships between key features.
•Detected and removed outliers to enhance model accuracy.
•Employed Linear Regression and Random Forest Regressor for predictions.
•Applied cross-validation with GridSearchCV for hyperparameter tuning.
•Evaluated model performance with various metrics.

Steps Involved:

•Imported necessary libraries such as pandas, numpy, seaborn, and matplotlib, and loaded the Boston Housing dataset.
•Visualized distributions of features like 'chas', 'indus', 'zn', 'crim', and their relationships with 'medv', creating scatter plots and histograms to understand feature distributions.
•Checked the shape, info, and descriptive statistics of the dataset, and visualized the correlation between features using a heatmap.
•Identified outliers using the IQR method and dropped outlier rows to create a cleaner dataset.
•Segregated the dataset into features (X) and target (y) and split the data into training and testing sets.
•Trained a Linear Regression model and evaluated its performance using metrics like R2 score, MSE, MAE, and adjusted R2 score, visualizing residuals and regression lines.
•Applied GridSearchCV to find the best parameters for the Linear Regression model, retrained the model with optimal parameters, and evaluated its performance.
•Trained a Random Forest Regressor model, evaluated its performance, applied GridSearchCV for hyperparameter tuning, and visualized residuals and regression lines.

Key Takeaway:

💡This project highlights the importance of data visualization, outlier detection, and hyperparameter tuning in building robust predictive models. Both Linear Regression and Random Forest Regressor were effective, with the latter showing better performance due to its ability to handle non-linear relationships.🔎 
