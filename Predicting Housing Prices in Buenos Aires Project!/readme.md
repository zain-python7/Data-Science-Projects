Predicting Housing Prices in Buenos Aires
Welcome to my housing price prediction project.

In this project, I built a machine learning model to predict apartment prices using real estate data. While the dataset is actually from Mexico City, the task was designed to simulate working with housing data for a major city like Buenos Aires.

Project Overview
The goal of this project was to understand how different features of an apartment — such as its location, size, and borough — affect its price. I cleaned the data, explored it visually, built a model using ridge regression, and evaluated its performance.

The workflow included:

Data wrangling

Feature engineering

Exploratory data analysis

Building and training a model

Evaluating feature importance

Tools and Libraries Used
Python

pandas, NumPy for data manipulation

matplotlib, seaborn, plotly for visualizations

scikit-learn for machine learning modeling and pipelines

Jupyter Notebooks for development

Data Wrangling Steps
Here’s a summary of the cleaning and filtering steps applied:

Loaded and combined multiple CSV files.

Filtered the data to include only apartment listings.

Focused on listings in Mexico City ("Distrito Federal") priced under $100,000 USD.

Removed outliers by trimming the bottom and top 10% of values for surface_covered_in_m2.

Split the combined latitude-longitude column into separate lat and lon columns.

Extracted borough names from the place_with_parent_names column.

Dropped columns with more than 50% missing values.

Removed categorical columns with extremely low or high cardinality.

Dropped columns that could leak the target variable or introduce multicollinearity.

Feature Engineering
Created new columns: lat, lon, and borough.

Ensured proper data types were used, especially for latitude and longitude.

Prepared a clean feature matrix and target vector for modeling.

Modeling
Built a pipeline using OneHotEncoder, SimpleImputer, and Ridge regression.

Evaluated model performance using Mean Absolute Error (MAE).

Compared model predictions against a baseline model.

Calculated feature importance to understand which variables influenced price the most.

Results
The final model was able to predict prices with reasonable accuracy for this dataset.

surface_covered_in_m2 turned out to be the most influential feature.

Borough also played a strong role in shaping price.

Next Steps
There are a few ways this project could be extended:

Try other regression models (like Random Forest or Gradient Boosting).

Tune hyperparameters for better performance.

Include more geographic or neighborhood-level features if available.

Thanks for checking out the project! If you have any suggestions or feedback, feel free to reach out or open an issue.
