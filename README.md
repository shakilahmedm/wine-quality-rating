# wine-quality-rating
Wine Quality dataset consists of various chemical properties of wine and a quality rating, making it suitable for predicting wine quality based on its chemical attributes. First  11 columns define physicochemical properties of wine and 12th column indicates the quality of the wine.

Project Overview
The goal of this project is to predict the quality of wine (classification and regression tasks) based on various features. The project includes data preprocessing, normalization, feature importance analysis, k-fold cross-validation, and model evaluation.

Requirements
Install the required packages with:

pip install numpy pandas matplotlib seaborn scikit-learn
Dataset
The dataset should be a CSV file named WineQT.csv, containing various chemical properties of wines and a quality column as the target variable. Missing values are handled, and features are standardized.

Modeling Techniques
This project explores the following models for classification and regression:

Classification: Logistic Regression, Decision Tree, Random Forest, SVM, Gradient Boosting
Regression: Linear Regression, Decision Tree, Random Forest, Gradient Boosting
Feature Importance
Feature importance is analyzed using a Random Forest Classifier, identifying the most influential features for predicting wine quality.

Hyperparameter Tuning
Hyperparameter tuning is performed using GridSearchCV for both classification and regression Random Forest models to optimize model performance.
Results
Results for each model are evaluated using k-fold cross-validation, with mean accuracy for classification and mean R² score for regression models. Final parameters from GridSearchCV are applied to obtain optimal results.
