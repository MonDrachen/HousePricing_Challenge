# House Pricing Prediction Using Machine Learning Pipelines

> Description:
In this project, I developed a machine learning pipeline to predict house prices using data from the Ames Housing dataset. This project, inspired by the Kaggle House Pricing competition, involved preparing the data, building a robust pipeline, and tuning a machine learning model for optimal performance.

## Key Features:

* Data Preparation:
Performed preprocessing for both numerical and categorical data. Missing numerical values were handled using median imputation, while categorical values were imputed with the most frequent values.
Categorical variables were one-hot encoded to make them suitable for modeling.

* Pipeline Construction:
Implemented a pipeline using scikit-learn, which combines preprocessing and model fitting in a streamlined manner.
Bundled the preprocessing steps with a RandomForestRegressor model, enabling consistent processing across training and validation sets.

* Modeling and Evaluation:
Trained a Random Forest model and evaluated its performance using Mean Absolute Error (MAE) as the primary metric.
Achieved an MAE of approximately 17,862, with subsequent tuning to reduce error further.

* Submission and Deployment:
Prepared final predictions on the test set and saved them in a format suitable for submission to the Kaggle competition.
This structured pipeline allowed for easy adjustments and re-evaluation, contributing to iterative improvements in model accuracy.

## Technologies Used:
Python, scikit-learn, Pandas, Jupyter Notebook, Random Forest Regressor, OneHotEncoder
