# Car-Price-Prediction

This project implements a robust car price prediction model using machine learning techniques. Built with Python, the system leverages pandas for data preprocessing, numpy for numerical operations, scikit-learn for model training and evaluation, seaborn, and matplotlib for data visualization. The dataset is cleaned and transformed, addressing issues like incorrect delimiters and categorical encoding using one-hot encoding to handle variables such as Fuel Type, Seller Type, and Transmission.

A RandomForestRegressor model is trained with hyperparameter tuning via RandomizedSearchCV to optimize performance. Feature importance analysis highlights key predictors like Present Price and Fuel Type. The final model is pickled for deployment, achieving low error metrics (MAE, MSE, RMSE). This project showcases end-to-end data science skills.

