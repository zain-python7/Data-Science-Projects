Bankruptcy Prediction Project
This project focuses on predicting company bankruptcy using financial data from Poland and Taiwan. It was developed over four lessons and one final assignment as part of a machine learning workflow training.

Purpose
The goal of this project is to build an end-to-end machine learning pipeline that can accurately predict whether a company is likely to go bankrupt based on its financial attributes. This helps in identifying financial risk early and supports better business or investment decisions.

Libraries Used and Their Purpose
pandas / json / gzip – Load and preprocess financial data stored in compressed .json.gz files

matplotlib – Create visualizations such as class distributions and feature importances

scikit-learn – Build, train, and evaluate machine learning models using pipelines and cross-validation

imbalanced-learn – Use RandomOverSampler to handle imbalanced class distributions

ipywidgets / IPython.display – Add interactive elements like confusion matrix displays in notebooks

Key Steps
Loaded and cleaned Polish and Taiwanese financial datasets

Handled missing values and severe class imbalance

Built and tuned models using:

Random Forest

Gradient Boosting

Evaluated models using:

Confusion matrices

Classification reports

Top 10 feature importance plots

Final Outcome
The result is a working machine learning pipeline that:

Reads and processes real-world financial data

Handles data quality issues and imbalance

Trains and evaluates robust classification models

Identifies the most influential features related to bankruptcy

This project demonstrates the full process of building a predictive model for a high-risk financial application.
