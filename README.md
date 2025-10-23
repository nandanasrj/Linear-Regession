# Linear-Regession
This project focuses on implementing and understanding both simple and multiple linear regression using the Housing dataset. The objective is to build a predictive model, analyze the relationship between input variables and the target variable, and evaluate model performance using standard regression metrics. The tools and libraries used for this project include Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

The process begins with importing the necessary libraries and loading the dataset (Housing.csv) into a Pandas DataFrame. The dataset is explored using descriptive statistics and data summary functions to understand its structure and check for missing values. Categorical columns are then converted into numerical form using one-hot encoding to make them compatible with the regression model.

The target variable (price) is defined as the dependent variable, while all other relevant columns are used as independent features. The dataset is split into training and testing subsets in an 80:20 ratio using the train_test_split() function to ensure that the model is evaluated on unseen data.

A linear regression model is then built using LinearRegression from the sklearn.linear_model module and trained on the training set. The model’s performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and the R² score to assess accuracy and reliability. The coefficients of the model are interpreted to understand the impact of each independent variable on the target variable. For simple linear regression, a regression line is plotted against actual data points to visualize the fit of the model.

Through this project, a clear understanding of linear regression, data preprocessing, model evaluation, and interpretation of results is achieved.
