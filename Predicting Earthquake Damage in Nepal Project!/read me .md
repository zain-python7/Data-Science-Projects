Predicting Earthquake Damage in Nepal
This project builds a machine learning model to predict the severity of earthquake damage to buildings in Nepal using demographic and structural data.

What We Did
Data Preparation: Cleaned and merged datasets containing household demographics, building structures, and damage reports.

Feature Engineering: Encoded categorical variables using appropriate encoders (OneHotEncoder, OrdinalEncoder).

Modeling: Trained and evaluated models including Logistic Regression and Decision Tree classifiers.

Hyperparameter Tuning: Optimized the decision tree max_depth for better validation accuracy.

Evaluation: Tested the final model on a held-out test set and analyzed feature importance to understand key predictors of building damage.

Libraries Used
Data Handling: pandas, numpy

Visualization: matplotlib.pyplot

Database Access: sqlite3

Encoding: category_encoders.OneHotEncoder

Machine Learning: sklearn (LogisticRegression, DecisionTreeClassifier, accuracy_score, train_test_split, pipeline utilities)

Warnings Management: warnings
