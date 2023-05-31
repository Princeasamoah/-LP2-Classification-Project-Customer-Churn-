# -LP2-Classification-Project-Customer-Churn-
Project 2 for the Data Analytics Professional - Career Accelerator Phase

Customer churning refers to the percentage of customers that stopped using a company's products or services within a specified timeframe. The aim of this project is to find the likelihood of a customer leaving an organization, the key indicators of churn as well as the retention strategies that can be implemented to avert this problem.Classification machine learning models in python are built and the best performing model selected to predict a customers likelihood of churning.

The implementation process involved several steps. Firstly, exploratory data analysis (EDA) was conducted to examine various factors related to customer churn. This included analyzing the churn ratio among customers based on different variables such as internet services, dependents and partners, charges, seniority status, contract type, paperless billing, and tenure.

Next, feature engineering techniques were applied to prepare the data for modeling. Sklearn's one-hot encoding method was used to encode categorical variables, excluding the churn variable. The first categories of each variable were dropped to avoid the dummy variable trap. Numerical columns were also scaled to ensure they were on a similar scale.

Five different models were built, and the best-performing model, which was determined to be the random forest model, was selected for further analysis.

To optimize the model's performance, hyperparameter tuning was performed using both grid search and randomized search cross-validation techniques. This process involved systematically varying the model's hyperparameters and evaluating their impact on model performance. The model was also cross-validated to assess its ability to generalize to unseen data.

Finally, the trained model was used to make predictions on new data, allowing for the identification of potential customer churn.
Prediction

