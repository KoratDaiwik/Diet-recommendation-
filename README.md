# Diet-recommendation-

The Diet Recommendation System is a machine learning project developed using Python, aimed at predicting a person's weight based on their age, diet type, gym habits, and fitness goals. This project leverages Decision Tree Regressor and Random Forest Regressor to accurately estimate the weight and further suggest personalized diet plans.
The dataset contains information about individuals such as age, cholesterol level, resting blood pressure, etc., and based on that, the system predicts their weight and analyzes their fitness goals.
The project is developed as part of a Data Science project in Python for practical implementation of regression models.

Features:-
Predicts Weight based on the user's health parameters.
Handles missing data by applying different strategies (mean, median, mode).
Automatically assigns random diet types (Veg/Non-Veg) if not provided.
Analyzes fitness goals like Bulking, Cutting, or Normal.
Provides visualization of the dataset and prediction accuracy.
Saves the prediction in the dataset itself.

Technologies Used:-
Python (Core Programming Language)
Jupyter Notebook / Google Colab (Development Environment)
Machine Learning Models (Decision Tree & Random Forest)
Data Visualization Libraries (Matplotlib, Seaborn)

Libraries Used:-
pandas - Data manipulation and analysis.
numpy - Numerical operations.
sklearn (scikit-learn) - Machine Learning models (DecisionTreeRegressor, RandomForestRegressor).
matplotlib - Data visualization.
seaborn - Statistical data visualization.

How It Works:-
Data Gathering: The project uses two CSV files: input.csv and dataset.csv.
Data Preprocessing: Missing values are handled, new columns like Diet Type, Gym, and Choice are generated.
Training Models: Two models are trained: Decision Tree and Random Forest.
Prediction: The model predicts the user's weight based on the given features.
Visualization: Multiple visualizations like distribution, correlation heatmap, and actual vs. predicted results are displayed.
Evaluation: The model's performance is evaluated using MSE, MAE, and R2 scores.
