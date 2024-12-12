# Predicting Squirrel Friendliness from Behavior and Characteristics

Developed Machine Learning Model based on squirrel data from Central Park Squirrel Census

Processed the categorical features using OneHotEncoder. Train Logistic Regression, Random Forest, SVM, XGBoost algorithms  to get the best precision score. Cross validation using 4k fold, including stratify in splitting method.

The best model is Random Forest, achieving 0.2132 precision score, 0.047 standard deviation, which is roughly 3.26 std above baseline precision score.

Required library version:
- python=3.12.5
- matplotlib=3.9.2
- plotly=5.23.0
- pandas=2.2.2
- scikit-learn=1.5.1
- numpy=1.26.4
- py-xgboost=2.1.1
- shap=0.45.1
- jupyter
